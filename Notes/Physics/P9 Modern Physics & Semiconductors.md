# P9 Modern Physics & Semiconductors

> [!tip] One Line
> Photoelectric effect: E = hf. Nuclear: E = mc². Semiconductors: p-type (+holes), n-type (e⁻), junction = diode.

---

## Dual Nature of Radiation & Matter

### Photoelectric Effect (Einstein, 1905)
```
E = hf    (photon energy, h = 6.626 × 10⁻³⁴ J·s)
KE_max = hf – φ    (φ = work function = minimum energy to eject electron)
φ = hf₀    (f₀ = threshold frequency)
```
- No photoelectric effect if f < f₀ (regardless of intensity)
- KE_max depends on frequency, NOT intensity
- Intensity determines NUMBER of electrons emitted (photocurrent)

**de Broglie Wavelength:**
```
λ = h/mv = h/p    (matter waves)
```
Electrons, protons etc. behave as waves: verified by electron diffraction.

**Heisenberg Uncertainty Principle:**
```
Δx · Δp ≥ h/(4π)
ΔE · Δt ≥ h/(4π)
```

---

## Atomic Models & Bohr's Model

**Bohr's postulates:**
1. Electrons move in fixed orbits (stationary states) with L = nh/(2π)
2. No energy radiated in orbit
3. Energy emitted/absorbed when electron jumps orbits: ΔE = hf

**For hydrogen (Z=1):**
```
rₙ = 0.529 × n² Å    (Bohr radius)
vₙ = 2.18 × 10⁶/n m/s
Eₙ = –13.6/n² eV
```

**Spectral series (hydrogen):**
| Series | n₁ | n₂ | Region |
|--------|-----|-----|--------|
| Lyman | 1 | 2,3,4... | UV |
| Balmer | 2 | 3,4,5... | Visible |
| Paschen | 3 | 4,5,6... | IR |
| Brackett | 4 | 5,6,7... | IR |

```
1/λ = RH(1/n₁² – 1/n₂²)    (RH = 1.097 × 10⁷ m⁻¹)
```

---

## Nuclear Physics

### Nuclear Dimensions
```
R = R₀A^(1/3)    (R₀ = 1.2 × 10⁻¹⁵ m, A = mass number)
```
Nuclear density: ~2.3 × 10¹⁷ kg/m³ (enormous and same for all nuclei)

### Binding Energy
```
BE = Δm × c²    (Δm = mass defect = sum of nucleon masses – nuclear mass)
BE/nucleon peaks at Fe-56 (most stable nucleus)
```

### Radioactive Decay
```
N = N₀e^(–λt)
t₁/₂ = 0.693/λ    (half-life)
A = λN    (activity, Becquerel = 1 decay/s)
```

**Types of decay:**
- α: loses ₂He⁴ (Z–2, A–4)
- β⁻: n → p + e⁻ + ν̄ (Z+1, A same)
- β⁺: p → n + e⁺ + ν (Z–1, A same)
- γ: no change in Z or A (energy emission only)

### Nuclear Reactions
```
Fission: ²³⁵U + n → ¹⁴¹Ba + ⁹²Kr + 3n + energy
Fusion: ²H + ³H → ⁴He + n + 17.6 MeV
```
E = mc², 1 amu = 931.5 MeV

---

## Semiconductors

### Types
- **Intrinsic:** pure semiconductor (Si, Ge); n_e = n_h = n_i at all times
- **n-type:** doped with pentavalent impurity (P, As, Sb); extra electrons are majority carriers
- **p-type:** doped with trivalent impurity (B, Al, In); holes are majority carriers

### p-n Junction Diode
- **Forward bias:** p connected to +, n to –; low resistance, current flows; V_threshold ≈ 0.7V (Si)
- **Reverse bias:** p to –, n to +; high resistance, tiny leakage current; breakdown at high voltage

**Half-wave rectifier:** one diode, rectifies one half of AC cycle
**Full-wave rectifier:** bridge rectifier (4 diodes), rectifies both halves

### Zener Diode
Works in reverse breakdown (Zener voltage). Used as voltage regulator.
```
Regulated output = Vz (constant regardless of load changes)
```

### Transistor (BJT)
- NPN or PNP; three regions: emitter, base, collector
- **CE configuration (common emitter):** most used amplifier
- **Current gain:** β = I_C/I_B (typically 50–300)
- **Voltage amplification:** A_v = β × R_C/R_in

### Logic Gates
| Gate | Symbol | Boolean | Truth table summary |
|------|--------|---------|---------------------|
| AND | · | A·B | Output 1 only when both inputs 1 |
| OR | + | A+B | Output 0 only when both inputs 0 |
| NOT | ¬ | Ā | Inverts input |
| NAND | | ¬(A·B) | AND + NOT |
| NOR | | ¬(A+B) | OR + NOT |
| XOR | ⊕ | A⊕B | Output 1 when inputs differ |

NAND and NOR are **universal gates** (can make any other gate from them).

---

## Practice Questions
1. Work function of metal = 2 eV. Minimum frequency of light to cause photoelectric effect?
2. Electron in H atom: energy at n=3?
3. Half-life of radioactive element = 10 days. After 30 days, fraction remaining?
4. In transistor: I_B = 50 μA, β = 100. Find I_C.

> [!question]- Answers
> 1. φ = hf₀ → f₀ = φ/h = (2 × 1.6×10⁻¹⁹)/(6.626×10⁻³⁴) = 4.83 × 10¹⁴ Hz
> 2. E₃ = –13.6/3² = –13.6/9 ≈ –1.51 eV
> 3. 30 days = 3 half-lives → fraction remaining = (1/2)³ = 1/8
> 4. I_C = β × I_B = 100 × 50 μA = 5000 μA = 5 mA

---
**Previous: [[P8 Optics]]**
