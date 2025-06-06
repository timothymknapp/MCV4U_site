+++
title = '8.5 Examples'
weight = 1
+++

This page provides detailed worked-out examples to help you understand how to determine the intersection of a line with a plane in 3D space.

---

## Example 1: Intersection of a Line and a Plane (One Solution)
Find the point of intersection between the line:

$$
\vec{r}(t) = \langle 1, 2, -3 \rangle + t\langle 2, -1, 4 \rangle,
$$

and the plane:

$$
2x - y + 3z - 6 = 0.
$$

### Solution:
- Write the parametric equations of the line:

  $$
  x = 1 + 2t, \quad y = 2 - t, \quad z = -3 + 4t.
  $$

- Substitute these into the plane equation:

  $$
  2(1 + 2t) - (2 - t) + 3(-3 + 4t) - 6 = 0.
  $$

- Simplify:

  $$
  2 + 4t - 2 + t - 9 + 12t - 6 = 0.
  $$

  $$
  17t - 15 = 0.
  $$

- Solve for $t$:

  $$
  t = \frac{15}{17}.
  $$

- Substitute $t = \frac{15}{17}$ back into the parametric equations:

  $$
  x = 1 + 2\left(\frac{15}{17}\right) = \frac{47}{17},
  $$

  $$
  y = 2 - \frac{15}{17} = \frac{19}{17},
  $$

  $$
  z = -3 + 4\left(\frac{15}{17}\right) = \frac{3}{17}.
  $$

Final answer:

$$
\boxed{\text{Point of intersection: } \left(\frac{47}{17}, \frac{19}{17}, \frac{3}{17}\right).}
$$

---

## Example 2: Line Intersects The plane (Point Solution)
Determine whether the line:

$$
\vec{r}(t) = \langle 1, 0, -2 \rangle + t\langle 2, 1, -3 \rangle,
$$

lies on the plane:

$$
2x + y - 3z - 4 = 0.
$$

### Solution:
- Write the parametric equations of the line:

  $$
  x = 1 + 2t, \quad y = t, \quad z = -2 - 3t.
  $$

- Substitute these into the plane equation:

  $$
  2(1 + 2t) + t - 3(-2 - 3t) - 4 = 0.
  $$

- Simplify:

  $$
  2 + 4t + t + 6 + 9t - 4 = 0.
  $$

  $$
  14t + 4 = 0.
  $$

- This simplifies to:

  $$
  14t = -4 \implies t = -\frac{2}{7}.
  $$

- Since $ t = -\frac{2}{7} $ , the line intersects the plane where its parameter equals -\frac{2}{7}.  To find the point of intersection use $ t = -\frac{2}{7} $ plugged into the line. 

$$
  \left( 1 + 2 \left(-\frac{2}{7}\right), \quad  2 - -\frac{2}{7}, \quad  -3 + 4\left(-\frac{2}{7} \right) \right)
$$


Final answer:

$$
\boxed{\left( \frac{3}{7}, \quad  - \frac{18}{7}, \quad - \frac{29}{7}  \right)}
$$

---

## Example 3: Point Solution
Determine whether the line:

$$
\vec{r}(t) = \langle 2, -1, 3 \rangle + t\langle 1, 2, -1 \rangle,
$$

intersects the plane:

$$
x + 2y - z + 5 = 0.
$$

### Solution:
- Write the parametric equations of the line:

  $$
  x = 2 + t, \quad y = -1 + 2t, \quad z = 3 - t.
  $$

- Substitute these into the plane equation:

  $$
  (2 + t) + 2(-1 + 2t) - (3 - t) + 5 = 0.
  $$

- Simplify:

  $$
  2 + t - 2 + 4t - 3 + t + 5 = 0.
  $$

  $$
  6t + 2 = 0.
  $$

- Solve for $t$:

  $$
  t = -\frac{1}{3}.
  $$

- Since $ t = -\frac{1}{3} $ , the line intersects the plane where its parameter equals -\frac{2}{7}.  To find the point of intersection use $ t = -\frac{1}{3} $ plugged into the line. 

$$
  \left( 2 + \left(-\frac{1}{3}\right), \quad  -1 + 2 \left(-\frac{1}{3}\right), \quad  3 - \left(-\frac{1}{3} \right) \right)
$$


Final answer:

$$
\boxed{\left( \frac{5}{3}, \quad  - \frac{1}{3}, \quad - \frac{10}{3}  \right)}
$$

---

## Example 4: Distance Between a Line and a Plane
Find the shortest distance between the line:

$$
\vec{r}(t) = \langle 1, 2, -3 \rangle + t\langle 2, -1, 4 \rangle,
$$

and the plane:

$$
2x - y + 3z - 6 = 0.
$$

### Solution:
- The formula for the distance between a line and a plane is:

  $$
  d = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}},
  $$

  where $(x_0, y_0, z_0)$ is a point on the line, and $\langle a, b, c \rangle$ is the normal vector of the plane.

- Use the point $(1, 2, -3)$ from the line and the normal vector $\langle 2, -1, 3 \rangle$ from the plane:

  $$
  d = \frac{|2(1) - 1(2) + 3(-3) - 6|}{\sqrt{2^2 + (-1)^2 + 3^2}}.
  $$

- Simplify:

  $$
  d = \frac{|2 - 2 - 9 - 6|}{\sqrt{4 + 1 + 9}} = \frac{|-15|}{\sqrt{14}} = \frac{15}{\sqrt{14}}.
  $$

Final answer:

$$
\boxed{\text{Shortest distance: } \frac{15}{\sqrt{14}}.}
$$

---

## Example 5: Application Problem
A drone is flying along the line:

$$
\vec{r}(t) = \langle 0, 0, 5 \rangle + t\langle 1, 2, -1 \rangle,
$$

and needs to land on a flat rooftop described by the plane:

$$
x + 2y + z - 10 = 0.
$$

Find the point where the drone will land.

### Solution:
- Write the parametric equations of the line:

  $$
  x = t, \quad y = 2t, \quad z = 5 - t.
  $$

- Substitute these into the plane equation:

  $$
  t + 2(2t) + (5 - t) - 10 = 0.
  $$

- Simplify:

  $$
  t + 4t + 5 - t - 10 = 0.
  $$

  $$
  4t - 5 = 0.
  $$

- Solve for $t$:

  $$
  t = \frac{5}{4}.
  $$

- Substitute $t = \frac{5}{4}$ back into the parametric equations:

  $$
  x = \frac{5}{4}, \quad y = 2\left(\frac{5}{4}\right) = \frac{10}{4} = \frac{5}{2}, \quad z = 5 - \frac{5}{4} = \frac{15}{4}.
  $$

Final answer:

$$
\boxed{\text{Landing point: } \left(\frac{5}{4}, \frac{5}{2}, \frac{15}{4}\right).}
$$