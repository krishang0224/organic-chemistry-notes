# P5 Gravitation & Simple Harmonic Motion

> [!tip] One Line
> Gravity: F = GMm/r². SHM: restoring force ∝ –x; energy oscillates between KE and PE, total stays constant.

---

## Gravitation

### Universal Law of Gravitation
```
F = GMm/r²    (G = 6.67 × 10⁻¹¹ N·m²/kg²)
```

### Gravitational Field & Potential
```
g = GM/r²     (gravitational field intensity, m/s²)
V = –GM/r     (gravitational potential, J/kg; negative = bound)
```
At Earth's surface: g₀ = 9.8 m/s² ≈ 10 m/s²

### Variation of g
```
With height: g_h = g₀(R/(R+h))² ≈ g₀(1 – 2h/R) for h << R
With depth: g_d = g₀(1 – d/R)
```
g = 0 at Earth's centre.

**g at poles > g at equator** (poles closer to center, no centrifugal effect)

---

## Satellites & Orbital Motion

**Orbital velocity:**
```
v₀ = √(GM/r) = √(gR²/(R+h))
```
At surface: v₀ = √(gR) ≈ 7.9 km/s

**Time period:**
```
T = 2π√(r³/GM)    (Kepler's 3rd law: T² ∝ r³)
```

**Escape velocity:** (to escape Earth's gravity)
```
v_esc = √(2GM/R) = √(2gR) ≈ 11.2 km/s
```
Note: v_esc = √2 × v₀ (for surface orbit)

**Geostationary orbit:** T = 24 h, height ≈ 36,000 km above equator

**Energy of satellite:**
```
KE = GMm/2r
PE = –GMm/r
Total E = –GMm/2r    (negative → bound system)
```

---

## Kepler's Laws
1. **Law of Orbits:** Planets move in ellipses with Sun at one focus
2. **Law of Areas:** Equal areas swept in equal times (conservation of L: angular momentum)
3. **Law of Periods:** T² ∝ a³ (a = semi-major axis)

---

## Simple Harmonic Motion (SHM)

**Definition:** Motion where restoring force ∝ displacement, directed toward equilibrium.

```
F = –kx    →    a = –ω²x    (defining equation)
```

**General solution:**
```
x = A cos(ωt + φ)
v = –Aω sin(ωt + φ)
a = –Aω² cos(ωt + φ)
ω = 2π/T = 2πf
```

**Maximum values:**
- x_max = A (amplitude)
- v_max = Aω (at equilibrium, x = 0)
- a_max = Aω² (at extreme, x = ±A)

---

## Energy in SHM

```
KE = ½mω²(A² – x²)
PE = ½mω²x²
Total E = ½mω²A² = ½kA²    (constant)
```

KE maximum at x = 0; PE maximum at x = ±A.

---

## Common SHM Systems

### Simple Pendulum
```
T = 2π√(L/g)    (valid for small angles, θ < 15°)
```
T independent of mass and amplitude.

### Spring-Mass System
```
T = 2π√(m/k)
```
- Springs in series: 1/k_eff = 1/k₁ + 1/k₂ (softer)
- Springs in parallel: k_eff = k₁ + k₂ (stiffer)

### Spring in vertical orientation: same T (gravity doesn't affect T, only changes equilibrium position)

---

## Practice Questions
1. If Earth's radius doubles, new g at surface?
2. Orbital velocity of satellite at height R above Earth (R = 6400 km, g = 10 m/s²)?
3. A spring k = 100 N/m, mass 0.25 kg. Find T and f.
4. In SHM, at what displacement is KE = PE?

> [!question]- Answers
> 1. g ∝ 1/R², double R → g becomes g₀/4 = 2.5 m/s²
> 2. v = √(gR²/(R+h)) = √(10 × (6.4×10⁶)²/(2×6.4×10⁶)) = √(gR/2) = √(10×6.4×10⁶/2) ≈ 5.6 km/s
> 3. ω = √(k/m) = √(100/0.25) = 20 rad/s; T = 2π/20 ≈ 0.314 s; f = 1/T ≈ 3.18 Hz
> 4. KE = PE → ½mω²(A²–x²) = ½mω²x² → A²–x² = x² → x = A/√2

---
**Previous: [[P4 Rotational Motion]]**
**Next: [[P6 Electrostatics & Current Electricity]]**
