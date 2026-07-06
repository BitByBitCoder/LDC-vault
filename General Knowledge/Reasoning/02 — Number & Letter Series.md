# 02 — Number & Letter Series
[[🧠 Reasoning — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Series | Answer | Pattern |
|--------|--------|---------|
| 5, 10, 15, 20, ? | **25** | +5 each time |
| 2, 6, 12, 20, 30, ? | **42** | +4,+6,+8,+10,+12 |
| 1, 4, 9, 16, 25, ? | **36** | 1²,2²,3²,4²,5²,**6²** |
| 3, 5, 9, 17, ? | **33** | ×2−1 each time (3→5→9→17→33) |
| 2, 10, 30, 68, 130, ? | **222** | +8,+20,+38,+62,+92 (diff increases by 12,18,24,30) |
| A, C, F, J, O, ? | **U** | +2,+3,+4,+5,+6 gaps |
| LT, MS, NR, OQ, ? | **PP** | First letter +1, Second letter −1 |
| AHOP : CKSU :: BJMR : ? | **DMQW** | Each letter +2 |

---

## Number Series — All Pattern Types

### Type 1 — Constant Difference
```
5, 10, 15, 20, 25 → +5 each time
2, 5, 8, 11, 14 → +3 each time
```

### Type 2 — Increasing Difference
```
2, 6, 12, 20, 30, 42
Differences: 4, 6, 8, 10, 12 (difference increases by 2)

1, 3, 7, 13, 21, 31
Differences: 2, 4, 6, 8, 10 (difference increases by 2)
```

### Type 3 — Squares
```
1, 4, 9, 16, 25, 36, 49, 64, 81, 100
= 1², 2², 3², 4², 5², 6², 7², 8², 9², 10²
```

### Type 4 — Cubes
```
1, 8, 27, 64, 125
= 1³, 2³, 3³, 4³, 5³
```

### Type 5 — Multiply then Add/Subtract
```
3, 5, 9, 17, 33
Pattern: ×2 − 1
3×2−1=5, 5×2−1=9, 9×2−1=17, 17×2−1=33
```

### Type 6 — Fibonacci-like (Add previous two)
```
1, 1, 2, 3, 5, 8, 13, 21
Each term = sum of previous two
```

### Type 7 — Two Alternating Series
```
2, 3, 5, 6, 8, 9, 11 ?
Series 1: 2, 5, 8, 11 (odd positions, +3)
Series 2: 3, 6, 9 (even positions, +3)
Next = 12
```

### Type 8 — Multiply Pattern
```
2, 6, 18, 54, 162
×3 each time

3, 6, 12, 24, 48
×2 each time
```

---

## Letter Series — All Pattern Types

### Alphabet Position Reference
```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

### Type 1 — Constant Jump
```
A, C, E, G, I → +2 each (skip one letter)
B, E, H, K, N → +3 each (skip two letters)
```

### Type 2 — Increasing Jump
```
A, C, F, J, O, U
Gaps: +2, +3, +4, +5, +6
A(1)→C(3)→F(6)→J(10)→O(15)→U(21)
```

### Type 3 — Reverse
```
Z, X, V, T, R → −2 each (going backwards)
```

### Type 4 — Letter Pairs
```
LT, MS, NR, OQ, PP
First letters: L, M, N, O, P → +1 each
Second letters: T, S, R, Q, P → −1 each
```

### Type 5 — Letter Coding in Series
```
AHOP : CKSU :: BJMR : DMQW
A+2=C, H+3=K, O+5=T... No wait:
A→C (+2), H→K (+3), O→T (+5), P→U (+5)
Check: B→D (+2), J→M (+3), M→Q (+4), R→W (+5)
Pattern: each letter increases by +2,+3,+4,+5
```

---

## Grid/Matrix Number Series

### From Your Papers
**Grid: 6,9,15 / 8,12,20 / 4,6,?**
```
Row 1: 6+9=15 ✓
Row 2: 8+12=20 ✓
Row 3: 4+6=10 ✓ → Answer = 10
```

**Grid: 8,32,4 / 7,5,? / 2,6,3**
```
Row 1: 8×4=32 ✓
Row 3: 2×3=6 ✓
Row 2: 7×5=35 → Answer = 35
```

---

## Meaningful Sequence (Arrangement)
**Q: Arrange in meaningful order: 1.Word 2.Paragraph 3.Sentence 4.Letters 5.Phrase**
```
Smallest to largest: Letters → Word → Phrase → Sentence → Paragraph
= 4, 1, 5, 3, 2
```

---

## Exam Traps ⚠️
> 1,4,9,16,25 = **squares** — next is **36** (NOT 30 or 40)
> 2,6,12,20,30 = increasing difference +4,+6,+8,+10 — next difference is **+12** = 42
> A,C,F,J,O — gaps are **+2,+3,+4,+5** so next gap is **+6** = U (NOT T or S)
> "×2−1" pattern: 3→5→9→17→**33** (NOT 31 or 35)
> Letter pairs LT,MS,NR,OQ — first +1, second −1 → **PP** (NOT PQ or OP)
