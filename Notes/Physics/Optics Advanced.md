# Optics — Advanced

> [!tip] One Line
> COMEDK optics traps: sign convention consistency, fringe shift in YDSE, equivalent lens combinations, and coherence conditions.

---

## Ray Optics — Deep

### Refraction Through a Prism — Full Analysis
```
i + e = A + δ    (i = angle of incidence, e = emergent angle, A = prism angle, δ = deviation)
At minimum deviation: i = e, r₁ = r₂ = A/2
n = sin((A+Dₘ)/2) / sin(A/2)
```

**For thin prism (small A):**
```
δ = (n–1)A
```
Dispersion: δ_V > δ_R (violet deviates more than red → n_V > n_R)

**Dispersive power:** ω = (n_V – n_R)/(n_y – 1) where n_y = mean refractive index

### Equivalent Mirror/Lens Systems
**Equivalent focal length of two lenses separated by d:**
```
1/F = 1/f₁ + 1/f₂ – d/(f₁f₂)
```
When d = 0: 1/F = 1/f₁ + 1/f₂

**Silvered lens (mirror + lens system):**
Equivalent mirror: P_eq = P_lens + P_mirror + P_lens = 2P_lens + P_mirror
f_eq = 1/P_eq (in meters)

### Common Image Position Traps
For concave mirror, object at:
- Beyond C (u < –2f): real, inverted, diminished (between F and C on same side)
- At C (u = –2f): real, inverted, same size (at C)
- Between C and F: real, inverted, magnified (beyond C)
- At F: image at infinity
- Between F and P: virtual, erect, magnified (behind mirror)

For convex mirror: always virtual, erect, diminished (between P and F, behind mirror)

---

## Wave Optics — Deep

### YDSE with Various Modifications

**Fringe width:** β = λD/d

**Shift due to slab (refractive index n, thickness t) in one path:**
```
Shift = (n–1)t × D/d = (n–1)t/β × β   [in terms of fringes]
Number of fringes shifted = (n–1)t/λ
```
Pattern shifts toward the side with the slab (toward the denser medium).

**Shift due to immersing in medium (refractive index μ):**
```
λ' = λ/μ → β' = β/μ   (fringe width decreases)
```

**Intensity when amplitudes are different (r₁ ≠ r₂):**
```
I_max = (√I₁ + √I₂)²
I_min = (√I₁ – √I₂)²
I = I₁ + I₂ + 2√(I₁I₂)cosδ
```

**Coherence:** Sources must have constant phase difference. Laser = highly coherent; thermal sources = incoherent.

### Thin Film Interference
For film of thickness t, refractive index n, viewed in reflected light:
```
Constructive: 2nt = (m + ½)λ   (due to phase change at denser medium reflection)
Destructive: 2nt = mλ
```
Air wedge: dark fringe at thin end (t=0 → phase change only → dark)

### Diffraction — Key Points
Single slit, minima at: a sinθ = mλ → y = mλD/a
Central max width = 2λD/a (twice the other maxima)

**Resolution (Rayleigh criterion):**
```
Telescope: θ_min = 1.22λ/D
```
Larger aperture D → better resolution (smaller θ_min).

**Diffraction limit:** Why can't optical microscopes resolve atoms? λ_visible ≈ 400–700nm >> atomic sizes.

---

## Optical Instruments — Advanced

### Compound Microscope
```
M = (L/f_o) × (D/f_e)   [image at ∞, D = 25cm least distance of distinct vision]
M = (L/f_o) × (1 + D/f_e)   [image at least distance]
```
L = tube length (image distance from objective – f_o)

**To increase magnification:** shorter f_o and f_e; longer tube

### Telescope
```
M = f_o/f_e   [normal adjustment, image at ∞]
M = f_o/f_e × (1 + f_e/D)   [final image at least distance]
```
**Length:** L = f_o + f_e (normal adjustment)

**Reflecting telescope:** Mirror replaces objective lens → no chromatic aberration, larger aperture possible.

---

## Polarization — Deep

**Malus's Law:** I = I₀cos²θ
**Brewster's angle:** n = tan(θ_B) → reflected ray fully polarized
At θ_B: reflected + refracted rays are perpendicular (90°)

**Circular polarization:** two perpendicular components with 90° phase difference
**Elliptical polarization:** two components with phase difference ≠ 0, ≠ 90°

---

## Practice (COMEDK style)

1. YDSE: d=0.5mm, D=1m, λ=600nm. A glass slab (n=1.5, t=0.1mm) covers one slit. Find fringe shift.
2. Two lenses f₁=20cm, f₂=–10cm, separated by 5cm. Find equivalent focal length.
3. Prism (A=60°, n=1.5). Find angle of minimum deviation.
4. Resolving power of telescope: objective diameter 10cm, λ=500nm. Find minimum angle resolved.

> [!question]- Answers
> 1. Shift = (n–1)t/β × β... or directly: shift in terms of fringes = (n–1)t/λ = 0.5 × 0.1×10⁻³/(600×10⁻⁹) = 50000/600 ≈ 83.3 fringes; actual distance = (n–1)t×D/d = 0.5×10⁻⁴×1/5×10⁻⁴ = 0.1m = 10cm... that's huge, let me redo: (n–1)t×D/d = (1.5–1)×0.1×10⁻³×1/(0.5×10⁻³) = 0.5×0.1/0.5 = 0.1m — wait that's 10cm. β = λD/d = 600×10⁻⁹×1/(0.5×10⁻³) = 1.2mm. Shift = 0.1m/1.2mm = 83.3 fringes. ✓
> 2. 1/F = 1/20 + 1/(–10) – 5/(20×(–10)) = 0.05 – 0.1 + 0.025 = –0.025; F = –40cm (diverging)
> 3. n = sin((60°+Dₘ)/2)/sin30°; 1.5 = sin((60°+Dₘ)/2)/0.5; sin((60°+Dₘ)/2) = 0.75; (60°+Dₘ)/2 = 48.59°; Dₘ = 2×48.59° – 60° = 37.2° ≈ 37°
> 4. θ_min = 1.22λ/D = 1.22×500×10⁻⁹/(10×10⁻²) = 6.1×10⁻⁶ rad
