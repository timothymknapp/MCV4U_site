+++
title = '8.6 Practice'
weight = 2
+++


Solve the following problems to reinforce your understanding of intersections of two planes in 3D space. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Ex1
Find the line of intersection between the planes:

$$
x + y + z = 6 \quad \text{and} \quad 2x - y + z = 4.
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- The direction vector of the line of intersection is given by the cross product of the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 2, -1, 1 \rangle.
  $$

  Compute $\vec{d} = \vec{n}_1 \times \vec{n}_2$:

  $$
  \vec{d} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & 1 & 1 \\
  2 & -1 & 1
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{d} = \mathbf{i}((1)(1) - (1)(-1)) - \mathbf{j}((1)(1) - (1)(2)) + \mathbf{k}((1)(-1) - (1)(2)).
  $$

  Simplify:

  $$
  \vec{d} = \langle 2, 1, -3 \rangle.
  $$

- Find a specific point on the line by solving the system of equations formed by the two planes. Let $z = 0$ (arbitrary choice):

  $$
  x + y = 6, \quad 2x - y = 4.
  $$

  Solve the system:

  $$
  x + y = 6 \implies y = 6 - x.
  $$

  Substitute $y = 6 - x$ into $2x - y = 4$:

  $$
  2x - (6 - x) = 4 \implies 2x - 6 + x = 4 \implies 3x = 10 \implies x = \frac{10}{3}.
  $$

  Substitute $x = \frac{10}{3}$ into $y = 6 - x$:

  $$
  y = 6 - \frac{10}{3} = \frac{18}{3} - \frac{10}{3} = \frac{8}{3}.
  $$

  So, a point on the line is $\left(\frac{10}{3}, \frac{8}{3}, 0\right)$.

- Write the vector equation of the line:

  $$
  \vec{r}(t) = \left\langle \frac{10}{3}, \frac{8}{3}, 0 \right\rangle + t\langle 2, 1, -3 \rangle.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \left\langle \frac{10}{3}, \frac{8}{3}, 0 \right\rangle + t\langle 2, 1, -3 \rangle.}
$$
</details>

---

## Ex2
Determine whether the planes:

$$
2x - 3y + z - 6 = 0 \quad \text{and} \quad 4x - 6y + 2z - 12 = 0
$$

intersect. If not, explain why.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 2, -3, 1 \rangle, \quad \vec{n}_2 = \langle 4, -6, 2 \rangle.
  $$

  Check if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$:

  $$
  \vec{n}_2 = 2\vec{n}_1.
  $$

  Since $\vec{n}_2$ is parallel to $\vec{n}_1$, the planes are either parallel or coincident.

- Check if the planes coincide by substituting a point from one plane into the other. Use $(3, 0, 0)$ from the first plane:

  $$
  4(3) - 6(0) + 2(0) - 12 = 0.
  $$

  The point satisfies the second plane, so the planes coincide.

Final answer:

$$
\boxed{\text{The planes coincide (infinite solutions).}}
$$
</details>

---

## EX3
Determine whether the planes:

$$
x + 2y - z - 5 = 0 \quad \text{and} \quad 2x + 4y - 2z - 10 = 0
$$

intersect. If not, explain why.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 2, -1 \rangle, \quad \vec{n}_2 = \langle 2, 4, -2 \rangle.
  $$

  Check if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$:

  $$
  \vec{n}_2 = 2\vec{n}_1.
  $$

  Since $\vec{n}_2$ is parallel to $\vec{n}_1$, the planes are either parallel or coincident.

- Check if the planes coincide by substituting a point from one plane into the other. Use $(5, 0, 0)$ from the first plane:

  $$
  2(5) + 4(0) - 2(0) - 10 = 0.
  $$

  The point satisfies the second plane, so the planes coincide.

Final answer:

$$
\boxed{\text{The planes coincide (infinite solutions).}}
$$

</details>

---

## Ex4
Two walls in a room are described by the planes:

$$
x - y + z - 2 = 0 \quad \text{and} \quad 2x + y - z - 3 = 0.
$$

Find the line where the two walls meet.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- The direction vector of the line of intersection is given by the cross product of the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, -1, 1 \rangle, \quad \vec{n}_2 = \langle 2, 1, -1 \rangle.
  $$

  Compute $\vec{d} = \vec{n}_1 \times \vec{n}_2$:

  $$
  \vec{d} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & -1 & 1 \\
  2 & 1 & -1
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{d} = \mathbf{i}((-1)(-1) - (1)(1)) - \mathbf{j}((1)(-1) - (1)(2)) + \mathbf{k}((1)(1) - (-1)(2)).
  $$

  Simplify:

  $$
  \vec{d} = \langle 0, 3, 3 \rangle.
  $$

- Find a specific point on the line by solving the system of equations formed by the two planes. Let $z = 0$ (arbitrary choice):

  $$
  x - y = 2, \quad 2x + y = 3.
  $$

  Solve the system:

  $$
  x - y = 2 \implies y = x - 2.
  $$

  Substitute $y = x - 2$ into $2x + y = 3$:

  $$
  2x + (x - 2) = 3 \implies 3x - 2 = 3 \implies 3x = 5 \implies x = \frac{5}{3}.
  $$

  Substitute $x = \frac{5}{3}$ into $y = x - 2$:

  $$
  y = \frac{5}{3} - 2 = \frac{5}{3} - \frac{6}{3} = -\frac{1}{3}.
  $$

  So, a point on the line is $\left(\frac{5}{3}, -\frac{1}{3}, 0\right)$.

- Write the vector equation of the line:

  $$
  \vec{r}(t) = \left\langle \frac{5}{3}, -\frac{1}{3}, 0 \right\rangle + t\langle 0, 3, 3 \rangle.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \left\langle \frac{5}{3}, -\frac{1}{3}, 0 \right\rangle + t\langle 0, 3, 3 \rangle.}
$$

</details>

---

## Ex5
Determine whether the planes:

$$
x + y + z - 6 = 0 \quad \text{and} \quad x + y + z - 9 = 0
$$

intersect. If not, find the shortest distance between them.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Compare the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 1, 1, 1 \rangle.
  $$

  Since $\vec{n}_2 = \vec{n}_1$, the planes are parallel.

- Check if the planes coincide by substituting a point from one plane into the other. Use $(6, 0, 0)$ from the first plane:

  $$
  6 + 0 + 0 - 9 \neq 0.
  $$

  The point does not satisfy the second plane, so the planes are parallel but distinct.

- Find the shortest distance between the planes using the formula:

  $$
  d = \frac{|c_2 - c_1|}{\|\vec{n}\|},
  $$

  where $c_1 = 6$, $c_2 = 9$, and $\vec{n} = \langle 1, 1, 1 \rangle$.

- Compute the magnitude of $\vec{n}$:

  $$
  \|\vec{n}\| = \sqrt{1^2 + 1^2 + 1^2} = \sqrt{3}.
  $$

- Compute the distance:

  $$
  d = \frac{|9 - 6|}{\sqrt{3}} = \frac{3}{\sqrt{3}} = \sqrt{3}.
  $$

Final answer:

$$
\boxed{\text{Shortest distance: } \sqrt{3}.}
$$
</details>



<iframe src="https://script.google.com/macros/s/AKfycbwVjMPvw9jAGnUMLse04rcaWkXdzNY92u1qmqUfgQZhvdl8RU7yTAuEUixId5ICl7aEPQ/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

