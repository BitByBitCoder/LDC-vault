---
tags: [storage, hdd, secondary, magnetic]
aliases: [HDD, Hard Disk, Magnetic Disk]
---
← [[00 Storage Index]] | ← [[04 ROM and Types]] | Next → [[06 SSD and Flash]]

# 05 · HDD (Hard Disk Drive)

Secondary storage. **Magnetic**, **non-volatile**, **direct access**. Data stored by magnetising spots on spinning **platters**.

## Anatomy
```
         spindle (spins platters)
              │
   ┌──────────┴──────────┐
   │  ░░ platter 1 ░░    │◀── read/write head (each surface)
   │  ░░ platter 2 ░░    │         ▲
   │  ░░ platter 3 ░░    │    actuator arm moves heads
   └─────────────────────┘
Each surface: concentric TRACKS → split into SECTORS
Same track number across all surfaces = CYLINDER
```

| Part | Meaning |
|------|---------|
| Platter | Aluminium or glass disk coated with magnetic material |
| Track | Concentric circle on a surface |
| Sector | Smallest unit of a track. Traditionally **512 B**, newer drives **4096 B** |
| Cylinder | Vertical stack of same-numbered tracks |
| Cluster | Group of sectors (OS allocation unit) |
| Head | Reads and writes. Floats on air cushion above platter |
| Spindle | Rotates platters |
| Actuator arm | Moves heads across tracks |

## Timing terms
| Term | Meaning |
|------|---------|
| **Seek time** | Head moves to the correct track |
| **Rotational latency** | Wait for the sector to rotate under head |
| **Access time** | Seek time + rotational latency |
| **Transfer rate** | Speed of reading or writing data |

**RPM:** 5400, 7200 (common), 10000, 15000 (servers). Higher RPM = lower latency.

## Interfaces
IDE/PATA (old) → **SATA** (modern) · SCSI/SAS (servers).

## Maintenance
- **Formatting:** low-level (factory), partitioning, high-level (file system).
- **Defragmentation:** reorganises scattered file pieces. Helps HDD, **not needed for SSD**.
- **Head crash:** head touches platter, data lost.
- **Disk scan / CHKDSK:** finds bad sectors.

## History
- First HDD: **IBM 350 RAMAC (1956)**, about **5 MB**, shipped inside the IBM 305 RAMAC computer.

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| HDD stores data using | \|\|Magnetism\|\| |
| Concentric circles on a platter | \|\|Tracks\|\| |
| Smallest unit of disk storage (traditional) | \|\|Sector (512 bytes)\|\| |
| Access time = | \|\|Seek time + rotational latency\|\| |
| Cylinder means | \|\|Same track number across all platter surfaces\|\| |
| Common HDD speed | \|\|7200 RPM\|\| |
| First hard disk | \|\|IBM 350 RAMAC, 1956\|\| |
| Process of arranging scattered file parts | \|\|Defragmentation\|\| |
| What reads/writes on HDD | \|\|Read/write head\|\| |
| Modern HDD interface | \|\|SATA\|\| |
| Data loss when head touches platter | \|\|Head crash\|\| |

> [!warning] Exam Trap ⚠️
> **Seek time ≠ access time.** Access = seek + rotational latency. Also **defragment HDD, never SSD** (it only wears SSD out; SSDs use TRIM).
