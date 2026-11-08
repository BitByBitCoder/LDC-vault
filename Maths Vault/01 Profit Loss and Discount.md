---
tags: [maths, ldc, high-priority]
priority: 🔴 HIGH
---

← [[00 Maths Vault Index]]

# Profit Loss and Discount

> [!abstract] 🔴 HIGH · ≈14% of arithmetic questions · Target accuracy **90%+** · Budget **2 days**
> Appears in **all 11 arithmetic sets** in your PDF — the single biggest scoring block. Master the CP–SP–MP ladder and every question becomes one line.

## Core formulas

| Concept | Formula | Quick example / shortcut |
|---|---|---|
| Profit % | (SP − CP) / CP × 100 | Always on **CP** |
| Discount % | (MP − SP) / MP × 100 | Always on **MP** |
| SP from CP | CP × (100 ± P%) / 100 | Multiplier: +20% → ×1.2 |
| Successive discounts a, b | a + b − ab/100 | 20% & 10% → 28%, not 30% |
| Same SP, one +x% one −x% | Loss = x²/100 % | 10% → 1% loss |
| False weight | Gain % = error / (true weight − error) × 100 | 1000 g vs 800 g → 200/800 = 25% |
| Marked above CP by m%, discount d% | Profit % = (100+m)(100−d)/100 − 100 | Use multipliers |

## Visual

```text
 CP ──(×1.20 profit)──► SP ◄──(×0.90 discount)── MP
 4000                  4800                      5333
        always go through SP — it is the meeting point
```

## Past-paper Q&A

Cover the last two columns, solve, then reveal. Sorted easy → hard (block learning), then re-shuffle for interleaved review.

| # | Question | Difficulty | Answer | Method |
|---|---|---|---|---|
| 1 | CP ₹80, SP ₹100. Profit %? | ⭐ | \|\|25%\|\| | \|\|20/80 × 100\|\| |
| 2 | Article sold at ₹240 with 20% profit. CP? | ⭐ | \|\|₹200\|\| | \|\|240 / 1.2\|\| |
| 3 | TV marked ₹25,000, sold ₹21,250. Discount %? | ⭐ | \|\|15%\|\| | \|\|3750/25000\|\| |
| 4 | Discount 12%, SP ₹1,320. Marked price? | ⭐ | \|\|₹1,500\|\| | \|\|1320 / 0.88\|\| |
| 5 | Purse marked ₹1,400 + 5% sales tax. Total? | ⭐ | \|\|₹1,470\|\| | \|\|1400 × 1.05\|\| |
| 6 | Ratio CP : SP = 3 : 6. Profit %? | ⭐ | \|\|100%\|\| | \|\|Profit = 3 on CP 3\|\| |
| 7 | Radio ₹225 + overhead ₹15, sold ₹300. Profit %? | ⭐ | \|\|25%\|\| | \|\|CP = 240; 60/240\|\| |
| 8 | Shirt ₹60, 25% discount. Sale price? | ⭐ | \|\|₹45\|\| | \|\|60 × 0.75\|\| |
| 9 | Successive discounts 20% and 10% = single discount? | ⭐⭐ | \|\|28%\|\| | \|\|20 + 10 − 2 = 28\|\| |
| 10 | Three successive discounts 6%, 10%, 15% = single discount? | ⭐⭐ | \|\|28.09%\|\| | \|\|1 − 0.94×0.90×0.85 = 0.2809\|\| |
| 11 | Two TVs sold at ₹39,600 each: +10% on one, −10% on other. Net? | ⭐⭐ | \|\|1% loss\|\| | \|\|x²/100 = 1\|\| |
| 12 | Chair sold ₹2,100 at 25% loss. SP for 15% profit? | ⭐⭐ | \|\|₹3,220\|\| | \|\|CP = 2100/0.75 = 2800; × 1.15\|\| |
| 13 | Dealer uses 800 g for 1 kg, sells at cost price. Gain %? | ⭐⭐ | \|\|25%\|\| | \|\|200/800\|\| |
| 14 | Dealer uses 900 g for 1 kg. Gain %? | ⭐⭐ | \|\|11 1/9 %\|\| | \|\|100/900\|\| |
| 15 | Jacket ticket ₹5,000, sold at 4% discount, gaining 20%. CP? | ⭐⭐ | \|\|₹4,000\|\| | \|\|SP = 4800; 4800/1.2\|\| |
| 16 | Sanga buys 4 apples ₹12, eats one, sells rest at ₹4 each. Result? | ⭐⭐ | \|\|No gain/no loss\|\| | \|\|Sells 3 × 4 = 12 = CP\|\| |
| 17 | 5 oranges per ₹1 bought. How many per ₹1 to gain 25%? | ⭐⭐ | \|\|4\|\| | \|\|(1/5) × 1.25 = 1/4\|\| |
| 18 | Eggs bought 7 per ₹1, sold at 40% profit. Eggs per ₹1? | ⭐⭐ | \|\|5\|\| | \|\|7 / 1.4\|\| |
| 19 | Book sold ₹858 at 10% gain. Gain/loss % if sold at ₹819? | ⭐⭐ | \|\|5% gain\|\| | \|\|CP = 780; 39/780\|\| |
| 20 | Sanga sells cow to Mawia at 10% loss; Mawia sells at ₹5,400 gaining 20%. Sanga's CP? | ⭐⭐⭐ | \|\|₹5,000\|\| | \|\|Mawia CP = 4500 = 0.9 × x\|\| |
| 21 | Discount 16%, still 5% gain. MP over CP? | ⭐⭐⭐ | \|\|25%\|\| | \|\|1.05 / 0.84 = 1.25\|\| |
| 22 | Marked at what % above CP so that 5% discount gives 33% profit? | ⭐⭐⭐ | \|\|40%\|\| | \|\|1.33 / 0.95 = 1.40\|\| |
| 23 | Marked 20% above CP; after discount profit is 8%. Discount %? | ⭐⭐⭐ | \|\|10%\|\| | \|\|1.08 / 1.20 = 0.90\|\| |
| 24 | Zuala sells 1/3 of ₹5,000 cloth at 40% loss. Profit % needed on rest to break even? | ⭐⭐⭐ | \|\|20%\|\| | \|\|Loss = 666.67; rest CP = 3333.33\|\| |
| 25 | Two plots sold ₹8 lakh each, one +16%, one −16%. Net result? | ⭐⭐⭐ | \|\|Loss ≈ ₹42,036 (2.56%)\|\| | \|\|CP = 8/1.16 + 8/0.84 lakh\|\| |

## Exam Trap ⚠️

> [!warning] Exam Trap ⚠️
> - Profit/loss % is on **CP**; discount % is on **MP** — mixing them is the #1 error.
> - 20% + 10% discount ≠ 30%. Use the multiplier chain (0.8 × 0.9 = 0.72).
> - Equal SP with +x% and −x% is **always a loss** — never 'no gain no loss'.
> - False-weight gain divides by the weight **actually given** (800 g / 900 g), not 1000 g.

---
[[02 Percentages]] →  |  Formulas: [[15 Master Formula Sheet]]  |  Log score: [[16 Accuracy Tracker]]
