+++
title = '6.6 Practice'
weight = 2
+++

---

#### Ex1.
A boat is traveling due north at $15~\text{km/h}$ relative to the water. A current flows from the west at $5~\text{km/h}$. Find the resultant velocity of the boat relative to the ground.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Represent the velocities as vectors:
   - Boat’s velocity: $\vec{v}_{\text{boat}} = 15~\text{km/h [N]}$.
   - Current’s velocity: $\vec{v}_{\text{current}} = 5~\text{km/h [E]}$.

2. Use the Pythagorean theorem to find the magnitude of the resultant velocity:

   $$
   |\vec{v}_{\text{resultant}}| = \sqrt{|\vec{v}_{\text{boat}}|^2 + |\vec{v}_{\text{current}}|^2}
   $$

   Substitute the values:

   $$
   |\vec{v}_{\text{resultant}}| = \sqrt{(15)^2 + (5)^2} = \sqrt{225 + 25} = \sqrt{250} \approx 15.8~\text{km/h}.
   $$

3. Use trigonometry to find the direction. Let $\theta$ be the angle east of north:

   $$
   \tan\theta = \frac{\text{opposite}}{\text{adjacent}} = \frac{5}{15}.
   $$

   $$
   \theta = \tan^{-1}\left(\frac{5}{15}\right) \approx 18.4^\circ.
   $$

**Answer**:  
The resultant velocity is approximately $ \boxed{15.8~\text{km/h [18.4° E of N]}} $.

</details>

---

#### Ex2.
A force of $|\vec{F}| = 20~\text{N}$ acts on an object, causing it to move $|\vec{d}| = 10~\text{m}$. The angle between the force and displacement vectors is $\theta = 45^\circ$. Calculate the work done by the force.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The work done is given by the dot product:

$$
W = \vec{F} \cdot \vec{d} = |\vec{F}| |\vec{d}| \cos\theta
$$

Substitute the given values:

$$
W = (20)(10) \cos(45^\circ)
$$

From trigonometry, $\cos(45^\circ) = \sqrt{2}/2 \approx 0.707$. Therefore:

$$
W = (20)(10)(0.707) \approx 141.4~\text{J}.
$$

**Answer**:  
The work done is approximately $ \boxed{141.4~\text{J}} $.

</details>

---

#### Ex3.
Two vectors are given:
- $\vec{a} = 8~\text{units [E]}$,
- $\vec{b} = 6~\text{units [S]}$.

Find the projection of $\vec{a}$ onto $\vec{b}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The formula for the projection of $\vec{a}$ onto $\vec{b}$ is:

$$
\text{Projection of } \vec{a} \text{ onto } \vec{b} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \vec{b}.
$$

1. Compute the dot product:

   $$
   \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta.
   $$

   Since $\vec{a}$ and $\vec{b}$ are perpendicular ($\theta = 90^\circ$):

   $$
   \vec{a} \cdot \vec{b} = (8)(6)(\cos 90^\circ) = 0.
   $$

2. Substitute into the formula:

   $$
   \text{Projection of } \vec{a} \text{ onto } \vec{b} = \frac{0}{|\vec{b}|^2} \vec{b} = \vec{0}.
   $$

**Answer**:  
The projection is $ \boxed{\vec{0}} $.

</details>

---

#### Ex4.

A force of $|\vec{F}| = 12~\text{N}$ acts at a distance of $|\vec{r}| = 4~\text{m}$ from a pivot point. The angle between $\vec{r}$ and $\vec{F}$ is $\theta = 30^\circ$. Calculate the torque.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The magnitude of the torque is given by the cross product:

$$
|\tau| = |\vec{r} \times \vec{F}| = |\vec{r}| |\vec{F}| \sin\theta
$$

Substitute the given values:

$$
|\tau| = (4)(12) \sin(30^\circ)
$$

From trigonometry, $\sin(30^\circ) = 0.5$. Therefore:

$$
|\tau| = (4)(12)(0.5) = 24~\text{N}\cdot\text{m}.
$$

**Answer**:  
The magnitude of the torque is $ \boxed{24~\text{N}\cdot\text{m}} $.

</details>

---

#### Ex5.

Two vectors are given:
- $|\vec{p}| = 3~\text{units}$,
- $|\vec{q}| = 7~\text{units}$,
- The angle between them is $\theta = 60^\circ$.

Find the area of the triangle formed by $\vec{p}$ and $\vec{q}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The area of the triangle is half the magnitude of the cross product:

$$
\text{Area of Triangle} = \frac{1}{2} |\vec{p} \times \vec{q}| = \frac{1}{2} |\vec{p}| |\vec{q}| \sin\theta
$$

Substitute the given values:

$$
\text{Area of Triangle} = \frac{1}{2} (3)(7) \sin(60^\circ)
$$

From trigonometry, $\sin(60^\circ) = \sqrt{3}/2 \approx 0.866$. Therefore:

$$
\text{Area of Triangle} = \frac{1}{2} (3)(7)(0.866) \approx 9.09~\text{units}^2.
$$

**Answer**:  
The area of the triangle is approximately $ \boxed{9.09~\text{units}^2} $.

</details>

---

#### Ex6.

Two vectors are given:
- $|\vec{u}| = 4~\text{units}$,
- $|\vec{v}| = 7~\text{units}$,
- The angle between them is $\theta = 90^\circ$.

Determine whether the vectors are orthogonal using the dot product.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The dot product is given by:
$$
\vec{u} \cdot \vec{v} = |\vec{u}| |\vec{v}| \cos\theta.
$$

Substitute the given values:
$$
\vec{u} \cdot \vec{v} = (4)(7) \cos(90^\circ).
$$

From trigonometry, $\cos(90^\circ) = 0$. Therefore:
$$
\vec{u} \cdot \vec{v} = (4)(7)(0) = 0.
$$

Since the dot product is zero, the vectors are orthogonal.

**Answer**:  
The vectors are $ \boxed{\text{orthogonal}} $.

</details>

---

#### Ex7.
Two vectors are given:
- $|\vec{m}| = 3~\text{units}$,
- $|\vec{n}| = 5~\text{units}$,
- Their dot product is $\vec{m} \cdot \vec{n} = -7.5$.

Find the angle $\theta$ between the vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Rearrange the dot product formula to solve for $\cos\theta$:
$$
\cos\theta = \frac{\vec{m} \cdot \vec{n}}{|\vec{m}| |\vec{n}|}.
$$

Substitute the given values:
$$
\cos\theta = \frac{-7.5}{(3)(5)} = \frac{-7.5}{15} = -0.5.
$$

Now, find $\theta$ using the inverse cosine function:
$$
\theta = \cos^{-1}(-0.5) = 120^\circ.
$$

**Answer**:  
The angle between the vectors is $ \boxed{120^\circ} $.

</details>

---

## Wrapping Up

These practice problems cover a variety of scenarios involving the applications of geometric vectors:
- Combining forces and velocities using vector addition.
- Calculating work done by a force using the dot product.
- Projecting one vector onto another.
- Determining torque using the cross product.
- Finding areas of triangles using the cross product.


<iframe src="https://script.google.com/macros/s/AKfycbyKGFxa-9B8mFQUvXX1KTlLhsMtWRKEUifYXWtr1HmQPzvT8fHzjCRoHTb4pLvpTwBT1g/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
