+++
title = '8.6 Practice'
weight = 2
+++


Solve the following problems to reinforce your understanding of intersections of two planes in 3D space. Click on the **"Solution"** dropdown to reveal the hidden solution.

---

## Ex1: Intersection of Two Planes

Find the line of intersection between the planes:

$$
x + y + z = 6 \quad \text{and} \quad 2x - y + z = 4
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

### Step 1: Check if planes are parallel

Normal vectors:

$$
\vec{n}_1 = \langle 1, 1, 1 \rangle, \quad \vec{n}_2 = \langle 2, -1, 1 \rangle
$$

Check ratios of components:

$$
\frac{2}{1} = 2,\quad \frac{-1}{1} = -1,\quad \frac{1}{1} = 1
$$

Ratios are not equal ⇒ **Planes are not parallel**, so they intersect along a line.


### Step 2: Eliminate one variable

We are given:

$$
(1)\quad x + y + z = 6 \\
(2)\quad 2x - y + z = 4
$$

Subtract equation (1) from equation (2):

$$
(2x - y + z) - (x + y + z) = 4 - 6 \Rightarrow x - 2y = -2 \quad \text{(Equation A)}
$$


### Step 3: Set one variable as the parameter

Let $y = t$

From Equation A:

$$
x - 2t = -2 \Rightarrow x = 2t - 2
$$

Now substitute both $x$ and $y = t$ into equation (1) to solve for $z$:

$$
(2t - 2) + t + z = 6 \Rightarrow 3t - 2 + z = 6 \Rightarrow z = 8 - 3t
$$


### Step 4: Write parametric and vector equations

Now we have:

$$
x = 2t - 2, \quad y = t, \quad z = 8 - 3t
$$

Vector form:

$$
\vec{r}(t) = \langle -2, 0, 8 \rangle + t\langle 2, 1, -3 \rangle
$$

You can also use any specific point on the line. If $t = 0$, point is $\left(-2, 0, 8\right)$, and direction vector is $\langle 2, 1, -3 \rangle$


### ✅ Final Answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \langle -2, 0, 8 \rangle + t\langle 2, 1, -3 \rangle}
$$

</details>

---

## Ex2: Relationship Between Two Planes

Determine whether the planes:

$$
2x - 3y + z - 6 = 0 \quad \text{and} \quad 4x - 6y + 2z - 12 = 0
$$

intersect. If not, explain why.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

### Step 1: Check if normals are scalar multiples

Normal vectors:

$$
\vec{n}_1 = \langle 2, -3, 1 \rangle, \quad \vec{n}_2 = \langle 4, -6, 2 \rangle
$$

Check ratios:

$$
\frac{4}{2} = 2,\quad \frac{-6}{-3} = 2,\quad \frac{2}{1} = 2
$$

All ratios match ⇒ **Normals are scalar multiples** ⇒ Planes are either parallel or coincident.


### Step 2: Check if planes are coincident

Compare constants:

Plane 1: $D_1 = -6$  
Plane 2: $D_2 = -12$

Ratio of constants:

$$
\frac{D_2}{D_1} = \frac{-12}{-6} = 2
$$

This matches the scalar multiple ⇒ **Planes are coincident**


### ✅ Final Answer:

$$
\boxed{\text{The planes coincide (infinite number of solutions).}}
$$

</details>

## Ex3: Relationship Between Two Planes

Determine whether the planes:

$$
x + 2y - z - 5 = 0 \quad \text{and} \quad 2x + 4y - 2z - 10 = 0
$$

intersect. If not, explain why.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

### Step 1: Check if normals are scalar multiples

Normal vectors:

$$
\vec{n}_1 = \langle 1, 2, -1 \rangle, \quad \vec{n}_2 = \langle 2, 4, -2 \rangle
$$

Check ratios:

$$
\frac{2}{1} = 2,\quad \frac{4}{2} = 2,\quad \frac{-2}{-1} = 2
$$

All ratios match ⇒ **Normals are scalar multiples** ⇒ Planes are either parallel or coincident.


### Step 2: Check if planes are coincident

Compare constants:

Plane 1: $D_1 = -5$  
Plane 2: $D_2 = -10$

Ratio of constants:

$$
\frac{D_2}{D_1} = \frac{-10}{-5} = 2
$$

This matches the scalar multiple ⇒ **Planes are coincident**


### ✅ Final Answer:

$$
\boxed{\text{The planes coincide (infinite number of solutions).}}
$$

</details>

---

## Ex4: Intersection of Two Planes

Two walls in a room are described by the planes:

$$
x - y + z - 2 = 0 \quad \text{and} \quad 2x + y - z - 3 = 0
$$

Find the line where the two walls meet.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

### Step 1: Check if planes are parallel

Normal vectors:

$$
\vec{n}_1 = \langle 1, -1, 1 \rangle, \quad \vec{n}_2 = \langle 2, 1, -1 \rangle
$$

Check ratios of components:

$$
\frac{2}{1} = 2,\quad \frac{1}{-1} = -1,\quad \frac{-1}{1} = -1
$$

Ratios are not equal ⇒ **Planes are not parallel**, so they intersect along a line.


### Step 2: Eliminate one variable

We are given:

$$
(1)\quad x - y + z = 2 \\
(2)\quad 2x + y - z = 3
$$

Add equations (1) and (2):

$$
(x - y + z) + (2x + y - z) = 2 + 3 \Rightarrow 3x = 5 \Rightarrow x = \frac{5}{3}
$$

Now substitute $x = \frac{5}{3}$ into equation (1):

$$
\frac{5}{3} - y + z = 2 \Rightarrow -y + z = 2 - \frac{5}{3} = \frac{1}{3}
\Rightarrow z = y + \frac{1}{3}
$$


### Step 3: Set one variable as the parameter

Let $y = t$, then:

$$
z = t + \frac{1}{3}, \quad x = \frac{5}{3}
$$

### Step 4: Write parametric and vector equations

Now we have:

$$
x = \frac{5}{3}, \quad y = t, \quad z = t + \frac{1}{3}
$$

Vector form:

$$
\vec{r}(t) = \left\langle \frac{5}{3}, 0, \frac{1}{3} \right\rangle + t\langle 0, 1, 1 \rangle
$$

You can also scale the direction vector for simplicity, e.g., use $\langle 0, 3, 3 \rangle$.


### ✅ Final Answer:

$$
\boxed{\text{Vector equation: } \vec{r}(t) = \left\langle \frac{5}{3}, 0, \frac{1}{3} \right\rangle + t\langle 0, 1, 1 \rangle}
$$

</details>


<iframe src="https://script.google.com/macros/s/AKfycbwVjMPvw9jAGnUMLse04rcaWkXdzNY92u1qmqUfgQZhvdl8RU7yTAuEUixId5ICl7aEPQ/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

