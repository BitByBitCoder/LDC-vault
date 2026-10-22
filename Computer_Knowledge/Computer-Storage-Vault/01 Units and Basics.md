---
tags: [storage, units, basics]
aliases: [Storage Units, Bit Byte]
---
← [[00 Storage Index]] | Next → [[02 Memory Hierarchy]]

# 01 · Units and Basics

## The ladder (each step ×1024 = 2¹⁰)
```
bit ──×4──▶ nibble ──×2──▶ byte ──×1024──▶ KB ──×1024──▶ MB ──×1024──▶ GB
                                                                      │
 YB ◀──×1024── ZB ◀──×1024── EB ◀──×1024── PB ◀──×1024── TB ◀──×1024──┘
```

| Unit | Equals | Power of 2 |
|------|--------|-----------|
| Bit | 0 or 1 (smallest unit) | 2⁰ bit |
| Nibble | 4 bits | |
| Byte | 8 bits | 2³ bits |
| Kilobyte (KB) | 1024 bytes | 2¹⁰ B |
| Megabyte (MB) | 1024 KB | 2²⁰ B |
| Gigabyte (GB) | 1024 MB | 2³⁰ B |
| Terabyte (TB) | 1024 GB | 2⁴⁰ B |
| Petabyte (PB) | 1024 TB | 2⁵⁰ B |
| Exabyte (EB) | 1024 PB | 2⁶⁰ B |
| Zettabyte (ZB) | 1024 EB | 2⁷⁰ B |
| Yottabyte (YB) | 1024 ZB | 2⁸⁰ B |

**Memory trick:** **K**ids **M**ake **G**reat **T**oys, **P**eople **E**njoy **Z**ebra **Y**ards (K M G T P E Z Y).

## Decimal vs binary
- Binary (OS, RAM): 1 KB = 1024 B. Formal names: KiB, MiB, GiB, TiB.
- Decimal (drive makers): 1 GB = 10⁹ B, 1 TB = 10¹² B.
- That is why a **1 TB drive shows ≈ 931 GB** in Windows.

## Other basics
- **Character:** ASCII = 1 byte per character. Unicode (UTF-16) ≈ 2 bytes.
- **Word:** number of bits the CPU processes at once (varies: 16, 32, 64).
- **Storage uses Bytes (B). Network speed uses bits (b).** 8 Mbps = 1 MB/s.
- **Capacity** = how much it holds. **Access time** = how fast data is found.
- **Volatile** = loses data when power is off. **Non-volatile** = keeps it.
- **Access methods:** Sequential (tape), Direct/Random (RAM, HDD, SSD).

## Approximate access times (orders of magnitude)
| Device | Time scale |
|--------|-----------|
| Register | < 1 ns |
| Cache | ~1–10 ns |
| RAM | ~10–100 ns |
| SSD | ~0.1 ms (100 µs) |
| HDD | ~5–10 ms |
| Tape | seconds to minutes |

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| Smallest unit of data | \|\|Bit\|\| |
| 1 byte = how many bits | \|\|8\|\| |
| 1 nibble = how many bits | \|\|4\|\| |
| 1 KB = how many bytes | \|\|1024\|\| |
| Unit after TB | \|\|Petabyte (PB)\|\| |
| Unit after Zettabyte | \|\|Yottabyte\|\| |
| 1 GB = how many MB | \|\|1024\|\| |
| Why does 1 TB drive show ~931 GB | \|\|Maker uses decimal (10¹²), OS uses binary (2³⁰)\|\| |
| Mbps vs MBps | \|\|Mbps = megabits/s, MBps = megabytes/s, 1 MBps = 8 Mbps\|\| |

> [!warning] Exam Trap ⚠️
> **Bit ≠ Byte.** Storage is in **B** (capital), speed in **b** (small). Also, **KB = 1024**, not 1000, in exam answers unless the question says "decimal".
