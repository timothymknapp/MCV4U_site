+++
title = '8.7 Examples'
weight = 1
+++


This page provides detailed worked-out examples to help you understand how to determine the intersection of three planes in 3D space.

---

## Example 1: Intersection at a Single Point
Find the point of intersection of the three planes:

$$
x + y + z = 6, \quad 2x - y + z = 4, \quad x + 3y - 2z = 2.
$$

### Solution:
- Write the system of equations:

  $$
  \begin{aligned}
  x + y + z &= 6, \\
  2x - y + z &= 4, \\
  x + 3y - 2z &= 2.
  \end{aligned}
  $$

- Solve using substitution or elimination:
  1. From the first equation, solve for $z$:

     $$
     z = 6 - x - y.
     $$

  2. Substitute $z = 6 - x - y$ into the second and third equations:

     $$
     2x - y + (6 - x - y) = 4 \implies x - 2y = -2,
     $$

     $$
     x + 3y - 2(6 - x - y) = 2 \implies x + 3y - 12 + 2x + 2y = 2 \implies 3x + 5y = 14.
     $$

  3. Solve the system of two equations:

     $$
     x - 2y = -2, \quad 3x + 5y = 14.
     $$

     Multiply the first equation by 3:

     $$
     3x - 6y = -6.
     $$

     Subtract from the second equation:

     $$
     (3x + 5y) - (3x - 6y) = 14 - (-6) \implies 11y = 20 \implies y = \frac{20}{11}.
     $$

  4. Substitute $y = \frac{20}{11}$ into $x - 2y = -2$:

     $$
     x - 2\left(\frac{20}{11}\right) = -2 \implies x - \frac{40}{11} = -2 \implies x = \frac{-22}{11} + \frac{40}{11} = \frac{18}{11}.
     $$

  5. Substitute $x = \frac{18}{11}$ and $y = \frac{20}{11}$ into $z = 6 - x - y$:

     $$
     z = 6 - \frac{18}{11} - \frac{20}{11} = \frac{66}{11} - \frac{38}{11} = \frac{28}{11}.
     $$

Final answer:

$$
\boxed{\text{Point of intersection: } \left(\frac{18}{11}, \frac{20}{11}, \frac{28}{11}\right).}
$$

---

## Example 2: Intersection Along a Line
Find the line of intersection of the three planes:

$$
x + y + z = 6, \quad 2x - y + z = 4, \quad 3x + 2y - z = 8.
$$

### Solution:
- Write the system of equations:

  $$
  \begin{aligned}
  x + y + z &= 6, \\
  2x - y + z &= 4, \\
  3x + 2y - z &= 8.
  \end{aligned}
  $$

- Eliminate $z$ by combining equations:
  1. Add the first and second equations:

     $$
     (x + y + z) + (2x - y + z) = 6 + 4 \implies 3x + 2z = 10.
     $$

  2. Add the first and third equations:

     $$
     (x + y + z) + (3x + 2y - z) = 6 + 8 \implies 4x + 3y = 14.
     $$

- Solve the reduced system:

  $$
  3x + 2z = 10, \quad 4x + 3y = 14.
  $$

  Let $x = t$ (parameter):

  $$
  3t + 2z = 10 \implies z = \frac{10 - 3t}{2},
  $$

  $$
  4t + 3y = 14 \implies y = \frac{14 - 4t}{3}.
  $$

- Write the parametric equations of the line:

  $$
  x = t, \quad y = \frac{14 - 4t}{3}, \quad z = \frac{10 - 3t}{2}.
  $$

Final answer:

$$
\boxed{\text{Line of intersection: } x = t, \, y = \frac{14 - 4t}{3}, \, z = \frac{10 - 3t}{2}.}
$$

---

## Example 3: No Intersection (Inconsistent System)
Determine whether the planes:

$$
x + y + z = 6, \quad 2x - y + z = 4, \quad 3x + 2y - z = 10,
$$

intersect. If not, explain why.

### Solution:
- Write the system of equations:

  $$
  \begin{aligned}
  x + y + z &= 6, \\
  2x - y + z &= 4, \\
  3x + 2y - z &= 10.
  \end{aligned}
  $$

- Eliminate $z$ by combining equations:
  1. Add the first and second equations:

     $$
     (x + y + z) + (2x - y + z) = 6 + 4 \implies 3x + 2z = 10.
     $$

  2. Add the first and third equations:

     $$
     (x + y + z) + (3x + 2y - z) = 6 + 10 \implies 4x + 3y = 16.
     $$

- Check for consistency:
  Substitute $z = \frac{10 - 3x}{2}$ into the third equation:

  $$
  3x + 2y - \frac{10 - 3x}{2} = 10.
  $$

  Simplify:

  $$
  3x + 2y - 5 + \frac{3x}{2} = 10 \implies \frac{9x}{2} + 2y = 15.
  $$

  This contradicts $4x + 3y = 16$, so the system is inconsistent.

Final answer:

$$
\boxed{\text{No intersection (inconsistent system).}}
$$

---

## Example 4: Infinite Solutions (Coincident Planes)
Determine whether the planes:

$$
x + y + z = 6, \quad 2x + 2y + 2z = 12, \quad 3x + 3y + 3z = 18,
$$

intersect. If not, explain why.

### Solution:
- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 2, 2, 2 \rangle, \quad \vec{n}_3 = \langle 3, 3, 3 \rangle.
  $$

  Each normal vector is a scalar multiple of $\vec{n}_1$, so the planes are parallel or coincident.

- Check if the planes coincide by substituting a point from one plane into the others. Use $(6, 0, 0)$ from the first plane:

  $$
  2(6) + 2(0) + 2(0) = 12, \quad 3(6) + 3(0) + 3(0) = 18.
  $$

  The point satisfies all three planes, so the planes coincide.

Final answer:

$$
\boxed{\text{The planes coincide (infinite solutions).}}
$$