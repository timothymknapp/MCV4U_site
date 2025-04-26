+++
title = '6.4 Practice'
weight = 2
+++


---

## Example 1: Calculating the Dot Product

#### Ex1.
Two vectors are given:
- $|\vec{a}| = 5~\text{units}$,
- $|\vec{b}| = 8~\text{units}$,
- The angle between them is $\theta = 60^\circ$.

Find the dot product $\vec{a} \cdot \vec{b}$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the formula for the dot product:

$$
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
$$

Substitute the given values:

$$
\vec{a} \cdot \vec{b} = (5)(8) \cos(60^\circ)
$$

From trigonometry, $\cos(60^\circ) = 0.5$. Therefore:

$$
\vec{a} \cdot \vec{b} = (5)(8)(0.5) = 20
$$

**Answer**:  
The dot product is $ \boxed{20} $.

</details>

---

## Example 2: Determining Orthogonality

#### Ex2.
Two vectors are given:
- $|\vec{u}| = 6~\text{units}$,
- $|\vec{v}| = 10~\text{units}$,
- The angle between them is $\theta = 90^\circ$.

Are the vectors orthogonal? Justify your answer using the dot product.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the formula for the dot product:

$$
\vec{u} \cdot \vec{v} = |\vec{u}| |\vec{v}| \cos\theta
$$

Substitute the given values:

$$
\vec{u} \cdot \vec{v} = (6)(10) \cos(90^\circ)
$$

From trigonometry, $\cos(90^\circ) = 0$. Therefore:

$$
\vec{u} \cdot \vec{v} = (6)(10)(0) = 0
$$

Since the dot product is zero, the vectors are orthogonal.

**Answer**:  
The vectors are $ \boxed{\text{orthogonal}} $.

</details>

---

## Example 3: Finding the Angle Between Vectors

#### Ex3.
Two vectors are given:
- $|\vec{p}| = 4~\text{units}$,
- $|\vec{q}| = 7~\text{units}$,
- The dot product is $\vec{p} \cdot \vec{q} = 14$.

Find the angle $\theta$ between the vectors.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Rearrange the dot product formula to solve for $\cos\theta$:

$$
\cos\theta = \frac{\vec{p} \cdot \vec{q}}{|\vec{p}| |\vec{q}|}
$$

Substitute the given values:

$$
\cos\theta = \frac{14}{(4)(7)} = \frac{14}{28} = 0.5
$$

Now, find $\theta$ using the inverse cosine function:

$$
\theta = \cos^{-1}(0.5) = 60^\circ
$$

**Answer**:  
The angle between the vectors is $ \boxed{60^\circ} $.

</details>

---

## Example 4: Work Done by a Force

#### Ex4.
A force of $|\vec{F}| = 12~\text{N}$ acts on an object, causing it to move $|\vec{d}| = 5~\text{m}$. The angle between the force and displacement vectors is $\theta = 30^\circ$.

Calculate the work done by the force.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The work done is given by the dot product of the force and displacement vectors:

$$
W = \vec{F} \cdot \vec{d} = |\vec{F}| |\vec{d}| \cos\theta
$$

Substitute the given values:

$$
W = (12)(5) \cos(30^\circ)
$$

From trigonometry, $\cos(30^\circ) = \sqrt{3}/2 \approx 0.866$. Therefore:

$$
W = (12)(5)(0.866) \approx 51.96~\text{J}
$$

**Answer**:  
The work done is approximately $ \boxed{51.96~\text{J}} $.

</details>

---

## Example 5: Comparing Alignment of Vectors

#### Ex5.
Two vectors are given:
- $|\vec{x}| = 3~\text{units}$,
- $|\vec{y}| = 9~\text{units}$,
- The dot product is $\vec{x} \cdot \vec{y} = -13.5$.

Determine whether the vectors are aligned, anti-aligned, or neither. Justify your answer.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Rearrange the dot product formula to solve for $\cos\theta$:

$$
\cos\theta = \frac{\vec{x} \cdot \vec{y}}{|\vec{x}| |\vec{y}|}
$$

Substitute the given values:

$$
\cos\theta = \frac{-13.5}{(3)(9)} = \frac{-13.5}{27} = -0.5
$$

Now, find $\theta$ using the inverse cosine function:

$$
\theta = \cos^{-1}(-0.5) = 120^\circ
$$

An angle of $120^\circ$ indicates that the vectors are not aligned or anti-aligned but rather point in directions that are somewhat opposite.

**Answer**:  
The vectors are $ \boxed{\text{neither aligned nor anti-aligned}} $.

</details>

---

## Wrapping Up

These examples demonstrate how to apply the geometric definition of the dot product in various contexts:
- Calculating the dot product from magnitudes and angles.
- Determining orthogonality.
- Finding the angle between two vectors.
- Solving real-world problems like calculating work.


<iframe src="https://script.google.com/macros/s/AKfycbwm1h8rTfMPjpqDBn-hNiRw2NG1XMqiM8n0_fPBNa0DGIp4WkdnO60nvIPrWraYbRoS/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

