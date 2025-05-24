+++
title = '8.3 Practice'
weight = 2
+++


Solve the following problems to reinforce your understanding of planes in 3D. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Ex1
Find the scalar equation of the plane that passes through the point $(2, -1, 4)$ and has a normal vector $\vec{n} = \langle 3, -2, 1 \rangle$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

The scalar equation of a plane is:

$$
a(x - x_0) + b(y - y_0) + c(z - z_0) = 0,
$$

where $\vec{n} = \langle a, b, c \rangle$ and $(x_0, y_0, z_0)$ is a point on the plane.

Substitute $\vec{n} = \langle 3, -2, 1 \rangle$ and $(x_0, y_0, z_0) = (2, -1, 4)$:

$$
3(x - 2) - 2(y + 1) + 1(z - 4) = 0.
$$

Simplify:

$$
3x - 6 - 2y - 2 + z - 4 = 0,
$$

$$
3x - 2y + z - 12 = 0.
$$

Final answer:

$$
\boxed{3x - 2y + z - 12 = 0}
$$
</details>

---

## Ex2
Find the vector equation of the plane that passes through the point $(1, 3, -2)$ and has direction vectors $\vec{u} = \langle 1, 0, 2 \rangle$ and $\vec{v} = \langle 0, -1, 1 \rangle$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

The vector equation of a plane is:

$$
\vec{r}(s, t) = \vec{r}_0 + s\vec{u} + t\vec{v}.
$$

Substitute $\vec{r}_0 = \langle 1, 3, -2 \rangle$, $\vec{u} = \langle 1, 0, 2 \rangle$, and $\vec{v} = \langle 0, -1, 1 \rangle$:

$$
\vec{r}(s, t) = \langle 1, 3, -2 \rangle + s\langle 1, 0, 2 \rangle + t\langle 0, -1, 1 \rangle.
$$

Final answer:

$$
\boxed{\vec{r}(s, t) = \langle 1, 3, -2 \rangle + s\langle 1, 0, 2 \rangle + t\langle 0, -1, 1 \rangle}
$$

</details>

---

## Ex3
Convert the vector equation from Problem 2 into parametric form.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

From the vector equation:

$$
\vec{r}(s, t) = \langle 1, 3, -2 \rangle + s\langle 1, 0, 2 \rangle + t\langle 0, -1, 1 \rangle,
$$

expand into parametric equations:

$$
x = 1 + s + 0t = 1 + s,
$$

$$
y = 3 + 0s - t = 3 - t,
$$

$$
z = -2 + 2s + t.
$$

Final answer:

$$
\boxed{x = 1 + s, \, y = 3 - t, \, z = -2 + 2s + t}
$$
</details>

---

## Ex4
Find the intercepts of the plane $2x + 3y - 6z + 12 = 0$ with the $x$-, $y$-, and $z$-axes.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

To find the $x$-intercept, set $y = 0$ and $z = 0$:

$$
2x + 12 = 0 \implies x = -6.
$$

To find the $y$-intercept, set $x = 0$ and $z = 0$:

$$
3y + 12 = 0 \implies y = -4.
$$

To find the $z$-intercept, set $x = 0$ and $y = 0$:

$$
-6z + 12 = 0 \implies z = 2.
$$

Final answer:

$$
\boxed{x\text{-intercept: } -6, \, y\text{-intercept: } -4, \, z\text{-intercept: } 2}
$$

</details>

---

## Ex5
Determine whether the point $(3, -1, 2)$ lies on the plane $2x + 3y - 6z + 12 = 0$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

Substitute $(x, y, z) = (3, -1, 2)$ into the plane equation:

$$
2(3) + 3(-1) - 6(2) + 12 = 0.
$$

Simplify:

$$
6 - 3 - 12 + 12 = 3 \neq 0.
$$

Final answer:

$$
\boxed{\text{The point does not lie on the plane.}}
$$

</details>

---

## Ex6
Find the scalar equation of the plane that passes through the points $A(1, 2, 3)$, $B(4, 5, 6)$, and $C(-1, 0, 1)$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Find two direction vectors on the plane:

  $$
  \vec{AB} = \langle 4 - 1, 5 - 2, 6 - 3 \rangle = \langle 3, 3, 3 \rangle,
  $$

  $$
  \vec{AC} = \langle -1 - 1, 0 - 2, 1 - 3 \rangle = \langle -2, -2, -2 \rangle.
  $$

- Compute the normal vector $\vec{n}$ as the cross product of $\vec{AB}$ and $\vec{AC}$:

  $$
  \vec{n} = \vec{AB} \times \vec{AC} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  3 & 3 & 3 \\
  -2 & -2 & -2
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{n} = \mathbf{i}((3)(-2) - (3)(-2)) - \mathbf{j}((3)(-2) - (3)(-2)) + \mathbf{k}((3)(-2) - (3)(-2)).
  $$

  Simplify:

  $$
  \vec{n} = \langle 0, 0, 0 \rangle.
  $$

  Since the cross product is zero, the points are collinear, and no unique plane exists. Final answer:

$$
\boxed{\text{No unique plane exists.}}
$$

</details>


<iframe src="https://script.google.com/macros/s/AKfycbyL1UlsB5C_zm4q1VK_CB_bA6IR5dgZoIxEK9hkOK7NArS2qK0fwCB4ePy5un_dToxD/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>



