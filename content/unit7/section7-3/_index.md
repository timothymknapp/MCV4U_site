+++
title = 'Section 7.3'
weight = 3
+++

Welcome to the world of **3D vectors** in Cartesian form! In this section, we extend our understanding of vectors from two dimensions to three dimensions. 3D vectors are essential for modeling real-world phenomena in physics, engineering, computer graphics, and beyond. We’ll explore how to represent, manipulate, and analyze 3D vectors using algebraic methods.

---

## Learning Goals and Success Criteria

### Learning Goal:
Understand the concept of 3D vectors in Cartesian form and their applications. Be able to perform operations such as addition, subtraction, scalar multiplication, and dot product, as well as calculate magnitude, unit vectors, and angles between vectors.

### Success Criteria:
- Represent a 3D vector in Cartesian form: $\vec{v} = (v_x, v_y, v_z)$.
- Perform vector addition, subtraction, and scalar multiplication in 3D.
- Calculate the magnitude of a 3D vector.
- Compute the dot product of two 3D vectors and use it to find the angle between them.
- Determine the unit vector of a given vector.
- Apply these concepts to solve real-world problems.

---

## Key Idea: 3D Vectors in Cartesian Form

A **3D vector** is represented in Cartesian form as:
$$
\vec{v} = (v_x, v_y, v_z),
$$
where:
- $v_x$ is the $x$-component,
- $v_y$ is the $y$-component,
- $v_z$ is the $z$-component.

This representation allows us to describe vectors in three-dimensional space algebraically and perform operations like addition, subtraction, and scaling.

---

### Operations on 3D Vectors

#### 1. Vector Addition and Subtraction
To add or subtract two 3D vectors, add or subtract their corresponding components:
$$
\vec{u} + \vec{v} = (u_x + v_x, u_y + v_y, u_z + v_z),
$$
$$
\vec{u} - \vec{v} = (u_x - v_x, u_y - v_y, u_z - v_z).
$$

#### 2. Scalar Multiplication
To multiply a vector by a scalar $k$, multiply each component by $k$:
$$
k\vec{v} = (k v_x, k v_y, k v_z).
$$

#### 3. Magnitude of a Vector
The magnitude of a 3D vector is the length of the vector and is calculated using the formula:
$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}.
$$

#### 4. Unit Vector
The unit vector of a vector $\vec{v}$ points in the same direction as $\vec{v}$ but has a magnitude of 1. It is calculated as:
$$
\hat{v} = \frac{\vec{v}}{|\vec{v}|},
$$
where $|\vec{v}|$ is the magnitude of $\vec{v}$.

#### 5. Dot Product
The dot product of two 3D vectors $\vec{u} = (u_x, u_y, u_z)$ and $\vec{v} = (v_x, v_y, v_z)$ is defined as:
$$
\vec{u} \cdot \vec{v} = u_x v_x + u_y v_y + u_z v_z.
$$

The dot product can also be used to find the angle $\theta$ between two vectors:
$$
\cos\theta = \frac{\vec{u} \cdot \vec{v}}{|\vec{u}| |\vec{v}|}.
$$

---

### Why Are 3D Vectors Important?

3D vectors are indispensable in fields that involve three-dimensional space:
- **Physics**: Modeling forces, velocities, and accelerations in 3D space.
- **Engineering**: Designing structures, analyzing stresses, and optimizing systems.
- **Computer Graphics**: Simulating realistic motion, lighting, and shading in 3D environments.
- **Robotics**: Controlling the movement and orientation of robots in 3D space.

By mastering 3D vectors, you’ll gain a powerful tool for solving complex problems in science and engineering.

---

### Transition from 2D to 3D

While 2D vectors are confined to the $xy$-plane, 3D vectors extend into the third dimension ($z$-axis). The operations we learned for 2D vectors—addition, subtraction, dot product, and magnitude—are directly applicable to 3D vectors. The only difference is the inclusion of the $z$-component in calculations.

For example:
- The magnitude formula extends from $|\vec{v}| = \sqrt{v_x^2 + v_y^2}$ in 2D to $|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$ in 3D.
- The dot product formula extends from $\vec{u} \cdot \vec{v} = u_x v_x + u_y v_y$ in 2D to $\vec{u} \cdot \vec{v} = u_x v_x + u_y v_y + u_z v_z$ in 3D.

---

### Applications of 3D Vectors

1. **Force Analysis**:  
   In physics, 3D vectors are used to resolve forces acting on objects in three-dimensional space.

2. **3D Modeling**:  
   In computer graphics, 3D vectors are used to represent points, directions, and transformations in 3D space.

3. **Navigation**:  
   In aviation and robotics, 3D vectors are used to model positions, velocities, and orientations.

4. **Machine Learning**:  
   In data science, 3D vectors are used to represent features in multi-dimensional datasets.

---
