# 01 — Seating Arrangement & Ranking
[[🧠 Reasoning — INDEX|← Back to Index]]

> Highest frequency topic — 27 questions (15.3%) in your papers

---

## Questions From Your Papers

| Question | Answer | Method |
|----------|--------|--------|
| Lee ranked 7th from top, 26th from bottom. Total students? | **32** | 7+26−1=32 |
| 32 students in row. Akash 12th from right, Priya 18th from left. Gap between them? | **3** | 32−12−18+1=3 |
| Sohan 28th from front, 37th from back. Total in queue? | **64** | 28+37−1=64 |
| P is 18th from front, Q is 12th from back, 5 between P and Q. Total? | **35** | 18+5+12=35 |
| In class of 43, boy ranked 19th. Two boys join, rank drops by 1. New rank from end? | **26th** | New rank from front=20, Total=45, From end=45−20+1=26 |

---

## TYPE 1 — Ranking Problems

### Master Formula
```
Total = Rank from Front + Rank from Back − 1
```

### Worked Examples

**Q: Lee is 7th from top and 26th from bottom. How many in class?**
```
Total = 7 + 26 − 1 = 32
```

**Q: Sohan is 28th from front, 37th from back. Total?**
```
Total = 28 + 37 − 1 = 64
```

**Q: P is 18th from front, Q is 12th from back, 5 persons between them. Total?**
```
Total = 18 + 5 + 12 = 35
(When persons are between two people — just add all three)
```

**Q: Boy ranked 19th in class of 43. Two new boys join, rank drops by 1 (now 20th). New rank from end?**
```
New total = 43 + 2 = 45
New rank from front = 20
Rank from end = 45 − 20 + 1 = 26
```

### Rank from Opposite End
```
Rank from End = Total − Rank from Front + 1
```

---

## TYPE 2 — Linear Seating (Row)

### Method
```
Step 1: Draw a straight line with positions
Step 2: Read each clue and fill in positions
Step 3: Answer the question from your diagram
```

### From Your Papers
**A, B, C, D, E sitting on bench. A next to B. C next to D. D not with E. E on left end. C is 2nd from right. A to right of B and E. A and C sitting together.**

```
Draw 5 positions: _ _ _ _ _
E is on left end → E _ _ _ _
C is 2nd from right → E _ _ C _
A and C together → E _ _ C A  OR  E _ A C _
A to right of B → B before A
A next to B → B A (together)
D not with E → D not at position 2
Final: E B A C D
Answer: A is between B and C
```

### Key Rules for Linear Seating
- "Immediate left/right" = directly next to, no gap
- "Second from left" = position 2 from left end
- If facing North = left is West, right is East
- Always draw the diagram — never solve in head

---

## TYPE 3 — Circular Seating

### Method
```
Step 1: Draw a circle
Step 2: All persons face the CENTRE (unless stated otherwise)
Step 3: When facing centre — your RIGHT is anti-clockwise direction
Step 4: Place persons one by one using clues
```

### Key Rule ⚠️
```
Facing CENTRE:
- Your right = anti-clockwise in the circle
- Your left = clockwise in the circle

Facing OUTSIDE:
- Your right = clockwise in the circle
- Your left = anti-clockwise in the circle
```

### From Your Papers
**6 persons A,B,C,D,E,F sit in a row facing north. F at extreme left. C at extreme right. A not at any end. D immediately left of A. B immediately right of A. E not next to F.**

```
Positions: F _ _ _ _ C
D left of A, B right of A → D A B (block)
A not at end → A is position 2,3,4,5
Place D A B block: F D A B _ C  OR  F _ D A B C
E not next to F → E not at position 2
Final: F D A B E C
3rd from left = A
```

---

## TYPE 4 — Queue / Position Problems

### From Your Papers
**In queue, P is 18th from front, Q is 12th from back, 5 persons between P and Q. Total?**
```
If P is before Q: 18 + 5 + 12 = 35
If Q is before P: This would contradict positions — check which makes sense
Answer = 35
```

---

## Exam Traps ⚠️
> Total = Front + Back **−1** — forgetting to subtract 1 is the #1 mistake
> In circular seating — **right = anti-clockwise** when facing centre
> "Immediate right" — no gap allowed between them
> When two more people join a class — **total increases by 2**, adjust accordingly
> "Rank drops by 1" — new rank from front increases by 1 (not decreases)
