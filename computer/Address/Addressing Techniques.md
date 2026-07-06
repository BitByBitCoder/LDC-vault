

Addressing techniques are methods used by the operating system to **organize and manage memory addresses**.

## 1. Contiguous Allocation
- Entire process is stored in a single continuous block of memory
- Simple to implement
- Can cause fragmentation

## 2. Paging
- Memory is divided into fixed-size blocks:
  - Pages (logical)
  - Frames (physical)
- Eliminates external fragmentation
- Uses page tables for mapping

## 3. Segmentation
- Memory is divided into variable-sized segments
- Each segment represents a logical part of a program (code, data, stack)
- Easier for programmers to manage

## Key Idea
- These techniques help in **efficient memory utilization and address management**