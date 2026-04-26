# P7 Magnetism & Electromagnetic Induction

> [!tip] One Line
> Moving charge = magnetic field. Changing magnetic flux = induced EMF (Faraday). Lenz's law: induced current opposes change (energy conservation).

---

## Magnetic Force on Moving Charge

```
F = qv × B = qvB sinθ    (Lorentz force)
```
Direction: Right-hand rule (or Fleming's left-hand rule for motors)
- Thumb: velocity v
- Index: B field
- Middle: Force on positive charge

**Circular motion in B field:**
```
r = mv/(qB)    (radius of circular path)
T = 2πm/(qB)   (period — independent of v!)
```

---

## Magnetic Force on Current-Carrying Conductor

```
F = BIl sinθ    (force on wire of length l carrying current I at angle θ to B)
F = I(L × B)    (vector form)
```

**Force between parallel wires:**
```
F/l = μ₀I₁I₂/(2πd)    (per unit length)
```
Same direction currents → attract; opposite direction → repel.

---

## Biot-Savart Law & Ampere's Law

**Biot-Savart:**
```
dB = μ₀I dl sinθ / (4πr²)
```

**Key results:**
- Long straight wire: B = μ₀I/(2πr) (circular field lines)
- Centre of circular loop: B = μ₀I/(2R)
- Solenoid: B = μ₀nI (inside, n = turns/length)
- Toroid: B = μ₀nI/(2πr) (inside)

**Ampere's Circuital Law:**
```
∮B·dl = μ₀I_enclosed
```

μ₀ = 4π × 10⁻⁷ T·m/A (permeability of free space)

---

## Electromagnetic Induction (Faraday's Law)

```
ε = –dΦ/dt    (EMF = –rate of change of magnetic flux)
Φ = NBA cosθ   (magnetic flux, Weber = T·m²)
```

**Lenz's Law:** Induced current flows to oppose the change in flux (direction from energy conservation).

**Motional EMF (rod moving in B field):**
```
ε = Bvl    (rod of length l moving with velocity v in field B)
```

---

## Self & Mutual Inductance

**Self-inductance:**
```
L = NΦ/I    (Henry = V·s/A)
ε = –L(dI/dt)
Solenoid: L = μ₀n²Al = μ₀N²A/l
```

**Mutual inductance:**
```
M = NΦ_B/I_A
ε₂ = –M(dI₁/dt)
```

**Energy stored in inductor:**
```
U = ½LI²
```

---

## AC Circuits

```
V = V₀ sin(ωt)    I = I₀ sin(ωt – φ)
V_rms = V₀/√2    I_rms = I₀/√2
```

**Impedances:**
```
Resistor: Z_R = R (no phase shift)
Capacitor: Z_C = 1/(ωC) (I leads V by 90°)
Inductor: Z_L = ωL (V leads I by 90°)
```

**Series LCR:**
```
Z = √(R² + (X_L – X_C)²)
tan φ = (X_L – X_C)/R
```

**Resonance:** X_L = X_C → Z = R (minimum impedance, maximum current)
```
ω₀ = 1/√(LC)    f₀ = 1/(2π√(LC))
```

**Power in AC:**
```
P = V_rms I_rms cos φ    (cos φ = power factor)
```
Pure L or C: cos φ = 0 → no power consumed.

---

## Transformer

```
V₁/V₂ = N₁/N₂ = I₂/I₁
```
Step-up: N₂ > N₁ (V increases, I decreases)
Step-down: N₂ < N₁ (V decreases, I increases)
Ideal transformer: P₁ = P₂ (no losses)

---

## Practice Questions
1. Electron moves at 10⁶ m/s in B = 0.1 T. Find radius of circular path. (m_e = 9.1×10⁻³¹ kg)
2. A coil has L = 0.5 H. EMF when current changes from 2A to 0 in 0.1s?
3. Transformer: primary 240V, 1000 turns. Secondary 12V. Find secondary turns.
4. In series LCR: R = 10Ω, X_L = 20Ω, X_C = 10Ω. Find Z and power factor.

> [!question]- Answers
> 1. r = mv/(qB) = (9.1×10⁻³¹ × 10⁶)/(1.6×10⁻¹⁹ × 0.1) = 9.1×10⁻²⁵/1.6×10⁻²⁰ ≈ 5.7×10⁻⁵ m = 0.057 mm
> 2. ε = L(ΔI/Δt) = 0.5 × (2/0.1) = 10 V
> 3. N₂/N₁ = V₂/V₁ → N₂ = 1000 × 12/240 = 50 turns
> 4. Z = √(10² + (20–10)²) = √(100+100) = 10√2 ≈ 14.1Ω; cos φ = R/Z = 10/10√2 = 1/√2 ≈ 0.707

---
**Previous: [[P6 Electrostatics & Current Electricity]]**
**Next: [[P8 Optics]]**
