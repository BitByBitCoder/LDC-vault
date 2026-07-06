Error detection\
\
The topic **Parity Bit** belongs to **Data Representation → Error
Detection** in Computer Fundamentals.\
It is related to **binary data transmission and error checking**.

Below is the **complete topic tree with all up-topics and subtopics** so
you see exactly where it fits.

# PARITY BIT --- COMPLETE TOPIC TREE

    Computer Fundamentals
    │
    ├── Data Representation
    │  │
    │  ├── Binary Data
    │  │  ├─ Bit
    │  │  ├─ Byte
    │  │  └─ Binary numbers
    │  │
    │  ├── Character Encoding
    │  │  ├─ ASCII
    │  │  ├─ Unicode
    │  │  └─ EBCDIC
    │  │
    │  └── Data Communication
    │      │
    │      └── Error Detection and Correction
    │          │
    │          ├── Error Detection Methods
    │          │  ├─ Parity Bit
    │          │  ├─ Checksum
    │          │  ├─ Cyclic Redundancy Check (CRC)
    │          │  └─ Hamming Code
    │          │
    │          └── Error Correction
    │              ├─ Forward error correction
    │              └─ Automatic retransmission

# WHAT IS A PARITY BIT

A **parity bit** is an **extra bit added to binary data to detect
transmission errors**.

Example:

    Original data
    1011001

Add parity bit:

    10110010

If the data changes during transmission, the system can **detect an
error**.

# TYPES OF PARITY

    Parity Bit
    │
    ├── Even Parity
    └── Odd Parity

## EVEN PARITY

The total number of **1s must be even**.

Example:

    Data
    1011

    Number of 1s = 3
    Add parity bit = 1

    Final data
    10111

Now number of **1s = 4 (even)**.

## ODD PARITY

The total number of **1s must be odd**.

Example:

    Data
    1011

    Number of 1s = 3
    Parity bit = 0

    Final data
    10110

Now number of **1s = 3 (odd)**.

# WHY PARITY BIT IS USED

Purpose:

- detect transmission errors
- ensure data integrity
- check corrupted data

Used in:

- memory systems
- network communication
- data transmission

# PARITY BIT PROCESS

    Data generated
          ↓
    Parity bit added
          ↓
    Data transmitted
          ↓
    Receiver checks parity
          ↓
    Error detected or data accepted

# RELATED TOPICS

Parity bit connects to several other computer topics:

    Data Representation
    │
    ├─ Binary numbers
    ├─ Bits and bytes
    ├─ Character encoding
    │
    └─ Data Communication
        ├─ Error detection
        ├─ Data transmission
        └─ Network communication

# IMPORTANT EXAM POINTS

  Concept       Meaning
  ------------- ------------------------------------
  Parity bit    Extra bit used for error detection
  Even parity   Number of 1s must be even
  Odd parity    Number of 1s must be odd

# COMMON EXAM QUESTION

Example:

**What is a parity bit?**

Answer:\
A **parity bit is an extra bit added to binary data to detect errors
during transmission**.

If you want, I can also show you the **complete DATA REPRESENTATION
MASTER TREE** connecting:

    Number systems
    ↓
    Binary arithmetic
    ↓
    Character encoding
    ↓
    Error detection
    ↓
    Parity bit

This whole chapter is **one of the most confusing parts of computer
fundamentals**, but once you see the **full structure it becomes much
easier.**
