+++
title = '8.6 Examples'
weight = 1
+++


This page provides detailed worked-out examples to help you understand how to determine the intersection of two planes in 3D space.

---

## Example 1: Intersection of Two Planes (Line of Intersection) Special Case: multiple variables eliminate

Find the line of intersection between the planes:

$$
2x - y + z - 4 = 0 \quad \text{and} \quad x + y - z - 2 = 0.
$$

### Step 1: Check if the planes are parallel

The normal vectors of the planes are:

$$
\vec{n}_1 = \langle 2, -1, 1 \rangle, \quad \vec{n}_2 = \langle 1, 1, -1 \rangle.
$$

To check if the planes are parallel, we see if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$. That would mean:

$$
\frac{1}{2} = \frac{1}{-1} = \frac{-1}{1}
$$

These ratios are clearly not equal, so the planes are **not parallel**. Therefore, they intersect along a line.


### Step 2: Eliminate one variable

We are given:

$$
(1)\quad 2x - y + z = 4 \quad
(2)\quad x + y - z = 2
$$

Add equations (1) and (2), (this elimiates both y and z):

$$
(2x - y + z) + (x + y - z) = 4 + 2 \Rightarrow 3x = 6 \Rightarrow x = 2
$$

Now substitute $x = 2$ into equation (2):

$$
2 + y - z = 2 \Rightarrow y - z = 0 \Rightarrow y = z
$$

### Step 3: Set one variable as the parameter 

Recall that the solution is a line since the planes are not parallel. since we are looking for a line we must introduce a parameter.  

Let $z = t$, then since $y = z$, we also have $y = t$.

From above, $x = 2$, so the parametric equations of the line are:

$$
x = 2, \quad y = t, \quad z = t
$$


### Step 4: Write the vector equation of the line

Using the point $(2, 0, 0)$ when $t = 0$, and direction vector $\langle 0, 1, 1 \rangle$, the vector equation is:

$$
\vec{r}(t) = \langle 2, 0, 0 \rangle + t\langle 0, 1, 1 \rangle
$$

Alternatively, scaling the direction vector gives an equivalent form:

$$
\vec{r}(t) = \langle 2, 0, 0 \rangle + t\langle 0, 3, 3 \rangle
$$


### ✅ Final Answer:

$$
\boxed{\vec{r}(t) = \langle 2, 0, 0 \rangle + t\langle 0, 3, 3 \rangle}
$$

---

### Example 2: Intersection of Two Planes (More Typical Case)

Find the line of intersection between the planes:

$$
(1)\quad 3x + y - 2z = 6 \quad \text{and} \quad (2)\quad x - 2y + z = 3
$$


#### Step 1: Check if the planes are parallel

Normal vectors:

$$
\vec{n}_1 = \langle 3, 1, -2 \rangle, \quad \vec{n}_2 = \langle 1, -2, 1 \rangle
$$

Check if $\vec{n}_2$ is a scalar multiple of $\vec{n}_1$. The ratios:

$$
\frac{1}{3}, \quad \frac{-2}{1}, \quad \frac{1}{-2}
$$

These are not equal ⇒ **Planes are not parallel**, so they intersect along a line.


#### Step 2: Eliminate one variable

We are given:

$$
(1)\quad 3x + y - 2z = 6 \quad
(2)\quad x - 2y + z = 3
$$

Let’s eliminate $y$. Multiply equation (1) by 2:

$$
(1')\quad 6x + 2y - 4z = 12
$$

Now add to equation (2):

$$
(6x + 2y - 4z) + (x - 2y + z) = 12 + 3 \\
7x - 3z = 15 \quad \text{(Equation A)}
$$


#### Step 3: Set one variable as the parameter

Let’s set $z = t$

Then from Equation A:

$$
7x - 3t = 15 \Rightarrow x = \frac{15 + 3t}{7}
$$

Now substitute both $x$ and $z = t$ into one of the original equations to solve for $y$. Use equation (2):

$$
x - 2y + z = 3 \Rightarrow \frac{15 + 3t}{7} - 2y + t = 3
$$

Multiply everything by 7 to eliminate denominator:

$$
15 + 3t - 14y + 7t = 21 \Rightarrow -14y + 10t = 6
\Rightarrow y = \frac{10t - 6}{14} = \frac{5t - 3}{7}
$$

#### Step 4: Parametric and Vector Equations

Now we have:

$$
x = \frac{15 + 3t}{7}, \quad y = \frac{5t - 3}{7}, \quad z = t
$$

This can be written as a vector equation:

$$
\vec{r}(t) = \left\langle \frac{15}{7}, -\frac{3}{7}, 0 \right\rangle + t\left\langle \frac{3}{7}, \frac{5}{7}, 1 \right\rangle
$$

Or, multiplying direction vector by 7 to simplify:

$$
\vec{r}(t) = \left\langle \frac{15}{7}, -\frac{3}{7}, 0 \right\rangle + t\langle 3, 5, 7 \rangle
$$


### ✅ Final Answer:

$$
\boxed{\vec{r}(t) = \left\langle \frac{15}{7}, -\frac{3}{7}, 0 \right\rangle + t\langle 3, 5, 7 \rangle}
$$

---

## Example 3: Coincident Planes (Infinite Solutions)

Determine the relationship between the planes:

$$
x - 2y + 3z - 6 = 0 \quad \text{and} \quad 2x - 4y + 6z - 12 = 0
$$

### Step 1: Check if normals are scalar multiples

Normal vectors:

$$
\vec{n}_1 = \langle 1, -2, 3 \rangle, \quad \vec{n}_2 = \langle 2, -4, 6 \rangle
$$

Check ratios:

$$
\frac{2}{1} = \frac{-4}{-2} = \frac{6}{3} = 2
$$

All ratios are equal ⇒ normals are scalar multiples ⇒ planes are **parallel**

### Step 2: Check if planes are coincident

Compare constants:

Plane 1: $D_1 = -6$  
Plane 2: $D_2 = -12$

Check ratio:

$$
\frac{D_2}{D_1} = \frac{-12}{-6} = 2
$$

This matches the scalar multiple of the normals ⇒ **Planes are coincident**

### Final Answer:

$$
\boxed{\text{The planes are coincident (infinite number of solutions).}}
$$

---

## Example 4: Parallel and Distinct Planes (No Intersection)

Determine the relationship between the planes:

$$
x + y + z - 3 = 0 \quad \text{and} \quad 2x + 2y + 2z - 5 = 0
$$

### Step 1: Check if normals are scalar multiples

Normal vectors:

$$
\vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 2, 2, 2 \rangle
$$

Check ratios:

$$
\frac{2}{1} = \frac{2}{1} = \frac{2}{1} = 2
$$

All ratios are equal ⇒ normals are scalar multiples ⇒ planes are **parallel**

### Step 2: Check if planes are coincident

Compare constants:

Plane 1: $D_1 = -3$  
Plane 2: $D_2 = -5$

Check ratio:

$$
\frac{D_2}{D_1} = \frac{-5}{-3} = \frac{5}{3}
$$

This does **not** match the scalar multiple (2) of the normals ⇒ **Planes are not coincident**

### Final Answer:

$$
\boxed{\text{The planes are parallel and distinct (no intersection).}}
$$

---

## Example 5: Application Problem
Two walls in a room are described by the planes:

$$
x + 2y - z - 4 = 0 \quad \text{and} \quad 2x - y + z - 5 = 0.
$$

Find the line where the two walls meet.

### Solution:
- The direction vector of the line of intersection is given by the cross product of the normal vectors of the planes:

  $$
  \vec{n}_1 = \langle 1, 2, -1 \rangle, \quad \vec{n}_2 = \langle 2, -1, 1 \rangle.
  $$

  Compute $\vec{d} = \vec{n}_1 \times \vec{n}_2$:

  $$
  \vec{d} = \begin{vmatrix}
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  1 & 2 & -1 \\
  2 & -1 & 1
  \end{vmatrix}.
  $$

  Expand the determinant:

  $$
  \vec{d} = \mathbf{i}((2)(1) - (-1)(-1)) - \mathbf{j}((1)(1) - (-1)(2)) + \mathbf{k}((1)(-1) - (2)(2)).
  $$

  Simplify:

  $$
  \vec{d} = \langle 1, -3, -5 \rangle.
  $$

- Find a specific point on the line by solving the system of equations formed by the two planes. Let $z = 0$ (arbitrary choice):

  $$
  x + 2y = 4, \quad 2x - y = 5.
  $$

  Solve the system:

  $$
  2x - y = 5 \implies y = 2x - 5.
  $$

  Substitute $y = 2x - 5$ into $x + 2y = 4$:

  $$
  x + 2(2x - 5) = 4 \implies x + 4x - 10 = 4 \implies 5x = 14 \implies x = \frac{14}{5}.
  $$

  Substitute $x = \frac{14}{5}$ into $y = 2x - 5$:

  $$
  y = 2\left(\frac{14}{5}\right) - 5 = \frac{28}{5} - \frac{25}{5} = \frac{3}{5}.
  $$

  So, a point on the line is $\left(\frac{14}{5}, \frac{3}{5}, 0\right)$.

- Write the vector equation of the line:

  $$
  \vec{r}(t) = \left\langle \frac{14}{5}, \frac{3}{5}, 0 \right\rangle + t\langle 1, -3, -5 \rangle.
  $$

Final answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \left\langle \frac{14}{5}, \frac{3}{5}, 0 \right\rangle + t\langle 1, -3, -5 \rangle.}
$$