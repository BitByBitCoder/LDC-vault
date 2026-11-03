---
tags: [storage, primary, ram, cache, registers]
aliases: [RAM, Cache, Registers, SRAM, DRAM, Virtual Memory]
---
← [[00 Storage Index]] | ← [[02 Memory Hierarchy]] | Next → [[04 ROM and Types]]

# 03 · Primary Memory (Registers, Cache, RAM)

## Registers
Tiny, fastest storage **inside the CPU**. Hold the data or instruction being processed right now.

| Register | Job |
|----------|-----|
| Accumulator (AC) | Holds results of ALU operations |
| Program Counter (PC) | Address of the **next** instruction |
| Instruction Register (IR) | Instruction **currently** executing |
| Memory Address Register (MAR) | Address to read or write in memory |
| Memory Data Register (MDR/MBR) | Data being read or written |
| Stack Pointer (SP) | Top of the stack |
| Flag/Status Register | Result flags (zero, carry, overflow) |

## Cache memory
- Small, very fast memory between CPU and RAM. Built from **SRAM**.
- Stores frequently used data and instructions.
- **Hit** = data found in cache. **Miss** = go to RAM.
- Levels: **L1** (smallest, fastest, inside each core) → **L2** → **L3** (largest, shared, slowest of the three).

## RAM (Random Access Memory)
- **Volatile**, read/write, main working memory. Any location reached in the same time ("random").
- Holds the OS, running programs, and their data.

### SRAM vs DRAM
| Feature | SRAM | DRAM |
|---------|------|------|
| Cell | Flip-flop (≈6 transistors) | 1 transistor + 1 capacitor |
| Refresh needed | **No** | **Yes** (capacitor leaks) |
| Speed | Faster | Slower |
| Cost | Costlier | Cheaper |
| Density | Low | High |
| Power | Lower when idle | Higher (refresh) |
| Used for | **Cache** | **Main RAM** |

### RAM types and modules
- **SDRAM:** synchronised with the system clock.
- **DDR SDRAM:** transfers data on **both** clock edges (Double Data Rate). Generations: DDR1 → DDR2 → DDR3 → DDR4 → DDR5. Not backward compatible (different notches).
- **GDDR / VRAM:** graphics memory.
- **DIMM:** desktop module. **SO-DIMM:** laptop module. **SIMM:** older module.

## Virtual memory
- Part of the **hard disk/SSD used as extra RAM** when RAM is full.
- Techniques: **paging** and **swapping**. File: page file (Windows) or swap (Linux).
- Too much swapping, system crawls = **thrashing**.

## Buffer vs Cache
| Buffer | Cache |
|--------|-------|
| Temporary holding area to match speed of two devices | Stores frequently used data for faster re-access |
| e.g. print spooler, video buffer | e.g. CPU cache, browser cache |

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| RAM full form | \|\|Random Access Memory\|\| |
| RAM is volatile or non-volatile | \|\|Volatile\|\| |
| Memory used for cache | \|\|SRAM\|\| |
| Memory used for main RAM | \|\|DRAM\|\| |
| Which needs refreshing | \|\|DRAM\|\| |
| Register holding next instruction address | \|\|Program Counter\|\| |
| Register holding result of arithmetic | \|\|Accumulator\|\| |
| Register holding current instruction | \|\|Instruction Register\|\| |
| DDR full form | \|\|Double Data Rate\|\| |
| Laptop RAM module | \|\|SO-DIMM\|\| |
| Virtual memory uses | \|\|Hard disk/SSD space as RAM\|\| |
| Fastest cache level | \|\|L1\|\| |
| Cache hit means | \|\|Needed data is found in cache\|\| |

> [!warning] Exam Trap ⚠️
> **SRAM = cache (fast, costly). DRAM = main RAM (cheap, refresh).** Students swap these. Also, **PC holds the NEXT instruction address; IR holds the CURRENT instruction.**
