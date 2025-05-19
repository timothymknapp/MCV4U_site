+++
title = '8.1: Lines in 2D and 3D'
weight = 1
+++

## Learning Goals:
- Understand how to represent lines in 2D and 3D using vector, scalar, and parametric equations.
- Use direction vectors to describe lines.
- Apply these concepts to solve geometric problems.

## Key Concepts:

### Scalar Equation of a Line (2D):
The scalar equation of a line in 2D is:
$$
ax + by + c = 0
$$
Where:
- $(a, b)$ is the normal vector to the line.
- $(x, y)$ are coordinates of any point on the line.
- $c$ is a constant.

### Vector Equation of a Line (2D):
The vector equation of a line in 2D is:

$$
\vec{r}(t) = \vec{r}_0 + t\vec{m}
$$

Where:
- $\vec{r}_0 = \langle x_0, y_0 \rangle$ is a position vector to a point on the line.
- $\vec{m} = \langle m_x, m_y \rangle$ is the direction vector parallel to the line.
- $t$ is a scalar parameter.

### Parametric Equations of a Line (2D):
From the vector equation, we derive parametric equations:

$$
x = x_0 + t \cdot m_x, \quad y = y_0 + t \cdot m_y
$$

### Lines in 3D:
In 3D, the scalar equation does not apply directly. Instead, we use:
- **Vector Equation**:

  $$
  \vec{r}(t) = \vec{r}_0 + t\vec{m}
  $$

  Where:
  - $\vec{r}_0 = \langle x_0, y_0, z_0 \rangle$ is a position vector to a point on the line.
  - $\vec{m} = \langle m_x, m_y, m_z \rangle$ is the direction vector parallel to the line.
  - $t$ is a scalar parameter.

- **Parametric Equations**:

  $$
  x = x_0 + t \cdot m_x, \quad y = y_0 + t \cdot m_y, \quad z = z_0 + t \cdot m_z
  $$

## Summary:
- In 2D, lines can be represented using scalar, vector, or parametric equations.
- In 3D, lines are represented using vector or parametric equations.
- Direction vectors play a crucial role in describing lines in both 2D and 3D.