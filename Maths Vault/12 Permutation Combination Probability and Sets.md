---
tags: [maths, ldc, medium-priority]
priority: 🟡 MEDIUM
---

← [[00 Maths Vault Index]]

# Permutation Combination Probability and Sets

> [!abstract] 🟡 MEDIUM · ≈2% of arithmetic questions · Target accuracy **85%+** · Budget **0.5 day**
> Rare but **appearing in the 2026 papers** — 4–5 questions in the latest sets. Cheap marks if you know the three formulas.

## Core formulas

| Concept | Formula | Quick example / shortcut |
|---|---|---|
| Arrangements (order matters) | ⁿPᵣ = n!/(n−r)! | 5P3 = 60 |
| Selection (order doesn't) | ⁿCᵣ = n!/(r!(n−r)!) | 15C4 = 1365 |
| Probability | Favourable / Total | 6 red of 20 → 3/10 |
| Union of sets | n(A∪B) = n(A) + n(B) − n(A∩B) | 70 + 45 − 100 = 15 |
| Cards | 52 = 26 red + 26 black | P(red) = 1/2 |

## Visual

```text
  English (70)       Mizo (45)
   ┌────────┬───┬────────┐
   │   55   │15 │   30   │   70 + 45 − 100 = 15 speak both
   └────────┴───┴────────┘
          total = 100
```

## Past-paper Q&A

Cover the last two columns, solve, then reveal. Sorted easy → hard (block learning), then re-shuffle for interleaved review.

| # | Question | Difficulty | Answer | Method |
|---|---|---|---|---|
| 1 | Box: 6 red, 4 blue, 10 green. P(red)? | ⭐ | \|\|3/10\|\| | \|\|6/20\|\| |
| 2 | 5 marbles: 3 red, 2 blue. P(blue)? | ⭐ | \|\|0.4\|\| | \|\|2/5\|\| |
| 3 | Card drawn from 52. P(red)? | ⭐ | \|\|1/2\|\| | \|\|26/52\|\| |
| 4 | A = {a,b,c}, B = {c,d,1,3}. n(A∪B)? | ⭐ | \|\|6\|\| | \|\|c counted once\|\| |
| 5 | Words of 3 letters from DELHI? | ⭐⭐ | \|\|60\|\| | \|\|5P3\|\| |
| 6 | Ways to choose 4 students from 15? | ⭐⭐ | \|\|1,365\|\| | \|\|15C4\|\| |
| 7 | 100 men: 70 English, 45 Mizo (all speak ≥ 1). Both? | ⭐⭐ | \|\|15\|\| | \|\|Inclusion–exclusion\|\| |
| 8 | Arrangements of the letters of KHAWBEL? | ⭐⭐⭐ | \|\|⚠️ Source flaw\|\| | \|\|7 distinct letters = 7! = 5040, not among options\|\| |

## Exam Trap ⚠️

> [!warning] Exam Trap ⚠️
> - Order matters → **P**; order doesn't → **C**.
> - In 'both languages' problems, assume everyone speaks at least one only if stated.
> - Count **distinct** letters first — repeated letters divide by their factorials.

---
← [[11 Ages and Linear Equations]]  |  [[13 Data Interpretation]] →  |  Formulas: [[15 Master Formula Sheet]]  |  Log score: [[16 Accuracy Tracker]]
