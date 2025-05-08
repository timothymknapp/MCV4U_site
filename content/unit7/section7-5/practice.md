+++
title = '7.5 Practice'
weight = 2
+++


In this section, you’ll find practice problems to reinforce your understanding of how the dot product and cross product are applied in real-world scenarios. Solutions are hidden -- expand them only after attempting the problem!

---

#### Ex1.
A force $\vec{F} = \langle 6, -2 \rangle$ moves an object along a displacement $\vec{d} = \langle 3, 4 \rangle$. Find the work done.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for work is:

$$
W = \vec{F} \cdot \vec{d}.
$$

Substitute the components of $\vec{F} = \langle 6, -2 \rangle$ and $\vec{d} = \langle 3, 4 \rangle$:

$$
\vec{F} \cdot \vec{d} = (6)(3) + (-2)(4) = 18 - 8 = 10.
$$

**Answer**:  
The work done is $ \boxed{10 \, \text{J}} $.

</details>

---


#### Ex2.
A $20 \, \text{N}$ force is applied at a $45^\circ$ angle to the direction of motion. The object moves $5 \, \text{m}$. Find the work done.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for work is:

$$
W = |\vec{F}||\vec{d}|\cos\theta.
$$

Substitute the given values:
- $|\vec{F}| = 20 \, \text{N}$,
- $|\vec{d}| = 5 \, \text{m}$,
- $\theta = 45^\circ$.

Compute:

$$
W = (20)(5)\cos(45^\circ) = (20)(5)\left(\frac{\sqrt{2}}{2}\right) = 50\sqrt{2}.
$$

**Answer**:  
The work done is $ \boxed{50\sqrt{2} \, \text{J}} $.

</details>

---


#### Ex3.
Let $\vec{r} = \langle 0, 0.3, 0 \rangle$ and $\vec{F} = \langle 5, 0, 0 \rangle$. Find the torque vector $\vec{\tau} = \vec{r} \times \vec{F}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the Cartesian formula:

$$
\vec{\tau} = \langle r_2F_3 - r_3F_2, \; r_3F_1 - r_1F_3, \; r_1F_2 - r_2F_1 \rangle.
$$

Substitute the components of $\vec{r} = \langle 0, 0.3, 0 \rangle$ and $\vec{F} = \langle 5, 0, 0 \rangle$:

1. **i-component** ($r_2F_3 - r_3F_2$):

   $$
   (0.3)(0) - (0)(0) = 0.
   $$

2. **j-component** ($r_3F_1 - r_1F_3$):

   $$
   (0)(5) - (0)(0) = 0.
   $$

3. **k-component** ($r_1F_2 - r_2F_1$):

   $$
   (0)(0) - (0.3)(5) = -1.5.
   $$

Combine the components:

$$
\vec{\tau} = \langle 0, 0, -1.5 \rangle.
$$

**Answer**:  
The torque vector is $ \boxed{\langle 0, 0, -1.5 \rangle} $.

</details>

---


#### Ex4.
A wrench of length $0.2 \, \text{m}$ is turned with a force of $30 \, \text{N}$ at an angle of $60^\circ$. What is the magnitude of the torque?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for torque magnitude is:

$$
|\vec{\tau}| = |\vec{r}||\vec{F}|\sin\theta.
$$

Substitute the given values:
- $|\vec{r}| = 0.2 \, \text{m}$,
- $|\vec{F}| = 30 \, \text{N}$,
- $\theta = 60^\circ$.

Compute:

$$
|\vec{\tau}| = (0.2)(30)\sin(60^\circ) = (0.2)(30)\left(\frac{\sqrt{3}}{2}\right) = 3\sqrt{3}.
$$

**Answer**:  
The magnitude of the torque is $ \boxed{3\sqrt{3} \, \text{N·m}} $.

</details>

---

#### Ex5.
Given the two vectors $\vec{a} = \langle 1, 2, 3 \rangle$ and $\vec{b} = \langle 4, 5, 6 \rangle$, compute their cosine similarity:

$$
\text{cosine similarity} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}.
$$

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Compute the dot product $\vec{a} \cdot \vec{b}$:

   $$
   \vec{a} \cdot \vec{b} = (1)(4) + (2)(5) + (3)(6) = 4 + 10 + 18 = 32.
   $$

2. Compute the magnitudes $|\vec{a}|$ and $|\vec{b}|$:

   $$
   |\vec{a}| = \sqrt{(1)^2 + (2)^2 + (3)^2} = \sqrt{1 + 4 + 9} = \sqrt{14}.
   $$

   $$
   |\vec{b}| = \sqrt{(4)^2 + (5)^2 + (6)^2} = \sqrt{16 + 25 + 36} = \sqrt{77}.
   $$

3. Compute the cosine similarity:

   $$
   \text{cosine similarity} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|} = \frac{32}{\sqrt{14} \cdot \sqrt{77}} = \frac{32}{\sqrt{1078}}.
   $$

Simplify:

$$
\text{cosine similarity} = \frac{32}{\sqrt{1078}}.
$$

**Answer**:  
The cosine similarity is $ \boxed{\frac{32}{\sqrt{1078}}} $.

</details>

---

#### Ex6.
Let $\vec{L} = \langle -1, 1, 0 \rangle$ and $\vec{N} = \langle 0, 1, 0 \rangle$. Compute the lighting intensity:

$$
I \propto \max(0, \vec{L} \cdot \vec{N}).
$$

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Normalize $\vec{L}$:

   $$
   |\vec{L}| = \sqrt{(-1)^2 + (1)^2 + (0)^2} = \sqrt{1 + 1 + 0} = \sqrt{2}.
   $$

   Normalized $\vec{L}$:

   $$
   \hat{L} = \left\langle \frac{-1}{\sqrt{2}}, \frac{1}{\sqrt{2}}, 0 \right\rangle.
   $$

2. Normalize $\vec{N}$:

   $$
   |\vec{N}| = \sqrt{(0)^2 + (1)^2 + (0)^2} = \sqrt{1} = 1.
   $$

   $\vec{N}$ is already normalized.

3. Compute the dot product $\hat{L} \cdot \vec{N}$:

   $$
   \hat{L} \cdot \vec{N} = \left(\frac{-1}{\sqrt{2}}\right)(0) + \left(\frac{1}{\sqrt{2}}\right)(1) + (0)(0) = 0 + \frac{1}{\sqrt{2}} + 0 = \frac{1}{\sqrt{2}}.
   $$

4. Apply $\max(0, \cdot)$:

   $$
   I \propto \max(0, \frac{1}{\sqrt{2}}) = \frac{1}{\sqrt{2}}.
   $$

**Answer**:  
The lighting intensity is proportional to $ \boxed{\frac{1}{\sqrt{2}}} $.

</details>

---

## Wrapping Up

These practice problems cover a variety of applications of the dot product and cross product:
- Computing work and torque.
- Analyzing lighting intensity in computer graphics.
- Measuring similarity in machine learning.



<iframe src="https://script.google.com/macros/s/AKfycbx7-wOySXbvV1cr32NLShRC3PBM9FngpV-xBNFbsIl14l9vZC4qBdtGJlLcR48udAaO/exec" width="80%" height="1500px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>


