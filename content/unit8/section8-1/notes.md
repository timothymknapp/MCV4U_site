+++
title = '8.1: Examples'
weight = 1
+++

This page provides detailed worked-out examples to help you understand how to apply the concepts of lines in 2D and 3D.

---

## Example 1: Vector and Parametric Equations of a Line (2D)
Find the vector and parametric equations of the line passing through the point $(-3, 4)$ with direction vector $\vec{m} = \langle 2, -1 \rangle$.

### Solution:
- **Vector Equation**:
  The general form of the vector equation of a line is:
  
  $$
  \vec{r}(t) = \vec{r}_0 + t\vec{m}
  $$

  Substituting $\vec{r}_0 = \langle -3, 4 \rangle$ and $\vec{m} = \langle 2, -1 \rangle$, we get:

  $$
  \vec{r}(t) = \langle -3, 4 \rangle + t\langle 2, -1 \rangle
  $$

- **Parametric Equations**:
  From the vector equation, expand into parametric form:

  $$
  x = -3 + 2t, \quad y = 4 - t
  $$

---

## Example 2: Vector and Parametric Equations of a Line (3D)
Find the vector and parametric equations of the line passing through the points $A(1, -2, 3)$ and $B(4, 0, 6)$.

### Solution:
- **Direction Vector**:
  The direction vector $\vec{m}$ is obtained by subtracting the coordinates of $A$ from $B$:

  $$
  \vec{m} = \langle 4 - 1, 0 - (-2), 6 - 3 \rangle = \langle 3, 2, 3 \rangle
  $$

- **Vector Equation**:
  Using point $A(1, -2, 3)$ as the position vector $\vec{r}_0$, the vector equation is:

  $$
  \vec{r}(t) = \langle 1, -2, 3 \rangle + t\langle 3, 2, 3 \rangle
  $$

- **Parametric Equations**:
  Expand the vector equation into parametric form:

  $$
  x = 1 + 3t, \quad y = -2 + 2t, \quad z = 3 + 3t
  $$

---

## Example 3: Intersection of Two Lines in 2D
Determine whether the lines $\vec{r}_1(t) = \langle 2, 3 \rangle + t\langle 1, -2 \rangle$ and $\vec{r}_2(s) = \langle 4, 1 \rangle + s\langle -1, 2 \rangle$ intersect. If they do, find the point of intersection.

### Solution:
Set the parametric equations of the two lines equal to each other:

$$
x_1 = x_2, \quad y_1 = y_2
$$

From the parametric equations:

$$
2 + t = 4 - s \quad \text{(1)}
$$

$$
3 - 2t = 1 + 2s \quad \text{(2)}
$$

- Solve equation (1) for $s$:

  $$
  s = 2 - t
  $$

- Substitute $s = 2 - t$ into equation (2):

  $$
  3 - 2t = 1 + 2(2 - t)
  $$

  Simplify:

  $$
  3 - 2t = 1 + 4 - 2t
  $$

  $$
  3 = 5
  $$

  This is a contradiction, so the lines **do not intersect**.

---

## Example 4: Scalar Equation of a Line in 2D
Convert the vector equation $\vec{r}(t) = \langle -1, 2 \rangle + t\langle 3, -4 \rangle$ into scalar form.

### Solution:
- From the vector equation, write the parametric equations:

  $$
  x = -1 + 3t, \quad y = 2 - 4t
  $$

- Solve for $t$ in terms of $x$:

  $$
  t = \frac{x + 1}{3}
  $$

- Substitute $t = \frac{x + 1}{3}$ into the equation for $y$:

  $$
  y = 2 - 4\left(\frac{x + 1}{3}\right)
  $$

  Simplify:

  $$
  y = 2 - \frac{4x + 4}{3}
  $$

  $$
  y = \frac{6}{3} - \frac{4x + 4}{3}
  $$

  $$
  y = \frac{-4x + 2}{3}

  $$
  Multiply through by 3 to eliminate the fraction:

  $$
  3y = -4x + 2
  $$

  Rearrange to standard scalar form:

  $$
  4x + 3y - 2 = 0
  $$

---

## Example 5: Distance Between a Point and a Line Using Perpendicular Decomposition

Find the shortest distance from the point $ P(3, -1) $ to the line $\vec{r}(t) = \langle 0, 2 \rangle + t\langle 3, 4 \rangle$.


### Solution:

#### Step 1: Identify Key Components
- The line is given in vector form:

  $$
  \vec{r}(t) = \langle 0, 2 \rangle + t\langle 3, 4 \rangle
  $$

  - A point on the line is $ A(0, 2) $.
  - The direction vector of the line is $\vec{m} = \langle 3, 4 \rangle$.

- The given point is $ P(3, -1) $.

#### Step 2: Find the Vector Connecting $ A $ to $ P $
The vector $\vec{AP}$ connects the point $ A(0, 2) $ on the line to the point $ P(3, -1) $:

$$
\vec{AP} = \langle 3 - 0, -1 - 2 \rangle = \langle 3, -3 \rangle
$$

#### Step 3: Decompose $\vec{AP}$ into Parallel and Perpendicular Components
We decompose $\vec{AP}$ into two components:
1. **Parallel Component ($\vec{AP}_{\parallel}$)**: The projection of $\vec{AP}$ onto the direction vector $\vec{m}$.
2. **Perpendicular Component ($\vec{AP}_{\perp}$)**: The part of $\vec{AP}$ orthogonal to $\vec{m}$.

##### (a) Parallel Component
The formula for the projection of $\vec{AP}$ onto $\vec{m}$ is:

$$
\vec{AP}_{\parallel} = \frac{\vec{AP} \cdot \vec{m}}{\|\vec{m}\|^2} \cdot \vec{m}
$$

First, compute the dot product $\vec{AP} \cdot \vec{m}$:

$$
\vec{AP} \cdot \vec{m} = \langle 3, -3 \rangle \cdot \langle 3, 4 \rangle = (3)(3) + (-3)(4) = 9 - 12 = -3
$$

Next, compute the magnitude squared of $\vec{m}$:

$$
\|\vec{m}\|^2 = (3)^2 + (4)^2 = 9 + 16 = 25
$$

Now, compute $\vec{AP}_{\parallel}$:

$$
\vec{AP}_{\parallel} = \frac{-3}{25} \cdot \langle 3, 4 \rangle = \langle -\frac{9}{25}, -\frac{12}{25} \rangle
$$

##### (b) Perpendicular Component
The perpendicular component is given by:

$$
\vec{AP}_{\perp} = \vec{AP} - \vec{AP}_{\parallel}
$$

Substitute $\vec{AP} = \langle 3, -3 \rangle$ and $\vec{AP}_{\parallel} = \langle -\frac{9}{25}, -\frac{12}{25} \rangle$:

$$
\vec{AP}_{\perp} = \langle 3, -3 \rangle - \langle -\frac{9}{25}, -\frac{12}{25} \rangle
$$

$$
\vec{AP}_{\perp} = \langle 3 + \frac{9}{25}, -3 + \frac{12}{25} \rangle = \langle \frac{75}{25} + \frac{9}{25}, \frac{-75}{25} + \frac{12}{25} \rangle = \langle \frac{84}{25}, \frac{-63}{25} \rangle
$$

#### Step 4: Compute the Magnitude of $\vec{AP}_{\perp}$
The shortest distance is the magnitude of $\vec{AP}_{\perp}$:

$$
\|\vec{AP}_{\perp}\| = \sqrt{\left(\frac{84}{25}\right)^2 + \left(\frac{-63}{25}\right)^2}
$$

Simplify:

$$
\|\vec{AP}_{\perp}\| = \sqrt{\frac{84^2}{25^2} + \frac{63^2}{25^2}} = \sqrt{\frac{7056}{625} + \frac{3969}{625}} = \sqrt{\frac{11025}{625}}
$$

$$
\|\vec{AP}_{\perp}\| = \sqrt{17.64} = 4.2
$$

---

### Final Answer:
The shortest distance from the point $ P(3, -1) $ to the line is:
$$
\boxed{4.2 \, \text{units}}
$$

---

### Explanation of the Method:
1. **Decomposition**: The vector $\vec{AP}$ is split into two parts: one parallel to the line and one perpendicular to it.
2. **Perpendicular Component**: The perpendicular component represents the shortest distance because it is orthogonal to the direction of the line.
3. **Magnitude**: The magnitude of the perpendicular component gives the shortest distance.