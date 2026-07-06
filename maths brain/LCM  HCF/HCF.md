

# HCF (Highest Common Factor)

The **HCF** is the **largest number that divides two or more numbers exactly**.

Also called:

- Greatest Common Divisor (GCD)
    
- Greatest Common Factor (GCF)
    

---

## Example 1: HCF of 12 and 18

Factors of 12:

1, 2, 3, 4, 6, 12

Factors of 18:

1, 2, 3, 6, 9, 18

Common factors:

1, 2, 3, 6

Highest common factor:

**HCF = 6**

---

## Example 2: Using Prime Factorization

Find HCF of 24 and 36.

24 = 2³ × 3

36 = 2² × 3²

Take only the common prime factors with the **smallest power**:

2² × 3¹

= 4 × 3

= **12**

So:

**HCF(24, 36) = 12**

---

## Shortcut Method (Division)

Find HCF of 48 and 18:

48 ÷ 18 = 2 remainder 12

18 ÷ 12 = 1 remainder 6

12 ÷ 6 = 2 remainder 0

The last divisor is **6**.

So:

**HCF(48, 18) = 6**

---

### Practice

Find the HCF of:

1. 12 and 20
    
2. 18 and 24
    
3. 30 and 45
    
4. 84 and 126
    
5. 319 and 29
    

Try them, and I'll check your answers.


Shortcut
Yes. For **two numbers**, there is a useful formula:

[  
\text{HCF} \times \text{LCM} = \text{First Number} \times \text{Second Number}  
]

\text{HCF}\times\text{LCM}=a\times b

### Example

For 24 and 40:

- LCM = 120
    
- Product = 24 × 40 = 960
    

So:

HCF = 960 ÷ 120 = 8

✅ HCF = 8

---

### Fastest Method (Euclidean Algorithm)

For 24 and 40:

40 ÷ 24 = 1 remainder 16

24 ÷ 16 = 1 remainder 8

16 ÷ 8 = 2 remainder 0

When the remainder becomes **0**, the last divisor is the HCF.

✅ HCF = 8

---

### Which method should you use?

- Small numbers → List factors.
    
- Numbers with easy prime factors → Prime factorization.
    
- Large numbers → Euclidean algorithm (division method).
    

Try this one:

Find the HCF of **36 and 48** using the division method.