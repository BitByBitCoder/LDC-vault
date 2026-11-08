---
tags: [maths, ldc, high-priority]
priority: 🔴 HIGH
---

← [[00 Maths Vault Index]]

# Simple and Compound Interest

> [!abstract] 🔴 HIGH · ≈8% of arithmetic questions · Target accuracy **90%+** · Budget **1.5 days**
> CI vs SI shortcuts save 1–2 minutes each. Half-yearly compounding is the favourite twist.

## Core formulas

| Concept | Formula | Quick example / shortcut |
|---|---|---|
| SI | PRT/100 | A = P(1 + RT/100) |
| CI amount | P(1 + r/100)ⁿ | CI = A − P |
| CI − SI, 2 years | P(r/100)² | Used in 3 questions here |
| CI − SI, 3 years | P(r/100)²(3 + r/100) | 20% → 0.128 P |
| Half-yearly | Rate ÷ 2, periods × 2 | 8% for 1½ yr → 4%, 3 periods |
| Doubles in n yrs | Triples in 2n yrs | 10 → 20 |
| Mixed rates | Weighted average of rates | 40% @25 + 60% @20 = 22% |

## Visual

```text
 Year 0 ──► Year 1 ──► Year 2
  P         P+I₁      P+I₁+I₂      ← CI grows on interest too
  P         P+I       P+2I         ← SI grows in a straight line
 Gap in year 2 = interest on interest = P(r/100)²
```

## Past-paper Q&A

Cover the last two columns, solve, then reveal. Sorted easy → hard (block learning), then re-shuffle for interleaved review.

| # | Question | Difficulty | Answer | Method |
|---|---|---|---|---|
| 1 | SI on ₹800, 3 years, 5%? | ⭐ | \|\|₹120\|\| | \|\|800×3×5/100\|\| |
| 2 | SI on ₹200, 5 years, 6%? | ⭐ | \|\|₹60\|\| | \|\|200×5×6/100\|\| |
| 3 | ₹5,000 becomes ₹6,000 at 5% SI. Time? | ⭐ | \|\|4 years\|\| | \|\|SI 1000\|\| |
| 4 | SI at 4% amounts to ₹31,200 in 5 years. Principal? | ⭐ | \|\|₹26,000\|\| | \|\|P × 1.2\|\| |
| 5 | ₹40,000 at 16% earns ₹9,600 SI. Time? | ⭐ | \|\|1.5 years\|\| | \|\|9600/6400\|\| |
| 6 | CI on ₹8,000 at 10% for 2 years? | ⭐ | \|\|₹1,680\|\| | \|\|8000 × 0.21\|\| |
| 7 | CI on ₹10,000 at 10% for 2 years? | ⭐ | \|\|₹2,100\|\| | \|\|10000 × 0.21\|\| |
| 8 | SI doubles in 10 years. Triples in? | ⭐⭐ | \|\|20 years\|\| | \|\|2 × 10\|\| |
| 9 | 40% invested at 25%, rest at 20%. Overall rate? | ⭐⭐ | \|\|22%\|\| | \|\|10 + 12\|\| |
| 10 | SI on a sum for 2 years = ₹500 at 10%. CI? | ⭐⭐ | \|\|₹525\|\| | \|\|P = 2500; 2500 × 0.21\|\| |
| 11 | SI for 2 years = ₹480 at 10%. CI? | ⭐⭐ | \|\|₹504\|\| | \|\|P = 2400\|\| |
| 12 | CI on ₹8,000 at 4% for 2 years (annual)? | ⭐⭐ | \|\|₹652.80\|\| | \|\|8000 × 0.0816\|\| |
| 13 | SI difference from two banks on ₹3,000 in 3 years is ₹90. Rate difference? | ⭐⭐ | \|\|1%\|\| | \|\|90/(30×3)\|\| |
| 14 | SI for 1 yr 3 months on ₹x at 16%? | ⭐⭐ | \|\|x/5\|\| | \|\|1.25 × 0.16 = 0.2\|\| |
| 15 | Borrow ₹400 at 5% SI, lend at 5% CI. Gain after 2 years? | ⭐⭐ | \|\|₹1\|\| | \|\|P(r/100)² = 400 × 0.0025\|\| |
| 16 | True discount on PW ₹6,000, 9 months, 12%? | ⭐⭐ | \|\|₹540\|\| | \|\|6000 × 0.12 × 0.75\|\| |
| 17 | CI − SI for 3 years at 20% is ₹160. Principal? | ⭐⭐⭐ | \|\|₹1,250\|\| | \|\|0.128 P = 160\|\| |
| 18 | SI for 6 years = ₹29,250; 7% first 2 yrs, 16% next 4. Sum? | ⭐⭐⭐ | \|\|₹37,500\|\| | \|\|(14+64)% = 78%\|\| |
| 19 | CI on ₹15,625 for 1½ yrs at 8% compounded half-yearly? | ⭐⭐⭐ | \|\|₹1,951\|\| | \|\|15625 × (1.04³ − 1)\|\| |
| 20 | ₹4,096 for 18 months at 12½%, compounded half-yearly. Amount? | ⭐⭐⭐ | \|\|₹4,913\|\| | \|\|(17/16)³ × 4096\|\| |
| 21 | Loan at 12% CI repaid in two equal annual instalments of ₹784. Loan? | ⭐⭐⭐ | \|\|₹1,325\|\| | \|\|784/1.12 + 784/1.2544\|\| |

## Exam Trap ⚠️

> [!warning] Exam Trap ⚠️
> - 'SI for 2 years' gives you P — find P **first**, then the CI.
> - Half-yearly: **halve the rate AND double the periods** — people do only one.
> - CI is the **interest only**; check whether the question wants amount or CI.
> - Unequal rates over different years: add rate-years (7×2 + 16×4), don't average.

---
← [[06 Time Speed and Distance]]  |  [[08 Number System HCF LCM and Squares]] →  |  Formulas: [[15 Master Formula Sheet]]  |  Log score: [[16 Accuracy Tracker]]
