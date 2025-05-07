+++
title = '7.2 Practice'
weight = 2
+++

---



#### Ex1.
Two vectors are given:
- $\vec{u} = (2, -5)$,
- $\vec{v} = (3, 4)$.

Find the dot product $\vec{u} \cdot \vec{v}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for the dot product is:
$$
\vec{u} \cdot \vec{v} = u_x v_x + u_y v_y.
$$

Substitute the components:
$$
\vec{u} \cdot \vec{v} = (2)(3) + (-5)(4) = 6 - 20 = -14.
$$

**Answer**:  
The dot product is $ \boxed{-14} $.

</details>

---

#### Ex2.
Two vectors are given:
- $\vec{a} = (1, 3)$,
- $\vec{b} = (-2, 4)$.

Find the angle $\theta$ between the vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for the angle between two vectors is:
$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}.
$$

1. Compute the dot product:
   $$
   \vec{a} \cdot \vec{b} = (1)(-2) + (3)(4) = -2 + 12 = 10.
   $$

2. Compute the magnitudes:
   $$
   |\vec{a}| = \sqrt{(1)^2 + (3)^2} = \sqrt{1 + 9} = \sqrt{10},
   $$
   $$
   |\vec{b}| = \sqrt{(-2)^2 + (4)^2} = \sqrt{4 + 16} = \sqrt{20}.
   $$

3. Substitute into the formula:
   $$
   \cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{10}{\sqrt{10} \cdot \sqrt{20}} = \frac{10}{\sqrt{200}} = \frac{10}{10\sqrt{2}} = \frac{1}{\sqrt{2}}.
   $$

4. Solve for $\theta$:
   $$
   \theta = \cos^{-1}\left(\frac{1}{\sqrt{2}}\right) = 45^\circ.
   $$

**Answer**:  
The angle between the vectors is $ \boxed{45^\circ} $.

</details>

---

#### Ex3.
Two vectors are given:
- $\vec{p} = (4, -3)$,
- $\vec{q} = (6, 8)$.

Determine whether the vectors are orthogonal.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Two vectors are orthogonal if their dot product is zero:
$$
\vec{p} \cdot \vec{q} = p_x q_x + p_y q_y.
$$

Substitute the components:
$$
\vec{p} \cdot \vec{q} = (4)(6) + (-3)(8) = 24 - 24 = 0.
$$

Since the dot product is zero, the vectors are orthogonal.

**Answer**:  
The vectors are $ \boxed{\text{orthogonal}} $.

</details>

---

#### Ex4.
A force $\vec{F} = (6, -2)$ acts on an object, causing a displacement $\vec{d} = (3, 1)$. Calculate the work done by the force.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for work is:
$$
W = \vec{F} \cdot \vec{d}.
$$

Compute the dot product:
$$
W = (6)(3) + (-2)(1) = 18 - 2 = 16.
$$

**Answer**:  
The work done is $ \boxed{16 \, \text{J}} $.

</details>

---

#### Ex5.
A light source emits a vector of intensity $\vec{I} = (5, 3)$, and the surface normal vector is $\vec{n} = (2, -4)$. Calculate the effective intensity of light hitting the surface, which is proportional to the dot product $\vec{I} \cdot \vec{n}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The effective intensity is proportional to the dot product:
$$
\vec{I} \cdot \vec{n} = I_x n_x + I_y n_y.
$$

Substitute the components:
$$
\vec{I} \cdot \vec{n} = (5)(2) + (3)(-4) = 10 - 12 = -2.
$$

The negative sign indicates that the light is not directly aligned with the surface normal.

**Answer**:  
The effective intensity is $ \boxed{-2} $.

</details>

---


<iframe src="https://script.google.com/macros/s/AKfycbw3qgS1OpdVyZpbd-pwFhVh8KLBlIIFC2M3HqmXaoOHzkfEtKbOhYo0zYsoRzaf-cWM2w/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>