# P4 Rotational Motion

> [!tip] One Line
> Rotation mirrors translation: α↔a, τ↔F, I↔m, L↔p. Torque causes angular acceleration; angular momentum conserved when no external torque.

---

## Rotational Kinematics

Analogous to linear kinematics:

| Linear | Rotational |
|--------|-----------|
| x (displacement) | θ (angular displacement, rad) |
| v (velocity, m/s) | ω (angular velocity, rad/s) |
| a (acceleration, m/s²) | α (angular acceleration, rad/s²) |
| v = u + at | ω = ω₀ + αt |
| s = ut + ½at² | θ = ω₀t + ½αt² |
| v² = u² + 2as | ω² = ω₀² + 2αθ |

**Relation to linear:** v = rω,  a_tangential = rα,  a_centripetal = rω²

---

## Moment of Inertia (I)

**I = Σmᵢrᵢ²** — resistance to angular acceleration (rotational analogue of mass).

**Key formulas:**
| Body | Axis | I |
|------|------|---|
| Thin rod | Through centre ⊥ | ML²/12 |
| Thin rod | Through end ⊥ | ML²/3 |
| Solid cylinder/disc | Through centre (symmetry axis) | ½MR² |
| Hollow cylinder | Through centre | MR² |
| Solid sphere | Through diameter | 2/5 MR² |
| Hollow sphere | Through diameter | 2/3 MR² |
| Rectangular plate | Through centre | M(a²+b²)/12 |

**Parallel Axis Theorem:** I = Icm + Md²
(I about any axis = I about parallel axis through COM + Md²)

**Perpendicular Axis Theorem** (planar bodies only): Iz = Ix + Iy

---

## Torque & Angular Momentum

```
τ = r × F = rF sinθ    (SI: N·m)
τ = Iα
L = Iω = r × p          (angular momentum, SI: kg·m²/s)
τ = dL/dt
```

**Conservation of Angular Momentum:** If τ_ext = 0 → L = constant
- Ice skater pulls arms in → I decreases → ω increases (L conserved)
- Diver tucks → I decreases → spins faster

---

## Rolling Motion (pure rolling = no slipping)

```
v_cm = Rω    (rolling condition)
KE_total = ½Mv_cm² + ½Iω²
         = ½Mv_cm²(1 + I/MR²)
```

For solid sphere: KE_rot/KE_total = 2/7
For solid cylinder: KE_rot/KE_total = 1/3

**Acceleration down incline (angle θ):**
```
a = g sinθ / (1 + I/MR²)
```
- Solid sphere fastest down incline (smallest I/MR² = 2/5)
- Hollow sphere slowest (I/MR² = 2/3)

---

## Equilibrium Conditions

For static equilibrium:
1. ΣF = 0 (translational equilibrium)
2. Στ = 0 (rotational equilibrium, about ANY point)

---

## Practice Questions
1. A disc (M, R) starts from rest and rolls down a 30° incline. Find acceleration.
2. An ice skater spins at 2 rad/s with I = 4 kg·m². She pulls arms in, I becomes 1 kg·m². New ω?
3. Find I of solid sphere about a tangent.
4. τ = 10 N·m, I = 2 kg·m². Find α.

> [!question]- Answers
> 1. a = g sin30° / (1 + ½) = (10 × 0.5)/1.5 = 10/3 ≈ 3.33 m/s²
> 2. L = Iω = 4 × 2 = 8 kg·m²/s. New ω = L/I' = 8/1 = 8 rad/s
> 3. Using parallel axis: I_tangent = 2/5 MR² + MR² = 7/5 MR²
> 4. α = τ/I = 10/2 = 5 rad/s²

---
**Previous: [[P3 Work Energy Power]]**
**Next: [[P5 Gravitation & SHM]]**
