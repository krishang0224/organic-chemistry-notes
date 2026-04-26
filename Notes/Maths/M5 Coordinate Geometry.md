# M5 Coordinate Geometry

> [!tip] One Line
> Straight lines: y=mx+c. Circles: (x–h)²+(y–k)²=r². Conics: parabola (y²=4ax), ellipse (x²/a²+y²/b²=1), hyperbola (x²/a²–y²/b²=1).

---

## Straight Lines

### Distance & Section Formulae
```
Distance PQ = √((x₂–x₁)² + (y₂–y₁)²)
Midpoint = ((x₁+x₂)/2, (y₁+y₂)/2)
Section (m:n internally) = ((mx₂+nx₁)/(m+n), (my₂+ny₁)/(m+n))
```

### Slope
```
m = tan θ = (y₂–y₁)/(x₂–x₁)
Parallel lines: m₁ = m₂
Perpendicular lines: m₁ × m₂ = –1
```

### Equations of Line
```
Slope-intercept: y = mx + c
Point-slope: y – y₁ = m(x – x₁)
Two-point: (y–y₁)/(y₂–y₁) = (x–x₁)/(x₂–x₁)
Intercept form: x/a + y/b = 1
Normal form: x cosα + y sinα = p
General: ax + by + c = 0
```

### Distance of Point from Line
```
d = |ax₁ + by₁ + c| / √(a²+b²)
```

### Angle Between Two Lines
```
tan θ = |(m₁–m₂)/(1+m₁m₂)|
```

---

## Circle

### Standard Forms
```
Center (h,k), radius r: (x–h)² + (y–k)² = r²
Center (0,0): x² + y² = r²
General: x² + y² + 2gx + 2fy + c = 0
Center = (–g, –f), radius = √(g²+f²–c)
```

### Tangent to Circle
At point (x₁,y₁) on x² + y² = r²:
```
xx₁ + yy₁ = r²
```
At point (x₁,y₁) on x²+y²+2gx+2fy+c = 0:
```
xx₁ + yy₁ + g(x+x₁) + f(y+y₁) + c = 0
```

Length of tangent from external point (x₁,y₁):
```
L = √(x₁²+y₁²+2gx₁+2fy₁+c)
```

---

## Conic Sections

### Parabola
```
y² = 4ax:  Focus (a,0), Directrix x = –a, Vertex (0,0), Axis: x-axis
x² = 4ay:  Focus (0,a), Directrix y = –a, Axis: y-axis
```
Eccentricity e = 1.

### Ellipse
```
x²/a² + y²/b² = 1    (a > b > 0)
Foci: (±ae, 0), e = √(1–b²/a²) < 1
Directrices: x = ±a/e
Latus rectum length = 2b²/a
```

### Hyperbola
```
x²/a² – y²/b² = 1
Foci: (±ae, 0), e = √(1+b²/a²) > 1
Asymptotes: y = ±(b/a)x
Conjugate hyperbola: y²/b² – x²/a² = 1
Rectangular hyperbola: xy = c² (asymptotes are coordinate axes)
```

### Summary Table
| Conic | Equation | e | Focus |
|-------|---------|---|-------|
| Circle | x²+y²=r² | 0 | Center |
| Parabola | y²=4ax | 1 | (a,0) |
| Ellipse | x²/a²+y²/b²=1 | 0<e<1 | (±ae,0) |
| Hyperbola | x²/a²–y²/b²=1 | e>1 | (±ae,0) |

---

## 3D Geometry (basics)

### Distance & Direction Cosines
```
d = √((x₂–x₁)²+(y₂–y₁)²+(z₂–z₁)²)
l² + m² + n² = 1    (direction cosines l,m,n)
Direction ratios a,b,c: l=a/√(a²+b²+c²) etc.
```

### Line in 3D
```
Symmetric form: (x–x₁)/a = (y–y₁)/b = (z–z₁)/c
Vector form: r = a + λb
```

### Plane
```
General: ax + by + cz = d    (normal vector = (a,b,c))
Distance from origin: d/√(a²+b²+c²)
Distance from point (x₁,y₁,z₁): |ax₁+by₁+cz₁–d|/√(a²+b²+c²)
```

---

## Practice Questions
1. Find equation of line through (2,3) with slope 4.
2. Circle: x²+y²–4x–6y+4 = 0. Find center and radius.
3. For parabola y²=12x, find focus and directrix.
4. Ellipse x²/25 + y²/9 = 1. Find eccentricity and foci.

> [!question]- Answers
> 1. y – 3 = 4(x – 2) → y = 4x – 5
> 2. g=–2, f=–3, c=4; Center=(2,3), r=√(4+9–4)=3
> 3. y²=4ax → 4a=12 → a=3; Focus=(3,0), Directrix: x=–3
> 4. a²=25, b²=9; e=√(1–9/25)=√(16/25)=4/5; Foci=(±ae,0)=(±4,0)

---
**Previous: [[M4 Probability & Statistics]]**
**Next: [[M6 Vectors & 3D]]**
