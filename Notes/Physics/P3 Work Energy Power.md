# P3 Work, Energy & Power

> [!tip] One Line
> Work = force × displacement (when in same direction). Energy is capacity to do work. Power is rate of doing work.

---

## Work

```
W = F·s·cosθ
```
Where θ = angle between force and displacement.

| θ | cosθ | Work |
|---|------|------|
| 0° | 1 | Maximum positive (+F·s) |
| 90° | 0 | Zero (force ⊥ displacement) |
| 180° | –1 | Negative (–F·s) |

> [!important] Key Cases
> - Normal force does zero work (always ⊥ to displacement on flat surface)
> - Friction does negative work (opposes motion)
> - Centripetal force does zero work (always ⊥ to velocity)

**Work by variable force:** W = area under F-x graph

**Units:** Joule (J) = N·m

---

## Kinetic Energy

```
KE = ½mv²
```

**Work-Energy Theorem:**
```
W_net = ΔKE = ½mv² – ½mu²
```
Net work done on an object = change in its kinetic energy.

> [!important] This is the most useful result in this chapter
> Any time you need to find work done by all forces combined, just find ΔKE. No need to calculate each force separately.

---

## Potential Energy

**Gravitational PE:**
```
PE = mgh   (h = height above reference)
```

**Spring PE (elastic PE):**
```
PE = ½kx²   (k = spring constant, x = compression/extension)
```

---

## Conservation of Mechanical Energy

When only conservative forces act (no friction):
```
KE + PE = constant
½mv₁² + mgh₁ = ½mv₂² + mgh₂
```

**Conservative forces:** gravity, spring force (path independent)
**Non-conservative forces:** friction, air drag (path dependent — dissipate energy)

> [!note] With friction
> KE + PE decreases. Energy lost to heat = work done by friction = f·d

---

## Power

```
P = W/t = F·v·cosθ
```

For constant force in direction of motion:
```
P = F·v
```

**Units:** Watt (W) = J/s
**Horsepower:** 1 hp = 746 W

---

## Collisions

### Types
| Type | KE conserved? | Momentum conserved? |
|------|--------------|-------------------|
| Elastic | ✅ Yes | ✅ Yes |
| Inelastic | ❌ No (lost to heat/sound) | ✅ Yes |
| Perfectly inelastic | ❌ Maximum loss | ✅ Yes |

> [!important] Momentum is ALWAYS conserved in all collisions (no external force)

### Perfectly Inelastic Collision (objects stick together)
```
m₁u₁ + m₂u₂ = (m₁+m₂)v
v = (m₁u₁ + m₂u₂)/(m₁+m₂)
```

### Elastic Collision (1D)
```
v₁ = ((m₁–m₂)u₁ + 2m₂u₂) / (m₁+m₂)
v₂ = ((m₂–m₁)u₂ + 2m₁u₁) / (m₁+m₂)
```

**Special cases:**
- Equal masses (m₁=m₂): velocities exchange
- m₂ >> m₁, m₂ at rest: m₁ bounces back with same speed, m₂ barely moves
- m₁ >> m₂, m₂ at rest: m₁ continues, m₂ flies off at ~2u₁

### Coefficient of Restitution (e)
```
e = relative speed of separation / relative speed of approach
e = 1 → elastic
e = 0 → perfectly inelastic
0 < e < 1 → inelastic
```

---

## Vertical Circular Motion

Object on string, moving in vertical circle of radius r:

**Minimum speed at top** (string just taut, T=0):
```
v_top(min) = √(gr)
```

**Minimum speed at bottom** (to complete circle):
```
v_bottom(min) = √(5gr)
```

**Tension at any point:**
```
T – mg·cosθ = mv²/r   (at angle θ from vertical)
At bottom: T_bottom = mg + mv²/r
At top:    T_top = mv²/r – mg
```

---

## Practice Questions

1. A 4 kg object moves from rest under 12 N force for 3 m. Find work done and final KE.

2. A 2 kg ball falls from 5 m. Find KE just before hitting ground. (g=10)

3. A spring (k=200 N/m) is compressed by 0.1 m. Find PE stored.

4. A 1000 kg car engine delivers 50 kW. Find max speed on flat road if friction force = 2000 N.

5. 5 kg moving at 6 m/s hits stationary 3 kg. They stick together. Find common velocity and KE lost.

> [!question]- Answers
> 1. W = F·s = 12×3 = 36 J; since starts from rest, KE = 36 J (Work-energy theorem)
> 2. Using conservation: KE = mgh = 2×10×5 = 100 J
> 3. PE = ½×200×0.01 = 1 J
> 4. At max speed P=Fv → v = P/F = 50000/2000 = 25 m/s
> 5. v = (5×6+0)/8 = 3.75 m/s; KE_initial=90J; KE_final=½×8×3.75²=56.25J; Lost=33.75J

---
**Previous: [[P2 Laws of Motion]]**
