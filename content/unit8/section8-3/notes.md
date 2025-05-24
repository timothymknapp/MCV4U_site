+++
title = '8.3 Examples'
weight = 1
+++

This page provides detailed worked-out examples to help you understand how to represent planes in 3D using scalar, vector, and parametric equations.

---

## Example 1: Scalar Equation of a Plane
Find the scalar equation of the plane that passes through the point $(3, -2, 1)$ and has a normal vector $\vec{n} = \langle 1, -2, 3 \rangle$.

### Solution:
The scalar equation of a plane is:

$$
a(x - x_0) + b(y - y_0) + c(z - z_0) = 0,
$$

where $\vec{n} = \langle a, b, c \rangle$ and $(x_0, y_0, z_0)$ is a point on the plane.

Substitute $\vec{n} = \langle 1, -2, 3 \rangle$ and $(x_0, y_0, z_0) = (3, -2, 1)$:

$$
1(x - 3) - 2(y + 2) + 3(z - 1) = 0.
$$

Simplify:

$$
x - 3 - 2y - 4 + 3z - 3 = 0,
$$

$$
x - 2y + 3z - 10 = 0.
$$

Final answer:

$$
\boxed{x - 2y + 3z - 10 = 0}
$$

---

## Example 2: Vector Equation of a Plane
Find the vector equation of the plane that passes through the point $(1, 2, -1)$ and has direction vectors $\vec{u} = \langle 2, 1, 0 \rangle$ and $\vec{v} = \langle 0, -1, 3 \rangle$.

### Solution:
The vector equation of a plane is:

$$
\vec{r}(s, t) = \vec{r}_0 + s\vec{u} + t\vec{v}.
$$

Substitute $\vec{r}_0 = \langle 1, 2, -1 \rangle$, $\vec{u} = \langle 2, 1, 0 \rangle$, and $\vec{v} = \langle 0, -1, 3 \rangle$:

$$
\vec{r}(s, t) = \langle 1, 2, -1 \rangle + s\langle 2, 1, 0 \rangle + t\langle 0, -1, 3 \rangle.
$$

Final answer:

$$
\boxed{\vec{r}(s, t) = \langle 1, 2, -1 \rangle + s\langle 2, 1, 0 \rangle + t\langle 0, -1, 3 \rangle}
$$

---

## Example 3: Parametric Equations of a Plane
Convert the vector equation from Example 2 into parametric form.

### Solution:
From the vector equation:

$$
\vec{r}(s, t) = \langle 1, 2, -1 \rangle + s\langle 2, 1, 0 \rangle + t\langle 0, -1, 3 \rangle,
$$

expand into parametric equations:

$$
x = 1 + 2s + 0t = 1 + 2s,
$$

$$
y = 2 + s - t,
$$

$$
z = -1 + 0s + 3t = -1 + 3t.
$$

Final answer:

$$
\boxed{x = 1 + 2s, \, y = 2 + s - t, \, z = -1 + 3t}
$$

---

## Example 4: Intercepts of a Plane
Find the intercepts of the plane $3x - 2y + 6z - 12 = 0$ with the $x$-, $y$-, and $z$-axes.

### Solution:
To find the $x$-intercept, set $y = 0$ and $z = 0$:

$$
3x - 12 = 0 \implies x = 4.
$$

To find the $y$-intercept, set $x = 0$ and $z = 0$:

$$
-2y - 12 = 0 \implies y = -6.
$$

To find the $z$-intercept, set $x = 0$ and $y = 0$:

$$
6z - 12 = 0 \implies z = 2.
$$

Final answer:

$$
\boxed{x\text{-intercept: } 4, \, y\text{-intercept: } -6, \, z\text{-intercept: } 2}
$$

---

## Example 5: Determining if a Point Lies on a Plane
Determine whether the point $(2, -1, 3)$ lies on the plane $3x - 2y + 6z - 12 = 0$.

### Solution:
Substitute $(x, y, z) = (2, -1, 3)$ into the plane equation:

$$
3(2) - 2(-1) + 6(3) - 12 = 0.
$$

Simplify:

$$
6 + 2 + 18 - 12 = 14 \neq 0.
$$

Final answer:

$$
\boxed{\text{The point does not lie on the plane.}}
$$