---
tags: [storage, filesystem, fat32, ntfs, ext4]
aliases: [File System, FAT32, NTFS, exFAT, ext4, APFS]
---
← [[00 Storage Index]] | ← [[10 RAID]] | Next → [[12 Calculations]]

# 11 · File Systems

**File system** = method the OS uses to name, store, and find files on a disk. Created during **high-level format** ([[05 HDD Magnetic Disk]]). Smallest allocation unit = **cluster**.

| File system | OS / use | Key facts |
|-------------|----------|-----------|
| **FAT** (File Allocation Table) | Old DOS/Windows | Table maps clusters. FAT12 floppy, FAT16 |
| **FAT32** | Pen drives, universal | Max single file **4 GB** (less 1 byte) |
| **exFAT** | Large pen drives, SD (SDXC) | No 4 GB limit. Works on Windows and Mac |
| **NTFS** | Windows (modern) | Journaling, permissions, encryption (EFS), compression, large files |
| **ext4** | Linux | Journaling. Also ext2, ext3 |
| **HFS+ / APFS** | macOS / iOS | APFS = Apple File System (SSD optimised) |

## Terms
- **Partition:** logical division of a disk (C:, D:).
- **Journaling:** log of changes so the disk recovers after crash.
- **Fragmentation:** file pieces scattered in clusters.
- **Root directory:** top-level folder. **Path:** location of a file (C:\Users\...).
- **Metadata:** info about the file (name, size, date, permissions).

## 🧪 Self-test
| Question | Answer |
|----------|--------|
| FAT full form | \|\|File Allocation Table\|\| |
| Max file size in FAT32 | \|\|4 GB\|\| |
| Modern Windows file system | \|\|NTFS\|\| |
| Linux file system | \|\|ext4 (ext family)\|\| |
| macOS modern file system | \|\|APFS\|\| |
| Best file system for big pen drive across OSes | \|\|exFAT\|\| |
| Logical division of a disk | \|\|Partition\|\| |
| Log that protects after a crash | \|\|Journal\|\| |
| Allocation unit of file system | \|\|Cluster\|\| |

> [!warning] Exam Trap ⚠️
> **FAT32 cannot hold a single file above 4 GB**, so a 6 GB movie fails on a FAT32 pen drive. Use exFAT or NTFS.
