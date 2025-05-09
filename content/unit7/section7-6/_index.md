+++
title = '7.6 Projections, Decomositions'
weight = 6
+++


In this section, we explore how to project one vector onto another and decompose a vector into components that are parallel and perpendicular to a given direction. These concepts are fundamental in physics, engineering, and computer graphics, where forces, velocities, and other quantities often need to be analyzed along specific directions.

---

## Learning Goals and Success Criteria

### Learning Goal:
Understand how to compute the projection of one vector onto another and resolve a vector into components.

### Success Criteria:
- Calculate scalar and vector projections.
- Resolve a vector into parallel and perpendicular components relative to another vector.
- Apply projection concepts to solve real-world problems, including 3D scenarios.

---

## Key Concepts

### 1. Scalar Projection
The **scalar projection** of $\vec{a}$ onto $\vec{b}$ measures how much of $\vec{a}$ lies in the direction of $\vec{b}$. It is given by:
\[
\text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
\]

**Context**:  
Scalar projection is useful when you only need the magnitude of the component of $\vec{a}$ in the direction of $\vec{b}$.

---

### 2. Vector Projection
The **vector projection** of $\vec{a}$ onto $\vec{b}$ gives the actual vector component of $\vec{a}$ in the direction of $\vec{b}$. It is given by:
\[
\text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
\]

**Context**:  
Vector projection is used when you need the directional component of $\vec{a}$ along $\vec{b}$ as a vector.

---

### 3. Decomposing a Vector
Any vector $\vec{v}$ can be decomposed into two components:
- **Parallel Component**: The part of $\vec{v}$ that lies along a given direction vector $\vec{d}$:
  \[
  \vec{v}_{\parallel} = \left( \frac{\vec{v} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
  \]
- **Perpendicular Component**: The part of $\vec{v}$ that is orthogonal to $\vec{d}$:
  \[
  \vec{v}_{\perp} = \vec{v} - \vec{v}_{\parallel}.
  \]

**Context**:  
This decomposition is essential for analyzing forces, velocities, or any vector quantity in terms of a specific direction.

---

### Applications of Projections
1. **Physics**: Resolving forces into components (e.g., along a ramp).
2. **Engineering**: Calculating stresses and strains in materials.
3. **Computer Graphics**: Simulating lighting and shadows using normal vectors.
4. **Geometry**: Finding distances from points to lines or planes.

---