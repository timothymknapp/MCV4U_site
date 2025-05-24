+++
title = '8.6 Examples'
weight = 1
+++


This page provides detailed worked-out examples to help you understand how to determine the intersection of two planes in 3D space.

---

## Example 1: Intersection of Two Planes (Line of Intersection)
Find the line of intersection between the planes:

$$
2x - y + z - 4 = 0 \quad \text{and} \quad x + y - z - 2 = 0.
$$

### Solution:
- The direction vector of the line of intersection is given by the cross product of the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 2, -1, 1 \rangle, \quad \vec{n}_2 = \langle 1, 1, -1 \rangle.
  $$

  Compute $\vec{d} = \vec{n}_1 \times \vec{n}_2$:

  $$
  \vec{d} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  2 & -1 & 1 \\
  1 & 1 & -1
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{d} = \mathbf{i}((-1)(-1) - (1)(1)) - \mathbf{j}((2)(-1) - (1)(1)) + \mathbf{k}((2)(1) - (-1)(1)).
  $$

  Simplify:

  $$
  \vec{d} = \langle 0, 3, 3 \rangle.
  $$

- Find a specific point on the line by solving the system of equations formed by the two planes. Let $z = 0$ (arbitrary choice):

  $$
  2x - y = 4, \quad x + y = 2.
  $$

  Solve the system:

  $$
  x + y = 2 \implies y = 2 - x.
  $$

  Substitute $y = 2 - x$ into $2x - y = 4$:

  $$
  2x - (2 - x) = 4 \implies 2x - 2 + x = 4 \implies 3x = 6 \implies x = 2.
  $$

  Substitute $x = 2$ into $y = 2 - x$:

  $$
  y = 2 - 2 = 0.
  $$

  So, a point on the line is $(2, 0, 0)$.

- Write the vector equation of the line:

  $$
  \vec{r}(t) = \langle 2, 0, 0 \rangle + t\langle 0, 3, 3 \rangle.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle 2, 0, 0 \rangle + t\langle 0, 3, 3 \rangle.}
$$

---

## Example 2: Parallel Planes (No Intersection)
Determine whether the planes:

$$
x - 2y + 3z - 6 = 0 \quad \text{and} \quad 2x - 4y + 6z - 12 = 0
$$

intersect. If not, explain why.

### Solution:
- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, -2, 3 \rangle, \quad \vec{n}_2 = \langle 2, -4, 6 \rangle.
  $$

  Check if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$:

  $$
  \vec{n}_2 = 2\vec{n}_1.
  $$

  Since $\vec{n}_2$ is parallel to $\vec{n}_1$, the planes are either parallel or coincident.

- Check if the planes coincide by substituting a point from one plane into the other. Use $(6, 0, 0)$ from the first plane:

  $$
  2(6) - 4(0) + 6(0) - 12 = 0.
  $$

  The point satisfies the second plane, so the planes coincide.

Final answer:

$$
\boxed{\text{The planes coincide (infinite solutions).}}
$$

---

## Example 3: Coincident Planes (Infinite Solutions)
Determine whether the planes:

$$
x + y + z - 3 = 0 \quad \text{and} \quad 2x + 2y + 2z - 6 = 0
$$

intersect. If not, explain why.

### Solution:
- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 2, 2, 2 \rangle.
  $$

  Check if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$:

  $$
  \vec{n}_2 = 2\vec{n}_1.
  $$

  Since $\vec{n}_2$ is parallel to $\vec{n}_1$, the planes are either parallel or coincident.

- Check if the planes coincide by substituting a point from one plane into the other. Use $(1, 1, 1)$ from the first plane:

  $$
  2(1) + 2(1) + 2(1) - 6 = 0.
  $$

  The point satisfies the second plane, so the planes coincide.

Final answer:

$$
\boxed{\text{The planes coincide (infinite solutions).}}
$$

---

## Example 4: Application Problem
Two walls in a room are described by the planes:

$$
x + 2y - z - 4 = 0 \quad \text{and} \quad 2x - y + z - 5 = 0.
$$

Find the line where the two walls meet.

### Solution:
- The direction vector of the line of intersection is given by the cross product of the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 2, -1 \rangle, \quad \vec{n}_2 = \langle 2, -1, 1 \rangle.
  $$

  Compute $\vec{d} = \vec{n}_1 \times \vec{n}_2$:

  $$
  \vec{d} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & 2 & -1 \\
  2 & -1 & 1
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{d} = \mathbf{i}((2)(1) - (-1)(-1)) - \mathbf{j}((1)(1) - (-1)(2)) + \mathbf{k}((1)(-1) - (2)(2)).
  $$

  Simplify:

  $$
  \vec{d} = \langle 1, -3, -5 \rangle.
  $$

- Find a specific point on the line by solving the system of equations formed by the two planes. Let $z = 0$ (arbitrary choice):

  $$
  x + 2y = 4, \quad 2x - y = 5.
  $$

  Solve the system:

  $$
  2x - y = 5 \implies y = 2x - 5.
  $$

  Substitute $y = 2x - 5$ into $x + 2y = 4$:

  $$
  x + 2(2x - 5) = 4 \implies x + 4x - 10 = 4 \implies 5x = 14 \implies x = \frac{14}{5}.
  $$

  Substitute $x = \frac{14}{5}$ into $y = 2x - 5$:

  $$
  y = 2\left(\frac{14}{5}\right) - 5 = \frac{28}{5} - \frac{25}{5} = \frac{3}{5}.
  $$

  So, a point on the line is $\left(\frac{14}{5}, \frac{3}{5}, 0\right)$.

- Write the vector equation of the line:

  $$
  \vec{r}(t) = \left\langle \frac{14}{5}, \frac{3}{5}, 0 \right\rangle + t\langle 1, -3, -5 \rangle.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \left\langle \frac{14}{5}, \frac{3}{5}, 0 \right\rangle + t\langle 1, -3, -5 \rangle.}
$$