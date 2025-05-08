+++
title = '7.5 Examples'
weight = 1
+++

In this section, we’ll work through examples that demonstrate how the dot product and cross product are applied in real-world scenarios. Each example focuses on a specific application, such as work, torque, lighting, and more.

---

## Example 1: Computing Work (Dot Product)

#### Ex1.
A force $\vec{F} = \langle 10, 5, 0 \rangle$ moves an object along a displacement $\vec{d} = \langle 4, 3, 0 \rangle$. Find the work done.

**Solution**:  
The formula for work is:

$$
W = \vec{F} \cdot \vec{d}.
$$

Substitute the components of $\vec{F} = \langle 10, 5, 0 \rangle$ and $\vec{d} = \langle 4, 3, 0 \rangle$:

$$
\vec{F} \cdot \vec{d} = (10)(4) + (5)(3) + (0)(0) = 40 + 15 + 0 = 55.
$$

**Answer**:  
The work done is $ \boxed{55 \, \text{J}} $.

---

## Example 2: Work at an Angle (Dot Product)

#### Ex2.
A person pulls a sled with a force of $50 \, \text{N}$ at an angle of $30^\circ$ above the horizontal. The sled moves $12 \, \text{m}$ horizontally. Find the work done.

**Solution**:  
The formula for work is:

$$
W = |\vec{F}||\vec{d}|\cos\theta.
$$

Substitute the given values:
- $|\vec{F}| = 50 \, \text{N}$,
- $|\vec{d}| = 12 \, \text{m}$,
- $\theta = 30^\circ$.

Compute:

$$
W = (50)(12)\cos(30^\circ) = (50)(12)\left(\frac{\sqrt{3}}{2}\right) = 300\sqrt{3}.
$$

**Answer**:  
The work done is $ \boxed{300\sqrt{3} \, \text{J}} $.

---

## Example 3: Torque in 3D (Cross Product)

#### Ex3.
Let $\vec{r} = \langle 2, 0, 0 \rangle$ and $\vec{F} = \langle 0, 5, 0 \rangle$. Compute the torque vector $\vec{\tau} = \vec{r} \times \vec{F}$.

**Solution**:  
The formula for torque is:

$$
\vec{\tau} = \vec{r} \times \vec{F}.
$$

Using the Cartesian formula:

$$
\vec{\tau} = \langle r_2F_3 - r_3F_2, \; r_3F_1 - r_1F_3, \; r_1F_2 - r_2F_1 \rangle.
$$

Substitute the components of $\vec{r} = \langle 2, 0, 0 \rangle$ and $\vec{F} = \langle 0, 5, 0 \rangle$:

1. **i-component** ($r_2F_3 - r_3F_2$):

   $$
   (0)(0) - (0)(5) = 0.
   $$

2. **j-component** ($r_3F_1 - r_1F_3$):

   $$
   (0)(0) - (2)(0) = 0.
   $$

3. **k-component** ($r_1F_2 - r_2F_1$):

   $$
   (2)(5) - (0)(0) = 10.
   $$

Combine the components:

$$
\vec{\tau} = \langle 0, 0, 10 \rangle.
$$

**Answer**:  
The torque vector is $ \boxed{\langle 0, 0, 10 \rangle} $.

---

## Example 4: Torque with Angle (Cross Product)

#### Ex4.
A wrench of length $0.4 \, \text{m}$ is turned with a force of $50 \, \text{N}$ at an angle of $90^\circ$. What is the magnitude of the torque?

**Solution**:  
The formula for torque magnitude is:

$$
|\vec{\tau}| = |\vec{r}||\vec{F}|\sin\theta.
$$

Substitute the given values:
- $|\vec{r}| = 0.4 \, \text{m}$,
- $|\vec{F}| = 50 \, \text{N}$,
- $\theta = 90^\circ$.

Compute:

$$
|\vec{\tau}| = (0.4)(50)\sin(90^\circ) = (0.4)(50)(1) = 20.
$$

**Answer**:  
The magnitude of the torque is $ \boxed{20 \, \text{N·m}} $.

---

## Example 5: Cosine Similarity (Dot Product)

#### Ex5.
Given the two vocabulary vectors $\vec{a} = \langle 1, 0, 2, 1 \rangle$ and $\vec{b} = \langle 2, 0, 1, 1 \rangle$, compute their cosine similarity:

$$
\text{cosine similarity} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}.
$$

**Solution**:  
1. Compute the dot product $\vec{a} \cdot \vec{b}$:

   $$
   \vec{a} \cdot \vec{b} = (1)(2) + (0)(0) + (2)(1) + (1)(1) = 2 + 0 + 2 + 1 = 5.
   $$

2. Compute the magnitudes $|\vec{a}|$ and $|\vec{b}|$:

   $$
   |\vec{a}| = \sqrt{(1)^2 + (0)^2 + (2)^2 + (1)^2} = \sqrt{1 + 0 + 4 + 1} = \sqrt{6}.
   $$

   $$
   |\vec{b}| = \sqrt{(2)^2 + (0)^2 + (1)^2 + (1)^2} = \sqrt{4 + 0 + 1 + 1} = \sqrt{6}.
   $$

3. Compute the cosine similarity:

   $$
   \text{cosine similarity} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|} = \frac{5}{\sqrt{6} \cdot \sqrt{6}} = \frac{5}{6}.
   $$

**Answer**:  
The cosine similarity is $ \boxed{\frac{5}{6}} $.

---

## Example 6: Lighting in Computer Graphics (Dot Product)

#### Ex6.
Let $\vec{L} = \langle -1, 2, 2 \rangle$ and $\vec{N} = \langle 0, 0, 1 \rangle$. Compute the lighting intensity:

$$
I \propto \max(0, \vec{L} \cdot \vec{N}).
$$

**Solution**:  
1. Normalize $\vec{L}$:

   $$
   |\vec{L}| = \sqrt{(-1)^2 + (2)^2 + (2)^2} = \sqrt{1 + 4 + 4} = \sqrt{9} = 3.
   $$

   Normalized $\vec{L}$:

   $$
   \hat{L} = \left\langle \frac{-1}{3}, \frac{2}{3}, \frac{2}{3} \right\rangle.
   $$

2. Normalize $\vec{N}$:

   $$
   |\vec{N}| = \sqrt{(0)^2 + (0)^2 + (1)^2} = \sqrt{1} = 1.
   $$

   $\vec{N}$ is already normalized.

3. Compute the dot product $\hat{L} \cdot \vec{N}$:

   $$
   \hat{L} \cdot \vec{N} = \left(\frac{-1}{3}\right)(0) + \left(\frac{2}{3}\right)(0) + \left(\frac{2}{3}\right)(1) = 0 + 0 + \frac{2}{3} = \frac{2}{3}.
   $$

4. Apply $\max(0, \cdot)$:

   $$
   I \propto \max(0, \frac{2}{3}) = \frac{2}{3}.
   $$

**Answer**:  
The lighting intensity is proportional to $ \boxed{\frac{2}{3}} $.

---

## Wrapping Up

These examples demonstrate how the dot product and cross product are applied in various fields:
- Computing work and torque.
- Analyzing lighting intensity in computer graphics.
- Measuring similarity in machine learning.
