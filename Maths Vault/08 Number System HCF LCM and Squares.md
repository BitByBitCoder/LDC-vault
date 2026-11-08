---
tags: [maths, ldc, high-priority]
priority: 🔴 HIGH
---

← [[00 Maths Vault Index]]

# Number System HCF LCM and Squares

> [!abstract] 🔴 HIGH · ≈11% of arithmetic questions · Target accuracy **90%+** · Budget **2 days**
> Divisibility, 'least number to add/subtract', HCF/LCM word problems and perfect squares — all fixed templates.

## Core formulas

| Concept | Formula | Quick example / shortcut |
|---|---|---|
| Add to be divisible by d | d − remainder | 1057 ÷ 23 → rem 22 → add 1 |
| Subtract to be divisible | remainder |  |
| Add to make perfect square | (next square) − n | 1290 → 36² = 1296 → 6 |
| Divide to make perfect square | Product of **unpaired** primes | 2925 = 3²·5²·13 → 13 |
| No. of factors | Π (power + 1) | 72 = 2³·3² → 4×3 = 12 |
| Sum of factors | Π (1 + p + … + pᵏ) | 200 → 15 × 31 = 465 |
| HCF with same remainder r | HCF of (a − r), (b − r) | 98, 126, r=2 → HCF(96,124) = 4 |
| Two numbers with HCF h, ratio a:b | ha and hb | 15:11, HCF 13 → 195, 143 |
| Largest n-digit divisible by m | n-digit max − (max mod LCM) | 99999 − 639 = 99360 |

## Visual

```text
        200
       /    \
      2     100          200 = 2³ × 5²
           /   \          factors = (3+1)(2+1) = 12
          2     50         sum    = (1+2+4+8)(1+5+25) = 465
               /  \
              2    25 = 5×5
```

## Past-paper Q&A

Cover the last two columns, solve, then reveal. Sorted easy → hard (block learning), then re-shuffle for interleaved review.

| # | Question | Difficulty | Answer | Method |
|---|---|---|---|---|
| 1 | Number ÷ 6 gives quotient 15, remainder 4. Number? | ⭐ | \|\|94\|\| | \|\|6×15 + 4\|\| |
| 2 | Least number to add to 1057 to be divisible by 23? | ⭐ | \|\|1\|\| | \|\|23 × 46 = 1058\|\| |
| 3 | Smallest to subtract from 52 to be divisible by 7? | ⭐ | \|\|3\|\| | \|\|52 − 49\|\| |
| 4 | Smallest to subtract from 8,972 to be divisible by 6? | ⭐ | \|\|2\|\| | \|\|8972 mod 6 = 2\|\| |
| 5 | Least four-digit perfect square? | ⭐ | \|\|1024\|\| | \|\|32²\|\| |
| 6 | Square root of 1024? | ⭐ | \|\|32\|\| | \|\|32² = 1024\|\| |
| 7 | Next term: 7, 11, 13, 17, 19, … | ⭐ | \|\|23\|\| | \|\|Primes\|\| |
| 8 | How many odd numbers: 121, 212, 414, 373, 124, 2288, 2377, 2654, 2779? | ⭐ | \|\|4\|\| | \|\|121, 373, 2377, 2779\|\| |
| 9 | Tens digit is twice units digit, digit sum 9. Number? | ⭐ | \|\|63\|\| | \|\|2u + u = 9\|\| |
| 10 | Sum of three consecutive even numbers = 72. Smallest? | ⭐ | \|\|22\|\| | \|\|72/3 − 2\|\| |
| 11 | Sum of three consecutive odd numbers = 87. Smallest? | ⭐ | \|\|27\|\| | \|\|29 − 2\|\| |
| 12 | Which is not prime: 13, 87, 131, 277? | ⭐⭐ | \|\|87\|\| | \|\|3 × 29\|\| |
| 13 | Which is not prime: 233, 251, 241, 259? | ⭐⭐ | \|\|259\|\| | \|\|7 × 37\|\| |
| 14 | Add 1875 + ? to be divisible by 29? | ⭐⭐ | \|\|10\|\| | \|\|1885 = 29 × 65\|\| |
| 15 | Digit sum 9, digit difference 5. Number? | ⭐⭐ | \|\|72 or 27\|\| | \|\|7+2, 7−2\|\| |
| 16 | How many factors does 72 have? | ⭐⭐ | \|\|12\|\| | \|\|(3+1)(2+1)\|\| |
| 17 | Sum of squares of three consecutive numbers = 434. Their sum? | ⭐⭐ | \|\|36\|\| | \|\|11, 12, 13\|\| |
| 18 | Add what to 1290 to get a perfect square? | ⭐⭐ | \|\|6\|\| | \|\|36² = 1296\|\| |
| 19 | Add what to 8200 to get a perfect square? | ⭐⭐ | \|\|81\|\| | \|\|91² = 8281\|\| |
| 20 | Least number to divide 2925 by to get a perfect square? | ⭐⭐ | \|\|13\|\| | \|\|Unpaired prime\|\| |
| 21 | Ratio 15:11, HCF 13. Numbers? | ⭐⭐ | \|\|195, 143\|\| | \|\|Multiply by 13\|\| |
| 22 | LCM of 8, 15, 24, 72? | ⭐⭐ | \|\|360\|\| | \|\|2³·3²·5\|\| |
| 23 | LCM of two numbers is 48, ratio 2:3. Sum? | ⭐⭐ | \|\|40\|\| | \|\|6k = 48 → k = 8\|\| |
| 24 | Smallest 5-digit number divisible by 279? | ⭐⭐ | \|\|10,044\|\| | \|\|36 × 279\|\| |
| 25 | Sum of all factors of 200? | ⭐⭐⭐ | \|\|465\|\| | \|\|15 × 31\|\| |
| 26 | Greatest number dividing 1241 and 949? | ⭐⭐⭐ | \|\|73\|\| | \|\|HCF(949, 292) = 73\|\| |
| 27 | HCF of 325, 884, 1469? | ⭐⭐⭐ | \|\|13\|\| | \|\|325 = 5²·13; 884 = 4·13·17\|\| |
| 28 | Greatest number dividing 98 and 126 leaving remainder 2? | ⭐⭐⭐ | \|\|4\|\| | \|\|HCF(96, 124)\|\| |
| 29 | LCM of 15, 24, 54, 84? | ⭐⭐⭐ | \|\|7,560\|\| | \|\|2³·3³·5·7\|\| |
| 30 | Greatest 5-digit number divisible by 18, 40, 54? | ⭐⭐⭐ | \|\|99,360\|\| | \|\|LCM 1080; 92 × 1080\|\| |

## Exam Trap ⚠️

> [!warning] Exam Trap ⚠️
> - **Add** → divisor − remainder; **subtract** → the remainder. Don't swap.
> - Perfect square by **dividing** → remove unpaired primes; by **adding** → next square − n.
> - Remainder in HCF problems: **subtract r first**, then take HCF.
> - Source flaw: a question on the remainder of 7²⁷ ÷ 340 has no correct option — ignore it.

---
← [[07 Simple and Compound Interest]]  |  [[09 Mensuration]] →  |  Formulas: [[15 Master Formula Sheet]]  |  Log score: [[16 Accuracy Tracker]]
