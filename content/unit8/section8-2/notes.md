+++
title = '8.2 Examples'
weight = 1
+++


This page provides detailed worked-out examples to help you understand how to solve problems involving intersections of lines in 2D and 3D.

---

## Example 1: Intersection of Two Lines in 2D (One Solution)
Find the point of intersection of the lines given by:

$$
\vec{r}_1(t) = \langle 1, 2 \rangle + t\langle 3, -1 \rangle, \quad \vec{r}_2(s) = \langle 4, 0 \rangle + s\langle -2, 1 \rangle.
$$

### Solution:
Since the lines are not paralle; Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2
$$

From the parametric equations:

$$
1 + 3t = 4 - 2s \quad \text{(1)}
$$

$$
2 - t = 0 + s \quad \text{(2)}
$$

- Solve equation (2) for $s$:
  
  $$
  s = 2 - t
  $$

- Substitute $s = 2 - t$ into equation (1):
  
  $$
  1 + 3t = 4 - 2(2 - t)
  $$

  Simplify:

  $$
  1 + 3t = 4 - 4 + 2t
  $$

  $$
  1 + 3t = 2t
  $$

  $$
  t = -1
  $$

- Substitute $t = -1$ into $s = 2 - t$:

  $$
  s = 2 - (-1) = 3
  $$

Point of intersection:

$$
x = 1 + 3(-1) = -2, \quad y = 2 - (-1) = 3
$$

Final answer:

$$
\boxed{(-2, 3)}
$$

---

## Example 2: Intersection of Two Lines in 3D (No Solution)
Determine whether the following lines intersect:

$$
\vec{r}_1(t) = \langle 1, 2, 3 \rangle + t\langle 2, -1, 1 \rangle, \quad \vec{r}_2(s) = \langle 4, 0, 1 \rangle + s\langle -1, 2, 1 \rangle.
$$

### Solution:
Since the lines are not parallel; Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2, \quad z_1 = z_2
$$

From the parametric equations:

$$
1 + 2t = 4 - s \quad \text{(1)}
$$

$$
2 - t = 0 + 2s \quad \text{(2)}
$$

$$
3 + t = 1 + s \quad \text{(3)}
$$

- Solve equation (1) for $s$:

  $$
  s = 4 - 1 - 2t = 3 - 2t
  $$

- Substitute $s = 3 - 2t$ into equation (2):

  $$
  2 - t = 2(3 - 2t)
  $$

  Simplify:

  $$
  2 - t = 6 - 4t
  $$

  $$
  3t = 4 \implies t = \frac{4}{3}
  $$

- Substitute $t = \frac{4}{3}$ into $s = 3 - 2t$:

  $$
  s = 3 - 2\left(\frac{4}{3}\right) = \frac{9}{3} - \frac{8}{3} = \frac{1}{3}
  $$

- Check equation (3) with $t = \frac{4}{3}$ and $s = \frac{1}{3}$:

  $$
  3 + \frac{4}{3} = 1 + \frac{1}{3}
  $$

  $$
  \frac{9}{3} + \frac{4}{3} = \frac{3}{3} + \frac{1}{3}
  $$

  $$
  \frac{13}{3} \neq \frac{4}{3}
  $$

Since equation (3) is not satisfied, the lines do not intersect. Final answer:
$$
\boxed{\text{No solution}}
$$

---

## Example 3: Distance Between Skew Lines in 3D
Find the shortest distance between the skew lines:
$$
\vec{r}_1(t) = \langle 1, 2, 3 \rangle + t\langle 1, -1, 2 \rangle, \quad \vec{r}_2(s) = \langle 4, 0, 1 \rangle + s\langle -1, 2, 1 \rangle.
$$

### Solution:
The formula for the shortest distance between skew lines is:
$$
\text{Distance} = \frac{|(\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2)|}{\|\vec{m}_1 \times \vec{m}_2\|}
$$

- Points on the lines:

  $$
  \vec{b}_1 = \langle 1, 2, 3 \rangle, \quad \vec{b}_2 = \langle 4, 0, 1 \rangle
  $$

- Direction vectors:

  $$
  \vec{m}_1 = \langle 1, -1, 2 \rangle, \quad \vec{m}_2 = \langle -1, 2, 1 \rangle
  $$

- Compute $\vec{b}_1 - \vec{b}_2$:

  $$
  \vec{b}_1 - \vec{b}_2 = \langle 1 - 4, 2 - 0, 3 - 1 \rangle = \langle -3, 2, 2 \rangle
  $$

- Compute $\vec{m}_1 \times \vec{m}_2$:

  $$
  \vec{m}_1 \times \vec{m}_2 = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & -1 & 2 \\
  -1 & 2 & 1
  \end{vmatrix}

  $$
  Expand the determinant:
  $$
  \vec{m}_1 \times \vec{m}_2 = \mathbf{i}((-1)(1) - (2)(2)) - \mathbf{j}((1)(1) - (2)(-1)) + \mathbf{k}((1)(2) - (-1)(-1))
  $$

  $$
  \vec{m}_1 \times \vec{m}_2 = \mathbf{i}(-1 - 4) - \mathbf{j}(1 + 2) + \mathbf{k}(2 - 1)
  $$

  $$
  \vec{m}_1 \times \vec{m}_2 = \langle -5, -3, 1 \rangle
  $$

- Compute $(\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2)$:

  $$
  (\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2) = \langle -3, 2, 2 \rangle \cdot \langle -5, -3, 1 \rangle
  $$

  $$
  = (-3)(-5) + (2)(-3) + (2)(1) = 15 - 6 + 2 = 11
  $$

- Compute $\|\vec{m}_1 \times \vec{m}_2\|$:

  $$
  \|\vec{m}_1 \times \vec{m}_2\| = \sqrt{(-5)^2 + (-3)^2 + (1)^2} = \sqrt{25 + 9 + 1} = \sqrt{35}
  $$

- Compute the distance:

  $$
  \text{Distance} = \frac{|11|}{\sqrt{35}} = \frac{11}{\sqrt{35}}
  $$

Final answer:

$$
\boxed{\frac{11}{\sqrt{35}} \, \text{units}}
$$

---

## Example 4: Infinite Solutions in 2D
Show that the lines $\vec{r}_1(t) = \langle 1, 2 \rangle + t\langle 2, -1 \rangle$ and $\vec{r}_2(s) = \langle 3, 1 \rangle + s\langle 4, -2 \rangle$ are coincident.

### Solution:
- Direction vectors:

  $$
  \vec{m}_1 = \langle 2, -1 \rangle, \quad \vec{m}_2 = \langle 4, -2 \rangle
  $$

  Since $\vec{m}_2 = 2\vec{m}_1$, the direction vectors are scalar multiples, so the lines are parallel.

- Check if the lines share a point:
  Set $t = 0$ in $\vec{r}_1(t)$:

  $$
  \vec{r}_1(0) = \langle 1, 2 \rangle
  $$

  Set $s = 0$ in $\vec{r}_2(s)$:

  $$
  \vec{r}_2(0) = \langle 3, 1 \rangle
  $$

  The points are different, but we check if they lie on the same line:
  Parametrize $\vec{r}_2(s)$ using $\vec{r}_1(t)$:

  $$
  \langle 1, 2 \rangle + t\langle 2, -1 \rangle = \langle 3, 1 \rangle + s\langle 4, -2 \rangle
  $$

  Solve:

  $$
  1 + 2t = 3 + 4s, \quad 2 - t = 1 - 2s
  $$

  From the second equation:

  $$
  t = 1 + 2s
  $$

  Substitute into the first equation:

  $$
  1 + 2(1 + 2s) = 3 + 4s
  $$

  $$
  1 + 2 + 4s = 3 + 4s
  $$

  $$
  3 = 3
  $$

  This is always true, so the lines coincide. Final answer:

$$
\boxed{\text{Infinite solutions}}
$$