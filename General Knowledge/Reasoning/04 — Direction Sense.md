# 04 — Direction Sense
[[🧠 Reasoning — INDEX|← Back to Index]]

---

## Questions From Your Papers

| Question | Answer | Method |
|----------|--------|--------|
| Mawia walks 2km North, turns right 1km, turns right 2km. Which direction facing? | **South** | Draw path |
| Bryan faces East, walks 4km, turns right 3km, turns right 4km. Which direction now? | **West** | Draw path |
| Person walks towards house at 7:45am, shadow to right. Which direction walking? | **South** | Shadow logic |
| Bismita walks 200m East, turns right 210m to hospital. Shortest distance from start to hospital? | **√(200²+210²) ≈ 290m** | Pythagoras |
| Man travels 6km North, 5km East, 6km North. Distance from start? | **13km** | Pythagoras |

---

## The Compass — Always Draw This

```
           NORTH
             ↑
    WEST ←  ME  → EAST
             ↓
           SOUTH
```

---

## Turn Rules

| Turn | Effect |
|------|--------|
| Right turn (clockwise 90°) | N→E→S→W→N |
| Left turn (anti-clockwise 90°) | N→W→S→E→N |
| U-turn (180°) | N→S, E→W, S→N, W→E |
| Two right turns | Facing opposite direction |
| Two left turns | Facing opposite direction |
| Four right turns | Back to original direction |

### Quick Turn Reference
| Facing | After Right Turn | After Left Turn | After U-Turn |
|--------|-----------------|-----------------|-------------|
| North | East | West | South |
| East | South | North | West |
| South | West | East | North |
| West | North | South | East |

---

## Worked Examples From Your Papers

### Q1: Mawia walks 2km North, turns right 1km, turns right 2km. Direction facing?
```
Start: facing North
Walk 2km North → at (0,2)
Right turn → now facing East
Walk 1km East → at (1,2)
Right turn → now facing South
Walk 2km South → at (1,0)
Currently facing: SOUTH
Answer: South
```

### Q2: Bryan faces East, 4km forward, right turn, 3km, right turn, 4km. Direction now?
```
Start: facing East
4km East → at (4,0)
Right turn → facing South
3km South → at (4,-3)
Right turn → facing West
4km West → at (0,-3)
Currently facing: WEST
Answer: West
```

### Q3: Man walks 6km North, 5km East, 6km North. Distance from start?
```
Total North = 6+6 = 12km
Total East = 5km
Shortest distance = √(12² + 5²) = √(144+25) = √169 = 13km
Answer: 13km
```

### Q4: Bismita walks 200m East, turns right, walks 210m. Shortest distance from start?
```
East = 200m (horizontal)
Right from East = South → 210m (vertical)
Distance = √(200² + 210²) = √(40000+44100) = √84100 ≈ 290m
```

---

## Shadow Logic — Direction from Shadow

| Time | Sun Position | Shadow Direction |
|------|-------------|-----------------|
| Morning (before noon) | East | Points West |
| Evening (after noon) | West | Points East |
| Noon | Directly above | Very short/no shadow |

### Q: Person walks at 7:45am, shadow to his RIGHT. Which direction walking?
```
7:45am = morning → sun in East → shadow points West
Shadow is to his RIGHT
If shadow (West) is on his right → he is facing SOUTH
Answer: South
```

### Shadow Shortcut Table
| Time | Shadow Direction | If shadow on LEFT | If shadow on RIGHT |
|------|-----------------|-------------------|-------------------|
| Morning | West | Facing North | Facing **South** |
| Evening | East | Facing South | Facing **North** |

---

## Shortest Distance — Pythagoras

```
When path has two perpendicular segments:
Shortest distance = √(horizontal² + vertical²)

Draw the path → identify horizontal and vertical components → apply formula
```

---

## Exam Traps ⚠️
> Right turn = **clockwise** — many confuse this
> Two right turns = **opposite direction** (not back to original)
> Morning shadow = **West** (sun is in East); Evening shadow = **East**
> Shadow to RIGHT in morning → facing **South** (not North)
> Always **draw the path** — never solve direction problems in head
> After 4 right turns = **back to original direction**
> Shortest distance ≠ total distance walked — use Pythagoras for straight-line distance
