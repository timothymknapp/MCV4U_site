+++
title = '8.7 Examples'
weight = 1
+++


This page provides detailed worked-out examples to help you understand how to determine the intersection of three planes in 3D space.

The **first four** examples use the Crazy Line Finding Technique (CLFT)  Each demonstrates a different type of solution:

1. **Point Solution**
2. **Line Solution (distinct planes)**
3. **No Solution**

Each example follows the same strategy:
- Use CLFT with tow of the equations
    - Eliminate one variable from two equations.
    - Express the remaining variables parametrically as a line.
- Substitute the found line into the third equation to determine the nature of the solution.
- This technique does not require that you check the cross and dot product of the normals.
---

## Example 1: Point Solution

### System:
$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & 2x - y + z = 3 \\
(\pi_3)\quad & x + 2y - z = 1
\end{aligned}
$$

### Step-by-step:

1. Eliminate $z$ from by subtracting $\pi_1$ from $\pi_2$:  

   $$
   x - 2y = -3 \quad \text{(equation A)}
   $$

2. Let $y=t$ in equationA, then isolate $x$.  

   $$
   \begin{aligned}
   x - 2t &= -3 \\
   x &= 2t - 3
   \end{aligned}
   $$

3. Plug $x = 2t - 3$ and $y=t$ into either $\pi_1$ or $\pi_2$ and solve for $z$ (be sure not to use $\pi_3$ yet)

   $$
   \begin{aligned}
   x + y + z &= 6  \\
   2t - 3 + t +z &=6 \\
   z &= -3t+9
   \end{aligned}
   $$

4. Collect up your parametric line solution to $\pi_1$ and $\pi_2$:  

  $$
  \begin{aligned}
  &x= 2t - 3\\
  &y=t\\
  &z= -3t+9
  \end{aligned}
  $$

5.  Plug the above line into $\pi_3$. ( you finally use $\pi_3$ !)

  $$
  \begin{aligned}
  x + 2y - z &= 1 \\
  2t - 3 + 2t -(-3t+9) &=1 \\
  7t&=13 \\
  t&=\frac{13}{7}
  \end{aligned}
  $$

6.  Since t equal a real number we have a point solution $(x,y,z)$. Use $t=\frac{13}{7}$ in our above line to find the point.

  $$
  \begin{aligned}
  x &= 2t - 3 = 2\left(\frac{13}{7}\right) - 3 =\frac{5}{7} \\
  y & = t =\frac{13}{7} \\
  z &= -3t+9 = -3\left(\frac{13}{7}\right) +9 =\frac{24}{7}
  \end{aligned}
  $$

This is a **point solution**.

Final answer:

$$
\boxed{\text{Point of intersection: } \left(\frac{5}{7}, \frac{13}{7}, \frac{24}{7}\right).}
$$


---

##  Example 2: Point Solution

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + 2z = 4 \\
(\pi_3)\quad & 2x + y + 3z = 10
\end{aligned}
$$

### Step-by-step:

1. Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$:  
   
   $$
   2x + 3z = 10 \quad \text{(equationA)}
   $$

2. Let $x=t$ in equationA, then isolate $z$.  

   $$
   \begin{aligned}
   2t + 3z &= 10 \\
   z&=\frac{10-2t}{3}
   \end{aligned}
   $$

3. Plug $x = t$ and $z=\frac{10-2t}{3}$ into either $\pi_1$ or $\pi_2$ and solve for $y$ (be sure not to use $\pi_3$ yet)

   $$
   \begin{aligned}
   x + y + z &= 6  \\
   t + y + \left( \frac{10-2t}{3} \right) &=6 \\
   3t + 3y + 10-2t &=18 \\
   y&= \frac{-t*8}{3}
   \end{aligned}
   $$

4. Collect up your parametric line solution to $\pi_1$ and $\pi_2$:  

  $$
  \begin{aligned}
  &x= t\\
  &y=\frac{-t+8}{3}\\
  &z= \frac{10-2t}{3}
  \end{aligned}
  $$

5.  Plug the above line into $\pi_3$. ( you finally use $\pi_3$ !)

  $$
  \begin{aligned}
  2x + y + 3z &= 10 \\
  2t +\frac{-t+8}{3}+3\left( \frac{10-2t}{3} right) &=10 \\
  6t -t + 8 +3(10-2t)&= 10 \\
  t&=8

6.  Since t equal a real number we have a point solution $(x,y,z)$. Use $t=8$ in our above line to find the point.

  $$
  \begin{aligned}
  &x= t = 8\\
  &y=\frac{-t+8}{3} = \frac{-8+8}{3} = 0\\
  &z= \frac{10-2(8)}{3} = -2
  \end{aligned}
  $$

This is a **point solution**.

Final answer:

$$
\boxed{\text{Point of intersection: } \left(8, 0, -2\right).}
$$

---

##  Example 3: Line Solution

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + 2z = 4 \\
(\pi_3)\quad & 2x + 0y + 3z = 10
\end{aligned}
$$

### Step-by-step:

1. Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$:  
   
   $$
   2x + 3z = 10 \quad \text{(equation A)}
   $$

2. Let $x = t$ in equation A, then isolate $z$.  

   $$
   \begin{aligned}
   2t + 3z &= 10 \\
   z &= \frac{10 - 2t}{3}
   \end{aligned}
   $$

3. Plug $x = t$ and $z = \frac{10 - 2t}{3}$ into either $\pi_1$ or $\pi_2$ and solve for $y$ (be sure not to use $\pi_3$ yet)

   $$
   \begin{aligned}
   x + y + z &= 6 \\
   t + y + \left( \frac{10 - 2t}{3} \right) &= 6 \\
   3t + 3y + 10 - 2t &= 18 \\
   y &= \frac{8 - t}{3}
   \end{aligned}
   $$

4. Collect up your parametric line solution to $\pi_1$ and $\pi_2$:  

   $$
   \begin{aligned}
   &x = t \\
   &y = \frac{8 - t}{3} \\
   &z = \frac{10 - 2t}{3}
   \end{aligned}
   $$

5.  Plug the above line into $\pi_3$. (you finally use $\pi_3$ !)

   $$
   \begin{aligned}
   2x + 0y + 3z &= 10 \\
   2t + 3\left( \frac{10 - 2t}{3} \right) &= 10 \\
   2t + (10 - 2t) &= 10 \\
   10 &= 10
   \end{aligned}
   $$

This is always true — there are no restrictions on $t$

6. Since the final result is $10 = 10$, this means the entire line lies on the third plane. Therefore, the system has **infinitely many solutions** along a line.

This is a **line solution**.

Final answer:

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

##  Example 4: No Solution (Triangular Prism)

### System:
$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & x - y + 2z = 4 \\
(\pi_3)\quad & 2x + 0y + 3z = 9
\end{aligned}
$$

This system represents three planes that form a **triangular prism** — they do not intersect at any common point.

---

### Step-by-step:

1. Eliminate $y$ from $(\pi_1)$ and $(\pi_2)$:  

   $$
   2x + 3z = 10 \quad \text{(Equation A)}
   $$

2. Let $x = t$ in Equation A, then isolate $z$:  

   $$
   \begin{aligned}
   2t + 3z &= 10 \\
   z &= \frac{10 - 2t}{3}
   \end{aligned}
   $$

3. Plug $x = t$ and $z = \frac{10 - 2t}{3}$ into either $\pi_1$ or $\pi_2$ and solve for $y$ (be sure not to use $\pi_3$ yet)

   $$
   \begin{aligned}
   x + y + z &= 6 \\
   t + y + \left( \frac{10 - 2t}{3} \right) &= 6 \\
   3t + 3y + 10 - 2t &= 18 \\
   y &= \frac{8 - t}{3}
   \end{aligned}
   $$

4. Collect up your parametric line solution to $\pi_1$ and $\pi_2$:  

   $$
   \begin{aligned}
   &x = t \\
   &y = \frac{8 - t}{3} \\
   &z = \frac{10 - 2t}{3}
   \end{aligned}
   $$

5.  Plug the above line into $\pi_3$. (you finally use $\pi_3$ !)

   $$
   \begin{aligned}
   2x + 0y + 3z &= 9 \\
   2t + 3\left( \frac{10 - 2t}{3} \right) &= 9 \\
   2t + (10 - 2t) &= 9 \\
   10 &= 9
   \end{aligned}
   $$

 This is a contradiction — it's never true

6. Since we end up with $10 = 9$, which is false, this means the line formed by $\pi_1$ and $\pi_2$ does **not** lie on $\pi_3$

Therefore, there is **no common point of intersection**

This system has:

$$
\boxed{\text{No solution}}
$$

## 📐 Geometric Interpretation

The three planes form a **triangular prism**, meaning:

- Each pair of planes intersects along a **line**
- These lines are **parallel**
- There is **no common point** shared by all three planes

This configuration is called an **inconsistent system**

---
---

**The below examples use different problem solving approaches than the preivous 4 examples**

## Ex5: Single Point Solution: Using a mix of Elimination and Substitution.

The following technique should only be used if the following three are true: 

1.  $ \vec{n_1} \times \vec{n_2} \cdot \vec{n_3} =\neq 0 $

2.  None if the three planes are parallel.

3.  None of the three planes are coincidental.

Find the point of intersection of the three planes:

$$
x + y + z = 6, \quad 2x - y + z = 4, \quad x + 3y - 2z = 2.
$$

### Solution:
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

---

## Ex6: Single Point Solution, using only substutution.

Given the system of equations:

$$
\begin{aligned}
(1)\quad & x + y + z = 6 \\
(2)\quad & 2x - y + z = 4 \\
(3)\quad & 3x + 2y - z = 8
\end{aligned}
$$

The following technique should only be used if th following three are true: 

1.  $ \vec{n_1} \times \vec{n_2} \cdot \vec{n_3} =\neq 0 $

2.  None if the three planes are parallel.

3.  None of the three planes are coincidental.

#### Step 1: Solve for one variable 

From Equation (1):  
$$
z = 6 - x - y
$$

#### Step 2: Substitute into Equation (2)

$$
2x - y + (6 - x - y) = 4 
$$

$$
x - 2y + 6 = 4
$$

$$
x = 2y - 2
$$

#### Step 3: Plug both into Equation (3)

Substitute $ x = 2y - 2 $ and $ z = 6 - x - y $ into Equation (3):

$$
3x + 2y - z = 8
$$

$$
3(2y - 2) + 2y - (6 - (2y - 2) - y) = 8
$$

Simplify step-by-step:

$$
6y - 6 + 2y - (6 - 2y + 2 - y) = 8
$$

$$
8y - 6 - (8 - 3y) = 8
$$

$$
8y - 6 - 8 + 3y = 8
$$

$$
11y - 14 = 8 
$$

$$
y = 2
$$

Now find $ x $ and $ z $:

$$
x = 2(2) - 2 = 2,\quad z = 6 - 2 - 2 = 2
$$

### ✅ Final Answer

The three planes intersect at a single point:

$$
\boxed{(2, 2, 2)}
$$

---

## Ex7: Solving a System Using Exclusivly Elimination (Point Solution)

### Given System:
$$
\begin{aligned}
(1)\quad & x + y + z = 6 \\
(2)\quad & 2x - y + z = 4 \\
(3)\quad & 3x + 2y - z = 10
\end{aligned}
$$

The following technique should only be used if th following three are true: 

1.  $ \vec{n_1} \times \vec{n_2} \cdot \vec{n_3} =\neq 0 $

2.  None if the three planes are parallel.

3.  None of the three planes are coincidental.

We will solve this system by eliminating variables step-by-step from different pairs of equations, then back-substitute to find all three variables.

---

### Step 1: Eliminate $z$ from equations (1) and (2)

Add equations (1) and (2):

$$
(x + y + z) + (2x - y + z) = 6 + 4 \Rightarrow 3x + 2z = 10 \quad \text{(Equation A)}
$$

---

### Step 2: Eliminate $z$ from equations (1) and (3)

Add equations (1) and (3):

$$
(x + y + z) + (3x + 2y - z) = 6 + 10 \Rightarrow 4x + 3y = 16 \quad \text{(Equation B)}
$$

---

### Step 3: Eliminate $z$ from equations (2) and (3)

Add equations (2) and (3):

$$
(2x - y + z) + (3x + 2y - z) = 4 + 10 \Rightarrow 5x + y = 14 \quad \text{(Equation C)}
$$

Now we have:

- Equation A: $3x + 2z = 10$
- Equation B: $4x + 3y = 16$
- Equation C: $5x + y = 14$

---

### Step 4: Eliminate $y$ between Equations B and C

Start with:

- Equation B: $4x + 3y = 16$
- Equation C: $5x + y = 14$

Multiply Equation C by 3:

$$
15x + 3y = 42 \quad \text{(Equation D)}
$$

Now subtract Equation B from Equation D:

$$
(15x + 3y) - (4x + 3y) = 42 - 16 \Rightarrow 11x = 26 \Rightarrow x = \frac{26}{11}
$$

---

### Step 5: Back-substitute to find $y$

Use Equation C: $5x + y = 14$

$$
5\left(\frac{26}{11}\right) + y = 14 \Rightarrow \frac{130}{11} + y = 14
\Rightarrow y = 14 - \frac{130}{11} = \frac{154 - 130}{11} = \frac{24}{11}
$$

---

### Step 6: Back-substitute to find $z$

Use Equation A: $3x + 2z = 10$

$$
3\left(\frac{26}{11}\right) + 2z = 10 \Rightarrow \frac{78}{11} + 2z = 10
\Rightarrow 2z = 10 - \frac{78}{11} = \frac{110 - 78}{11} = \frac{32}{11}
\Rightarrow z = \frac{16}{11}
$$

---

## ✅ Final Answer:

$$
\boxed{
\begin{aligned}
x &= \frac{26}{11} \\
y &= \frac{24}{11} \\
z &= \frac{16}{11}
\end{aligned}
}
$$

This is a **point solution** — the three planes intersect at a single point.

---

## Ex 8: Infinite Solutions (Coincident Planes)

### Problem:
Determine whether the following planes intersect. If so, describe the nature of the solution.

$$
\begin{aligned}
(\pi_1)\quad & x + y + z = 6 \\
(\pi_2)\quad & 2x + 2y + 2z = 12 \\
(\pi_3)\quad & 3x + 3y + 3z = 18
\end{aligned}
$$

---

### Step-by-step Solution:

#### Step 1: Compare the normal vectors of the planes

The general form of a plane is:
$$
Ax + By + Cz = D
$$
with normal vector $\vec{n} = \langle A, B, C \rangle$

So we find the normals:

- $(\pi_1)$: $\vec{n}_1 = \langle 1, 1, 1 \rangle$
- $(\pi_2)$: $\vec{n}_2 = \langle 2, 2, 2 \rangle = 2\cdot\vec{n}_1$
- $(\pi_3)$: $\vec{n}_3 = \langle 3, 3, 3 \rangle = 3\cdot\vec{n}_1$

✅ All three normal vectors are scalar multiples of each other ⇒ The planes are either **parallel or coincident**

---

#### Step 2: Check if the planes coincide by comparing constants

To determine if the planes are **coincident**, compare the ratios of the constants on both sides:

$$
\frac{D_2}{D_1} = \frac{12}{6} = 2, \quad \frac{D_3}{D_1} = \frac{18}{6} = 3
$$

Also recall:

- $\vec{n}_2 = 2\cdot\vec{n}_1$, $D_2 = 2\cdot D_1$
- $\vec{n}_3 = 3\cdot\vec{n}_1$, $D_3 = 3\cdot D_1$

✅ Since the constants scale in the same way as the normal vectors, all three equations represent the **same plane**

---

#### Step 3: Confirm with a point

Pick a point that satisfies $(\pi_1)$: $x + y + z = 6$

Try $(6, 0, 0)$:

- Plug into $(\pi_2)$: $2(6) + 2(0) + 2(0) = 12$ ✅
- Plug into $(\pi_3)$: $3(6) + 3(0) + 3(0) = 18$ ✅

This confirms the point lies on all three planes.

---

### Final Conclusion:

All three planes are **coincident** — they are the same plane.

Therefore, the system has:

$$
\boxed{\text{Infinitely many solutions}}
$$
---

