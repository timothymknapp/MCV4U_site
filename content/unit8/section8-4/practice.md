+++
title = '8.4 Practice'
weight = 2
+++

Solve the following problems to reinforce your understanding of creating equations of lines and planes in 3D. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Ex1
Find the vector and parametric equations of the line passing through the points $P(3, -1, 2)$ and $Q(5, 2, -4)$.

<details>
<summary><strong>Solution</strong></summary>

- Find the direction vector $\vec{m}$:

  $$
  \vec{m} = \langle 5 - 3, 2 - (-1), -4 - 2 \rangle = \langle 2, 3, -6 \rangle.
  $$

- Use point $P(3, -1, 2)$ and $\vec{m} = \langle 2, 3, -6 \rangle$ to write the vector equation:

  $$
  \vec{r}(t) = \langle 3, -1, 2 \rangle + t\langle 2, 3, -6 \rangle.
  $$

- Convert to parametric form:

  $$
  x = 3 + 2t, \quad y = -1 + 3t, \quad z = 2 - 6t.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle 3, -1, 2 \rangle + t\langle 2, 3, -6 \rangle}
$$

$$
\boxed{\text{Parametric equations: } x = 3 + 2t, \, y = -1 + 3t, \, z = 2 - 6t.}
$$

</details>

---

## Ex2
Find the scalar and vector equations of the plane containing the points $A(0, 1, 2)$, $B(2, 3, 4)$, and $C(-1, -2, 0)$.

<details>
<summary><strong>Solution</strong></summary>

- Find two direction vectors on the plane:

  $$
  \vec{AB} = \langle 2 - 0, 3 - 1, 4 - 2 \rangle = \langle 2, 2, 2 \rangle,
  $$

  $$
  \vec{AC} = \langle -1 - 0, -2 - 1, 0 - 2 \rangle = \langle -1, -3, -2 \rangle.
  $$

- Compute the normal vector $\vec{n}$ as the cross product of $\vec{AB}$ and $\vec{AC}$:

  $$
  \vec{n} = \vec{AB} \times \vec{AC} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  2 & 2 & 2 \\
  -1 & -3 & -2
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{n} = \mathbf{i}((2)(-2) - (2)(-3)) - \mathbf{j}((2)(-2) - (2)(-1)) + \mathbf{k}((2)(-3) - (2)(-1)).
  $$

  Simplify:

  $$
  \vec{n} = \langle 2, -2, -4 \rangle.
  $$

- Use $\vec{n} = \langle 2, -2, -4 \rangle$ and point $A(0, 1, 2)$ to write the scalar equation:

  $$
  2(x - 0) - 2(y - 1) - 4(z - 2) = 0.
  $$

  Simplify:

  $$
  2x - 2y - 4z + 10 = 0.
  $$

- Write the vector equation:

  $$
  \vec{r}(s, t) = \langle 0, 1, 2 \rangle + s\langle 2, 2, 2 \rangle + t\langle -1, -3, -2 \rangle.
  $$

Final answer:

$$
\boxed{\text{Scalar equation: } 2x - 2y - 4z + 10 = 0}
$$

$$
\boxed{\text{Vector equation: } \vec{r}(s, t) = \langle 0, 1, 2 \rangle + s\langle 2, 2, 2 \rangle + t\langle -1, -3, -2 \rangle.}
$$

</details>

---

## Ex3
Find the equation of a line that passes through the point $R(1, 0, -1)$ and is parallel to the plane $x + 2y - 3z + 5 = 0$.

<details>
<summary><strong>Solution</strong></summary>

- The normal vector of the plane is $\vec{n} = \langle 1, 2, -3 \rangle$.
- A line parallel to the plane must have a direction vector $\vec{m}$ that is perpendicular to $\vec{n}$. Choose $\vec{m} = \langle 2, -1, 0 \rangle$ (any vector satisfying $\vec{m} \cdot \vec{n} = 0$).

- Use point $R(1, 0, -1)$ and $\vec{m} = \langle 2, -1, 0 \rangle$ to write the vector equation:

  $$
  \vec{r}(t) = \langle 1, 0, -1 \rangle + t\langle 2, -1, 0 \rangle.
  $$

- Convert to parametric form:

  $$
  x = 1 + 2t, \quad y = -t, \quad z = -1.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle 1, 0, -1 \rangle + t\langle 2, -1, 0 \rangle}
$$

$$
\boxed{\text{Parametric equations: } x = 1 + 2t, \, y = -t, \, z = -1.}
$$

</details>

---

## Ex4
Find the equation of a plane that contains the point $S(3, -2, 1)$ and is perpendicular to the line $\vec{r}(t) = \langle 0, 1, 2 \rangle + t\langle 1, -1, 2 \rangle$.

<details>
<summary><strong>Solution</strong></summary>

- The direction vector of the line is $\vec{m} = \langle 1, -1, 2 \rangle$, which serves as the normal vector $\vec{n}$ of the plane.
- Use $\vec{n} = \langle 1, -1, 2 \rangle$ and point $S(3, -2, 1)$ to write the scalar equation:

  $$
  1(x - 3) - 1(y + 2) + 2(z - 1) = 0.
  $$

  Simplify:

  $$
  x - y + 2z - 7 = 0.
  $$

Final answer:

$$
\boxed{\text{Scalar equation: } x - y + 2z - 7 = 0.}
$$

</details>

---

## Ex5
Find the intercepts of the plane $4x - y + 2z - 8 = 0$ with the $x$-, $y$-, and $z$-axes.

<details>
<summary><strong>Solution</strong></summary>

- To find the $x$-intercept, set $y = 0$ and $z = 0$:

  $$
  4x - 8 = 0 \implies x = 2.
  $$

- To find the $y$-intercept, set $x = 0$ and $z = 0$:

  $$
  -y - 8 = 0 \implies y = -8.
  $$

- To find the $z$-intercept, set $x = 0$ and $y = 0$:

  $$
  2z - 8 = 0 \implies z = 4.
  $$

Final answer:

$$
\boxed{\text{x-intercept: } 2, \, \text{y-intercept: } -8, \, \text{z-intercept: } 4.}
$$

</details>



<iframe src="https://script.google.com/macros/s/AKfycby3OaMvvRmS2db_FZsl7a1xS-YpYwJWL1G-TVLo16OOz-le12DtM7T0MCfyBIFw337FVg/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

