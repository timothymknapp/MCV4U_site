+++
title = '7.3 Practice'
weight = 2
+++


#### Ex1.
Two vectors are given:
- $\vec{u} = (2, -3, 4)$,
- $\vec{v} = (-1, 5, -2)$.

Find the resultant vector $\vec{w} = \vec{u} + \vec{v}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

To add two vectors, add their corresponding components:

$$
\vec{w} = \vec{u} + \vec{v} = (u_x + v_x, u_y + v_y, u_z + v_z).
$$

Substitute the components:

$$
\vec{w} = (2 + (-1), -3 + 5, 4 + (-2)) = (1, 2, 2).
$$

**Answer**:  
The resultant vector is $ \boxed{(1, 2, 2)} $.

</details>

---

#### Ex2.
A vector $\vec{v} = (3, -2, 6)$ is scaled by a factor of $k = -2$. Find the new vector.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

To multiply a vector by a scalar, multiply each component by the scalar:

$$
k\vec{v} = (k v_x, k v_y, k v_z).
$$

Substitute the values:

$$
k\vec{v} = (-2)(3, -2, 6) = (-6, 4, -12).
$$

**Answer**:  
The new vector is $ \boxed{(-6, 4, -12)} $.

</details>

---

#### Ex3.
Find the magnitude of the vector $\vec{v} = (4, -3, 5)$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for the magnitude of a vector is:

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}.
$$

Substitute the components:

$$
|\vec{v}| = \sqrt{(4)^2 + (-3)^2 + (5)^2} = \sqrt{16 + 9 + 25} = \sqrt{50} = 5\sqrt{2}.
$$

**Answer**:  
The magnitude is $ \boxed{5\sqrt{2}} $.

</details>

---

#### Ex4.
Find the unit vector of $\vec{v} = (6, -8, 0)$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for the unit vector is:

$$
\hat{v} = \frac{\vec{v}}{|\vec{v}|}.
$$

1. Compute the magnitude:

   $$
   |\vec{v}| = \sqrt{(6)^2 + (-8)^2 + (0)^2} = \sqrt{36 + 64 + 0} = \sqrt{100} = 10.
   $$

2. Divide each component by the magnitude:

   $$
   \hat{v} = \left(\frac{6}{10}, \frac{-8}{10}, \frac{0}{10}\right) = (0.6, -0.8, 0).
   $$

**Answer**:  
The unit vector is $ \boxed{(0.6, -0.8, 0)} $.

</details>

---

#### Ex5.
Two vectors are given:
- $\vec{u} = (1, 2, -3)$,
- $\vec{v} = (4, -1, 2)$.

Find:
1. The dot product $\vec{u} \cdot \vec{v}$.
2. The angle $\theta$ between the vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Compute the dot product:

   $$
   \vec{u} \cdot \vec{v} = u_x v_x + u_y v_y + u_z v_z.
   $$

   Substitute the components:

   $$
   \vec{u} \cdot \vec{v} = (1)(4) + (2)(-1) + (-3)(2) = 4 - 2 - 6 = -4.
   $$

2. Compute the magnitudes:

   $$
   |\vec{u}| = \sqrt{(1)^2 + (2)^2 + (-3)^2} = \sqrt{1 + 4 + 9} = \sqrt{14},
   $$

   $$
   |\vec{v}| = \sqrt{(4)^2 + (-1)^2 + (2)^2} = \sqrt{16 + 1 + 4} = \sqrt{21}.
   $$

3. Use the dot product formula to find $\cos\theta$:

   $$
   \cos\theta = \frac{\vec{u} \cdot \vec{v}}{|\vec{u}| |\vec{v}|} = \frac{-4}{\sqrt{14} \cdot \sqrt{21}} = \frac{-4}{\sqrt{294}} = \frac{-4}{7\sqrt{6}}.
   $$

4. Solve for $\theta$:

   $$
   \theta = \cos^{-1}\left(\frac{-4}{7\sqrt{6}}\right).
   $$

**Answer**:  
The dot product is $ \boxed{-4} $, and the angle is $ \boxed{\cos^{-1}\left(\frac{-4}{7\sqrt{6}}\right)} $.

</details>

---

#### Ex6.
A drone moves with a velocity vector $\vec{v}_1 = (5, 3, -2) \, \text{m/s}$ relative to the ground. A wind blows with a velocity vector $\vec{v}_2 = (-1, 2, 1) \, \text{m/s}$. Find the resultant velocity of the drone relative to the ground.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The resultant velocity is the sum of the two vectors:

$$
\vec{v}_{\text{resultant}} = \vec{v}_1 + \vec{v}_2.
$$

Add the components:

$$
\vec{v}_{\text{resultant}} = (5 + (-1), 3 + 2, -2 + 1) = (4, 5, -1).
$$

**Answer**:  
The resultant velocity is $ \boxed{(4, 5, -1) \, \text{m/s}} $.

</details>

---


<iframe src="https://script.google.com/macros/s/AKfycbw8JMUDkhp4uuUQRnsVXcLwgNyqbLAO8URhI6hClel052j8-6lU19sAARy2YNFD6HAZqw/exec" width="80%" height="1500px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

