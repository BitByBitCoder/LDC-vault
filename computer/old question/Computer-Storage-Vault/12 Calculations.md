---
tags: [storage, calculations, arithmetic]
aliases: [Storage Calculations, Capacity Formulas]
---
← [[00 Storage Index]] | ← [[11 File Systems]] | Next → [[13 Exam Traps and Rapid Fire]]

# 12 · Calculations

> [!tip] How to use
> Read the **difficulty**, attempt on paper, then open the solution.

## 📐 Formula sheet
| What | Formula |
|------|---------|
| Unit conversion | Big → small: **× 1024**. Small → big: **÷ 1024** |
| Bits ↔ bytes | **× 8** or **÷ 8** |
| HDD capacity | Surfaces × Tracks per surface × Sectors per track × Bytes per sector |
| Surfaces | Platters × 2 |
| Memory size | **2ⁿ** locations for **n address lines** |
| Total memory bits | Locations × word size (bits) |
| Download time | File size (bits) ÷ speed (bits/s) |
| Marketed → OS size | Bytes (decimal) ÷ 2³⁰ = GB shown |
| RAID capacity | See [[10 RAID]] |

## Conversion ladder (visual)
```
 GB ──×1024──▶ MB ──×1024──▶ KB ──×1024──▶ B ──×8──▶ bits
 GB ◀──÷1024── MB ◀──÷1024── KB ◀──÷1024── B ◀──÷8── bits
```

---

### Q1 · Difficulty: ⭐ Easy
Convert **5 GB** to MB.
> [!success]- Solution
> GB → MB = ×1024
> 5 × 1024 = **5120 MB**

### Q2 · Difficulty: ⭐ Easy
How many **bits** are in **2 KB**?
> [!success]- Solution
> 2 KB → B: 2 × 1024 = 2048 B
> B → bits: 2048 × 8 = **16,384 bits**

### Q3 · Difficulty: ⭐ Easy
How many **1.44 MB floppies** hold **72 MB**?
> [!success]- Solution
> 72 ÷ 1.44 = **50 floppies**

### Q4 · Difficulty: ⭐⭐ Medium
How many **700 MB CDs** are needed to store **4 GB**?
> [!success]- Solution
> 1. 4 GB = 4 × 1024 = 4096 MB
> 2. 4096 ÷ 700 = 5.85
> 3. Cannot use part of a disc, round **up**
> 
> **6 CDs**

### Q5 · Difficulty: ⭐⭐ Medium
A memory chip has **12 address lines** and **8-bit** words. Find its capacity.
> [!success]- Solution
> ```
> 12 lines ──▶ 2¹² = 4096 locations
> each holds 8 bits = 1 byte
> ```
> 4096 × 1 B = 4096 B = **4 KB**

### Q6 · Difficulty: ⭐⭐ Medium
A CPU has a **20-bit address bus**. How much memory can it address?
> [!success]- Solution
> 2²⁰ = 1,048,576 bytes = **1 MB**
> (Check: 2¹⁰ = 1 KB, 2²⁰ = 1 MB, 2³⁰ = 1 GB)

### Q7 · Difficulty: ⭐⭐ Medium
Download a **2 GB** file at **16 Mbps**. Time taken?
> [!success]- Solution
> ```
> 2 GB ──×1024──▶ 2048 MB ──×8──▶ 16,384 Mb
> time = 16,384 Mb ÷ 16 Mb/s = 1024 s
> ```
> 1024 s = **17 min 4 s** (≈ 17.07 min)
> Trap: forgetting ×8 gives 128 s, wrong.

### Q8 · Difficulty: ⭐⭐⭐ Hard
A HDD has **4 platters** (both sides used), **1000 tracks** per surface, **100 sectors** per track, **512 bytes** per sector. Find the capacity.
> [!success]- Solution
> ```
> Surfaces = 4 platters × 2 = 8
> Total sectors = 8 × 1000 × 100 = 800,000
> Bytes = 800,000 × 512 = 409,600,000 B
> ```
> In binary: 409,600,000 ÷ 1024 ÷ 1024 = **390.6 MB**
> (Decimal: **409.6 MB**. Say which one the options use.)

### Q9 · Difficulty: ⭐⭐⭐ Hard
A "1 TB" drive (decimal). What size does Windows show?
> [!success]- Solution
> 1 TB = 10¹² B
> 10¹² ÷ 2³⁰ = 10¹² ÷ 1,073,741,824 = **≈ 931.3 GB**

### Q10 · Difficulty: ⭐⭐ Medium
Usable capacity of **4 disks × 2 TB** in RAID 0, RAID 5, RAID 10?
> [!success]- Solution
> | Level | Formula | Usable |
> |-------|---------|--------|
> | RAID 0 | n × s = 4 × 2 | **8 TB** |
> | RAID 5 | (n−1) × s = 3 × 2 | **6 TB** |
> | RAID 10 | n/2 × s = 2 × 2 | **4 TB** |

### Q11 · Difficulty: ⭐⭐⭐ Hard
How many **bytes** in **1 GB** + **512 MB**? Give the answer in MB and in bytes.
> [!success]- Solution
> 1 GB = 1024 MB → total = 1024 + 512 = **1536 MB**
> Bytes = 1536 × 1024 × 1024 = **1,610,612,736 B**

> [!warning] Exam Trap ⚠️
> **Round UP** when counting discs or drives. **Bits vs bytes** in speed questions. **Decimal vs binary** in marketed-size questions.
