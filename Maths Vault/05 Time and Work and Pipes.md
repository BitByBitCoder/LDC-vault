---
tags: [maths, ldc, high-priority]
priority: 🔴 HIGH
---

← [[00 Maths Vault Index]]

# Time and Work and Pipes

> [!abstract] 🔴 HIGH · ≈8% of arithmetic questions · Target accuracy **90%+** · Budget **1.5 days**
> One rule — **work = rate × time** — covers workers, pipes and leaks. A leak is just a negative worker.

## Core formulas

| Concept | Formula | Quick example / shortcut |
|---|---|---|
| One day's work | 1/n | A in 15 days → 1/15 |
| Together | ab/(a+b) | 10 & 40 → 8 |
| Man-days | M₁D₁/W₁ = M₂D₂/W₂ | Total work = men × days |
| Pipes | Inlet +, outlet − | 1/10 − 1/12 = 1/60 |
| Leak | Leak rate = 1/t₁ − 1/t₂ | 8 h → 10 h: 1/8 − 1/10 = 1/40 |
| Equivalence | M men = W women → 1 M = W/M women | 16 M = 20 W → 1 M = 1.25 W |

## Visual

```text
        ┌──────────── TANK ────────────┐
 Pipe A │▓▓▓ +1/10 per hr  (fills)     │
 Pipe B │░░░ −1/12 per hr  (empties)   │
        └──────────────────────────────┘
 Net = 1/10 − 1/12 = 1/60   →  60 hours to fill
```

## Past-paper Q&A

Cover the last two columns, solve, then reveal. Sorted easy → hard (block learning), then re-shuffle for interleaved review.

| # | Question | Difficulty | Answer | Method |
|---|---|---|---|---|
| 1 | 8 men finish in 6 days. 1 man? | ⭐ | \|\|48 days\|\| | \|\|8 × 6\|\| |
| 2 | 5 girls embroider a dress in 9 days. 3 girls? | ⭐ | \|\|15 days\|\| | \|\|45 girl-days\|\| |
| 3 | John 10 days, Peter 40 days together? | ⭐ | \|\|8 days\|\| | \|\|400/50\|\| |
| 4 | Kavi does 1/13 of a work per day. Whole work? | ⭐ | \|\|13 days\|\| | \|\|Reciprocal\|\| |
| 5 | 6 machines make 270 cups/min. 10 machines in 4 min? | ⭐ | \|\|1,800\|\| | \|\|45 per machine per min\|\| |
| 6 | Outlet empties a cistern in 5 h. 2/5 of cistern? | ⭐ | \|\|2 hours\|\| | \|\|2/5 × 5\|\| |
| 7 | A 15 days, B 20 days work 4 days together. Fraction left? | ⭐⭐ | \|\|8/15\|\| | \|\|Done = 4 × 7/60 = 7/15\|\| |
| 8 | A 50 d, B 75 d work together for 10 days. Fraction done? | ⭐⭐ | \|\|1/3\|\| | \|\|10 × 5/150\|\| |
| 9 | Worker 6 days; with assistant 3 days. Assistant alone? | ⭐⭐ | \|\|6 days\|\| | \|\|1/3 − 1/6\|\| |
| 10 | A+B in 12 days, A alone 18. B alone? | ⭐⭐ | \|\|36 days\|\| | \|\|1/12 − 1/18\|\| |
| 11 | Mawia+Enga 15 days, Mawia alone 20. Enga alone? | ⭐⭐ | \|\|60 days\|\| | \|\|1/15 − 1/20\|\| |
| 12 | A 10 d, B 20 d; with C all finish in 4 d. C alone? | ⭐⭐ | \|\|10 days\|\| | \|\|1/4 − 1/10 − 1/20 = 1/10\|\| |
| 13 | Pipe A fills in 12 h, B in 18 h. Together? | ⭐⭐ | \|\|7.2 hours\|\| | \|\|216/30\|\| |
| 14 | A fills in 10 h; B empties in 12 h. Both open? | ⭐⭐ | \|\|60 hours\|\| | \|\|1/10 − 1/12\|\| |
| 15 | Tank fills in 8 h; 2 h longer with a leak. Leak empties full tank in? | ⭐⭐⭐ | \|\|40 hours\|\| | \|\|1/8 − 1/10 = 1/40\|\| |
| 16 | 16 men or 20 women do a job in 25 days. 28 men + 15 women? | ⭐⭐⭐ | \|\|10 days\|\| | \|\|28 M = 35 W → 50 W\|\| |
| 17 | 12 men or 18 women reap a field in 14 days. 8 men + 16 women? | ⭐⭐⭐ | \|\|9 days\|\| | \|\|8 M = 12 W → 28 W\|\| |
| 18 | 150 men have food for 45 days; after 10 days 25 leave. Remaining food lasts? | ⭐⭐⭐ | \|\|42 days\|\| | \|\|150 × 35 = 125 × d\|\| |
| 19 | Thanga does 5/8 job in 10 days. More days to finish? | ⭐⭐⭐ | \|\|6 days\|\| | \|\|3/8 ÷ (1/16)\|\| |
| 20 | Zuala+Siama finish in 3 days; Siama leaves after 2; Zuala finishes in 2 more. Siama alone? | ⭐⭐⭐ | \|\|6 days\|\| | \|\|Zuala = 6 d; 1/3 − 1/6 = 1/6\|\| |
| 21 | Chhura 30 d, Na-a 40 d; Chhura leaves 5 days before end. Total days? | ⭐⭐⭐ | \|\|20 days\|\| | \|\|T/40 + (T−5)/30 = 1\|\| |

## Exam Trap ⚠️

> [!warning] Exam Trap ⚠️
> - The **leak/tank question appears twice** in different papers — same method: subtract rates.
> - 'Leaves 5 days before completion' → Chhura works **T − 5** days, the other works **T**.
> - Convert men↔women **once**, then use a single unit.
> - Never add times — add **rates** (1/t).

---
← [[04 Ratio Proportion and Partnership]]  |  [[06 Time Speed and Distance]] →  |  Formulas: [[15 Master Formula Sheet]]  |  Log score: [[16 Accuracy Tracker]]
