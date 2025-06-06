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


#### Step 1: Check Parallelism
To determine if the line lies on the plane, we first check if the line is **parallel** to the plane. This is done by verifying whether the **direction vector of the line** ($\vec{d}$) is perpendicular to the **normal vector of the plane** ($\vec{n}$).

- The direction vector of the line is:

  $$
  \vec{d} = \langle 2, -1, 3 \rangle.
  $$

- The normal vector of the plane is:

  $$
  \vec{n} = \langle 2, -1, 3 \rangle.
  $$

- Compute the dot product:
 
  $$
  \vec{d} \cdot \vec{n} = \langle 2, -1, 3 \rangle \cdot \langle 2, -1, 3 \rangle = (2)(2) + (-1)(-1) + (3)(3).
  $$
 
  Simplify:
 
  $$
  \vec{d} \cdot \vec{n} = 4 + 1 + 9 = 14.
  $$

- Since $\vec{d} \cdot \vec{n} \neq 0$, the line is **not parallel** to the plane.

#### Step 2: Conclusion
Since the line is **not parallel** to the plane, it **cannot lie entirely on the plane**. There is no need to check whether a specific point on the line satisfies the plane equation.

Final Answer

$$
\boxed{\text{The line does not lie on the plane.}}
$$

</details>
 
---

## Ex3

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

#### Step 1: Check Parallelism
To determine if the line intersects the plane, we first check if the line is **parallel** to the plane. This is done by verifying whether the **direction vector of the line** ($\vec{d}$) is perpendicular to the **normal vector of the plane** ($\vec{n}$).

- The direction vector of the line is:
 
  $$
  \vec{d} = \langle 1, -1, 2 \rangle.
  $$

- The normal vector of the plane is:
 
  $$
  \vec{n} = \langle 1, -1, 2 \rangle.
  $$

- Compute the dot product:
 
  $$
  \vec{d} \cdot \vec{n} = \langle 1, -1, 2 \rangle \cdot \langle 1, -1, 2 \rangle = (1)(1) + (-1)(-1) + (2)(2).
  $$
  
  Simplify:
  
  $$
  \vec{d} \cdot \vec{n} = 1 + 1 + 4 = 6.
  $$

- Since $\vec{d} \cdot \vec{n} \neq 0$, the line is **not parallel** to the plane.

#### Step 2: Solve for Intersection
Since the line is not parallel to the plane, we solve for the intersection by substituting the parametric equations of the line into the plane equation.

- The parametric equations of the line are:
  
  $$
  x = t, \quad y = 1 - t, \quad z = -2 + 2t.
  $$

- Substitute these into the plane equation $x - y + 2z - 6 = 0$:
  
  $$
  t - (1 - t) + 2(-2 + 2t) - 6 = 0.
  $$

- Simplify:
  $$
  t - 1 + t - 4 + 4t - 6 = 0.
  $$
  
  Combine like terms:
  
  $$
  6t - 11 = 0.
  $$

- Solve for $t$:
  
  $$
  t = \frac{11}{6}.
  $$

#### Step 3: Find the Intersection Point
Substitute $t = \frac{11}{6}$ into the parametric equations of the line to find the intersection point:
$$
x = \frac{11}{6}, \quad y = 1 - \frac{11}{6} = -\frac{5}{6}, \quad z = -2 + 2\left(\frac{11}{6}\right) = \frac{5}{3}.
$$

- The intersection point is:
  $$
  \left(\frac{11}{6}, -\frac{5}{6}, \frac{5}{3}\right).
  $$


Final Answer

$$
\boxed{\text{The line intersects the plane at the point } \left(\frac{11}{6}, -\frac{5}{6}, \frac{5}{3}\right).}
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

