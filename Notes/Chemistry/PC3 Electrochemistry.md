# PC3 Electrochemistry

> [!tip] One Line
> Higher SRP = better oxidizing agent = gets reduced. ΔG = –nFE. Electrolysis forces non-spontaneous reaction using external current.

---

## Electrochemical Cell (Galvanic)

Spontaneous redox reaction generates electricity.

```
Anode (–): Oxidation occurs → loses electrons
Cathode (+): Reduction occurs → gains electrons
Electrons flow: Anode → Cathode (external circuit)
Ions flow: through salt bridge
```

**Cell notation:** Zn | Zn²⁺ || Cu²⁺ | Cu
(Anode left, cathode right, || = salt bridge)

---

## Standard Electrode Potential (E°)

**Standard Reduction Potential (SRP):** tendency to be reduced (accept e⁻).
- Higher SRP → better oxidizing agent (more easily reduced)
- Lower SRP → better reducing agent (more easily oxidized)

**Cell EMF:**
```
E°cell = E°cathode – E°anode = E°reduction(+) – E°reduction(–)
```

**Important values:**
| Half-reaction | E° (V) |
|--------------|--------|
| F₂ + 2e⁻ → 2F⁻ | +2.87 |
| MnO₄⁻ + 8H⁺ + 5e⁻ → Mn²⁺ | +1.51 |
| Cl₂ + 2e⁻ → 2Cl⁻ | +1.36 |
| Cu²⁺ + 2e⁻ → Cu | +0.34 |
| 2H⁺ + 2e⁻ → H₂ | 0.00 (reference) |
| Zn²⁺ + 2e⁻ → Zn | –0.76 |
| Li⁺ + e⁻ → Li | –3.04 |

---

## Thermodynamics of Cells

```
ΔG° = –nFE°cell
ΔG° = –RT ln K    →    E° = (RT/nF) ln K = (0.0592/n) log K   (at 25°C)
```

**Nernst Equation (non-standard conditions):**
```
E = E° – (0.0592/n) log Q    (at 25°C)
```
As reaction proceeds → Q increases → E decreases → E = 0 at equilibrium.

**Battery is dead when:** E = 0 (equilibrium reached)

---

## Conductance

```
Resistance (R) = ρ × l/A
Conductance (G) = 1/R
Resistivity (ρ) = 1/κ    (κ = specific conductance or conductivity)
Cell constant = l/A
κ = G × (l/A)    (SI unit: S/m or S cm⁻¹)
```

**Molar conductivity (Λm):**
```
Λm = κ × 1000 / M    (M = molarity in mol/L)
```

### Kohlrausch's Law
At infinite dilution, each ion contributes independently:
```
Λ°m = λ°cation + λ°anion
```
Used to find Λ°m of weak electrolytes (can't be measured directly by extrapolation).

**Variation with concentration:**
- Strong electrolytes: Λm increases linearly as √C decreases
- Weak electrolytes: Λm increases sharply as C → 0 (dissociation increases)

---

## Electrolysis

**Non-spontaneous** redox driven by external EMF.

**Faraday's Laws:**
1. Mass deposited ∝ charge passed: **m = ZIt** (Z = electrochemical equivalent)
2. Same charge deposits masses in ratio of equivalent masses

```
m = (M × I × t) / (n × F)
```
F = 96500 C/mol (charge of 1 mol electrons)

**Electrolysis of water (dilute H₂SO₄):**
- Cathode: 2H⁺ + 2e⁻ → H₂
- Anode: 2H₂O → O₂ + 4H⁺ + 4e⁻

**Electrolysis of molten NaCl:**
- Cathode: Na⁺ + e⁻ → Na
- Anode: 2Cl⁻ → Cl₂ + 2e⁻

---

## Practice Questions
1. Zn-Cu galvanic cell: which is anode, which cathode?
2. E°cell = 1.10 V, n = 2. Find ΔG°.
3. Why does Λm of weak electrolytes increase sharply at very low concentration?
4. 2A current for 1 hour through CuSO₄. Mass of Cu deposited? (Cu = 63.5, n=2)

> [!question]- Answers
> 1. Zn = anode (lower SRP, –0.76 V, gets oxidized); Cu = cathode (+0.34 V, gets reduced)
> 2. ΔG° = –nFE° = –2 × 96500 × 1.10 = –212,300 J = –212.3 kJ
> 3. At low concentration, weak electrolyte dissociates more (α → 1), so more ions → higher conductance
> 4. m = (63.5 × 2 × 3600) / (2 × 96500) = (63.5 × 7200) / 193000 ≈ 2.37 g

---
**Previous: [[PC2 Chemical Equilibrium]]**
**Next: [[PC4 Thermodynamics]]**
