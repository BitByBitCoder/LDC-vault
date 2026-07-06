COMPUTER PERFORMANCE LAWS\
\
You are talking about **"laws in computing"** like **Moore's Law**. In
computer fundamentals, these are **performance laws / principles** that
explain how computers grow in speed, power, and efficiency.

Below is a **complete topic tree + important facts** you should know.

# COMPUTER PERFORMANCE LAWS

    Computer Performance Laws
     ├─ Moore's Law
     ├─ Amdahl's Law
     ├─ Gustafson's Law
     ├─ Metcalfe's Law
     ├─ Kryder's Law
     ├─ Wirth's Law
     ├─ Dennard Scaling
     └─ Koomey's Law

# 1. MOORE\'S LAW

### Who proposed it

**Gordon Moore**

- Co-founder of **Intel**

### Year

**1965**

### Definition

The **number of transistors on a microchip doubles about every 18--24
months**, making computers **faster and cheaper**.

### Meaning

More transistors → more processing power.

### Example

    1970 CPU
    ≈ 2,000 transistors

    Modern CPU
    ≈ tens of billions

### Importance

Explains why computers become:

- faster
- smaller
- cheaper

# 2. AMDAHL\'S LAW

### Who proposed it

**Gene Amdahl**

### Year

1967

### Definition

The **maximum speed improvement of a system is limited by the part that
cannot be parallelized**.

### Meaning

If some tasks must run **sequentially**, adding more processors gives
limited benefit.

### Simple Example

    Program
    90% parallel
    10% sequential

    Maximum speedup ≈ 10×

### Used in

- parallel computing
- supercomputers

# 3. GUSTAFSON\'S LAW

### Who proposed it

**John Gustafson**

### Year

1988

### Definition

Increasing the number of processors allows **larger problems to be
solved efficiently**.

### Idea

Instead of making programs faster, **solve bigger problems**.

### Used in

- supercomputing
- scientific simulations

# 4. METCALFE\'S LAW

### Who proposed it

**Robert Metcalfe**

### Year

1980

### Definition

The **value of a network is proportional to the square of the number of
connected users**.

### Formula

    Value ∝ n²

### Example

10 users → 100 connections possible.

### Used in

- Internet growth
- social networks
- communication networks

# 5. KRYDER\'S LAW

### Who proposed it

**Mark Kryder**

### Definition

The **storage capacity of hard drives increases rapidly over time**.

### Meaning

Hard disks store more data every year.

Example

    1980 HDD
    ≈ 10 MB

    Today
    ≈ 20 TB+

# 6. WIRTH\'S LAW

### Who proposed it

**Niklaus Wirth**

### Definition

**Software becomes slower faster than hardware becomes faster.**

Meaning

    Software bloat
    ↓
    programs require more resources

# 7. DENNARD SCALING

### Who proposed it

**Robert Dennard**

### Definition

As **transistors become smaller**, their **power consumption stays
constant**.

This allowed CPUs to become faster without overheating.

But it **broke around 2005**, leading to multicore CPUs.

# 8. KOOMEY\'S LAW

### Who proposed it

**Jonathan Koomey**

### Definition

The **number of computations per joule of energy doubles every 1.5
years**.

Meaning\
Computers become **more energy efficient** over time.

# COMPLETE RELATIONSHIP TREE

    Computer Growth Laws
    │
    ├─ Hardware Growth
    │  ├─ Moore's Law
    │  ├─ Dennard Scaling
    │  └─ Kryder's Law
    │
    ├─ Performance Limits
    │  ├─ Amdahl's Law
    │  └─ Gustafson's Law
    │
    ├─ Network Growth
    │  └─ Metcalfe's Law
    │
    └─ Software Trends
        └─ Wirth's Law

# QUICK EXAM SUMMARY

  Law                Field                Main Idea
  ------------------ -------------------- --------------------------------------------
  Moore\'s Law       Hardware             Transistors double every \~2 years
  Amdahl\'s Law      Parallel computing   Sequential part limits speed
  Gustafson\'s Law   Supercomputing       More processors solve larger problems
  Metcalfe\'s Law    Networks             Network value grows with users²
  Kryder\'s Law      Storage              HDD capacity grows rapidly
  Wirth\'s Law       Software             Software becomes slower over time
  Dennard Scaling    Chip design          Power stays constant as transistors shrink
  Koomey\'s Law      Energy               Efficiency doubles every 1.5 years

✅ If you want, I can also give you a **FULL COMPUTER FUNDAMENTALS
MASTER TREE (500+ topics)** from your **Pradeep K. Sinha book**, which
is extremely useful for **competitive exams like LDC**.
