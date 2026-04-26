# P8 Optics

> [!tip] One Line
> Mirrors: use sign convention. Lenses: 1/v – 1/u = 1/f. Wave optics: path difference λ for bright, λ/2 for dark.

---

## Reflection (Mirrors)

### Sign Convention (Cartesian)
- All distances measured from pole (P) of mirror
- Distances in direction of incident light: positive
- Distances opposite to incident light: negative
- Heights above axis: positive; below: negative

### Mirror Formula
```
1/v + 1/u = 1/f    (f = R/2, R = radius of curvature)
```
Magnification: m = –v/u = h_i/h_o

**Concave mirror (f < 0):** can form real/inverted or virtual/erect images
**Convex mirror (f > 0):** always virtual, erect, diminished; used as rear-view mirror

---

## Refraction

### Snell's Law
```
n₁ sinθ₁ = n₂ sinθ₂
n = c/v = speed of light in vacuum / speed in medium
```

**Total Internal Reflection (TIR):**
Occurs when light goes from denser → rarer medium and θ > critical angle θ_c
```
sin θ_c = n₂/n₁ = 1/n    (if n₂ = 1, air)
```
Applications: optical fibers, diamonds, mirage

### Refraction at Spherical Surface
```
n₂/v – n₁/u = (n₂–n₁)/R
```

---

## Lenses

### Lens Maker's Formula
```
1/f = (n–1)(1/R₁ – 1/R₂)
```

### Thin Lens Formula
```
1/v – 1/u = 1/f    (same sign convention as mirrors)
m = v/u = h_i/h_o
```

**Power of lens:**
```
P = 1/f    (Dioptre, f in metres)
```
Combination: P = P₁ + P₂ + ... (lenses in contact)

**Convex lens (converging):** f > 0; can form real or virtual images
**Concave lens (diverging):** f < 0; always virtual, erect, diminished

---

## Prism

```
n = sin((A+D_m)/2) / sin(A/2)
```
A = angle of prism, D_m = minimum deviation

**Dispersion:** different wavelengths refract differently (violet most, red least)
- Violet has smallest wavelength, highest frequency, largest n → bends most
- VIBGYOR: Violet bends most, Red bends least

---

## Wave Optics

### Young's Double Slit Experiment (YDSE)

```
Path difference = d sinθ ≈ yd/D    (for small θ, y = fringe position, D = screen distance, d = slit separation)
```

**Bright fringe (constructive):** Δ = nλ → y = nλD/d
**Dark fringe (destructive):** Δ = (2n–1)λ/2 → y = (2n–1)λD/2d

**Fringe width:** β = λD/d (width between adjacent bright or dark fringes)

If medium of refractive index n used: λ' = λ/n → fringes become narrower

### Intensity in YDSE
```
I = 4I₀ cos²(δ/2)    (δ = phase difference = 2π/λ × path difference)
```
Constructive: I_max = 4I₀; Destructive: I_min = 0 (equal intensities)

---

## Diffraction

Single slit: minima at **a sinθ = nλ** (n = ±1, ±2,...)
Central maximum: width = 2λD/a

Resolving power of telescope: minimum angle = 1.22λ/D
Resolving power of microscope: RP = 2μ sinθ / λ

---

## Polarisation

Transverse waves can be polarised; longitudinal cannot.
**Malus's Law:** I = I₀ cos²θ (intensity after polarizer at angle θ to initial polarization)

Brewster's angle: tanθ_B = n (reflected light fully polarized)

---

## Optical Instruments

**Microscope:**
```
Magnification = (L/f_o) × (D/f_e)
```
(L = tube length, f_o = objective focal length, f_e = eyepiece focal length, D = 25 cm least distance)

**Telescope:**
```
M = f_o/f_e    (angular magnification, image at infinity)
```

---

## Practice Questions
1. An object 30 cm from concave mirror (f = –10 cm). Find image position.
2. Critical angle of glass-air = 42°. Find refractive index of glass.
3. YDSE: λ = 600 nm, d = 0.3 mm, D = 1.5 m. Find fringe width.
4. Polarizer and analyzer at 60°. If I₀ = 40 W/m², find I.

> [!question]- Answers
> 1. u = –30, f = –10; 1/v = 1/f – 1/u = –1/10 + 1/30... wait, mirror formula 1/v + 1/u = 1/f → 1/v = 1/f – 1/u = 1/(–10) – 1/(–30) = –1/10 + 1/30 = (–3+1)/30 = –2/30; v = –15 cm (real, inverted, same side as object)
> 2. sin 42° = 1/n → n = 1/sin42° ≈ 1/0.669 ≈ 1.5
> 3. β = λD/d = (600×10⁻⁹ × 1.5)/(0.3×10⁻³) = 9×10⁻⁷/3×10⁻⁴ = 3×10⁻³ m = 3 mm
> 4. I = I₀ cos²θ = 40 × cos²60° = 40 × (0.5)² = 40 × 0.25 = 10 W/m²

---
**Previous: [[P7 Magnetism & EMI]]**
**Next: [[P9 Modern Physics & Semiconductors]]**
