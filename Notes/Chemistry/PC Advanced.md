# PC Advanced — Physical Chemistry Depth

> [!tip] One Line
> COMEDK throws numerical traps. Know where units break, where Kp vs Kc matters, and how Nernst equation shifts with Q.

---

## Equilibrium — Tricky Points

### Degree of Dissociation & Van't Hoff Factor

For PCl₅ ⇌ PCl₃ + Cl₂ (start: 1 mol, α = degree of dissociation):
```
At eq: (1–α) mol PCl₅, α mol PCl₃, α mol Cl₂
Total = 1 + α moles
Observed molar mass = M/(1+α)   →  α = (M_theoretical – M_observed)/M_observed
```

**i = 1 + α** for one→two split; **i = 1 + 2α** for one→three; etc.

### Effect of Pressure on Equilibrium
- Increase pressure → shifts to side with FEWER moles of gas
- If Δn = 0 (e.g., H₂ + I₂ ⇌ 2HI): pressure change has NO effect
- Adding inert gas at **constant volume**: no effect (partial pressures unchanged)
- Adding inert gas at **constant pressure**: volume increases → partial pressures decrease → shifts to more moles side

### Kp vs Kc Traps
```
Kp = Kc(RT)^Δn
```
If Δn = 0: Kp = Kc
If Δn > 0: Kp > Kc
If Δn < 0: Kp < Kc
R = 0.0821 L·atm/mol·K (use this when P in atm)

---

## Ionic Equilibrium — Tricky Points

### Weak Acid — When Approximation Fails
[H⁺] = √(Ka·C) only valid when α << 1, i.e., Ka/C << 0.01
If Ka/C > 0.01 → use quadratic: α² + (Ka/C)α – Ka/C = 0... 
Actually: Ka = Cα²/(1–α); solve properly.

### Buffer Capacity
Buffer resists pH change best when [salt]/[acid] = 1, i.e., pH = pKa
Effective buffer range: pH = pKa ± 1

### Salt Hydrolysis
- Strong acid + weak base (NH₄Cl): hydrolysis of NH₄⁺, solution ACIDIC
  pH = 7 – ½(pKb – logC)
- Weak acid + strong base (CH₃COONa): hydrolysis of CH₃COO⁻, solution BASIC
  pH = 7 + ½(pKa + logC)
- Weak acid + weak base (CH₃COONH₄): pH ≈ 7 + ½(pKa – pKb)

### Common Ion Effect on Solubility
AgCl in 0.1M NaCl:
- Ksp(AgCl) = 1.8×10⁻¹⁰ = [Ag⁺][Cl⁻] = s × (0.1 + s) ≈ s × 0.1
- s = 1.8×10⁻⁹ M (much less soluble than in pure water where s = 1.34×10⁻⁵)

---

## Electrochemistry — Tricky Points

### Nernst Equation Traps
```
E = E° – (0.0592/n) log Q   (at 25°C)
```
- When Q = 1: E = E° (standard conditions)
- As cell discharges: Q increases → E decreases
- At equilibrium: E = 0, Q = K → E° = (0.0592/n) log K

**Common trap:** For concentration cell (same electrode, different concentrations):
E° = 0 (identical electrodes), so E = –(0.0592/n) log([dilute]/[concentrated])
Current flows from dilute to concentrated (as expected).

### Electrolysis — Faraday Traps
```
m = (M × I × t)/(n × F)
```
- n here is **charge per ion** (n-factor for electrolysis = ionic charge)
- Cu²⁺ → Cu: n = 2; Al³⁺ → Al: n = 3

**Series electrolysis:** Same current flows through all cells → moles of electrons same → masses deposited in ratio of equivalent masses.

### Kohlrausch — Calculating Ka
For weak acid CH₃COOH:
```
Λm at concentration C = Λ°m × α   (α = degree of dissociation)
α = Λm(C) / Λ°m
Ka = Cα² / (1–α)
```
Λ°m of CH₃COOH = λ°(H⁺) + λ°(CH₃COO⁻) — from Kohlrausch law (can't extrapolate directly for weak acids).

---

## Thermodynamics — Tricky Points

### Enthalpy of Neutralization
- Strong acid + strong base: ΔH = –57.1 kJ/mol (always, for water formation)
- Weak acid + strong base: ΔH = –57.1 + ΔH_ionization (less exothermic because ionization is endothermic)
- HCN + NaOH: less than 57.1 kJ because HCN ionization requires energy

### Hess's Law — Standard Traps
- ΔH°f of elements in standard state = 0 (not compounds!)
- ΔH°combustion is always negative
- ΔH°rxn = Σ ΔH°f(products) – Σ ΔH°f(reactants)

### Born-Haber Cycle
Lattice energy of ionic crystals:
```
ΔH°f = ΔH°sublimation + ½ΔH°dissociation + IE + EA + Lattice energy
```
(Hess's law applied to ionic solid formation)
Higher lattice energy → more stable ionic compound, higher melting point.

### Entropy Rules (for direction prediction)
Increases when:
- Gases produced from solids/liquids
- Number of moles of gas increases
- Ionic solid dissolves (usually — but not always: MgSO₄ dissolving has ΔS < 0 due to ion hydration)
- Temperature increases

Decreases when:
- Gas → liquid/solid
- Ordered structure forms

---

## Mole Concept — COMEDK Number Traps

### Mass Spectrometry / Average Atomic Mass
Average mass = Σ (isotope mass × fractional abundance)
Example: Cl = 35×0.75 + 37×0.25 = 35.5

### Empirical vs Molecular Formula
1. % → grams (÷100) → moles (÷atomic mass) → ratio (÷smallest)
2. Molecular mass ÷ empirical formula mass = n
3. Molecular formula = n × empirical formula

### % yield vs % purity
These are often combined:
- actual moles = (mass × purity%) / molar mass
- % yield = (actual product / theoretical) × 100

---

## Practice (COMEDK style)

1. PCl₅ dissociates 40% at 1 atm. Find Kp.
2. pH of 0.1M NH₄Cl (Kb of NH₃ = 1.8×10⁻⁵)?
3. For Daniel cell (Zn/Cu), if [Zn²⁺] = 0.1M and [Cu²⁺] = 0.01M, find E. (E° = 1.10V)
4. ΔH°f of CO₂ = –393 kJ/mol, CO = –111 kJ/mol. Find ΔH° for CO + ½O₂ → CO₂.

> [!question]- Answers
> 1. Δn=1; at α=0.4: (0.6), (0.4), (0.4) total=1.4 mol. Kp = Kc(RT)¹; Kc = (0.4×0.4)/(0.6×1.4) = 0.16/0.84 ≈ 0.19; Kp = 0.19×RT (at 298K ≈ 4.6)... actually for Kp directly: partial pressures; mole fractions: PCl₃=Cl₂=0.4/1.4, PCl₅=0.6/1.4; Kp = (0.4/1.4)² × 1 / (0.6/1.4) = (0.16/1.96)/(0.6/1.4) = (0.0816)/(0.4286) ≈ 0.19 atm
> 2. pOH of NH₄⁺ solution: [H⁺] = √(Kw/Kb × C) = √(10⁻¹⁴/1.8×10⁻⁵ × 0.1) = √(5.56×10⁻¹¹) ≈ 7.45×10⁻⁶; pH ≈ 5.13
> 3. E = 1.10 – (0.0592/2)log([Zn²⁺]/[Cu²⁺]) = 1.10 – 0.0296×log(0.1/0.01) = 1.10 – 0.0296×1 = 1.0704 V
> 4. ΔH = ΔH°f(CO₂) – ΔH°f(CO) – 0 = –393 – (–111) = –282 kJ/mol
