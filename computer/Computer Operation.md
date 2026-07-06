The topic **"Arithmetic Operations"** usually appears in **Computer
Fundamentals → CPU → Arithmetic Logic Unit (ALU)**.\
It explains **what kinds of operations a computer processor performs on
data**.

I'll show you the **full topic hierarchy (up-topics and subtopics)** and
explain each part.

# OPERATIONS IN COMPUTER --- COMPLETE TOPIC TREE

    Computer Fundamentals
    │
    ├── Computer Hardware
    │  │
    │  └── Central Processing Unit (CPU)
    │      │
    │      ├── Control Unit
    │      │
    │      └── Arithmetic Logic Unit (ALU)
    │          │
    │          ├── Arithmetic Operations
    │          │  ├─ Addition
    │          │  ├─ Subtraction
    │          │  ├─ Multiplication
    │          │  └─ Division
    │          │
    │          ├── Logical Operations
    │          │  ├─ AND
    │          │  ├─ OR
    │          │  ├─ NOT
    │          │  └─ XOR
    │          │
    │          ├── Comparison Operations
    │          │  ├─ Equal
    │          │  ├─ Greater than
    │          │  └─ Less than
    │          │
    │          └── Bitwise Operations
    │              ├─ Shift left
    │              ├─ Shift right
    │              └─ Bit masking

# 1. WHAT IS AN OPERATION

An **operation** is an **action performed on data by the CPU**.

Example

    5 + 3

The computer performs the **addition operation**.

# 2. ARITHMETIC OPERATIONS

Arithmetic operations are **mathematical calculations** performed by the
computer.

### Types

  Operation        Example
  ---------------- ---------
  Addition         5 + 3
  Subtraction      7 − 2
  Multiplication   4 × 6
  Division         8 ÷ 2

These operations are executed inside the **ALU (Arithmetic Logic
Unit)**.

# 3. LOGICAL OPERATIONS

Logical operations compare **true or false values**.

  Operation   Example
  ----------- -----------------------
  AND         True if both are true
  OR          True if one is true
  NOT         Reverses value
  XOR         True if values differ

Example

    1 AND 1 = 1
    1 AND 0 = 0

# 4. COMPARISON OPERATIONS

Used to **compare numbers or values**.

  Operation      Example
  -------------- ---------
  Equal          5 = 5
  Greater than   7 \> 3
  Less than      2 \< 8

Used heavily in **programming and decision making**.

# 5. BITWISE OPERATIONS

These operations work on **binary numbers (bits)**.

Example

    0101 AND 0011
    = 0001

Types:

- Shift left
- Shift right
- Bit masking

# WHERE THIS TOPIC FITS IN COMPUTER FUNDAMENTALS

    Computer Fundamentals
    │
    ├── Computer Hardware
    │  └── CPU
    │      └── ALU
    │          └── Operations

So the **operation topic belongs to the CPU section**.

# HOW CPU PERFORMS OPERATIONS

    Input data
          ↓
    Registers
          ↓
    ALU performs operation
          ↓
    Result stored in memory

# COMMON EXAM QUESTION

**Which unit performs arithmetic operations in a computer?**

Answer:

**Arithmetic Logic Unit (ALU)**.

If you want, I can also show you the **FULL CPU ARCHITECTURE TREE (200+
topics)** including:

- registers
- instruction cycle
- fetch--decode--execute
- machine instructions
- addressing modes

This will show **exactly where operations fit in the processor
architecture.**

Result\
\
\
Good question 👍\
You are asking **what type of result each computer operation
produces**.\
This belongs to **CPU → Arithmetic Logic Unit (ALU) → Operations →
Result Types**.

# RESULT OF DIFFERENT OPERATIONS

    Computer Fundamentals
    │
    └── CPU
        │
        └── Arithmetic Logic Unit (ALU)
            │
            ├── Arithmetic Operations → Result: Number
            ├── Logical Operations → Result: Boolean (True/False)
            ├── Comparison Operations → Result: Boolean (True/False)
            └── Bitwise Operations → Result: Binary number

# 1. ARITHMETIC OPERATIONS

Arithmetic operations perform **mathematical calculations**.

### Result Type

➡ **Numeric value (number)**

### Examples

  Operation        Example   Result
  ---------------- --------- --------
  Addition         5 + 3     8
  Subtraction      10 − 4    6
  Multiplication   6 × 2     12
  Division         8 ÷ 2     4

So the **output is always a number**.

# 2. LOGICAL OPERATIONS

Logical operations work with **truth values**.

### Result Type

➡ **Boolean value**

Possible results:

    True
    False

### Examples

  Operation   Example          Result
  ----------- ---------------- --------
  AND         True AND False   False
  OR          True OR False    True
  NOT         NOT True         False

# 3. COMPARISON OPERATIONS

These compare values.

### Result Type

➡ **Boolean value**

### Examples

  Operation      Example   Result
  -------------- --------- --------
  Equal          5 = 5     True
  Greater than   7 \> 4    True
  Less than      3 \< 2    False

# 4. BITWISE OPERATIONS

These operate on **binary numbers (bits)**.

### Result Type

➡ **Binary number**

### Example

    0101 AND 0011
    = 0001

The result is still **binary data**.

# SUMMARY TABLE

  Operation Type   Result
  ---------------- ---------------
  Arithmetic       Number
  Logical          True / False
  Comparison       True / False
  Bitwise          Binary number

# SIMPLE VIEW

    Arithmetic → Number
    Logical → True / False
    Comparison → True / False
    Bitwise → Binary number

✅ If you want, I can also show you **ALL CPU OPERATIONS (about 25--30
types)** including:

- increment
- decrement
- shift
- rotate
- modulo
- logical negation

These are the **actual operations real processors support**.
