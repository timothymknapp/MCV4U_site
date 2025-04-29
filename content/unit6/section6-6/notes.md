+++
title = '6.6 Examples'
weight = 1
+++


In this section, we’ll work through example problems that demonstrate the practical applications of geometric vectors. These examples cover:
- Vector addition.
- Dot product applications (work and projections).
- Cross product applications (torque and area).

---

## Example 1: Vector Addition

#### Ex1.
A plane is flying due east at $200~\text{km/h}$ relative to the air. A wind blows from the north at $50~\text{km/h}$. Find the resultant velocity of the plane relative to the ground.

**Solution**:  
1. Represent the velocities as vectors:
   - Plane’s velocity: $\vec{v}_{\text{plane}} = 200~\text{km/h [E]}$.
   - Wind’s velocity: $\vec{v}_{\text{wind}} = 50~\text{km/h [S]}$.

2. Use the Pythagorean theorem to find the magnitude of the resultant velocity:

   $$
   |\vec{v}_{\text{resultant}}| = \sqrt{|\vec{v}_{\text{plane}}|^2 + |\vec{v}_{\text{wind}}|^2}
   $$

   Substitute the values:

   $$
   |\vec{v}_{\text{resultant}}| = \sqrt{(200)^2 + (50)^2} = \sqrt{40000 + 2500} = \sqrt{42500} \approx 206.2~\text{km/h}.
   $$

3. Use trigonometry to find the direction. Let $\theta$ be the angle south of east:

   $$
   \tan\theta = \frac{\text{opposite}}{\text{adjacent}} = \frac{50}{200}.
   $$

   $$
   \theta = \tan^{-1}\left(\frac{50}{200}\right) \approx 14.0^\circ.
   $$

**Answer**:  
The resultant velocity is approximately $ \boxed{206.2~\text{km/h [14.0° S of E]}} $.

---

## Example 2: Work Done by a Force

#### Ex2.
A force of $|\vec{F}| = 15~\text{N}$ acts on an object, causing it to move $|\vec{d}| = 8~\text{m}$. The angle between the force and displacement vectors is $\theta = 30^\circ$. Calculate the work done by the force.

**Solution**:  
The work done is given by the dot product:

$$
W = \vec{F} \cdot \vec{d} = |\vec{F}| |\vec{d}| \cos\theta
$$

Substitute the given values:

$$
W = (15)(8) \cos(30^\circ)
$$

From trigonometry, $\cos(30^\circ) = \sqrt{3}/2 \approx 0.866$. Therefore:

$$
W = (15)(8)(0.866) \approx 103.9~\text{J}.
$$

**Answer**:  
The work done is approximately $ \boxed{103.9~\text{J}} $.

---

## Example 3: Projection of One Vector onto Another

#### Ex3.
Two vectors are given:
- $\vec{a} = 6~\text{units [E]}$,
- $\vec{b} = 8~\text{units [N]}$.

Find the projection of $\vec{a}$ onto $\vec{b}$.

**Solution**:  
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
   \vec{a} \cdot \vec{b} = (6)(8)(\cos 90^\circ) = 0.
   $$

2. Substitute into the formula:

   $$
   \text{Projection of } \vec{a} \text{ onto } \vec{b} = \frac{0}{|\vec{b}|^2} \vec{b} = \vec{0}.
   $$

**Answer**:  
The projection is $ \boxed{\vec{0}} $.

---

## Example 4: Torque Calculation

#### Ex4.
A force of $|\vec{F}| = 10~\text{N}$ acts at a distance of $|\vec{r}| = 3~\text{m}$ from a pivot point. The angle between $\vec{r}$ and $\vec{F}$ is $\theta = 60^\circ$. Calculate the torque.

**Solution**:  
The magnitude of the torque is given by the cross product:

$$
|\tau| = |\vec{r} \times \vec{F}| = |\vec{r}| |\vec{F}| \sin\theta
$$

Substitute the given values:

$$
|\tau| = (3)(10) \sin(60^\circ)
$$

From trigonometry, $\sin(60^\circ) = \sqrt{3}/2 \approx 0.866$. Therefore:

$$
|\tau| = (3)(10)(0.866) \approx 25.98~\text{N}\cdot\text{m}.
$$

**Answer**:  
The magnitude of the torque is approximately $ \boxed{25.98~\text{N}\cdot\text{m}} $.

---

## Example 5: Area of a Triangle

#### Ex5.
Two vectors are given:
- $|\vec{p}| = 4~\text{units}$,
- $|\vec{q}| = 5~\text{units}$,
- The angle between them is $\theta = 45^\circ$.

Find the area of the triangle formed by $\vec{p}$ and $\vec{q}$.

**Solution**:  
The area of the triangle is half the magnitude of the cross product:

$$
\text{Area of Triangle} = \frac{1}{2} |\vec{p} \times \vec{q}| = \frac{1}{2} |\vec{p}| |\vec{q}| \sin\theta
$$

Substitute the given values:

$$
\text{Area of Triangle} = \frac{1}{2} (4)(5) \sin(45^\circ)
$$

From trigonometry, $\sin(45^\circ) = \sqrt{2}/2 \approx 0.707$. Therefore:

$$
\text{Area of Triangle} = \frac{1}{2} (4)(5)(0.707) \approx 7.07~\text{units}^2.
$$

**Answer**:  
The area of the triangle is approximately $ \boxed{7.07~\text{units}^2} $.

---

## Example 6: Testing Orthogonality of Vectors

#### Ex6.
Two vectors are given:
- $|\vec{a}| = 5~\text{units}$,
- $|\vec{b}| = 3~\text{units}$,
- The angle between them is $\theta = 90^\circ$.

Determine whether the vectors are orthogonal using the dot product.

**Solution**:  
The dot product is given by:
$$
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta.
$$

Substitute the given values:
$$
\vec{a} \cdot \vec{b} = (5)(3) \cos(90^\circ).
$$

From trigonometry, $\cos(90^\circ) = 0$. Therefore:
$$
\vec{a} \cdot \vec{b} = (5)(3)(0) = 0.
$$

Since the dot product is zero, the vectors are orthogonal.

**Answer**:  
The vectors are $ \boxed{\text{orthogonal}} $.

---

## Example 7: Angle Between Two Vectors

#### Ex7.
Two vectors are given:
- $|\vec{p}| = 6~\text{units}$,
- $|\vec{q}| = 8~\text{units}$,
- Their dot product is $\vec{p} \cdot \vec{q} = 24$.

Find the angle $\theta$ between the vectors.

**Solution**:  
Rearrange the dot product formula to solve for $\cos\theta$:
$$
\cos\theta = \frac{\vec{p} \cdot \vec{q}}{|\vec{p}| |\vec{q}|}.
$$

Substitute the given values:
$$
\cos\theta = \frac{24}{(6)(8)} = \frac{24}{48} = 0.5.
$$

Now, find $\theta$ using the inverse cosine function:
$$
\theta = \cos^{-1}(0.5) = 60^\circ.
$$

**Answer**:  
The angle between the vectors is $ \boxed{60^\circ} $.

---

## Wrapping Up

These examples demonstrate how to apply geometric vectors in various contexts:
- Combining forces and velocities using vector addition.
- Calculating work done by a force using the dot product.
- Projecting one vector onto another.
- Determining torque using the cross product.
- Finding areas of triangles using the cross product.
