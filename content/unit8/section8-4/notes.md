+++
title = '8.4 Examples'
weight = 1
+++ 

This page provides detailed worked-out examples to help you understand how to create equations of lines and planes in 3D.

---

## Example 1: Creating a Line Equation
Find the vector and parametric equations of the line passing through the points $A(2, -3, 1)$ and $B(-1, 0, 4)$.

### Solution:
- Find the direction vector $\vec{m}$:

  $$
  \vec{m} = \langle -1 - 2, 0 - (-3), 4 - 1 \rangle = \langle -3, 3, 3 \rangle.
  $$

- Use point $A(2, -3, 1)$ and $\vec{m} = \langle -3, 3, 3 \rangle$ to write the vector equation:

  $$
  \vec{r}(t) = \langle 2, -3, 1 \rangle + t\langle -3, 3, 3 \rangle.
  $$

- Convert to parametric form:

  $$
  x = 2 - 3t, \quad y = -3 + 3t, \quad z = 1 + 3t.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle 2, -3, 1 \rangle + t\langle -3, 3, 3 \rangle}
$$

$$
\boxed{\text{Parametric equations: } x = 2 - 3t, \, y = -3 + 3t, \, z = 1 + 3t.}
$$

---

## Example 2: Creating a Plane Equation
Find the scalar and vector equations of the plane containing the points $A(1, 0, -2)$, $B(3, 2, 1)$, and $C(-1, 1, 0)$.

### Solution:
- Find two direction vectors on the plane:

  $$
  \vec{AB} = \langle 3 - 1, 2 - 0, 1 - (-2) \rangle = \langle 2, 2, 3 \rangle,
  $$

  $$
  \vec{AC} = \langle -1 - 1, 1 - 0, 0 - (-2) \rangle = \langle -2, 1, 2 \rangle.
  $$

- Compute the normal vector $\vec{n}$ as the cross product of $\vec{AB}$ and $\vec{AC}$:

  $$
  \vec{n} = \vec{AB} \times \vec{AC} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  2 & 2 & 3 \\
  -2 & 1 & 2
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{n} = \mathbf{i}((2)(2) - (3)(1)) - \mathbf{j}((2)(2) - (3)(-2)) + \mathbf{k}((2)(1) - (2)(-2)).
  $$

  Simplify:

  $$
  \vec{n} = \langle 1, -10, 6 \rangle.
  $$

- Use $\vec{n} = \langle 1, -10, 6 \rangle$ and point $A(1, 0, -2)$ to write the scalar equation:

  $$
  1(x - 1) - 10(y - 0) + 6(z + 2) = 0.
  $$

  Simplify:

  $$
  x - 10y + 6z + 11 = 0.
  $$

- Write the vector equation:

  $$
  \vec{r}(s, t) = \langle 1, 0, -2 \rangle + s\langle 2, 2, 3 \rangle + t\langle -2, 1, 2 \rangle.
  $$

Final answer:

$$
\boxed{\text{Scalar equation: } x - 10y + 6z + 11 = 0}
$$

$$
\boxed{\text{Vector equation: } \vec{r}(s, t) = \langle 1, 0, -2 \rangle + s\langle 2, 2, 3 \rangle + t\langle -2, 1, 2 \rangle.}
$$

---

## Example 3: Parallel Line to a Plane
Find the equation of a line that passes through the point $P(2, -1, 3)$ and is parallel to the plane $x - 2y + 3z - 6 = 0$.

### Solution:
- The normal vector of the plane is $\vec{n} = \langle 1, -2, 3 \rangle$.
- A line parallel to the plane must have a direction vector $\vec{m}$ that is perpendicular to $\vec{n}$. Choose $\vec{m} = \langle 2, 1, 0 \rangle$ (any vector satisfying $\vec{m} \cdot \vec{n} = 0$).

- Use point $P(2, -1, 3)$ and $\vec{m} = \langle 2, 1, 0 \rangle$ to write the vector equation:

  $$
  \vec{r}(t) = \langle 2, -1, 3 \rangle + t\langle 2, 1, 0 \rangle.
  $$

- Convert to parametric form:

  $$
  x = 2 + 2t, \quad y = -1 + t, \quad z = 3.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle 2, -1, 3 \rangle + t\langle 2, 1, 0 \rangle}
$$

$$
\boxed{\text{Parametric equations: } x = 2 + 2t, \, y = -1 + t, \, z = 3.}
$$

---

## Example 4: Perpendicular Plane to a Line
Find the equation of a plane that contains the point $Q(1, 2, -1)$ and is perpendicular to the line $\vec{r}(t) = \langle 0, 1, 2 \rangle + t\langle 3, -1, 2 \rangle$.

### Solution:
- The direction vector of the line is $\vec{m} = \langle 3, -1, 2 \rangle$, which serves as the normal vector $\vec{n}$ of the plane.
- Use $\vec{n} = \langle 3, -1, 2 \rangle$ and point $Q(1, 2, -1)$ to write the scalar equation:

  $$
  3(x - 1) - 1(y - 2) + 2(z + 1) = 0.
  $$

  Simplify:

  $$
  3x - y + 2z + 1 = 0.
  $$

Final answer:

$$
\boxed{\text{Scalar equation: } 3x - y + 2z + 1 = 0.}
$$

---

## Example 5: Intercepts of a Plane
Find the intercepts of the plane $2x - 3y + 4z - 12 = 0$ with the $x$-, $y$-, and $z$-axes.

### Solution:
- To find the $x$-intercept, set $y = 0$ and $z = 0$:

  $$
  2x - 12 = 0 \implies x = 6.
  $$

- To find the $y$-intercept, set $x = 0$ and $z = 0$:

  $$
  -3y - 12 = 0 \implies y = -4.
  $$

- To find the $z$-intercept, set $x = 0$ and $y = 0$:

  $$
  4z - 12 = 0 \implies z = 3.
  $$

Final answer:

$$
\boxed{\text{x-intercept: } 6, \, \text{y-intercept: } -4, \, \text{z-intercept: } 3.}
$$

