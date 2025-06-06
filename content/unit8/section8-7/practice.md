+++
title = '8.7 Practice'
weight = 2
+++

Solve the following problems to reinforce your understanding of intersections of three planes in 3D space. Click on the **"Solution"** dropdown to reveal the hidden solution.

---
## Ex1: Determine the Intersection

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + z = 2 \\
(\pi_3)\quad & x + y - z = 4
\end{aligned}
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

The following technique should only be used if you have checked and discovered that the following three are true: 

1.  $ \vec{n_1} \times \vec{n_2} \cdot \vec{n_3} =\neq 0 $

2.  None of the three planes are parallel.

3.  None of the three planes are coincidental.

We will use a **step-by-step elimination strategy** to solve this system.


### Step 1: Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$

Subtract $(\pi_2)$ from $(\pi_1)$:

$$
(x + y + z) - (x - y + z) = 6 - 2 \Rightarrow 2y = 4 \Rightarrow y = 2
$$

✅ Now we know $y = 2$


### Step 2: Eliminate $z$ from $(\pi_2)$ and $(\pi_3)$

Add $(\pi_2)$ and $(\pi_3)$:

$$
(x - y + z) + (x + y - z) = 2 + 4 \Rightarrow 2x = 6 \Rightarrow x = 3
$$

✅ Now we also know $x = 3$


### Step 3: Back-substitute to find $z$

Use $(\pi_1)$: $x + y + z = 6$

Substitute $x = 3$, $y = 2$:

$$
3 + 2 + z = 6 \Rightarrow z = 1
$$

✅ Found $z = 1$


### Final Answer:

$$
\boxed{\text{Point of intersection: } (3, 2, 1)}
$$

This system has a **unique solution** — the three planes intersect at a single point.

</details>

---

## Ex2 Determine the intersection: 

### System:
$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & 2x - y + z = 4 \\
(\pi_3)\quad & 3x + 2y - z = 10
\end{aligned}
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

We will follow the method:

1. Use only two planes to find the **line of intersection**
2. Express this line in **parametric form**
3. Plug into the **third plane**
4. Interpret the result
5. NOTE: this method does not require checking the value of $ \vec{n_1} \times \vec{n_2} \cdot \vec{n_3} $


### Step 1: Eliminate $z$ from $(\pi_1)$ and $(\pi_2)$

Add both equations:

$$
(x + y + z) + (2x - y + z) = 6 + 4 \Rightarrow 3x + 2z = 10 \quad \text{(Equation A)}
$$

✅ Only used $(\pi_1)$ and $(\pi_2)$


### Step 2: Let $x = t$, solve for $z$

From Equation A:
$$
3t + 2z = 10 \Rightarrow z = \frac{10 - 3t}{2}
$$


### Step 3: Plug into $(\pi_1)$ to solve for $y$

Use $(\pi_1): x + y + z = 6$

Substitute $x = t$, $z = \frac{10 - 3t}{2}$:

$$
\begin{aligned}
t + y + \frac{10 - 3t}{2} =& 6 \Rightarrow \text{Multiply all terms by 2:} \\
 2t + 2y + 10 - 3t =& 12 \\
 -t + 2y =& 2 \\
 2y =& t + 2 \\
 y =& \frac{t + 2}{2} \\
\end{aligned}
$$

✅ We now have a parametric line formed by $(\pi_1)$ and $(\pi_2)$


### Step 4: Parametric Form of the Line

$$
\boxed{
\begin{aligned}
x &= t \\
y &= \frac{t + 2}{2} \\
z &= \frac{10 - 3t}{2}
\end{aligned}
}
\quad \text{for all real } t
$$

This is the **line of intersection of $(\pi_1)$ and $(\pi_2)$**


### Step 5: Plug Into $(\pi_3)$: $3x + 2y - z = 10$

Now plug in the expressions:

$$
3t + 2\left( \frac{t + 2}{2} \right) - \frac{10 - 3t}{2} = 10
$$

Multiply everything by 2 to eliminate fractions:

$$
6t + 2(2+t)-(10-3t)=20
$$

$$
t = \frac{26}{11}
$$

✅ We get a specific value of $t$ ⇒ The line intersects the third plane at one point


### Step 6: Back-substitute to Find the Point

Use $t = \frac{26}{11}$:

- $x = t = \frac{26}{11}$
- $y = \frac{t + 2}{2} = \frac{\frac{26}{11} + 2}{2} = \frac{\frac{26 + 22}{11}}{2} = \frac{48}{22} = \frac{24}{11}$
- $z = \frac{10 - 3t}{2} = \frac{10 - \frac{78}{11}}{2} = \frac{\frac{110 - 78}{11}}{2} = \frac{32}{22} = \frac{16}{11}$


### ✅ Final Answer:

$$
\boxed{\text{Point of intersection: } \left( \frac{26}{11},\ \frac{24}{11},\ \frac{16}{11} \right)}
$$

This system has a **unique solution** — the three planes intersect at a single point.


### Tip

- Recall that if plugging into the third equation leads to:
  - A unique value of $t$ → **Point solution**
  - An identity like $0 = 0$ → **Line solution**
  - A contradiction like $0 = 5$ → **No solution**

</details>

---

## Ex3 Determine the intersection:

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + 2z = 4 \\
(\pi_3)\quad & 2x + 0y + 3z = 10
\end{aligned}
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

We will use only $(\pi_1)$ and $(\pi_2)$ to find the line of intersection, then plug into $(\pi_3)$ to check consistency.


### Step 1: Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$

Add both equations:

$$
(x + y + z) + (x - y + 2z) = 6 + 4 \Rightarrow 2x + 3z = 10 \quad \text{(Equation A)}
$$

✅ Only used $(\pi_1)$ and $(\pi_2)$


### Step 2: Let $x = t$, solve for $z$

From Equation A:
$$
2t + 3z = 10 \Rightarrow z = \frac{10 - 2t}{3}
$$


### Step 3: Plug into $(\pi_1)$ to solve for $y$

Use $(\pi_1): x + y + z = 6$

Substitute $x = t$, $z = \frac{10 - 2t}{3}$:

$$
t + y + \frac{10 - 2t}{3} = 6
\Rightarrow \text{Multiply all terms by 3:}
\Rightarrow 3t + 3y + 10 - 2t = 18
\Rightarrow t + 3y = 8
\Rightarrow y = \frac{8 - t}{3}
$$

✅ We now have a parametric line formed by $(\pi_1)$ and $(\pi_2)$


### Step 4: Parametric Form of the Line

$$
\boxed{
\begin{aligned}
x &= t \\
y &= \frac{8 - t}{3} \\
z &= \frac{10 - 2t}{3}
\end{aligned}
}
\quad \text{for all real } t
$$

This is the **line of intersection of $(\pi_1)$ and $(\pi_2)$**


### Step 5: Plug Into $(\pi_3)$: $2x + 0y + 3z = 10$

Now plug in the expressions:

$$
2t + 3\left( \frac{10 - 2t}{3} \right) = 10
\Rightarrow 2t + (10 - 2t) = 10
\Rightarrow 10 = 10
$$

 This is always true — the entire line lies on the third plane


###  Final Answer:

$$
\boxed{\text{The system has infinitely many solutions along the line.}}
$$

Parametric form:

$$
\begin{aligned}
x &= t \\
y &= \frac{8 - t}{3} \\
z &= \frac{10 - 2t}{3}
\end{aligned}
\quad \text{for all real } t
$$

</details>

---

## Ex4: Determine the Intersection

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + 2z = 4 \\
(\pi_3)\quad & 2x + 0y + 3z = 11
\end{aligned}
$$

<details>
<summary><strong id="solution-title">Solution</strong></summary>

We will again:
- Use only $(\pi_1)$ and $(\pi_2)$ to find the line of intersection
- Plug into $(\pi_3)$
- Show that it leads to a contradiction


### Step 1: Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$

As before:
$$
2x + 3z = 10 \quad \text{(Equation A)}
$$

Let $x = t$, so:
$$
z = \frac{10 - 2t}{3}, \quad y = \frac{8 - t}{3}
$$

✅ Same parametric line as in Example 3


### Step 2: Plug Into $(\pi_3)$: $2x + 0y + 3z = 11$

Now plug in the expressions:

$$
2t + 3\left( \frac{10 - 2t}{3} \right) = 11
\Rightarrow 2t + (10 - 2t) = 11
\Rightarrow 10 = 11
$$

❌ Contradiction!

This means the line formed by $(\pi_1)$ and $(\pi_2)$ does **not lie on** $(\pi_3)$, and they never intersect.


### ✅ Final Answer:

$$
\boxed{\text{No solution — inconsistent system.}}
$$

The three planes do not share any common point of intersection.

</details>

## Ex5
Three walls in a room are described by the planes:

$$
x + y + z = 6, \quad 2x - y + z = 4, \quad x + 3y - 2z = 2.
$$

Find the point where the three walls meet.

<details>
<summary><strong id="solution-title">Solution</strong></summary>

- Write the system of equations:

  $$
  \begin{aligned}
  x + y + z &= 6, \\
  2x - y + z &= 4, \\
  x + 3y - 2z &= 2.
  \end{aligned}
  $$

- Solve using substitution or elimination:
  1. From the first equation, solve for $z$:

     $$
     z = 6 - x - y.
     $$

  2. Substitute $z = 6 - x - y$ into the second and third equations:

     $$
     2x - y + (6 - x - y) = 4 \implies x - 2y = -2,
     $$

     $$
     x + 3y - 2(6 - x - y) = 2 \implies x + 3y - 12 + 2x + 2y = 2 \implies 3x + 5y = 14.
     $$

  3. Solve the system of two equations:

     $$
     x - 2y = -2, \quad 3x + 5y = 14.
     $$

     Multiply the first equation by 3:

     $$
     3x - 6y = -6.
     $$

     Subtract from the second equation:

     $$
     (3x + 5y) - (3x - 6y) = 14 - (-6) \implies 11y = 20 \implies y = \frac{20}{11}.
     $$

  4. Substitute $y = \frac{20}{11}$ into $x - 2y = -2$:

     $$
     x - 2\left(\frac{20}{11}\right) = -2 \implies x - \frac{40}{11} = -2 \implies x = \frac{-22}{11} + \frac{40}{11} = \frac{18}{11}.
     $$

  5. Substitute $x = \frac{18}{11}$ and $y = \frac{20}{11}$ into $z = 6 - x - y$:

     $$
     z = 6 - \frac{18}{11} - \frac{20}{11} = \frac{66}{11} - \frac{38}{11} = \frac{28}{11}.
     $$

Final answer:

$$
\boxed{\text{Point of intersection: } \left(\frac{18}{11}, \frac{20}{11}, \frac{28}{11}\right).}
$$

</details>



<iframe src="https://script.google.com/macros/s/AKfycbxPd6X6yN1pqxMdNI1vcRvPJTM8oQ6_gYvstnnT-2ya2hmvJjiZZz3q2hI67-Gg_TMp/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

