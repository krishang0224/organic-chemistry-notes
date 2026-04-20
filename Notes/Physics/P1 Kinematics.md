# P1 Kinematics

> [!tip] One Line
> Kinematics = describing motion using displacement, velocity, acceleration — without asking why it happens.

---

## Key Definitions

| Term | Definition | Unit |
|------|-----------|------|
| Distance | Total path length (scalar) | m |
| Displacement | Shortest path from start to end (vector) | m |
| Speed | Distance/time (scalar) | m/s |
| Velocity | Displacement/time (vector) | m/s |
| Acceleration | Rate of change of velocity | m/s² |

> [!warning] Distance ≠ Displacement
> A car going around a circular track once: distance = 2πr, displacement = 0

---

## Equations of Motion (Uniform Acceleration)

```
v = u + at                    … (1)
s = ut + ½at²                 … (2)
v² = u² + 2as                 … (3)
s_nth = u + a(2n–1)/2         … (4)  ← distance in nth second
```

**Variables:** u = initial velocity, v = final velocity, a = acceleration, s = displacement, t = time

> [!important] When to use which
> - Know u, a, t → want v or s → use (1) or (2)
> - Don't know t → use (3)
> - Want distance in specific second n → use (4)

---

## Graphs

### Displacement-Time (s-t)
| Shape | Meaning |
|-------|---------|
| Straight line (slope +ve) | Uniform velocity |
| Horizontal line | At rest |
| Curve (slope increasing) | Accelerating |
| Curve (slope decreasing) | Decelerating |

**Slope of s-t graph = velocity**

### Velocity-Time (v-t)
| Shape | Meaning |
|-------|---------|
| Horizontal line | Uniform velocity (a=0) |
| Straight line (slope +ve) | Uniform acceleration |
| Straight line (slope –ve) | Uniform deceleration |

**Slope of v-t graph = acceleration**
**Area under v-t graph = displacement**

### Acceleration-Time (a-t)
**Area under a-t graph = change in velocity**

---

## Projectile Motion

> Object launched at angle θ with speed u. Only gravity acts (g downward).

```
Horizontal: uₓ = ucosθ  (constant throughout)
Vertical:   uᵧ = usinθ  (decreases, becomes 0 at top, then negative)
```

### Key Formulas
```
Time of flight:    T = 2usinθ / g
Maximum height:    H = u²sin²θ / 2g
Range:             R = u²sin2θ / g
```

> [!important] Key Results
> - Range is maximum at θ = 45° → R_max = u²/g
> - Same range for θ and (90°–θ): e.g., 30° and 60° give same range
> - At highest point: vertical velocity = 0, horizontal velocity = ucosθ (unchanged)
> - Time to reach max height = T/2 = usinθ/g

### At Any Time t
```
x = ucosθ · t
y = usinθ · t – ½gt²
vₓ = ucosθ
vᵧ = usinθ – gt
```

---

## Relative Motion

**Relative velocity of A with respect to B:**
```
v_AB = v_A – v_B
```

**Rain-man problem:** If rain falls vertically and man walks horizontally, man must tilt umbrella forward. Angle from vertical = tan⁻¹(v_man / v_rain)

**River-boat problem:**
- Boat speed in still water = v_b, river speed = v_r
- To cross in minimum time: point boat perpendicular to river
- To cross with zero drift: point boat upstream at angle θ = sin⁻¹(v_r/v_b)

---

## Practice Questions

1. A ball is thrown vertically up with 20 m/s. Find: (a) max height (b) time to return (g=10)

2. A projectile is fired at 30° with 40 m/s. Find range and max height. (g=10)

3. A car accelerates from rest at 4 m/s². Find velocity after 5s and distance covered.

4. Two trains approach each other at 60 km/h and 40 km/h. Relative speed?

5. Distance covered in 4th second by a body starting from rest with a = 3 m/s²?

> [!question]- Answers
> 1. (a) v²=u²–2gs → 0=400–20s → H=20m; (b) T=2u/g=4s
> 2. R=u²sin60°/g=40²×(√3/2)/10=80√3≈138.6m; H=u²sin²30°/2g=1600×0.25/20=20m
> 3. v=0+4×5=20m/s; s=½×4×25=50m
> 4. 60+40=100 km/h (moving towards each other, velocities add)
> 5. s₄=u+a(2×4–1)/2=0+3×7/2=10.5m

---
**Next: [[P2 Laws of Motion]]**
