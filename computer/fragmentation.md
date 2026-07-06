Fragemntation\

### Question

**123. Fragmentation of the file system**

\(a\) can always be prevented\
(b) can be temporarily removed by compaction\
(c) is a characteristic of all file systems\
(d) None of these

# ✅ Correct Answer

**(b) can be temporarily removed by compaction**

# Where This Topic Belongs (Topic Tree)

    Computer Fundamentals
    │
    └── Operating System
        │
        ├── File System
        │  │
        │  ├─ File Allocation Methods
        │  │  ├─ Contiguous allocation
        │  │  ├─ Linked allocation
        │  │  └─ Indexed allocation
        │  │
        │  └─ Disk Management
        │      │
        │      ├─ Fragmentation
        │      │  ├─ Internal fragmentation
        │      │  └─ External fragmentation
        │      │
        │      └─ Compaction / Defragmentation

So the topic path is:

    Operating System
    ↓
    File System
    ↓
    Disk Management
    ↓
    Fragmentation

# What Fragmentation Means

Fragmentation occurs when **files are stored in non-continuous blocks on
disk**.

Example:

    File A
    Block 3
    Block 15
    Block 27

The file pieces are **scattered across the disk**.

This makes the disk **slower** because the system must search multiple
locations.

# Types of Fragmentation

## 1️⃣ External Fragmentation

Free memory space becomes **scattered into small pieces**.

Example:

    Free blocks
    Block 4
    Block 10
    Block 18

## 2️⃣ Internal Fragmentation

Allocated memory contains **unused space inside blocks**.

Example:

    Block size = 8 KB
    File size = 6 KB
    Unused space = 2 KB

# What Compaction Does

Compaction rearranges files to make them **continuous again**.

Example:

    Before
    File blocks scattered

    After
    File blocks placed together

Compaction **reduces fragmentation temporarily**.

# Why Other Options Are Wrong

### (a) can always be prevented

❌ Wrong --- fragmentation naturally occurs during file creation and
deletion.

### (c) is a characteristic of all file systems

❌ Wrong --- some file systems reduce fragmentation.

### (d) None of these

❌ Incorrect because option **(b)** is correct.

# Simple Memory Trick

    Fragmentation = scattered files
    Compaction = rearrange files

If you want, I can also show you the **FULL FILE SYSTEM TREE (about 100+
concepts)** including:

- FAT / NTFS / EXT file systems
- disk scheduling
- file allocation methods
- storage management

These topics appear **very often in computer fundamentals exams**.

\
\
413. Fragmentation of the file system (a) prevented (b) temporarily
removed by compaction (c) characteristic of all (d) None of the above

The correct answer is:

**(b) temporarily removed by compaction**

**Explanation (quick):**\
Fragmentation occurs when files are stored in scattered locations. It
can be temporarily removed by **compaction/defragmentation**, which
rearranges data into contiguous blocks.
