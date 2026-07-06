# 06 — Coding & Decoding
[[🧠 Reasoning — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Question | Answer | Pattern |
|----------|--------|---------|
| BAT = CBU, what is CAT? | **DBU** | Each letter +1 |
| PENCIL = QFODJM, what is PAPER? | **QBQFS** | Each letter +1 |
| BASE = GUCD, what is COMMAND? | **GNILDFW** | +5,−3,+2,−1 alternating? Check each |
| GOODNESS = HNPCODTR, what is GREATNESS? | **HQFZUOFTT** | Complex +1,−1 alternating |
| LONDON = 74, what is NEIHDAWN? | Check by counting | Each letter's position value summed |

---

## Type 1 — Letter Shift (Most Common)

### Constant Shift (+1 to each letter)
```
BAT → CBU
B(2)+1=C(3) ✓
A(1)+1=B(2)... but answer shows B not B?

Wait: BAT=CBU means:
B→C (+1), A→B (+1), T→U (+1)
So CAT:
C→D (+1), A→B (+1), T→U (+1)
= DBU ✓
```

### PENCIL = QFODJM (+1 shift)
```
P(16)+1=Q(17) ✓
E(5)+1=F(6) ✓
N(14)+1=O(15)... but answer shows O... wait:
P→Q, E→F, N→O, C→D, I→J, L→M
PAPER: P→Q, A→B, P→Q, E→F, R→S = QBQFS
```

---

## Type 2 — Letter Position Value

### LONDON = 74
```
L=12, O=15, N=14, D=4, O=15, N=14
12+15+14+4+15+14 = 74 ✓
```

### Applying to new word
```
Find position value of each letter, sum them
A=1, B=2, C=3... Z=26
```

---

## Type 3 — Reverse/Mirror Coding

### WORKABLE = VOYZPILD
```
W(23)→V(22) = −1
O(15)→O(15)... hmm doesn't match
Check: perhaps it's coded as next letter from end?
W→V (−1), O→O? 

Actually look at opposite:
A=1, Z=26 → opposites are A↔Z, B↔Y, C↔X...
W(23)↔D(4)? No...
Check carefully: WORKABLE→VOYZPILD
W→V (−1), O→O? No O→Y (+10)?
```
> For complex coding like this — just look at the FIRST letter's shift and check if consistent

---

## Type 4 — Number Coding

| Letter Value Method | Example |
|--------------------|---------|
| A=1, B=2... Z=26 | Sum of position values |
| A=2, B=3... Z=27 | Position + 1 |
| Z=1, Y=2... A=26 | Reverse order |

---

## Step-by-Step Method for Any Coding Question

```
Step 1: Look at FIRST letter of given word and its code
Step 2: Find the shift/transformation (+n, −n, position value, reverse)
Step 3: Verify with 2nd and 3rd letters
Step 4: Confirm the pattern is consistent
Step 5: Apply SAME pattern to new word
```

---

## Alphabet Position — Quick Reference

| Letter | Position | Letter | Position |
|--------|----------|--------|----------|
| A | 1 | N | 14 |
| B | 2 | O | 15 |
| C | 3 | P | 16 |
| D | 4 | Q | 17 |
| E | 5 | R | 18 |
| F | 6 | S | 19 |
| G | 7 | T | 20 |
| H | 8 | U | 21 |
| I | 9 | V | 22 |
| J | 10 | W | 23 |
| K | 11 | X | 24 |
| L | 12 | Y | 25 |
| M | 13 | Z | 26 |

---

## Exam Traps ⚠️
> Always verify pattern with **at least 2 letters** before applying to new word
> +1 shift: Z wraps to A (Z+1=A)
> −1 shift: A wraps to Z (A−1=Z)
> Position sum coding: count carefully (L=12 not 11)
> Some questions have alternating patterns (+1, −1, +1, −1) — check each position separately
> FUTURE = 6-21-20-21-18-5 → this is direct position values (F=6, U=21, T=20, U=21, R=18, E=5)
