+++
title = '8.2: Intersections of Lines'
weight = 2
+++


## Learning Goals:
- Understand how to determine the intersection of two lines in 2D and 3D.
- Identify the types of solutions that can arise when solving systems of equations for intersecting lines.
- Apply algebraic and geometric methods to analyze intersections of lines.

## Key Concepts:

### Types of Solutions for Intersecting Lines:
When solving for the intersection of two lines, there are three possible outcomes:
1. **One Solution**: The lines intersect at a single point.
   - In 2D: This occurs when the lines are not parallel and have different slopes.
   - In 3D: This occurs when the direction vectors of the lines are not scalar multiples, and the lines are not skew.

2. **No Solution**: The lines do not intersect.
   - In 2D: This occurs when the lines are parallel but distinct.
   - In 3D: This occurs when the lines are skew (not parallel but do not intersect).

3. **Infinite Solutions**: The lines coincide (are identical).
   - In 2D: This occurs when the lines are scalar multiples of each other.
   - In 3D: This occurs when the parametric equations of the lines describe the same line.

### Solving Systems of Equations:
To find the intersection of two lines, solve their equations simultaneously:
- **Scalar Form (2D Only)**: Solve the system of linear equations.
- **Vector/Parametric Form (2D and 3D)**: Equate the parametric equations of the lines and solve for the parameters.

#### Example in 2D:
Given two lines in vector form:
$$
\vec{r}_1(t) = \langle x_1, y_1 \rangle + t\langle m_{x1}, m_{y1} \rangle, \quad \vec{r}_2(s) = \langle x_2, y_2 \rangle + s\langle m_{x2}, m_{y2} \rangle
$$
Set the $x$- and $y$-components equal:
$$
x_1 + t m_{x1} = x_2 + s m_{x2}, \quad y_1 + t m_{y1} = y_2 + s m_{y2}
$$
Solve for $t$ and $s$. If a solution exists, substitute back to find the intersection point.

#### Example in 3D:
For two lines in parametric form:
$$
\vec{r}_1(t) = \langle x_1, y_1, z_1 \rangle + t\langle m_{x1}, m_{y1}, m_{z1} \rangle, \quad \vec{r}_2(s) = \langle x_2, y_2, z_2 \rangle + s\langle m_{x2}, m_{y2}, m_{z2} \rangle
$$
Set the $x$-, $y$-, and $z$-components equal:
$$
x_1 + t m_{x1} = x_2 + s m_{x2}, \quad y_1 + t m_{y1} = y_2 + s m_{y2}, \quad z_1 + t m_{z1} = z_2 + s m_{z2}
$$
Solve the system of three equations for $t$ and $s$. If a solution exists, the lines intersect at a single point.

### Distance Between Skew Lines (3D Only):
If two lines in 3D do not intersect and are not parallel, they are called **skew lines**. The shortest distance between skew lines can be calculated using the formula:
$$
\text{Distance} = \frac{|(\vec{b}_1 - \vec{b}_2) \cdot (\vec{m}_1 \times \vec{m}_2)|}{\|\vec{m}_1 \times \vec{m}_2\|}
$$
Where:
- $\vec{b}_1$ and $\vec{b}_2$ are points on the first and second lines, respectively.
- $\vec{m}_1$ and $\vec{m}_2$ are the direction vectors of the lines.

## Summary:
- In 2D, lines can intersect at one point, be parallel, or coincide.
- In 3D, lines can intersect at one point, be skew, or coincide.
- Use algebraic methods to solve for intersections and geometric methods to interpret results.