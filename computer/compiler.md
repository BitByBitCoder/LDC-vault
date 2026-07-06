Compiler execute\
Question

**177. What is the first step for converting high level language to
executable code?**

\(a\) Semantic analysis\
(b) Lexical analysis\
(c) Syntax analysis\
(d) Source analysis

# ✅ Correct Answer

**(b) Lexical analysis**

# Where This Topic Belongs (Topic Tree)

    Computer Fundamentals
    │
    └── System Software
        │
        └── Language Translators
            │
            ├─ Assembler
            ├─ Interpreter
            └─ Compiler
                │
                └── Compilation Process
                    ├─ Lexical Analysis
                    ├─ Syntax Analysis
                    ├─ Semantic Analysis
                    ├─ Code Optimization
                    └─ Code Generation

Topic path:

    System Software
    ↓
    Compiler
    ↓
    Compilation Process
    ↓
    Lexical Analysis

# Steps in Converting High-Level Language to Executable Code

    Source code
    ↓
    Lexical analysis
    ↓
    Syntax analysis
    ↓
    Semantic analysis
    ↓
    Code generation
    ↓
    Executable program

# 1️⃣ Lexical Analysis (First Step)

Lexical analysis breaks the program into **tokens**.

Tokens include:

- keywords
- identifiers
- operators
- constants

Example:

    int x = 5;

Tokens:

    int | x | = | 5 | ;

# 2️⃣ Syntax Analysis

Checks whether the program follows **grammar rules**.

Example:

    x = 5 + ;

This is a **syntax error**.

# 3️⃣ Semantic Analysis

Checks **meaning and correctness**.

Example:

    int x;
    x = "hello";

This is a **semantic error** (type mismatch).

# Why Other Options Are Wrong

  Option              Reason
  ------------------- -------------------------------
  Semantic analysis   occurs after syntax analysis
  Syntax analysis     second stage
  Source analysis     not a standard compiler stage

# Simple Memory Trick

    Lexical → Syntax → Semantic

First step = **Lexical analysis**.

If you want, I can also show you the **FULL COMPILER DESIGN TREE (100+
concepts)** including:

- parsing
- symbol tables
- intermediate code
- optimization
- linking and loading

This topic appears **often in computer fundamentals and programming
exams**.
