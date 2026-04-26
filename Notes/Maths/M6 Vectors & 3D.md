# M6 Vectors & 3D Geometry

> [!tip] One Line
> Dot product = |a||b|cosθ (scalar). Cross product = |a||b|sinθ n̂ (vector). For 3D lines/planes — use direction vectors.

---

## Vectors — Basics

**Position vector:** OP = xi + yj + zk
**Magnitude:** |a| = √(x²+y²+z²)
**Unit vector:** â = a/|a|

### Types
- **Equal vectors:** same magnitude and direction
- **Collinear vectors:** parallel (same/opposite direction)
- **Coplanar vectors:** lie in same plane

### Addition & Subtraction
Triangle law, Parallelogram law (vector addition).

---

## Dot Product (Scalar Product)

```
a·b = |a||b|cosθ = a₁b₁ + a₂b₂ + a₃b₃
cosθ = a·b / (|a||b|)
```

**Properties:**
- a·a = |a|²
- a·b = b·a (commutative)
- a·b = 0 ↔ a ⊥ b (perpendicular, if non-zero vectors)
- i·i = j·j = k·k = 1; i·j = j·k = k·i = 0

**Projection of a on b:** a·b̂ = a·b/|b|

---

## Cross Product (Vector Product)

```
a × b = |a||b|sinθ n̂
|a × b| = area of parallelogram with sides a, b
```

**Component form:**
```
a × b = |i  j  k |
        |a₁ a₂ a₃|
        |b₁ b₂ b₃|
= i(a₂b₃–a₃b₂) – j(a₁b₃–a₃b₁) + k(a₁b₂–a₂b₁)
```

**Properties:**
- a × b = –b × a (anti-commutative)
- a × a = 0
- a × b = 0 ↔ a ∥ b (parallel/collinear)
- i×j = k, j×k = i, k×i = j (right-hand rule)

**Area of triangle:** ½|a × b|

---

## Scalar Triple Product (Box Product)

```
[a b c] = a·(b × c) = |a₁ a₂ a₃|
                       |b₁ b₂ b₃|
                       |c₁ c₂ c₃|
```

**Volume of parallelepiped** = |[a b c]|
**Coplanar vectors** if [a b c] = 0

---

## 3D Geometry

### Lines

**Vector form:** r = a + λb (a = point on line, b = direction vector)

**Cartesian (symmetric) form:**
```
(x–x₁)/l = (y–y₁)/m = (z–z₁)/n
```

**Angle between two lines:**
```
cosθ = |a₁a₂ + b₁b₂ + c₁c₂| / (√(a₁²+b₁²+c₁²) × √(a₂²+b₂²+c₂²))
```

**Distance between skew lines:**
```
d = |((a₂–a₁)·(b₁×b₂))| / |b₁×b₂|
```

### Planes

**Vector form:** r·n̂ = d (n = normal vector)

**Cartesian:** ax + by + cz = d

**Through three points:** use cross product of two direction vectors as normal.

**Angle between two planes:** angle between their normals.

**Angle between line and plane:**
```
sinθ = |b·n| / (|b||n|)
```

**Distance from point (x₁,y₁,z₁) to plane ax+by+cz+d=0:**
```
dist = |ax₁+by₁+cz₁+d| / √(a²+b²+c²)
```

---

## Practice Questions
1. a = 2i+3j–k, b = i–j+2k. Find a·b and a×b.
2. Find angle between vectors a = i+j and b = i–j.
3. Are vectors a=2i–j+3k, b=4i–2j+6k collinear?
4. Find distance from (1,2,3) to plane 2x–y+2z = 5.

> [!question]- Answers
> 1. a·b = 2(1)+3(–1)+(–1)(2) = 2–3–2 = –3; a×b = i(3×2–(–1)(–1)) – j(2×2–(–1)×1) + k(2×(–1)–3×1) = i(6–1)–j(4+1)+k(–2–3) = 5i–5j–5k
> 2. cosθ = (1×1+1×(–1))/(√2×√2) = 0/2 = 0 → θ = 90°
> 3. b = 2a (4=2×2, –2=2×(–1), 6=2×3) → collinear (yes)
> 4. d = |2(1)–1(2)+2(3)–5|/√(4+1+4) = |2–2+6–5|/3 = 1/3

---
**Previous: [[M5 Coordinate Geometry]]**
**Next: [[M7 Complex Numbers & Quadratic Equations]]**
