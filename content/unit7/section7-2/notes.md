+++
title = '7.2 Examples'
weight = 1
+++


In this section, we’ll work through example problems that reinforce the concepts of the **Cartesian dot product**. These examples cover:
- Computing the dot product algebraically.
- Finding the angle between two vectors.
- Testing for orthogonality.
- Applying the dot product to solve practical problems.

---

## Example 1: Computing the Dot Product Algebraically

#### Ex1.
Two vectors are given:
- $\vec{u} = (3, -2)$,
- $\vec{v} = (4, 5)$.

Find the dot product $\vec{u} \cdot \vec{v}$.

**Solution**:  
The formula for the dot product is:
$$
\vec{u} \cdot \vec{v} = u_x v_x + u_y v_y.
$$

Substitute the components:
$$
\vec{u} \cdot \vec{v} = (3)(4) + (-2)(5) = 12 - 10 = 2.
$$

**Answer**:  
The dot product is $ \boxed{2} $.

---

## Example 2: Finding the Angle Between Two Vectors

#### Ex2.
Two vectors are given:
- $\vec{a} = (1, 2)$,
- $\vec{b} = (-3, 4)$.

Find the angle $\theta$ between the vectors.

**Solution**:  
The formula for the angle between two vectors is:
$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}.
$$

1. Compute the dot product:
   $$
   \vec{a} \cdot \vec{b} = (1)(-3) + (2)(4) = -3 + 8 = 5.
   $$

2. Compute the magnitudes:
   $$
   |\vec{a}| = \sqrt{(1)^2 + (2)^2} = \sqrt{1 + 4} = \sqrt{5},
   $$
   $$
   |\vec{b}| = \sqrt{(-3)^2 + (4)^2} = \sqrt{9 + 16} = \sqrt{25} = 5.
   $$

3. Substitute into the formula:
   $$
   \cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{5}{\sqrt{5} \cdot 5} = \frac{5}{5\sqrt{5}} = \frac{1}{\sqrt{5}}.
   $$

4. Solve for $\theta$:
   $$
   \theta = \cos^{-1}\left(\frac{1}{\sqrt{5}}\right) \approx 63.4^\circ.
   $$

**Answer**:  
The angle between the vectors is approximately $ \boxed{63.4^\circ} $.

---

## Example 3: Testing for Orthogonality

#### Ex3.
Two vectors are given:
- $\vec{p} = (2, -3)$,
- $\vec{q} = (6, 4)$.

Determine whether the vectors are orthogonal.

**Solution**:  
Two vectors are orthogonal if their dot product is zero:
$$
\vec{p} \cdot \vec{q} = p_x q_x + p_y q_y.
$$

Substitute the components:
$$
\vec{p} \cdot \vec{q} = (2)(6) + (-3)(4) = 12 - 12 = 0.
$$

Since the dot product is zero, the vectors are orthogonal.

**Answer**:  
The vectors are $ \boxed{\text{orthogonal}} $.

---

## Example 4: Work Done by a Force

#### Ex4.
A force $\vec{F} = (5, 3)$ acts on an object, causing a displacement $\vec{d} = (2, -4)$. Calculate the work done by the force.

**Solution**:  
The formula for work is:
$$
W = \vec{F} \cdot \vec{d}.
$$

Compute the dot product:
$$
W = (5)(2) + (3)(-4) = 10 - 12 = -2.
$$

The negative sign indicates that the force opposes the direction of displacement.

**Answer**:  
The work done is $ \boxed{-2 \, \text{J}} $.

---
