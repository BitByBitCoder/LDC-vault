---
tags: [storage, raid]
aliases: [RAID, Disk Array]
---
← [[00 Storage Index]] | ← [[09 Cloud DAS NAS SAN]] | Next → [[11 File Systems]]

# 10 · RAID

**Redundant Array of Independent (originally *Inexpensive*) Disks.** Many disks combined for **speed**, **safety**, or both. Proposed by **Patterson, Gibson and Katz (1987)**.

## Core ideas
- **Striping:** split data across disks → **speed**.
- **Mirroring:** exact copy on another disk → **safety**.
- **Parity:** extra calculated data to **rebuild** a failed disk.

```
RAID 0 (stripe)    RAID 1 (mirror)    RAID 5 (stripe + parity)
 A1 | A2            A  | A             A1 | A2 | P
 A3 | A4            B  | B             B1 | P  | B2
 fast, NO safety    copy, safe         P  | C1 | C2
                                       parity rotates across disks
```

| Level | Technique | Min disks | Survives | Usable capacity (n disks of size s) |
|-------|-----------|-----------|----------|-------------------------------------|
| **RAID 0** | Striping | 2 | **0** failures | n × s |
| **RAID 1** | Mirroring | 2 | 1 failure | s (2 disks), n/2 × s |
| **RAID 5** | Stripe + distributed parity | **3** | **1** disk | (n − 1) × s |
| **RAID 6** | Stripe + double parity | **4** | **2** disks | (n − 2) × s |
| **RAID 10 (1+0)** | Mirror then stripe | **4** | 1 per mirror pair | n/2 × s |

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| RAID full form | \|\|Redundant Array of Independent Disks\|\| |
| RAID with no fault tolerance | \|\|RAID 0\|\| |
| RAID using mirroring | \|\|RAID 1\|\| |
| Min disks for RAID 5 | \|\|3\|\| |
| Min disks for RAID 6 | \|\|4\|\| |
| Min disks for RAID 10 | \|\|4\|\| |
| RAID 6 survives how many failed disks | \|\|2\|\| |
| Fastest, but zero safety | \|\|RAID 0\|\| |
| Original meaning of "I" in RAID | \|\|Inexpensive\|\| |

> [!warning] Exam Trap ⚠️
> **RAID 0 is NOT redundant** despite the name. **RAID is not a backup.** Deleted or corrupted files are copied to every disk too.
