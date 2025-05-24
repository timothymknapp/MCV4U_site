+++
title = '8.5 Practice'
weight = 2
+++

Solve the following problems to reinforce your understanding of intersections of lines with planes in 3D. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Ex1
Find the point of intersection between the line:

$$
\vec{r}(t) = \langle 2, -1, 3 \rangle + t\langle 1, 2, -1 \rangle,
$$

and the plane:

$$
x + 2y - z - 4 = 0.
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Write the parametric equations of the line:

  $$
  x = 2 + t, \quad y = -1 + 2t, \quad z = 3 - t.
  $$

- Substitute these into the plane equation:

  $$
  (2 + t) + 2(-1 + 2t) - (3 - t) - 4 = 0.
  $$

- Simplify:

  $$
  2 + t - 2 + 4t - 3 + t - 4 = 0.
  $$

  $$
  6t - 7 = 0.
  $$

- Solve for $t$:

  $$
  t = \frac{7}{6}.
  $$

- Substitute $t = \frac{7}{6}$ back into the parametric equations:

  $$
  x = 2 + \frac{7}{6} = \frac{19}{6}, \quad y = -1 + 2\left(\frac{7}{6}\right) = \frac{4}{3}, \quad z = 3 - \frac{7}{6} = \frac{11}{6}.
  $$

Final answer:

$$
\boxed{\text{Point of intersection: } \left(\frac{19}{6}, \frac{4}{3}, \frac{11}{6}\right).}
$$

</details>

---

## Ex2
Determine whether the line:

$$
\vec{r}(t) = \langle 1, 0, -2 \rangle + t\langle 2, -1, 3 \rangle,
$$

lies on the plane:

$$
2x - y + 3z - 5 = 0.
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Write the parametric equations of the line:

  $$
  x = 1 + 2t, \quad y = -t, \quad z = -2 + 3t.
  $$

- Substitute these into the plane equation:

  $$
  2(1 + 2t) - (-t) + 3(-2 + 3t) - 5 = 0.
  $$

- Simplify:

  $$
  2 + 4t + t - 6 + 9t - 5 = 0.
  $$

  $$
  14t - 9 = 0.
  $$

- Solve for $t$:

  $$
  t = \frac{9}{14}.
  $$

- Since the equation holds true for all values of $t$, the line lies entirely on the plane.

Final answer:

$$
\boxed{\text{The line lies on the plane (infinite solutions).}}
$$

</details>

---

##  Ex3

Determine whether the line:

$$
\vec{r}(t) = \langle 0, 1, -2 \rangle + t\langle 1, -1, 2 \rangle,
$$

intersects the plane:

$$
x - y + 2z - 6 = 0.
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Write the parametric equations of the line:

  $$
  x = t, \quad y = 1 - t, \quad z = -2 + 2t.
  $$

- Substitute these into the plane equation:

  $$
  t - (1 - t) + 2(-2 + 2t) - 6 = 0.
  $$

- Simplify:

  $$
  t - 1 + t - 4 + 4t - 6 = 0.
  $$

  $$
  6t - 11 = 0.
  $$

- Solve for $t$:

  $$
  t = \frac{11}{6}.
  $$

- Check if the line intersects the plane by substituting $t = \frac{11}{6}$ into the parametric equations. If no valid solution exists, the line is parallel to the plane.

Final answer:

$$
\boxed{\text{The line is parallel to the plane (no solution).}}
$$

</details>

---

## Ex4
Find the shortest distance between the line:

$$
\vec{r}(t) = \langle 0, 1, -2 \rangle + t\langle 1, -1, 2 \rangle,
$$

and the plane:

$$
x - y + 2z - 6 = 0.
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Use the formula for the distance between a line and a plane:

  $$
  d = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}},
  $$

  where $(x_0, y_0, z_0)$ is a point on the line, and $\langle a, b, c \rangle$ is the normal vector of the plane.

- Use the point $(0, 1, -2)$ from the line and the normal vector $\langle 1, -1, 2 \rangle$ from the plane:

  $$
  d = \frac{|1(0) - 1(1) + 2(-2) - 6|}{\sqrt{1^2 + (-1)^2 + 2^2}}.
  $$

- Simplify:

  $$
  d = \frac{|0 - 1 - 4 - 6|}{\sqrt{1 + 1 + 4}} = \frac{|-11|}{\sqrt{6}} = \frac{11}{\sqrt{6}}.
  $$

Final answer:

$$
\boxed{\text{Shortest distance: } \frac{11}{\sqrt{6}}.}
$$

</details>

---

## Ex5
A drone is flying along the line:

$$
\vec{r}(t) = \langle 0, 0, 5 \rangle + t\langle 1, 2, -1 \rangle,
$$

and needs to land on a flat rooftop described by the plane:

$$
x + 2y + z - 10 = 0.
$$

Find the point where the drone will land.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

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

</details>



<iframe src="https://script.google.com/macros/s/AKfycby9hbt_ywXBAt4Hs92Ssb55WEO__Lgya3v65ix86nzH4OnxRsvNIK2JUqsFyy2AkYaUTw/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

