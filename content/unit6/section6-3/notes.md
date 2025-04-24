+++
title = '6.3 Examples'
weight = 1
+++


In this section, we’ll work through example problems that reinforce the geometric interpretation of the **dot product**:  
$$
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
$$  
where $|\vec{a}|$ and $|\vec{b}|$ are the magnitudes of the vectors, and $\theta$ is the angle between them.

---

## Example 1: Conceptual Question on Dot Product and Vector Addition

**Question**:  
Explain how the dot product interacts with vector addition. Specifically, if $\vec{c} = \vec{a} + \vec{b}$, does $\vec{c} \cdot \vec{d}$ equal $(\vec{a} \cdot \vec{d}) + (\vec{b} \cdot \vec{d})$? Why or why not?

**Solution**:  
Yes, the dot product is **distributive** over vector addition. This means:
$$
\vec{c} \cdot \vec{d} = (\vec{a} + \vec{b}) \cdot \vec{d} = (\vec{a} \cdot \vec{d}) + (\vec{b} \cdot \vec{d})
$$
This property arises because the dot product is a linear operation. Geometrically, it means you can calculate the projection of each component of $\vec{c}$ onto $\vec{d}$ separately and then sum the results.

---

## Example 2: Calculating the Dot Product from Quadrant Bearings

**Question**:  
Two vectors are given in quadrant bearing notation:
- $\vec{a} = 5~\text{units}, \text{N45°E}$
- $\vec{b} = 8~\text{units}, \text{S60°E}$

Calculate the dot product $\vec{a} \cdot \vec{b}$.

**Solution**:  
1. Convert the quadrant bearings into angles relative to the positive x-axis (east):
   - For $\vec{a}$: N45°E means $90^\circ - 45^\circ = 45^\circ$.
   - For $\vec{b}$: S60°E means $270^\circ - 60^\circ = 210^\circ$.

2. Find the angle $\theta$ between the two vectors:
   - The difference between their directions is $|210^\circ - 45^\circ| = 165^\circ$.

3. Use the dot product formula:
   $$
   \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
   $$
   Substituting the values:
   $$
   \vec{a} \cdot \vec{b} = (5)(8) \cos(165^\circ)
   $$

4. Calculate $\cos(165^\circ)$:
   - Using a calculator, $\cos(165^\circ) \approx -0.9659$.

5. Final calculation:
   $$
   \vec{a} \cdot \vec{b} = (5)(8)(-0.9659) \approx -38.64
   $$

**Answer**:  
The dot product is approximately $-38.64$.

---

## Example 3: Determining Orthogonality Using the Dot Product

**Question**:  
Two vectors are given:
- $\vec{u} = 6~\text{units}, \text{due east}$
- $\vec{v} = 4~\text{units}, \text{due north}$

Are these vectors orthogonal? Justify your answer using the dot product.

**Solution**:  
1. Recall that two vectors are orthogonal if their dot product is zero:
   $$
   \vec{u} \cdot \vec{v} = |\vec{u}| |\vec{v}| \cos\theta
   $$

2. Determine the angle $\theta$ between the vectors:
   - $\vec{u}$ points due east ($0^\circ$), and $\vec{v}$ points due north ($90^\circ$).
   - The angle between them is $90^\circ$.

3. Substitute into the formula:
   $$
   \vec{u} \cdot \vec{v} = (6)(4) \cos(90^\circ)
   $$

4. Since $\cos(90^\circ) = 0$, the dot product becomes:
   $$
   \vec{u} \cdot \vec{v} = (6)(4)(0) = 0
   $$

**Conclusion**:  
The dot product is zero, so the vectors are orthogonal.

---
