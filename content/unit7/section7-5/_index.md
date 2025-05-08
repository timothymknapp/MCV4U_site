+++
title = '7.5 Dot and Cross Applications'
weight = 5
+++

In this section, we’ll explore how the **dot product** and **cross product** are applied to solve real-world problems in physics, engineering, computer science, and beyond. These operations provide powerful tools for analyzing forces, motion, lighting, and more, bridging the gap between abstract mathematics and practical scenarios.

---

## Learning Goals and Success Criteria

### Learning Goal:
Apply the dot product and cross product to solve real-world problems involving work, torque, lighting, orthogonality, and other applications.

### Success Criteria:
- Use the dot product to compute **work** when force and displacement vectors are given.
- Use the cross product to calculate **torque** as a vector.
- Explain the geometric meaning of both quantities and their relevance in various fields.

---

## Key Applications

### 1. Work (Dot Product)
**Formula**:  

$$
W = \vec{F} \cdot \vec{d} = |\vec{F}||\vec{d}|\cos\theta
$$

**Context**:  
Work measures the energy transferred when a force $\vec{F}$ moves an object along a displacement $\vec{d}$. The dot product captures the component of the force acting in the direction of motion, scaled by the magnitude of the displacement. Work is a **scalar quantity**.

**Variables**:
- $\vec{F}$: Force vector (e.g., pushing or pulling an object).
- $\vec{d}$: Displacement vector (e.g., how far the object moves).
- $\theta$: Angle between $\vec{F}$ and $\vec{d}$.

---

### 2. Torque (Cross Product)
**Formula**:  

$$
\vec{\tau} = \vec{r} \times \vec{F}
$$

**Context**:  
Torque measures the rotational effect of a force $\vec{F}$ applied at a distance $\vec{r}$ from a pivot point. The cross product ensures that the torque vector is perpendicular to the plane formed by $\vec{r}$ and $\vec{F}$, following the **right-hand rule**. Torque is a **vector quantity**.

**Variables**:
- $\vec{r}$: Position vector from the axis of rotation to the point of force application.
- $\vec{F}$: Force vector causing the rotation.

---

### 3. Cosine Similarity (Machine Learning)
**Formula**:  

$$
\text{cosine similarity} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}
$$

**Context**:  
Cosine similarity measures the similarity between two vectors by calculating the cosine of the angle between them. It is widely used in machine learning for tasks like document comparison, recommendation systems, and clustering.

**Variables**:
- $\vec{a}, \vec{b}$: Vectors representing data points (e.g., word frequencies in documents).

---

### 4. Lighting in Computer Graphics
**Formula**:  

$$
I \propto \max(0, \vec{L} \cdot \vec{N})
$$

**Context**:  
The dot product between the light direction vector $\vec{L}$ and the surface normal vector $\vec{N}$ determines how much light reflects off a surface. This calculation is fundamental in simulating realistic lighting in 3D graphics.

**Variables**:
- $\vec{L}$: Normalized light direction vector.
- $\vec{N}$: Normalized surface normal vector.

---

### 5. Orthogonality Check (Dot Product)
**Formula**:  

$$
\vec{a} \cdot \vec{b} = 0
$$

**Context**:  
Two vectors are orthogonal if their dot product is zero. This property is used in geometry, physics, and signal processing to test for perpendicularity.

**Variables**:
- $\vec{a}, \vec{b}$: Vectors being tested for orthogonality.

---

### 6. Magnetic Force on a Moving Charge (Cross Product)
**Formula**:  

$$
\vec{F} = q \vec{v} \times \vec{B}
$$

**Context**:  
The magnetic force on a charged particle moving through a magnetic field depends on the cross product of the velocity $\vec{v}$ and the magnetic field $\vec{B}$. This force is always perpendicular to both $\vec{v}$ and $\vec{B}$.

**Variables**:
- $q$: Charge of the particle.
- $\vec{v}$: Velocity vector of the particle.
- $\vec{B}$: Magnetic field vector.

---

### 7. Angular Momentum (Cross Product)
**Formula**:  

$$
\vec{L} = \vec{r} \times \vec{p}
$$

**Context**:  
Angular momentum measures the rotational motion of a particle about a point. It is computed as the cross product of the position vector $\vec{r}$ and the momentum vector $\vec{p}$.

**Variables**:
- $\vec{r}$: Position vector of the particle.
- $\vec{p}$: Momentum vector ($\vec{p} = m\vec{v}$).

---

### 8. Volume of a Parallelepiped (Scalar Triple Product)
**Formula**:  

$$
V = |\vec{a} \cdot (\vec{b} \times \vec{c})|
$$

**Context**:  
The scalar triple product computes the volume of the parallelepiped formed by three vectors $\vec{a}$, $\vec{b}$, and $\vec{c}$. This application is common in geometry and physics.

**Variables**:
- $\vec{a}, \vec{b}, \vec{c}$: Vectors defining the edges of the parallelepiped.

---

## What’s Next?

In the upcoming sections, we’ll dive deeper into these applications with detailed examples and practice problems. You’ll learn how to:
- Compute work and torque using the dot and cross products.
- Analyze lighting intensity in computer graphics.
- Solve problems involving angular momentum, magnetic forces, and more.

