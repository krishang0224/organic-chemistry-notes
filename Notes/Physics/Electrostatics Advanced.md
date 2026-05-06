# Electrostatics & Current Electricity — Advanced

> [!tip] One Line
> COMEDK traps: energy stored in capacitor slabs, Kirchhoff multi-loop, potentiometer logic, and Wheatstone sensitivity.

---

## Electrostatics — Deep

### Energy Density of Electric Field
```
u = ½ε₀E²   (J/m³)
```
Energy stored in capacitor = ½CV² = ½ε₀E² × Volume

### Dielectric in Capacitor — Two Cases
**Slab inserted with battery connected (V constant):**
- C increases (C = KC₀)
- Q increases (Q = CV = KC₀V)
- E unchanged (E = V/d)
- Energy increases (U = ½CV² = KC₀V²/2 → increases) — energy comes from battery

**Slab inserted with battery disconnected (Q constant):**
- C increases
- V decreases (V = Q/C = Q/KC₀)
- E decreases
- Energy decreases (U = Q²/2C = Q²/2KC₀ → decreases) — energy released as heat

### Force Between Plates of Capacitor
```
F = Q²/(2ε₀A) = ε₀E²A/2 = σ²A/2ε₀
```

### Capacitors with Partial Dielectric
- Dielectric fills half of gap (parallel to plates): two capacitors in series
- Dielectric fills half of area (perpendicular to plates): two capacitors in parallel

---

## Current Electricity — Deep

### Potentiometer — Key Concepts
```
Principle: V ∝ l (at constant current)
```
- **Comparison of EMF:** ε₁/ε₂ = l₁/l₂
- **Internal resistance:** r = R(l₁–l₂)/l₂ where R = external resistance
- **Condition:** Driver cell EMF > cell being tested (always)
- Potentiometer draws NO current from the cell — ideal voltmeter

**Advantage over voltmeter:** Doesn't draw current → measures true EMF, not terminal voltage.

### Metre Bridge (Wheatstone)
```
P/Q = R/S → S = R(100–l)/l   (l = balancing length from left)
```
- S is unknown resistance
- Sensitivity: maximum when all four resistances are equal (P=Q=R=S)
- Swap P and Q to check — if no galvanometer deflection change, null point is accurate

### Kirchhoff's Laws — Multi-Loop Problems
**Strategy:**
1. Assign current directions (assumed — if negative, actual direction is opposite)
2. KCL at each junction: ΣI = 0
3. KVL for each loop: go in one direction, add +V for EMF in direction of travel, –V against
4. Solve simultaneous equations

**Sign convention for KVL:**
- Crossing EMF from – to +: add +ε
- Crossing EMF from + to –: add –ε
- Crossing resistor in direction of current: add –IR
- Crossing resistor against current: add +IR

### Drift Velocity & Resistance
```
v_d = eEτ/m = I/(nAe)
ρ = m/(ne²τ)   (τ = mean free time/relaxation time)
```
Higher temperature → more collisions → smaller τ → higher ρ → higher R (for metals)
Semiconductors: more carriers at high T → ρ decreases (opposite to metals)

### Power Dissipation in Resistor
```
P = I²R = V²/R = IV
```
For **maximum power transfer** from source to external load:
R_external = r (internal resistance) → P_max = ε²/4r

---

## Capacitor Circuits — Common Tricks

### Energy stored vs Energy supplied by battery
When capacitor charges from 0 to Q:
- Energy supplied by battery = Qε = CV²
- Energy stored in capacitor = ½CV²
- Energy dissipated as heat = ½CV² (always half, regardless of resistance!)

### Two Capacitors Connected (charge redistribution)
C₁ charged to V₁, C₂ uncharged, then connected:
```
Final voltage: V_f = C₁V₁/(C₁+C₂)
Energy lost = ½C₁C₂(V₁)²/(C₁+C₂)   (dissipated as heat/spark)
```

---

## Practice (COMEDK style)

1. A 4μF capacitor is charged to 100V and disconnected. A dielectric (K=2) fills it. Find new V, C, energy.
2. Two cells: ε₁=6V, r₁=1Ω and ε₂=4V, r₂=1Ω connected in parallel to external R=2Ω. Find current.
3. Potentiometer: balance length for 1.02V standard cell = 51cm. Balance for unknown cell = 60cm. Find EMF.
4. Find power consumed by 5Ω in: [5Ω and 10Ω in parallel, connected to 12V source with 2Ω internal resistance]

> [!question]- Answers
> 1. Battery disconnected → Q constant = 4×100 = 400μC; new C = KC₀ = 8μF; V = Q/C = 400/8 = 50V; U₀ = ½×4×10⁻⁶×10000 = 20mJ; U_new = ½×8×10⁻⁶×2500 = 10mJ (energy halved)
> 2. Using Kirchhoff or equivalent: ε_eq = (ε₁/r₁+ε₂/r₂)/(1/r₁+1/r₂) = (6+4)/2 = 5V; r_eq = r₁r₂/(r₁+r₂) = 0.5Ω; I = 5/(0.5+2) = 2A
> 3. ε_unknown/ε_standard = 60/51; ε = 1.02 × 60/51 = 1.2V
> 4. Parallel: R_parallel = (5×10)/(5+10) = 10/3 Ω; Total R = 10/3 + 2 = 16/3Ω; I_total = 12/(16/3) = 2.25A; V_parallel = I×R_parallel = 2.25×10/3 = 7.5V; P(5Ω) = V²/R = 56.25/5 = 11.25W
