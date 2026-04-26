# P6 Electrostatics & Current Electricity

> [!tip] One Line
> Coulomb's law like gravity (1/r²). E field points away from +, toward –. Kirchhoff's laws: ΣI = 0 at junction, ΣV = 0 in loop.

---

## Electrostatics

### Coulomb's Law
```
F = kq₁q₂/r²    (k = 9 × 10⁹ N·m²/C², ε₀ = 8.85 × 10⁻¹² C²/N·m²)
k = 1/(4πε₀)
```

### Electric Field (E)
```
E = F/q₀ = kQ/r²    (due to point charge Q)
```
Direction: away from +Q, toward –Q.

**Superposition:** E_total = ΣEᵢ (vector sum)

### Electric Potential (V)
```
V = kQ/r    (scalar, J/C = V)
E = –dV/dr    (E = –gradient of V)
```
Equipotential surfaces: no work done moving charge along them; always ⊥ to E field.

### Electric Flux & Gauss's Law
```
Φ = E·A cosθ
Gauss's Law: Φ = q_enclosed / ε₀
```

**Applications:**
- Infinite plane sheet: E = σ/2ε₀
- Two parallel plates (capacitor): E = σ/ε₀
- Inside conductor: E = 0 (charge on surface only)
- Outside sphere: E = kQ/r² (same as point charge)
- Inside sphere: E = 0

---

## Capacitance

```
C = Q/V    (F = C/V = Farad)
Parallel plate: C = ε₀A/d
With dielectric: C = Kε₀A/d = KC₀
```

**Combinations:**
```
Series: 1/C_eff = Σ1/Cᵢ    (Q same, V adds)
Parallel: C_eff = ΣCᵢ      (V same, Q adds)
```

**Energy stored in capacitor:**
```
U = ½CV² = Q²/2C = ½QV
```

---

## Current Electricity

### Ohm's Law & Resistance
```
V = IR    (R = ρl/A, ρ = resistivity in Ω·m)
```

**Temperature dependence:** R = R₀(1 + αT) where α = temperature coefficient

**Combinations:**
```
Series: R_eff = ΣRᵢ
Parallel: 1/R_eff = Σ1/Rᵢ
```

### Kirchhoff's Laws
1. **KCL (Junction rule):** ΣI = 0 at any junction (charge conservation)
2. **KVL (Loop rule):** ΣV = 0 around any closed loop (energy conservation)

### Power
```
P = VI = I²R = V²/R    (W = watts)
```

### EMF and Internal Resistance
```
V_terminal = ε – Ir    (ε = EMF, r = internal resistance, I = current)
```
Short circuit: I = ε/r (when R = 0)
Open circuit: V = ε (when I = 0)

---

## Wheatstone Bridge
Balanced when: P/Q = R/S → no current through galvanometer
```
P/Q = R/S    (balance condition)
```

**Metre bridge:** L₁/(100–L₁) = R/S

---

## Drift Velocity & Current
```
I = nAev_d    (n = electron density, A = area, e = 1.6×10⁻¹⁹ C, v_d = drift velocity)
J = I/A = nev_d = σE    (J = current density, σ = conductivity = 1/ρ)
```

---

## Practice Questions
1. Two charges +2μC and –2μC separated by 1 m. Force between them?
2. A 6V battery (internal resistance 1Ω) connected to 2Ω resistor. Find current and terminal voltage.
3. Three capacitors 2, 3, 6 μF in parallel. Effective capacitance?
4. In Wheatstone bridge: P=10Ω, Q=5Ω, R=20Ω. Find S for balance.

> [!question]- Answers
> 1. F = k|q₁||q₂|/r² = 9×10⁹ × 2×10⁻⁶ × 2×10⁻⁶ / 1² = 9×10⁹ × 4×10⁻¹² = 0.036 N (attractive)
> 2. I = ε/(R+r) = 6/(2+1) = 2A; V_terminal = ε – Ir = 6 – 2×1 = 4V
> 3. C_eff = 2+3+6 = 11 μF
> 4. P/Q = R/S → 10/5 = 20/S → S = 20×5/10 = 10Ω

---
**Previous: [[P5 Gravitation & SHM]]**
**Next: [[P7 Magnetism & EMI]]**
