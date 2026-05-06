# Modern Physics — Advanced

> [!tip] One Line
> Numerical traps: energy levels in eV, nuclear binding energy in MeV, activity decay, and de Broglie in accelerated particles.

---

## Photoelectric Effect — Deep

### Stopping Potential
```
KE_max = eV₀    (V₀ = stopping potential)
eV₀ = hf – φ
```
- Plot V₀ vs f: slope = h/e, x-intercept = threshold frequency f₀
- Intensity increases → more electrons (more current) but KE_max unchanged
- Frequency increases → KE_max increases, threshold stays same

### de Broglie Wavelength in Various Cases
```
General: λ = h/mv = h/p

For particle accelerated through potential V:
p = √(2meV) → λ = h/√(2meV)

For thermal particle at temperature T:
KE = 3/2 kT → λ = h/√(3mkT)
```
Electrons have much smaller mass → much smaller λ → better microscope resolution.

### Davisson-Germer Experiment
- Electron diffraction by nickel crystal → confirmed de Broglie hypothesis
- Peak at 54V, 50° → λ_calculated = λ_de Broglie (match)

---

## Bohr Model — Deep

### Energy Level Transitions
```
ΔE = E_final – E_initial = –13.6(1/n_f² – 1/n_i²) eV
```
- Emission: n_i > n_f (energy released, photon emitted)
- Absorption: n_f > n_i (energy absorbed, photon absorbed)
- Minimum energy to ionize from n=1: 13.6 eV

### Hydrogen-Like Ions
For atom with atomic number Z:
```
Eₙ = –13.6Z²/n² eV
rₙ = 0.529n²/Z Å
```
He⁺: Z=2; Li²⁺: Z=3

### Spectral Lines Count
From n_i to n_f (n_i > n_f): number of spectral lines = (n_i – n_f)(n_i – n_f + 1)/2

For atom excited to level n: lines = n(n–1)/2

---

## X-Rays

```
λ_min = hc/eV = 12400/V (Å)   (V in volts — cut-off wavelength)
```
- **Characteristic X-rays:** electron transition between inner shells; wavelength characteristic of element
- **Bremsstrahlung (continuous):** deceleration of electrons; continuous spectrum with cut-off at λ_min

**Moseley's Law:** √f = a(Z – b) — relates X-ray frequency to atomic number

---

## Radioactivity — Deep

### Activity
```
A = λN = A₀e^(–λt)    (Becquerel = 1 decay/s, Curie = 3.7×10¹⁰ Bq)
A₀ = λN₀
```
**Mean life:** τ = 1/λ = t₁/₂/0.693

### Nuclear Reactions — Conservation Laws
- Mass number (A): conserved
- Atomic number (Z): conserved
- Energy: conserved (Q value = ΔMc²)

**Q value:**
```
Q = (M_reactants – M_products) × 931.5 MeV/amu
Q > 0: exothermic (energy released)
Q < 0: endothermic (energy required)
```

### Nuclear Binding Energy Per Nucleon
- Peaks at Fe-56 (~8.8 MeV/nucleon) → most stable
- Light nuclei: fusion releases energy (going toward Fe)
- Heavy nuclei: fission releases energy (going toward Fe)
- BE/nucleon dips at ⁴He, ¹²C (magic numbers — extra stability)

### Radioactive Decay Series
| Parent | End product | α decays | β decays |
|--------|------------|---------|---------|
| U-238 | Pb-206 | 8 | 6 |
| U-235 | Pb-207 | 7 | 4 |
| Th-232 | Pb-208 | 6 | 4 |

Formula: if α decays = a, then ΔZ from α = 2a; need β decays = 2a – ΔZ_total

---

## Semiconductors — Advanced

### p-n Junction in Detail
**Depletion region:** No free carriers; built-in electric field from + ions (n-side) to – ions (p-side).
**Built-in potential:** Opposes further diffusion; typically 0.6–0.7V for Si.

**Forward bias (V_f):** Reduces barrier → current flows exponentially above threshold (~0.7V Si, ~0.3V Ge)

**Reverse saturation current:** Very small (~μA); temperature-dependent (doubles every ~10°C)

**Zener breakdown vs Avalanche breakdown:**
- Zener (<5V): quantum tunneling through thin depletion layer
- Avalanche (>6V): impact ionization (carrier multiplication)

### Transistor in Detail (CE configuration)
```
I_E = I_B + I_C
β = I_C/I_B    (current gain, 50–300)
α = I_C/I_E = β/(1+β)   (< 1 always)
```

**Voltage gain:**
```
A_v = –β × R_C/r_i   (r_i = input resistance)
```

**Transistor as switch:**
- Cut-off: I_B = 0, I_C = 0 (OFF)
- Saturation: maximum I_C (ON) — V_CE ≈ 0.2V

### Logic Family Speed
NAND and NOR are universal gates.

---

## Practice (COMEDK style)

1. UV light (λ=300nm) falls on metal (φ=2.0eV). Find KE_max and stopping potential.
2. Electron accelerated through 100V. Find de Broglie wavelength.
3. ²²⁶Ra (half-life = 1600 yr). How many decays per second in 1g of Ra?
4. In a transistor: β=100, I_B=40μA. Find I_C and I_E.

> [!question]- Answers
> 1. E = hc/λ = (6.626×10⁻³⁴ × 3×10⁸)/(300×10⁻⁹) = 6.626×10⁻¹⁹ J = 4.14eV; KE = 4.14–2.0 = 2.14eV; V₀ = 2.14V
> 2. λ = h/√(2meV) = 6.626×10⁻³⁴/√(2×9.1×10⁻³¹×1.6×10⁻¹⁹×100) = 6.626×10⁻³⁴/√(2.912×10⁻²⁷) = 6.626×10⁻³⁴/1.706×10⁻¹³·⁵ ≈ 1.23Å
> 3. N = (1/226)×6.022×10²³ = 2.665×10²¹; λ = 0.693/t₁/₂ = 0.693/(1600×365×24×3600) = 1.374×10⁻¹¹ s⁻¹; A = λN = 3.66×10¹⁰ Bq ≈ 1 Curie ✓
> 4. I_C = β×I_B = 100×40μA = 4000μA = 4mA; I_E = I_B + I_C = 40+4000 = 4040μA ≈ 4.04mA
