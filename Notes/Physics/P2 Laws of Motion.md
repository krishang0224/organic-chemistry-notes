# P2 Laws of Motion

> [!tip] One Line
> Newton's 3 laws explain why objects move the way they do — inertia, F=ma, and action-reaction.

---

## Newton's Three Laws

### First Law (Inertia)
> A body continues in its state of rest or uniform motion unless acted upon by an external force.

- **Inertia** = resistance to change in motion
- Inertia ∝ mass (heavier object → harder to move/stop)
- No net force → no acceleration (v = constant or 0)

### Second Law
> F = ma (net force = mass × acceleration)

- F and a are in the **same direction**
- **Impulse:** J = F·Δt = Δp (change in momentum)
- Momentum: p = mv

### Third Law
> Every action has an equal and opposite reaction. Forces act on **different** bodies.

- Gun recoil, rocket propulsion, walking — all third law
- Action and reaction are equal in magnitude, opposite in direction, act on different bodies (so they don't cancel)

---

## Free Body Diagram (FBD)

Steps:
1. Isolate the object
2. Draw all forces acting ON it (not forces it exerts)
3. Apply F_net = ma along each axis

**Common forces:**
- Weight: W = mg (downward)
- Normal force: N (perpendicular to surface)
- Tension: T (along string, away from object)
- Friction: f (opposing relative motion)

---

## Friction

### Types
| Type | Formula | Condition |
|------|---------|-----------|
| Static friction | f_s ≤ μ_s·N | Object not moving |
| Kinetic friction | f_k = μ_k·N | Object sliding |
| Rolling friction | f_r = μ_r·N | Object rolling |

**Order:** μ_s > μ_k > μ_r (static > kinetic > rolling)

> [!important]
> Static friction is self-adjusting — it matches the applied force until it reaches its maximum (μ_s·N). After that, kinetic friction takes over.

### Angle of Friction
tan λ = μ (where λ = angle of friction)

### Angle of Repose
tan θ = μ (maximum angle of incline where object stays at rest)

---

## Common Systems

### Two blocks on frictionless surface (Force F applied to system)
```
Total mass = m₁ + m₂
Acceleration a = F/(m₁+m₂)
Tension T = m₂·a (force on the block not directly pushed)
```

### Atwood's Machine (two masses over pulley)
```
a = (m₁–m₂)g / (m₁+m₂)
T = 2m₁m₂g / (m₁+m₂)
```

### Block on inclined plane (angle θ, no friction)
```
a = g·sinθ (along the plane, downward)
N = mg·cosθ
```

### Block on inclined plane (with friction μ)
```
If moving down: a = g(sinθ – μcosθ)
If moving up: a = g(sinθ + μcosθ) [decelerating]
Stays stationary if: tanθ ≤ μ
```

---

## Circular Motion Basics

For object moving in circle of radius r at speed v:
```
Centripetal acceleration: a_c = v²/r = ω²r
Centripetal force: F_c = mv²/r
```
Direction: always toward center (not a separate force — provided by tension, gravity, normal, friction, etc.)

### Banking of Roads
```
tan θ = v²/rg   (ideal speed, no friction)
```

### Conical Pendulum
```
T·cosθ = mg
T·sinθ = mω²r
tan θ = ω²r/g
```

---

## Practice Questions

1. A 5 kg block on a frictionless surface is pulled by 20 N. Find acceleration.

2. Two masses 3 kg and 5 kg connected by string over pulley (Atwood). Find acceleration and tension.

3. A 10 kg block on incline of 30° (μ=0.2). Does it slide? If it does, find acceleration.

4. A car takes a turn of radius 50m at 10 m/s on flat road. Minimum μ needed?

5. A 2 kg object is pulled by 15 N force. Friction force is 3 N. Find acceleration.

> [!question]- Answers
> 1. a = F/m = 20/5 = 4 m/s²
> 2. a = (5–3)×10/(5+3) = 20/8 = 2.5 m/s²; T = 2×5×3×10/8 = 37.5 N
> 3. tan30°=0.577 > μ=0.2, so it slides; a = g(sin30°–0.2×cos30°) = 10(0.5–0.173) = 3.27 m/s²
> 4. μ = v²/rg = 100/500 = 0.2
> 5. a = (15–3)/2 = 6 m/s²

---
**Previous: [[P1 Kinematics]]**
**Next: [[P3 Work Energy Power]]**
