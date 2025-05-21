+++
title = '8.2 Practice'
weight = 2
+++

# Section 8.2: Practice Problems

Solve the following problems to reinforce your understanding of intersections of lines in 2D and 3D. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## EX1
Find the point of intersection of the lines given by:

$$
\vec{r}_1(t) = \langle -1, 3 \rangle + t\langle 2, -1 \rangle, \quad \vec{r}_2(s) = \langle 4, 0 \rangle + s\langle -1, 2 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

Because the lines are not parallel; Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2
$$

From the parametric equations:

$$
-1 + 2t = 4 - s \quad \text{(1)}
$$

$$
3 - t = 0 + 2s \quad \text{(2)}
$$

- Solve equation (2) for $s$:

  $$
  s = \frac{3 - t}{2}
  $$

- Substitute $s = \frac{3 - t}{2}$ into equation (1):

  $$
  -1 + 2t = 4 - \frac{3 - t}{2}
  $$

  Multiply through by 2 to eliminate the fraction:

  $$
  -2 + 4t = 8 - (3 - t)
  $$

  Simplify:

  $$
  -2 + 4t = 8 - 3 + t
  $$

  $$
  4t - t = 5 + 2
  $$

  $$
  3t = 7 \implies t = \frac{7}{3}
  $$

- Substitute $t = \frac{7}{3}$ into $s = \frac{3 - t}{2}$:

  $$
  s = \frac{3 - \frac{7}{3}}{2} = \frac{\frac{9}{3} - \frac{7}{3}}{2} = \frac{\frac{2}{3}}{2} = \frac{1}{3}
  $$

Point of intersection:

$$
x = -1 + 2\left(\frac{7}{3}\right) = -1 + \frac{14}{3} = \frac{-3}{3} + \frac{14}{3} = \frac{11}{3}
$$

$$
y = 3 - \frac{7}{3} = \frac{9}{3} - \frac{7}{3} = \frac{2}{3}
$$

Final answer:

$$
\boxed{\left(\frac{11}{3}, \frac{2}{3}\right)}
$$
</details>

---

## Ex2
Determine whether the following lines intersect:

$$
\vec{r}_1(t) = \langle 2, 1, -3 \rangle + t\langle 1, 2, -1 \rangle, \quad \vec{r}_2(s) = \langle 4, -1, 5 \rangle + s\langle -2, 3, 1 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

Because the lines are not parallel; Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2, \quad z_1 = z_2
$$

From the parametric equations:

$$
2 + t = 4 - 2s \quad \text{(1)}
$$

$$
1 + 2t = -1 + 3s \quad \text{(2)}
$$

$$
-3 - t = 5 + s \quad \text{(3)}
$$

- Solve equation (1) for $t$:

  $$
  t = 4 - 2s - 2 = 2 - 2s
  $$

- Substitute $t = 2 - 2s$ into equation (2):

  $$
  1 + 2(2 - 2s) = -1 + 3s
  $$

  Simplify:

  $$
  1 + 4 - 4s = -1 + 3s
  $$

  $$
  5 - 4s = -1 + 3s
  $$

  $$
  6 = 7s \implies s = \frac{6}{7}
  $$

- Substitute $s = \frac{6}{7}$ into $t = 2 - 2s$:

  $$
  t = 2 - 2\left(\frac{6}{7}\right) = 2 - \frac{12}{7} = \frac{14}{7} - \frac{12}{7} = \frac{2}{7}
  $$

- Check equation (3) with $t = \frac{2}{7}$ and $s = \frac{6}{7}$:

  $$
  -3 - \frac{2}{7} = 5 + \frac{6}{7}
  $$

  $$
  \frac{-21}{7} - \frac{2}{7} = \frac{35}{7} + \frac{6}{7}
  $$

  $$
  \frac{-23}{7} \neq \frac{41}{7}
  $$

Since equation (3) is not satisfied, the lines do not intersect. Final answer:

$$
\boxed{\text{No solution}}
$$
</details>

---

## Ex3
Find the shortest distance between the skew lines:

$$
\vec{r}_1(t) = \langle 0, 1, 2 \rangle + t\langle 1, -1, 3 \rangle, \quad \vec{r}_2(s) = \langle 3, 4, 1 \rangle + s\langle -1, 2, 2 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

The formula for the shortest distance between skew lines is:

$$
\text{Distance} = \frac{|(\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2)|}{\|\vec{m}_1 \times \vec{m}_2\|}
$$

- Points on the lines:

  $$
  \vec{b}_1 = \langle 0, 1, 2 \rangle, \quad \vec{b}_2 = \langle 3, 4, 1 \rangle
  $$

- Direction vectors:

  $$
  \vec{m}_1 = \langle 1, -1, 3 \rangle, \quad \vec{m}_2 = \langle -1, 2, 2 \rangle
  $$

- Compute $\vec{b}_1 - \vec{b}_2$:

  $$
  \vec{b}_1 - \vec{b}_2 = \langle 0 - 3, 1 - 4, 2 - 1 \rangle = \langle -3, -3, 1 \rangle
  $$

- Compute $\vec{m}_1 \times \vec{m}_2$:

  $$
  \vec{m}_1 \times \vec{m}_2 = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & -1 & 3 \\
  -1 & 2 & 2
  \end{vmatrix}

  $$

  Expand the determinant:

  $$
  \vec{m}_1 \times \vec{m}_2 = \mathbf{i}((-1)(2) - (3)(2)) - \mathbf{j}((1)(2) - (3)(-1)) + \mathbf{k}((1)(2) - (-1)(-1))
  $$

  $$
  \vec{m}_1 \times \vec{m}_2 = \mathbf{i}(-2 - 6) - \mathbf{j}(2 + 3) + \mathbf{k}(2 - 1)
  $$

  $$
  \vec{m}_1 \times \vec{m}_2 = \langle -8, -5, 1 \rangle
  $$

- Compute $(\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2)$:
  
  $$
  (\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2) = \langle -3, -3, 1 \rangle \cdot \langle -8, -5, 1 \rangle
  $$
 
  $$
  = (-3)(-8) + (-3)(-5) + (1)(1) = 24 + 15 + 1 = 40
  $$

- Compute $\|\vec{m}_1 \times \vec{m}_2\|$:
  $$
  \|\vec{m}_1 \times \vec{m}_2\| = \sqrt{(-8)^2 + (-5)^2 + (1)^2} = \sqrt{64 + 25 + 1} = \sqrt{90}
  $$

- Compute the distance:
  $$
  \text{Distance} = \frac{|40|}{\sqrt{90}} = \frac{40}{\sqrt{90}} = \frac{40}{3\sqrt{10}} = \frac{4\sqrt{10}}{3}
  $$

Final answer:
$$
\boxed{\frac{4\sqrt{10}}{3} \, \text{units}}
$$
</details>

---

## Ex4
Show that the lines $\vec{r}_1(t) = \langle 2, 3 \rangle + t\langle 1, -2 \rangle$ and $\vec{r}_2(s) = \langle 4, -1 \rangle + s\langle 2, -4 \rangle$ are coincident.

<details>
<summary><strong>Solution</strong></summary>

- Direction vectors:

  $$
  \vec{m}_1 = \langle 1, -2 \rangle, \quad \vec{m}_2 = \langle 2, -4 \rangle
  $$

  Since the ratios of the components odf the slope vectors are all equal, the lines are parallel.

- Check if the lines share a point:
  Set $t = 0$ in $\vec{r}_1(t)$:

  $$
  \vec{r}_1(0) = \langle 2, 3 \rangle
  $$

  Set $s = 0$ in $\vec{r}_2(s)$:

  $$
  \vec{r}_2(0) = \langle 4, -1 \rangle
  $$

  The points are different, but we check if they lie on the same line:
  Parametrize $\vec{r}_2(s)$ using $\vec{r}_1(t)$:

  $$
  \langle 2, 3 \rangle + t\langle 1, -2 \rangle = \langle 4, -1 \rangle + s\langle 2, -4 \rangle
  $$

  Solve:

  $$
  2 + t = 4 + 2s, \quad 3 - 2t = -1 - 4s
  $$

  From the first equation:

  $$
  t = 2 + 2s
  $$

  Substitute into the second equation:

  $$
  3 - 2(2 + 2s) = -1 - 4s
  $$

  Simplify:

  $$
  3 - 4 - 4s = -1 - 4s
  $$

  $$
  -1 = -1
  $$

  This is always true, so the lines coincide. Final answer:

$$
\boxed{\text{Infinite solutions}}
$$

</details>

---

## Ex5
Determine the intersection of the following lines:

$$
\vec{r}_1(t) = \langle 1, 0, -2 \rangle + t\langle 2, 1, 3 \rangle, \quad \vec{r}_2(s) = \langle 3, 1, 4 \rangle + s\langle -1, 2, 1 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2, \quad z_1 = z_2
$$

From the parametric equations:

$$
1 + 2t = 3 - s \quad \text{(1)}
$$

$$
0 + t = 1 + 2s \quad \text{(2)}
$$

$$
-2 + 3t = 4 + s \quad \text{(3)}
$$

- Solve equation (2) for $t$:

  $$
  t = 1 + 2s
  $$

- Substitute $t = 1 + 2s$ into equation (1):

  $$
  1 + 2(1 + 2s) = 3 - s
  $$

  Simplify:

  $$
  1 + 2 + 4s = 3 - s
  $$

  $$
  3 + 4s = 3 - s
  $$

  $$
  5s = 0 \implies s = 0
  $$

- Substitute $s = 0$ into $t = 1 + 2s$:

  $$
  t = 1 + 2(0) = 1
  $$

- Check equation (3) with $t = 1$ and $s = 0$:

  $$
  -2 + 3(1) = 4 + 0
  $$

  $$
  1 = 4
  $$

  This is satisfied.

Point of intersection:

$$
x = 1 + 2(1) = 3, \quad y = 0 + 1 = 1, \quad z = -2 + 3(1) = 1
$$

Final answer:

$$
\boxed{(3, 1, 1)}
$$

</details>

---

## Ex6
Determine the intersection of the following lines:

$$
\vec{r}_1(t) = \langle 1, 2, 3 \rangle + t\langle 1, -1, 2 \rangle, \quad \vec{r}_2(s) = \langle 4, 0, 1 \rangle + s\langle -1, 2, 1 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2, \quad z_1 = z_2
$$

From the parametric equations:

$$
1 + t = 4 - s \quad \text{(1)}
$$

$$
2 - t = 0 + 2s \quad \text{(2)}
$$

$$
3 + 2t = 1 + s \quad \text{(3)}
$$

- Solve equation (1) for $t$:

  $$
  t = 3 - s
  $$

- Substitute $t = 3 - s$ into equation (2):

  $$
  2 - (3 - s) = 2s
  $$

  Simplify:

  $$
  2 - 3 + s = 2s
  $$

  $$
  -1 + s = 2s
  $$

  $$
  s = -1
  $$

- Substitute $s = -1$ into $t = 3 - s$:

  $$
  t = 3 - (-1) = 4
  $$

- Check equation (3) with $t = 4$ and $s = -1$:

  $$
  3 + 2(4) = 1 + (-1)
  $$

  $$
  3 + 8 = 0
  $$

  $$
  11 \neq 0
  $$

Since equation (3) is not satisfied, the lines do not intersect. To confirm they are skew, check if the direction vectors are not scalar multiples:

$$
\vec{m}_1 = \langle 1, -1, 2 \rangle, \quad \vec{m}_2 = \langle -1, 2, 1 \rangle
$$

These vectors are not scalar multiples, so the lines are skew. Final answer:

$$
\boxed{\text{No solution (skew lines)}}
$$
</details>

---

## Ex7
Determine the intersection of the following lines:

$$
\vec{r}_1(t) = \langle 2, 1, -3 \rangle + t\langle 2, -1, 3 \rangle, \quad \vec{r}_2(s) = \langle 4, 0, 1 \rangle + s\langle 4, -2, 6 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

- Direction vectors:

  $$
  \vec{m}_1 = \langle 2, -1, 3 \rangle, \quad \vec{m}_2 = \langle 4, -2, 6 \rangle
  $$

  Since $\vec{m}_2 = 2\vec{m}_1$, the direction vectors are scalar multiples, so the lines are parallel.

- Check if the lines share a point:

  Set $t = 0$ in $\vec{r}_1(t)$:

  $$
  \vec{r}_1(0) = \langle 2, 1, -3 \rangle
  $$

  Set $s = 0$ in $\vec{r}_2(s)$:

  $$
  \vec{r}_2(0) = \langle 4, 0, 1 \rangle
  $$

  The points are different, so the lines are parallel but distinct. Final answer:

$$
\boxed{\text{No solution (parallel lines)}}
$$

</details>

---

## Ex8

Determine the intersection of the following lines:

$$
\vec{r}_1(t) = \langle 1, 2, 3 \rangle + t\langle 1, -1, 2 \rangle, \quad \vec{r}_2(s) = \langle 2, 1, 5 \rangle + s\langle 2, -2, 4 \rangle.
$$

<details>
<summary><strong>Solution</strong></summary>

- Direction vectors:

  $$
  \vec{m}_1 = \langle 1, -1, 2 \rangle, \quad \vec{m}_2 = \langle 2, -2, 4 \rangle
  $$

  Since $\vec{m}_2 = 2\vec{m}_1$, the direction vectors are scalar multiples, so the lines are parallel.

- Check if the lines share a point:
  Parametrize $\vec{r}_2(s)$ using $\vec{r}_1(t)$:

  $$
  \langle 1, 2, 3 \rangle + t\langle 1, -1, 2 \rangle = \langle 2, 1, 5 \rangle + s\langle 2, -2, 4 \rangle
  $$

  Solve:

  $$
  1 + t = 2 + 2s, \quad 2 - t = 1 - 2s, \quad 3 + 2t = 5 + 4s
  $$

  From the first equation:

  $$
  t = 1 + 2s
  $$

  Substitute into the second equation:

  $$
  2 - (1 + 2s) = 1 - 2s
  $$

  Simplify:

  $$
  1 - 2s = 1 - 2s
  $$
  This is always true, so the lines coincide. Final answer:

$$
\boxed{\text{Infinite solutions (coincident lines)}}
$$

</details>



<iframe src="https://script.google.com/macros/s/AKfycbxm4gzccLCeA8yb8OwRwZPCO2WI77TDB9Wf9JZhBC4IzyxynZA5PoRi2Lv6EkXcV8Bq2Q/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>





