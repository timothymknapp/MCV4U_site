+++
title = '7.6 Examples'
weight = 1
+++


In this section, we’ll work through examples that demonstrate how to compute scalar and vector projections, decompose vectors into components, and apply these concepts to real-world scenarios. Both 2D and 3D examples are included.

---

## Example 1: Scalar and Vector Projection (2D)

#### Ex1.
Let $\vec{a} = \langle 4, 3 \rangle$ and $\vec{b} = \langle 1, 0 \rangle$.
1. Find the scalar projection of $\vec{a}$ onto $\vec{b}$.
2. Find the vector projection of $\vec{a}$ onto $\vec{b}$.

**Solution**:

1. **Scalar Projection**:
   
   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
   \]
   
   Compute the dot product:
   
   \[
   \vec{a} \cdot \vec{b} = (4)(1) + (3)(0) = 4.
   \]
   
   Compute $|\vec{b}|$:
   
   \[
   |\vec{b}| = \sqrt{(1)^2 + (0)^2} = 1.
   \]
   
   Substitute:
   
   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{4}{1} = 4.
   \]

2. **Vector Projection**:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]
   
   Compute $|\vec{b}|^2$:
   
   \[
   |\vec{b}|^2 = (1)^2 + (0)^2 = 1.
   \]
   
   Substitute:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{4}{1} \right) \langle 1, 0 \rangle = \langle 4, 0 \rangle.
   \]

**Answer**:
- Scalar Projection: $ \boxed{4} $.
- Vector Projection: $ \boxed{\langle 4, 0 \rangle} $.

---

## Example 2: Decomposing a Vector (2D)

#### Ex2.
Let $\vec{a} = \langle 3, 4 \rangle$ and $\vec{b} = \langle 5, 0 \rangle$. Decompose $\vec{a}$ into components parallel and perpendicular to $\vec{b}$.

**Solution**:

1. **Parallel Component**:
   
   \[
   \vec{a}_{\parallel} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]
   
   Compute the dot product:
   
   \[
   \vec{a} \cdot \vec{b} = (3)(5) + (4)(0) = 15.
   \]
   
   Compute $|\vec{b}|^2$:
   
   \[
   |\vec{b}|^2 = (5)^2 + (0)^2 = 25.
   \]
   
   Substitute:
   
   \[
   \vec{a}_{\parallel} = \left( \frac{15}{25} \right) \langle 5, 0 \rangle = \langle 3, 0 \rangle.
   \]

2. **Perpendicular Component**:
   
   \[
   \vec{a}_{\perp} = \vec{a} - \vec{a}_{\parallel}.
   \]
   
   Substitute:
   
   \[
   \vec{a}_{\perp} = \langle 3, 4 \rangle - \langle 3, 0 \rangle = \langle 0, 4 \rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\langle 3, 0 \rangle} $.
- Perpendicular Component: $ \boxed{\langle 0, 4 \rangle} $.

---

## Example 3: Force on a Ramp (2D)

#### Ex3.
A person pushes a box up a ramp with a force vector $\vec{F} = \langle 60, 30 \rangle$, where the ramp is inclined in the direction of $\vec{d} = \langle 3, 1 \rangle$. Decompose the force into components:
1. $\vec{F}_{\parallel}$ — the component moving the box up the ramp.
2. $\vec{F}_{\perp}$ — the component pressing into the ramp.

**Solution**:

1. **Parallel Component**:
   
   \[
   \vec{F}_{\parallel} = \left( \frac{\vec{F} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
   \]
   
   Compute the dot product:
   
   \[
   \vec{F} \cdot \vec{d} = (60)(3) + (30)(1) = 180 + 30 = 210.
   \]
   
   Compute $|\vec{d}|^2$:
   
   \[
   |\vec{d}|^2 = (3)^2 + (1)^2 = 9 + 1 = 10.
   \]
   
   Substitute:
   
   \[
   \vec{F}_{\parallel} = \left( \frac{210}{10} \right) \langle 3, 1 \rangle = \langle 63, 21 \rangle.
   \]

2. **Perpendicular Component**:
   
   \[
   \vec{F}_{\perp} = \vec{F} - \vec{F}_{\parallel}.
   \]
   
   Substitute:
   
   \[
   \vec{F}_{\perp} = \langle 60, 30 \rangle - \langle 63, 21 \rangle = \langle -3, 9 \rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\langle 63, 21 \rangle} $.
- Perpendicular Component: $ \boxed{\langle -3, 9 \rangle} $.

---

## Example 4: Pulling a Sled (2D)

#### Ex4.
A child pulls a sled with a rope at a $30^\circ$ angle above the horizontal, applying a force of $100 \, \text{N}$. How much of the force is directed horizontally?

**Solution**:
The horizontal component of the force is:

\[
F_{\text{horizontal}} = F \cos\theta.
\]

Substitute:

\[
F_{\text{horizontal}} = (100) \cos(30^\circ) = (100)\left(\frac{\sqrt{3}}{2}\right) = 50\sqrt{3}.
\]

**Answer**:
The horizontal force is $ \boxed{50\sqrt{3} \, \text{N}} $.

---

## Example 5: Distance from a Point to a Line (2D)

#### Ex5.
Let $\vec{a} = \langle 3, 4 \rangle$ and $\vec{b} = \langle 1, 2 \rangle$. Find the perpendicular distance from the point to the line in the direction of $\vec{b}$.

**Solution**:
The formula for the distance is:

\[
\text{Distance} = |\vec{a} - \text{proj}_{\vec{b}} \vec{a}|.
\]

1. Compute $\text{proj}_{\vec{b}} \vec{a}$:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]

   Compute the dot product:

   \[
   \vec{a} \cdot \vec{b} = (3)(1) + (4)(2) = 3 + 8 = 11.
   \]

   Compute $|\vec{b}|^2$:

   \[
   |\vec{b}|^2 = (1)^2 + (2)^2 = 1 + 4 = 5.
   \]

   Substitute:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{11}{5} \right) \langle 1, 2 \rangle = \left\langle \frac{11}{5}, \frac{22}{5} \right\rangle.
   \]

2. Compute $\vec{a} - \text{proj}_{\vec{b}} \vec{a}$:

   \[
   \vec{a} - \text{proj}_{\vec{b}} \vec{a} = \langle 3, 4 \rangle - \left\langle \frac{11}{5}, \frac{22}{5} \right\rangle = \left\langle \frac{4}{5}, \frac{-2}{5} \right\rangle.
   \]

3. Compute the magnitude:

   \[
   \text{Distance} = \sqrt{\left(\frac{4}{5}\right)^2 + \left(\frac{-2}{5}\right)^2} = \sqrt{\frac{16}{25} + \frac{4}{25}} = \sqrt{\frac{20}{25}} = \sqrt{\frac{4}{5}} = \frac{2}{\sqrt{5}}.
   \]

**Answer**:
The distance is $ \boxed{\frac{2}{\sqrt{5}}} $.

---

## Example 6: Scalar and Vector Projection (3D)

#### Ex6.
Let $\vec{a} = \langle 2, -1, 3 \rangle$ and $\vec{b} = \langle 1, 2, -2 \rangle$.
1. Find the scalar projection of $\vec{a}$ onto $\vec{b}$.
2. Find the vector projection of $\vec{a}$ onto $\vec{b}$.

**Solution**:

1. **Scalar Projection**:
   
   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
   \]
   
   Compute the dot product:
   
   \[
   \vec{a} \cdot \vec{b} = (2)(1) + (-1)(2) + (3)(-2) = 2 - 2 - 6 = -6.
   \]
   
   Compute $|\vec{b}|$:
   
   \[
   |\vec{b}| = \sqrt{(1)^2 + (2)^2 + (-2)^2} = \sqrt{1 + 4 + 4} = \sqrt{9} = 3.
   \]
   
   Substitute:
   
   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{-6}{3} = -2.
   \]

2. **Vector Projection**:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]
   
   Compute $|\vec{b}|^2$:
   
   \[
   |\vec{b}|^2 = (1)^2 + (2)^2 + (-2)^2 = 1 + 4 + 4 = 9.
   \]
   
   Substitute:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{-6}{9} \right) \langle 1, 2, -2 \rangle = \left\langle \frac{-2}{3}, \frac{-4}{3}, \frac{4}{3} \right\rangle.
   \]

**Answer**:
- Scalar Projection: $ \boxed{-2} $.
- Vector Projection: $ \boxed{\left\langle \frac{-2}{3}, \frac{-4}{3}, \frac{4}{3} \right\rangle} $.

---


## Example 7: Decomposing a Vector (3D)

#### Ex7.
Let $\vec{v} = \langle 1, 2, 3 \rangle$ and $\vec{d} = \langle 2, -1, 1 \rangle$. Decompose $\vec{v}$ into components parallel and perpendicular to $\vec{d}$.

**Solution**:

1. **Parallel Component**:

   \[
   \vec{v}_{\parallel} = \left( \frac{\vec{v} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
   \]

   Compute the dot product:

   \[
   \vec{v} \cdot \vec{d} = (1)(2) + (2)(-1) + (3)(1) = 2 - 2 + 3 = 3.
   \]

   Compute $|\vec{d}|^2$:

   \[
   |\vec{d}|^2 = (2)^2 + (-1)^2 + (1)^2 = 4 + 1 + 1 = 6.
   \]

   Substitute:

   \[
   \vec{v}_{\parallel} = \left( \frac{3}{6} \right) \langle 2, -1, 1 \rangle = \left\langle 1, -\frac{1}{2}, \frac{1}{2} \right\rangle.
   \]

2. **Perpendicular Component**:

   \[
   \vec{v}_{\perp} = \vec{v} - \vec{v}_{\parallel}.
   \]

   Substitute:

   \[
   \vec{v}_{\perp} = \langle 1, 2, 3 \rangle - \left\langle 1, -\frac{1}{2}, \frac{1}{2} \right\rangle = \left\langle 0, \frac{5}{2}, \frac{5}{2} \right\rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\left\langle 1, -\frac{1}{2}, \frac{1}{2} \right\rangle} $.
- Perpendicular Component: $ \boxed{\left\langle 0, \frac{5}{2}, \frac{5}{2} \right\rangle} $.

---