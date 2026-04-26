# PC2 Chemical Equilibrium

> [!tip] One Line
> At equilibrium, forward rate = reverse rate. K tells you extent; Q tells you which way to go; Le Chatelier tells you how to shift.

---

## Equilibrium Constant

For: aA + bB ⇌ cC + dD

```
Kc = [C]ᶜ[D]ᵈ / [A]ᵃ[B]ᵇ   (concentrations, mol/L)
Kp = (Pc)ᶜ(Pd)ᵈ / (Pa)ᵃ(Pb)ᵇ  (partial pressures, atm)
```

**Relation:** Kp = Kc(RT)^Δn    where Δn = (moles gaseous products) – (moles gaseous reactants)

**Key facts:**
- K >> 1: products favoured (forward reaction nearly complete)
- K << 1: reactants favoured (reverse reaction favoured)
- K changes only with temperature
- Catalyst does NOT change K (speeds both directions equally)
- Pure solids and liquids NOT included in K expression

---

## Reaction Quotient (Q)

Same expression as K but with non-equilibrium concentrations:
- Q < K → reaction proceeds forward (makes more product)
- Q > K → reaction proceeds backward
- Q = K → system is at equilibrium

---

## Le Chatelier's Principle

*If a system at equilibrium is disturbed, it shifts to counteract the disturbance.*

| Disturbance | Shift Direction |
|------------|----------------|
| Add reactant | Forward |
| Remove product | Forward |
| Add product | Backward |
| Increase pressure (for gases) | Toward fewer moles of gas |
| Decrease pressure | Toward more moles of gas |
| Increase temperature | Toward endothermic direction |
| Decrease temperature | Toward exothermic direction |
| Add catalyst | No shift (equilibrium reached faster) |
| Add inert gas (constant V) | No shift |
| Add inert gas (constant P) | Toward more moles of gas |

---

## Degree of Dissociation (α)

α = fraction of original substance that dissociates.

For: A ⇌ nB, starting with 1 mol A:
- At equilibrium: (1–α) mol A, nα mol B
- Total moles = 1 – α + nα = 1 + (n–1)α

**Van't Hoff factor:** i = 1 + (n–1)α

---

## Ionic Equilibrium

### pH Scale
```
pH = –log[H⁺]    pOH = –log[OH⁻]    pH + pOH = 14 (at 25°C)
```
- pH < 7: acidic; pH = 7: neutral; pH > 7: basic

### Weak Acid/Base Equilibrium
For HA ⇌ H⁺ + A⁻:
```
Ka = [H⁺][A⁻]/[HA]
[H⁺] = √(Ka × C)    (if α << 1)
pH = ½(pKa – log C)
```

### Buffer (Henderson-Hasselbalch)
```
pH = pKa + log([A⁻]/[HA])    (for acidic buffer — weak acid + its conjugate base)
pOH = pKb + log([BH⁺]/[B])   (for basic buffer)
```

### Solubility Product (Ksp)
For sparingly soluble salt MₓAᵧ ⇌ xMⁿ⁺ + yAᵐ⁻:
```
Ksp = [Mⁿ⁺]ˣ[Aᵐ⁻]ʸ
```
- If ionic product > Ksp → precipitation occurs
- Common ion effect: adding common ion decreases solubility

---

## Common Equilibria

| Reaction | K expression |
|---------|-------------|
| H₂O ⇌ H⁺ + OH⁻ | Kw = 10⁻¹⁴ at 25°C |
| CH₃COOH ⇌ H⁺ + CH₃COO⁻ | Ka = 1.8 × 10⁻⁵ |
| NH₃ + H₂O ⇌ NH₄⁺ + OH⁻ | Kb = 1.8 × 10⁻⁵ |
| Ka × Kb = Kw | (for conjugate pair) |

---

## Practice Questions
1. N₂ + 3H₂ ⇌ 2NH₃, Δn = ? What is Kp in terms of Kc?
2. At equilibrium, Q > K. Which direction will reaction shift?
3. pH of 0.01 M HCl?
4. Buffer: 0.1 M CH₃COOH + 0.1 M CH₃COONa, pKa = 4.74. Find pH.

> [!question]- Answers
> 1. Δn = 2 – (1+3) = –2. Kp = Kc(RT)⁻²
> 2. Backward (toward reactants) — too much product present
> 3. [H⁺] = 0.01 M (strong acid), pH = –log(0.01) = 2
> 4. pH = 4.74 + log(0.1/0.1) = 4.74 + 0 = 4.74

---
**Previous: [[PC1 Mole Concept]]**
**Next: [[PC3 Electrochemistry]]**
