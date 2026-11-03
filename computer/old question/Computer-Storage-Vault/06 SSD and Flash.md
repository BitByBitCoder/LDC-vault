---
tags: [storage, ssd, flash, pendrive, sdcard, nvme]
aliases: [SSD, Pen Drive, USB Flash, SD Card, NVMe]
---
← [[00 Storage Index]] | ← [[05 HDD Magnetic Disk]] | Next → [[07 Optical Discs]]

# 06 · SSD and Flash Storage

**Flash** = non-volatile semiconductor memory ([[04 ROM and Types]]). **No moving parts.**

## SSD vs HDD
| Feature | SSD | HDD |
|---------|-----|-----|
| Technology | NAND flash chips | Magnetic platters |
| Moving parts | None | Yes |
| Speed | Much faster | Slower |
| Shock resistance | High | Low |
| Noise | Silent | Audible |
| Power | Lower | Higher |
| Cost per GB | Higher | Lower |
| Defrag | Not needed | Needed |
| Wear | Limited **write cycles** | Mechanical wear |

## SSD terms
- **Controller:** manages reads, writes, wear levelling.
- **Wear levelling:** spreads writes evenly across cells.
- **TRIM:** OS tells SSD which blocks are free.
- **Cell types (bits per cell):** **SLC 1** → **MLC 2** → **TLC 3** → **QLC 4**. More bits = cheaper, denser, slower, less durable.
- **Form factors / interfaces:** 2.5" SATA SSD · **M.2** slot · **NVMe** (protocol over PCIe, fastest).
- **SSHD (hybrid drive):** HDD with a small SSD cache.

## Portable flash
| Device | Facts |
|--------|-------|
| **Pen drive / USB flash drive** | Plug into USB port. Also called thumb drive, jump drive |
| **SD card** | Secure Digital. Sizes: SD, miniSD, **microSD** |
| **SDHC** | High Capacity: **4 GB to 32 GB** |
| **SDXC** | eXtended Capacity: **above 32 GB up to 2 TB** |
| **SDUC** | Ultra Capacity: up to 128 TB |
| **CompactFlash (CF)** | Older camera card |
| **eMMC** | Soldered flash in cheap phones and laptops |

## USB speeds
| Version | Max speed |
|---------|-----------|
| USB 1.1 | 12 Mbps |
| USB 2.0 | 480 Mbps |
| USB 3.0 / 3.2 Gen 1 | 5 Gbps |
| USB 3.1 Gen 2 | 10 Gbps |
| USB 3.2 Gen 2x2 | 20 Gbps |
| USB4 | 40 Gbps |

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| SSD uses what chips | \|\|NAND flash\|\| |
| SSD has moving parts? | \|\|No\|\| |
| SSD vs HDD: which is faster | \|\|SSD\|\| |
| Which is costlier per GB | \|\|SSD\|\| |
| SD card full form | \|\|Secure Digital\|\| |
| SDHC capacity range | \|\|4 GB to 32 GB\|\| |
| SDXC capacity range | \|\|Above 32 GB to 2 TB\|\| |
| SLC stores how many bits per cell | \|\|1\|\| |
| Fastest SSD interface | \|\|NVMe (over PCIe, M.2)\|\| |
| Should an SSD be defragmented | \|\|No\|\| |
| Pen drive is volatile or non-volatile | \|\|Non-volatile\|\| |

> [!warning] Exam Trap ⚠️
> **Pen drive, SSD and memory card are flash = non-volatile, secondary.** Do **not** confuse flash with RAM. **SDHC ≤ 32 GB, SDXC > 32 GB.**
