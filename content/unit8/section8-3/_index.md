+++
title = '8.3 Planes'
weight = 3
+++

In this section, we explore how to represent planes in three-dimensional space using scalar, vector, and parametric equations. Understanding these representations is crucial for solving geometric problems, such as finding intercepts, determining whether a point lies on a plane, or analyzing the orientation of planes.

## Key Concepts:
1. **Scalar Equation of a Plane**:
   - The general form is:
     $$
     ax + by + cz + d = 0,
     $$
     where $\vec{n} = \langle a, b, c \rangle$ is the normal vector to the plane, and $d$ is determined by substituting a known point on the plane.

2. **Vector Equation of a Plane**:
   - A plane can also be described using a position vector $\vec{r}_0$ and two direction vectors $\vec{u}$ and $\vec{v}$ that lie on the plane:
     $$
     \vec{r}(s, t) = \vec{r}_0 + s\vec{u} + t\vec{v},
     $$
     where $s$ and $t$ are scalar parameters.

3. **Parametric Equations of a Plane**:
   - The parametric form is derived from the vector equation:
     $$
     x = x_0 + su_x + tv_x, \quad y = y_0 + su_y + tv_y, \quad z = z_0 + su_z + tv_z.
     $$

4. **Intercepts of a Plane**:
   - To find the intercepts of a plane with the coordinate axes, set two variables to zero and solve for the third.

5. **Point on a Plane**:
   - A point $(x_1, y_1, z_1)$ lies on a plane if it satisfies the plane's scalar equation.

## Why Study Planes in 3D?
Understanding planes in 3D is essential for applications in physics, engineering, computer graphics, and more. For example:
- In physics, planes describe surfaces where forces act.
- In computer graphics, planes define boundaries for rendering objects.
- In engineering, planes model flat surfaces like walls, floors, or structural components.
