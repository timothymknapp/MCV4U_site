+++
title = '7.3 Examples'
weight = 1
+++


In this section, we’ll work through example problems that reinforce the concepts of the **Cartesian cross product**. These examples cover:
- Computing the cross product of two vectors.
- Finding the area of parallelograms and triangles using the cross product.
- Determining whether two vectors are parallel.
- Applying the cross product to solve practical problems, such as calculating torque.

---

## Example 1: Computing the Cross Product

#### Ex1.
Two vectors are given:
- $\vec{u} = (2, -1, 3)$,
- $\vec{v} = (4, 0, -1)$.

Find the cross product $\vec{u} \times \vec{v}$.

**Solution**:  
The formula for the cross product is:
$$
\vec{u} \times \vec{v} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_x & u_y & u_z \\
v_x & v_y & v_z
\end{vmatrix},
$$
where $\mathbf{i}, \mathbf{j}, \mathbf{k}$ are unit vectors along the $x$-, $y$-, and $z$-axes.

Expand the determinant:
$$
\vec{u} \times \vec{v} = \mathbf{i} \begin{vmatrix} u_y & u_z \\ v_y & v_z \end{vmatrix}
- \mathbf{j} \begin{vmatrix} u_x & u_z \\ v_x & v_z \end{vmatrix}
+ \mathbf{k} \begin{vmatrix} u_x & u_y \\ v_x & v_y \end{vmatrix}.
$$

Substitute the components:
$$
\vec{u} \times \vec{v} = \mathbf{i} \begin{vmatrix} -1 & 3 \\ 0 & -1 \end{vmatrix}
- \mathbf{j} \begin{vmatrix} 2 & 3 \\ 4 & -1 \end{vmatrix}
+ \mathbf{k} \begin{vmatrix} 2 & -1 \\ 4 & 0 \end{vmatrix}.
$$

Compute each minor:
$$
\begin{vmatrix} -1 & 3 \\ 0 & -1 \end{vmatrix} = (-1)(-1) - (3)(0) = 1,
$$
$$
\begin{vmatrix} 2 & 3 \\ 4 & -1 \end{vmatrix} = (2)(-1) - (3)(4) = -2 - 12 = -14,
$$
$$
\begin{vmatrix} 2 & -1 \\ 4 & 0 \end{vmatrix} = (2)(0) - (-1)(4) = 0 + 4 = 4.
$$

Combine the results:
$$
\vec{u} \times \vec{v} = \mathbf{i}(1) - \mathbf{j}(-14) + \mathbf{k}(4) = (1)\mathbf{i} + (14)\mathbf{j} + (4)\mathbf{k}.
$$

Write in component form:
$$
\vec{u} \times \vec{v} = (1, 14, 4).
$$

**Answer**:  
The cross product is $ \boxed{(1, 14, 4)} $.

---

## Example 2: Area of a Parallelogram

#### Ex2.
Two vectors are given:
- $\vec{a} = (3, 0, -2)$,
- $\vec{b} = (1, 4, 0)$.

Find the area of the parallelogram formed by these vectors.

**Solution**:  
The area of the parallelogram is the magnitude of the cross product:
$$
\text{Area} = |\vec{a} \times \vec{b}|.
$$

1. Compute the cross product:
   $$
   \vec{a} \times \vec{b} = \begin{vmatrix}
   \mathbf{i} & \mathbf{j} & \mathbf{k} \\
   3 & 0 & -2 \\
   1 & 4 & 0
   \end{vmatrix}.
   $$

   Expand the determinant:
   $$
   \vec{a} \times \vec{b} = \mathbf{i} \begin{vmatrix} 0 & -2 \\ 4 & 0 \end{vmatrix}
   - \mathbf{j} \begin{vmatrix} 3 & -2 \\ 1 & 0 \end{vmatrix}
   + \mathbf{k} \begin{vmatrix} 3 & 0 \\ 1 & 4 \end{vmatrix}.
   $$

   Compute each minor:
   $$
   \begin{vmatrix} 0 & -2 \\ 4 & 0 \end{vmatrix} = (0)(0) - (-2)(4) = 8,
   $$
   $$
   \begin{vmatrix} 3 & -2 \\ 1 & 0 \end{vmatrix} = (3)(0) - (-2)(1) = 2,
   $$
   $$
   \begin{vmatrix} 3 & 0 \\ 1 & 4 \end{vmatrix} = (3)(4) - (0)(1) = 12.
   $$

   Combine the results:
   $$
   \vec{a} \times \vec{b} = \mathbf{i}(8) - \mathbf{j}(2) + \mathbf{k}(12) = (8, -2, 12).
   $$

2. Compute the magnitude:
   $$
   |\vec{a} \times \vec{b}| = \sqrt{(8)^2 + (-2)^2 + (12)^2} = \sqrt{64 + 4 + 144} = \sqrt{212} = 2\sqrt{53}.
   $$

**Answer**:  
The area of the parallelogram is $ \boxed{2\sqrt{53}} $.

---

## Example 3: Area of a Triangle

#### Ex3.
Two vectors are given:
- $\vec{p} = (2, -1, 3)$,
- $\vec{q} = (4, 0, -1)$.

Find the area of the triangle formed by these vectors.

**Solution**:  
The area of the triangle is half the magnitude of the cross product:
$$
\text{Area} = \frac{1}{2} |\vec{p} \times \vec{q}|.
$$

From Example 1, we know:
$$
\vec{p} \times \vec{q} = (1, 14, 4).
$$

Compute the magnitude:
$$
|\vec{p} \times \vec{q}| = \sqrt{(1)^2 + (14)^2 + (4)^2} = \sqrt{1 + 196 + 16} = \sqrt{213}.
$$

Divide by 2:
$$
\text{Area} = \frac{1}{2} \sqrt{213}.
$$

**Answer**:  
The area of the triangle is $ \boxed{\frac{\sqrt{213}}{2}} $.

---

## Example 4: Testing for Parallel Vectors

#### Ex4.
Determine whether the vectors $\vec{u} = (2, -4, 6)$ and $\vec{v} = (-1, 2, -3)$ are parallel.

**Solution**:  
Two vectors are parallel if their cross product is the zero vector:
$$
\vec{u} \times \vec{v} = \mathbf{0}.
$$

Compute the cross product:
$$
\vec{u} \times \vec{v} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & -4 & 6 \\
-1 & 2 & -3
\end{vmatrix}.
$$

Expand the determinant:
$$
\vec{u} \times \vec{v} = \mathbf{i} \begin{vmatrix} -4 & 6 \\ 2 & -3 \end{vmatrix}
- \mathbf{j} \begin{vmatrix} 2 & 6 \\ -1 & -3 \end{vmatrix}
+ \mathbf{k} \begin{vmatrix} 2 & -4 \\ -1 & 2 \end{vmatrix}.
$$

Compute each minor:
$$
\begin{vmatrix} -4 & 6 \\ 2 & -3 \end{vmatrix} = (-4)(-3) - (6)(2) = 12 - 12 = 0,
$$
$$
\begin{vmatrix} 2 & 6 \\ -1 & -3 \end{vmatrix} = (2)(-3) - (6)(-1) = -6 + 6 = 0,
$$
$$
\begin{vmatrix} 2 & -4 \\ -1 & 2 \end{vmatrix} = (2)(2) - (-4)(-1) = 4 - 4 = 0.
$$

Combine the results:
$$
\vec{u} \times \vec{v} = \mathbf{i}(0) - \mathbf{j}(0) + \mathbf{k}(0) = (0, 0, 0).
$$

Since the cross product is the zero vector, the vectors are parallel.

**Answer**:  
The vectors are $ \boxed{\text{parallel}} $.

---

## Example 5: Torque Calculation

#### Ex5.
A force $\vec{F} = (3, -2, 4)$ acts at a point $\vec{r} = (1, 2, -1)$. Calculate the torque $\vec{\tau} = \vec{r} \times \vec{F}$.

**Solution**:  
The formula for torque is:
$$
\vec{\tau} = \vec{r} \times \vec{F}.
$$

Compute the cross product:
$$
\vec{\tau} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
1 & 2 & -1 \\
3 & -2 & 4
\end{vmatrix}.
$$

Expand the determinant:
$$
\vec{\tau} = \mathbf{i} \begin{vmatrix} 2 & -1 \\ -2 & 4 \end{vmatrix}
- \mathbf{j} \begin{vmatrix} 1 & -1 \\ 3 & 4 \end{vmatrix}
+ \mathbf{k} \begin{vmatrix} 1 & 2 \\ 3 & -2 \end{vmatrix}.
$$

Compute each minor:
$$
\begin{vmatrix} 2 & -1 \\ -2 & 4 \end{vmatrix} = (2)(4) - (-1)(-2) = 8 - 2 = 6,
$$
$$
\begin{vmatrix} 1 & -1 \\ 3 & 4 \end{vmatrix} = (1)(4) - (-1)(3) = 4 + 3 = 7,
$$
$$
\begin{vmatrix} 1 & 2 \\ 3 & -2 \end{vmatrix} = (1)(-2) - (2)(3) = -2 - 6 = -8.
$$

Combine the results:
$$
\vec{\tau} = \mathbf{i}(6) - \mathbf{j}(7) + \mathbf{k}(-8) = (6, -7, -8).
$$

**Answer**:  
The torque is $ \boxed{(6, -7, -8)} $.

---

