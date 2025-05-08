+++
title = '7.4 Practice'
weight = 2
+++

---


#### Ex1.
Two vectors are given:
- $\vec{u} = (1, 2, -3)$,
- $\vec{v} = (4, -1, 2)$.

Find the cross product $\vec{u} \times \vec{v}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the Cartesian formula:

$$
\vec{u} \times \vec{v} = \langle u_2v_3 - u_3v_2, \; u_3v_1 - u_1v_3, \; u_1v_2 - u_2v_1 \rangle.
$$

Substitute the components of $\vec{u} = (1, 2, -3)$ and $\vec{v} = (4, -1, 2)$:

1. **i-component** ($u_2v_3 - u_3v_2$):

   $$
   (2)(2) - (-3)(-1) = 4 - 3 = 1.
   $$

2. **j-component** ($u_3v_1 - u_1v_3$):

   $$
   (-3)(4) - (1)(2) = -12 - 2 = -14.
   $$

3. **k-component** ($u_1v_2 - u_2v_1$):

   $$
   (1)(-1) - (2)(4) = -1 - 8 = -9.
   $$

Combine the components:

$$
\vec{u} \times \vec{v} = \langle 1, -14, -9 \rangle.
$$

**Answer**:  
The cross product is $ \boxed{\langle 1, -14, -9 \rangle} $.

</details>

---


#### Ex2.
Two vectors are given:
- $\vec{a} = (2, -3, 4)$,
- $\vec{b} = (-1, 5, -2)$.

Find a vector that is perpendicular to both $\vec{a}$ and $\vec{b}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the Cartesian formula:

$$
\vec{a} \times \vec{b} = \langle a_2b_3 - a_3b_2, \; a_3b_1 - a_1b_3, \; a_1b_2 - a_2b_1 \rangle.
$$

Substitute the components of $\vec{a} = (2, -3, 4)$ and $\vec{b} = (-1, 5, -2)$:

1. **i-component** ($a_2b_3 - a_3b_2$):

   $$
   (-3)(-2) - (4)(5) = 6 - 20 = -14.
   $$

2. **j-component** ($a_3b_1 - a_1b_3$):

   $$
   (4)(-1) - (2)(-2) = -4 + 4 = 0.
   $$

3. **k-component** ($a_1b_2 - a_2b_1$):

   $$
   (2)(5) - (-3)(-1) = 10 - 3 = 7.
   $$

Combine the components:

$$
\vec{a} \times \vec{b} = \langle -14, 0, 7 \rangle.
$$

**Answer**:  
A vector perpendicular to both $\vec{a}$ and $\vec{b}$ is $ \boxed{\langle -14, 0, 7 \rangle} $.

</details>

---


#### Ex3.
Two vectors are given:
- $\vec{p} = (3, 0, -2)$,
- $\vec{q} = (1, 4, 0)$.

Find the area of the parallelogram formed by these vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

First, compute the cross product $\vec{p} \times \vec{q}$ using the Cartesian formula:

$$
\vec{p} \times \vec{q} = \langle p_2q_3 - p_3q_2, \; p_3q_1 - p_1q_3, \; p_1q_2 - p_2q_1 \rangle.
$$

Substitute the components of $\vec{p} = (3, 0, -2)$ and $\vec{q} = (1, 4, 0)$:

1. **i-component** ($p_2q_3 - p_3q_2$):

   $$
   (0)(0) - (-2)(4) = 0 + 8 = 8.
   $$

2. **j-component** ($p_3q_1 - p_1q_3$):

   $$
   (-2)(1) - (3)(0) = -2 - 0 = -2.
   $$

3. **k-component** ($p_1q_2 - p_2q_1$):

   $$
   (3)(4) - (0)(1) = 12 - 0 = 12.
   $$

Combine the components:

$$
\vec{p} \times \vec{q} = \langle 8, -2, 12 \rangle.
$$

Next, compute the magnitude of the cross product:

$$
|\vec{p} \times \vec{q}| = \sqrt{(8)^2 + (-2)^2 + (12)^2} = \sqrt{64 + 4 + 144} = \sqrt{212} = 2\sqrt{53}.
$$

**Answer**:  
The area of the parallelogram is $ \boxed{2\sqrt{53}} $.

</details>

---


#### Ex4.
Two vectors are given:
- $\vec{u} = (2, -1, 3)$,
- $\vec{v} = (4, 0, -1)$.

Find the area of the triangle formed by these vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

First, compute the cross product $\vec{u} \times \vec{v}$ using the Cartesian formula:

$$
\vec{u} \times \vec{v} = \langle u_2v_3 - u_3v_2, \; u_3v_1 - u_1v_3, \; u_1v_2 - u_2v_1 \rangle.
$$

Substitute the components of $\vec{u} = (2, -1, 3)$ and $\vec{v} = (4, 0, -1)$:

1. **i-component** ($u_2v_3 - u_3v_2$):

   $$
   (-1)(-1) - (3)(0) = 1 - 0 = 1.
   $$

2. **j-component** ($u_3v_1 - u_1v_3$):

   $$
   (3)(4) - (2)(-1) = 12 + 2 = 14.
   $$

3. **k-component** ($u_1v_2 - u_2v_1$):

   $$
   (2)(0) - (-1)(4) = 0 + 4 = 4.
   $$

Combine the components:

$$
\vec{u} \times \vec{v} = \langle 1, -14, 4 \rangle.
$$

Next, compute the magnitude of the cross product:

$$
|\vec{u} \times \vec{v}| = \sqrt{(1)^2 + (-14)^2 + (4)^2} = \sqrt{1 + 196 + 16} = \sqrt{213}.
$$

The area of the triangle is half the magnitude of the cross product:

$$
\text{Area} = \frac{1}{2} |\vec{u} \times \vec{v}| = \frac{1}{2} \sqrt{213}.
$$

**Answer**:  
The area of the triangle is $ \boxed{\frac{\sqrt{213}}{2}} $.

</details>

---

## Wrapping Up

These practice problems cover a variety of scenarios involving the **Cartesian cross product**:
- Computing the cross product algebraically.
- Finding vectors perpendicular to two given vectors.
- Calculating areas of parallelograms and triangles.




<iframe src="https://script.google.com/macros/s/AKfycbzoh3CvYtyCEPLxDsWRiKI-WnjF3cHLbdlC_AHwd4CggFFzPnSCQSamiEiOUaH5DYVW1A/exec" width="80%" height="1500px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
