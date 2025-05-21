+++
title = '8.1 Practice'
weight = 2
+++

Solve the following problems to reinforce your understanding of lines in 2D and 3D. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Problem 1: Vector and Parametric Equations of a Line (2D)
Find the vector and parametric equations of the line passing through the point $(-2, 5)$ with direction vector $\vec{m} = \langle 4, -3 \rangle$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- **Vector Equation**:
  The general form of the vector equation is:
  
  $$
  \vec{r}(t) = \vec{r}_0 + t\vec{m}
  $$

  Substituting $\vec{r}_0 = \langle -2, 5 \rangle$ and $\vec{m} = \langle 4, -3 \rangle$, we get:

  $$
  \vec{r}(t) = \langle -2, 5 \rangle + t\langle 4, -3 \rangle
  $$

- **Parametric Equations**:
  Expand into parametric form:

  $$
  x = -2 + 4t, \quad y = 5 - 3t
  $$

</details>

---

## Problem 2: Vector and Parametric Equations of a Line (3D)
Find the vector and parametric equations of the line passing through the points $A(2, -1, 4)$ and $B(-3, 0, 6)$.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- **Direction Vector**:
  Compute the direction vector $\vec{m}$ by subtracting the coordinates of $A$ from $B$:

  $$
  \vec{m} = \langle -3 - 2, 0 - (-1), 6 - 4 \rangle = \langle -5, 1, 2 \rangle
  $$

- **Vector Equation**:
  Using point $A(2, -1, 4)$ as the position vector $\vec{r}_0$, the vector equation is:

  $$
  \vec{r}(t) = \langle 2, -1, 4 \rangle + t\langle -5, 1, 2 \rangle
  $$

- **Parametric Equations**:
  Expand into parametric form:

  $$
  x = 2 - 5t, \quad y = -1 + t, \quad z = 4 + 2t
  $$

</details>

---

## Problem 3: Intersection of Two Lines in 2D
Determine whether the lines $\vec{r}_1(t) = \langle 1, 3 \rangle + t\langle 2, -1 \rangle$ and $\vec{r}_2(s) = \langle 4, 1 \rangle + s\langle -1, 2 \rangle$ intersect. If they do, find the point of intersection.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

Set the parametric equations equal:

$$
x_1 = x_2, \quad y_1 = y_2
$$

From the parametric equations:

$$
1 + 2t = 4 - s \quad \text{(1)}
$$

$$
3 - t = 1 + 2s \quad \text{(2)}
$$

- Solve equation (1) for $s$:

  $$
  s = 3 - 2t
  $$

- Substitute $s = 3 - 2t$ into equation (2):

  $$
  3 - t = 1 + 2(3 - 2t)
  $$

  Simplify:

  $$
  3 - t = 1 + 6 - 4t
  $$

  $$
  3 - t = 7 - 4t
  $$

  $$
  3t = 4 \implies t = \frac{4}{3}
  $$

- Substitute $t = \frac{4}{3}$ into $s = 3 - 2t$:

  $$
  s = 3 - 2\left(\frac{4}{3}\right) = \frac{9}{3} - \frac{8}{3} = \frac{1}{3}
  $$

Point of intersection:

$$
x = 1 + 2\left(\frac{4}{3}\right) = \frac{3}{3} + \frac{8}{3} = \frac{11}{3}, \quad y = 3 - \frac{4}{3} = \frac{9}{3} - \frac{4}{3} = \frac{5}{3}
$$

Final answer:

$$
\boxed{\left(\frac{11}{3}, \frac{5}{3}\right)}
$$

</details>

---

## Problem 4: Scalar Equation of a Line in 2D
Convert the vector equation $\vec{r}(t) = \langle 1, -2 \rangle + t\langle 2, 3 \rangle$ into scalar form.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- From the vector equation, write the parametric equations:

  $$
  x = 1 + 2t, \quad y = -2 + 3t
  $$

- Solve for $t$ in terms of $x$:

  $$
  t = \frac{x - 1}{2}
  $$

- Substitute $t = \frac{x - 1}{2}$ into the equation for $y$:

  $$
  y = -2 + 3\left(\frac{x - 1}{2}\right)
  $$

  Simplify:

  $$
  y = -2 + \frac{3x - 3}{2}
  $$

  $$
  y = \frac{-4}{2} + \frac{3x - 3}{2}
  $$

  $$
  y = \frac{3x - 7}{2}
  $$

  Multiply through by 2 to eliminate the fraction:

  $$
  2y = 3x - 7
  $$

  Rearrange to standard scalar form:

  $$
  3x - 2y - 7 = 0
  $$

</details>

---

## Problem 5: Distance Between a Point and a Line in 2D
Find the shortest distance from the point $P(4, 2)$ to the line $\vec{r}(t) = \langle 0, 1 \rangle + t\langle 3, 4 \rangle$ using the perpendicular decomposition technique.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

#### Step 1: Identify Key Components
- The line is given in vector form:

  $$
  \vec{r}(t) = \langle 0, 1 \rangle + t\langle 3, 4 \rangle
  $$

  - A point on the line is $A(0, 1)$.
  - The direction vector of the line is $\vec{m} = \langle 3, 4 \rangle$.

- The given point is $P(4, 2)$.

#### Step 2: Find the Vector Connecting $A$ to $P$
The vector $\vec{AP}$ is:

$$
\vec{AP} = \langle 4 - 0, 2 - 1 \rangle = \langle 4, 1 \rangle
$$

#### Step 3: Decompose $\vec{AP}$ into Parallel and Perpendicular Components
- **Parallel Component**:

  Compute the projection of $\vec{AP}$ onto $\vec{m}$:

  $$
  \vec{AP}_{\parallel} = \frac{\vec{AP} \cdot \vec{m}}{\|\vec{m}\|^2} \cdot \vec{m}
  $$

  Compute $\vec{AP} \cdot \vec{m}$:

  $$
  \vec{AP} \cdot \vec{m} = \langle 4, 1 \rangle \cdot \langle 3, 4 \rangle = (4)(3) + (1)(4) = 12 + 4 = 16
  $$

  Compute $\|\vec{m}\|^2$:

  $$
  \|\vec{m}\|^2 = (3)^2 + (4)^2 = 9 + 16 = 25
  $$

  Compute $\vec{AP}_{\parallel}$:

  $$
  \vec{AP}_{\parallel} = \frac{16}{25} \cdot \langle 3, 4 \rangle = \langle \frac{48}{25}, \frac{64}{25} \rangle
  $$

- **Perpendicular Component**:
  Compute $\vec{AP}_{\perp}$:

  $$
  \vec{AP}_{\perp} = \vec{AP} - \vec{AP}_{\parallel}
  $$

  $$
  \vec{AP}_{\perp} = \langle 4, 1 \rangle - \langle \frac{48}{25}, \frac{64}{25} \rangle = \langle \frac{100}{25} - \frac{48}{25}, \frac{25}{25} - \frac{64}{25} \rangle = \langle \frac{52}{25}, \frac{-39}{25} \rangle
  $$

#### Step 4: Compute the Magnitude of $\vec{AP}_{\perp}$
The shortest distance is:

$$
\|\vec{AP}_{\perp}\| = \sqrt{\left(\frac{52}{25}\right)^2 + \left(\frac{-39}{25}\right)^2}
$$

$$
\|\vec{AP}_{\perp}\| = \sqrt{\frac{2704}{625} + \frac{1521}{625}} = \sqrt{\frac{4225}{625}} = \sqrt{6.76} = 2.6
$$

Final answer:

$$
\boxed{2.6 \, \text{units}}
$$

</details>





<iframe src="https://script.google.com/macros/s/AKfycbx5fIyrVfwmZpJfelkVyP5UvwSCQK08MGKjC2Iajsk7Wky1qtgjoxcujsu5_6s3eFUN/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>



