---
tags: [storage, hierarchy]
aliases: [Memory Hierarchy, Storage Pyramid]
---
← [[00 Storage Index]] | ← [[01 Units and Basics]] | Next → [[03 Primary Memory]]

# 02 · Memory Hierarchy

## The pyramid
```
              ▲ Faster, Costlier, Smaller
             ┌───────────┐
             │ Registers │  inside CPU        ← fastest
            ┌┴───────────┴┐
            │ Cache L1/L2/L3 │  SRAM
           ┌┴──────────────┴┐
           │ Main Memory RAM │  DRAM         ← PRIMARY ends here
          ┌┴────────────────┴┐
          │ SSD / HDD         │             ← SECONDARY
         ┌┴──────────────────┴┐
         │ Optical, Tape, Cloud │           ← TERTIARY / OFFLINE
         └──────────────────────┘
              ▼ Slower, Cheaper, Larger
```

## Three classes
| Class | Examples | CPU access | Volatile? |
|-------|----------|-----------|-----------|
| **Primary** (main) | Registers, Cache, RAM, ROM | Direct | RAM/Cache/Registers = Yes. ROM = No |
| **Secondary** (auxiliary) | HDD, SSD, pen drive, CD/DVD | Via I/O, data loaded to RAM first | No |
| **Tertiary / Offline** | Tape library, optical jukebox, archives | Robot or manual mount | No |

## Moving down the pyramid
- Speed ↓
- Capacity ↑
- Cost per bit ↓
- CPU access frequency ↓

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| Fastest memory in a computer | \|\|Registers\|\| |
| Memory between CPU and RAM | \|\|Cache\|\| |
| Which is primary memory | \|\|RAM, ROM, Cache, Registers\|\| |
| Which is secondary memory | \|\|HDD, SSD, CD, DVD, pen drive\|\| |
| Cheapest per GB | \|\|Magnetic tape / HDD (among common)\|\| |
| Costliest per GB | \|\|Registers / Cache\|\| |
| Another name for secondary memory | \|\|Auxiliary / backup / external memory\|\| |
| CPU talks directly to | \|\|Primary memory only\|\| |
| Order by speed (fast→slow) | \|\|Register > Cache > RAM > SSD > HDD > Optical > Tape\|\| |

> [!warning] Exam Trap ⚠️
> **ROM is primary** even though it is non-volatile. **Cache and registers are also primary**, not "special". Pen drive and SSD are **secondary** even though they are flash.
