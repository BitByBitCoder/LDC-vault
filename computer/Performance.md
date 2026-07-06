### Performance Question

**"The average time required to reach a storage location in memory and
obtain its contents is called \_\_\_\_\_\_."**

✅ **Correct Answer:** **Access Time**

# Where This Topic Belongs (Topic Tree)

    Computer Fundamentals
    │
    ├── Computer Hardware
    │
    └── Memory System
        │
        ├── Types of Memory
        │  ├─ Primary Memory
        │  │  ├─ RAM
        │  │  ├─ ROM
        │  │  └─ Cache
        │  │
        │  └─ Secondary Memory
        │      ├─ HDD
        │      ├─ SSD
        │      └─ Optical Disk
        │
        └── Memory Performance
            │
            ├─ Access Time
            ├─ Memory Cycle Time
            ├─ Latency
            └─ Transfer Rate

So the topic path is:

    Memory System
    ↓
    Memory Performance
    ↓
    Access Time

# What **Access Time** Means

**Access Time** = the **average time taken by the CPU to locate and read
data from memory**.

Example process:

    CPU requests data
    ↓
    Memory finds address
    ↓
    Data retrieved
    ↓
    Sent back to CPU

The time taken for this entire process = **Access Time**.

# Example Values

  Memory Type   Access Time
  ------------- -----------------------
  Cache         \~1 nanosecond
  RAM           \~50--100 nanoseconds
  SSD           \~0.1 milliseconds
  HDD           \~5--10 milliseconds

Lower access time = **faster memory**.

# Related Terms (Often Asked Together)

  Term                Meaning
  ------------------- ------------------------------------
  Access Time         Time to locate and read data
  Memory Cycle Time   Time between two memory operations
  Latency             Delay before data transfer begins
  Transfer Rate       Speed of data transfer

# Typical Exam Questions

1️⃣ **Average time to obtain data from memory**\
→ **Access Time**

2️⃣ **Time between two memory operations**\
→ **Memory Cycle Time**

3️⃣ **Speed of memory data transfer**\
→ **Transfer Rate**

✔ **Simple memory trick**

    Access Time = time to reach memory + get data
