+++
title = '7.6 Practice'
weight = 2
+++


In this section, you’ll find practice problems to reinforce your understanding of scalar and vector projections, decomposing vectors, and their applications. Solutions are hidden expand them only after attempting the problem!

---

#### Ex1.
Compute the scalar and vector projections of $\vec{a} = \langle 2, 5 \rangle$ onto $\vec{b} = \langle 4, 1 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Scalar Projection**:

   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
   \]

   Compute the dot product:

   \[
   \vec{a} \cdot \vec{b} = (2)(4) + (5)(1) = 8 + 5 = 13.
   \]

   Compute $|\vec{b}|$:

   \[
   |\vec{b}| = \sqrt{(4)^2 + (1)^2} = \sqrt{16 + 1} = \sqrt{17}.
   \]

   Substitute:

   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{13}{\sqrt{17}}.
   \]

2. **Vector Projection**:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]

   Compute $|\vec{b}|^2$:

   \[
   |\vec{b}|^2 = (4)^2 + (1)^2 = 16 + 1 = 17.
   \]

   Substitute:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{13}{17} \right) \langle 4, 1 \rangle = \left\langle \frac{52}{17}, \frac{13}{17} \right\rangle.
   \]

**Answer**:
- Scalar Projection: $ \boxed{\frac{13}{\sqrt{17}}} $.
- Vector Projection: $ \boxed{\left\langle \frac{52}{17}, \frac{13}{17} \right\rangle} $.

</details>

---

#### Ex2.
Decompose $\vec{v} = \langle 6, -2 \rangle$ into components parallel and perpendicular to $\vec{d} = \langle 1, 1 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Parallel Component**:

   \[
   \vec{v}_{\parallel} = \left( \frac{\vec{v} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
   \]

   Compute the dot product:

   \[
   \vec{v} \cdot \vec{d} = (6)(1) + (-2)(1) = 6 - 2 = 4.
   \]

   Compute $|\vec{d}|^2$:

   \[
   |\vec{d}|^2 = (1)^2 + (1)^2 = 1 + 1 = 2.
   \]

   Substitute:

   \[
   \vec{v}_{\parallel} = \left( \frac{4}{2} \right) \langle 1, 1 \rangle = \langle 2, 2 \rangle.
   \]

2. **Perpendicular Component**:

   \[
   \vec{v}_{\perp} = \vec{v} - \vec{v}_{\parallel}.
   \]

   Substitute:

   \[
   \vec{v}_{\perp} = \langle 6, -2 \rangle - \langle 2, 2 \rangle = \langle 4, -4 \rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\langle 2, 2 \rangle} $.
- Perpendicular Component: $ \boxed{\langle 4, -4 \rangle} $.

</details>

---

#### Ex3.
A lawn mower is pushed with a force of $60 \, \text{N}$ at an angle of $45^\circ$ with the ground. How much force is directed horizontally?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

The horizontal component of the force is:

\[
F_{\text{horizontal}} = F \cos\theta.
\]

Substitute:

\[
F_{\text{horizontal}} = (60) \cos(45^\circ) = (60)\left(\frac{\sqrt{2}}{2}\right) = 30\sqrt{2}.
\]

**Answer**:
The horizontal force is $ \boxed{30\sqrt{2} \, \text{N}} $.

</details>

---

#### Ex4.
Compute the scalar and vector projections of $\vec{a} = \langle 1, 2, -3 \rangle$ onto $\vec{b} = \langle 4, -1, 2 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Scalar Projection**:

   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
   \]

   Compute the dot product:

   \[
   \vec{a} \cdot \vec{b} = (1)(4) + (2)(-1) + (-3)(2) = 4 - 2 - 6 = -4.
   \]

   Compute $|\vec{b}|$:

   \[
   |\vec{b}| = \sqrt{(4)^2 + (-1)^2 + (2)^2} = \sqrt{16 + 1 + 4} = \sqrt{21}.
   \]

   Substitute:

   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{-4}{\sqrt{21}}.
   \]

2. **Vector Projection**:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]

   Compute $|\vec{b}|^2$:

   \[
   |\vec{b}|^2 = (4)^2 + (-1)^2 + (2)^2 = 16 + 1 + 4 = 21.
   \]

   Substitute:

   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{-4}{21} \right) \langle 4, -1, 2 \rangle = \left\langle \frac{-16}{21}, \frac{4}{21}, \frac{-8}{21} \right\rangle.
   \]

**Answer**:
- Scalar Projection: $ \boxed{\frac{-4}{\sqrt{21}}} $.
- Vector Projection: $ \boxed{\left\langle \frac{-16}{21}, \frac{4}{21}, \frac{-8}{21} \right\rangle} $.

</details>

---

#### Ex5.
Compute the scalar and vector projections of $\vec{a} = \langle 3, -1, 4 \rangle$ onto $\vec{b} = \langle 2, 2, -1 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Scalar Projection**:

   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|}.
   \]

   Compute the dot product:

   \[
   \vec{a} \cdot \vec{b} = (3)(2) + (-1)(2) + (4)(-1) = 6 - 2 - 4 = 0.
   \]
   
   Compute $|\vec{b}|$:
   
   \[
   |\vec{b}| = \sqrt{(2)^2 + (2)^2 + (-1)^2} = \sqrt{4 + 4 + 1} = \sqrt{9} = 3.
   \]
   
   Substitute:
   
   \[
   \text{comp}_{\vec{b}} \vec{a} = \frac{0}{3} = 0.
   \]

2. **Vector Projection**:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|^2} \right) \vec{b}.
   \]
   
   Compute $|\vec{b}|^2$:
   
   \[
   |\vec{b}|^2 = (2)^2 + (2)^2 + (-1)^2 = 4 + 4 + 1 = 9.
   \]
   
   Substitute:
   
   \[
   \text{proj}_{\vec{b}} \vec{a} = \left( \frac{0}{9} \right) \langle 2, 2, -1 \rangle = \langle 0, 0, 0 \rangle.
   \]

**Answer**:
- Scalar Projection: $ \boxed{0} $.
- Vector Projection: $ \boxed{\langle 0, 0, 0 \rangle} $.

</details>

---

#### Ex6.
Decompose $\vec{v} = \langle 2, 3, -1 \rangle$ into components parallel and perpendicular to $\vec{d} = \langle 1, 1, 1 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Parallel Component**:
   
   \[
   \vec{v}_{\parallel} = \left( \frac{\vec{v} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
   \]
   
   Compute the dot product:
   
   \[
   \vec{v} \cdot \vec{d} = (2)(1) + (3)(1) + (-1)(1) = 2 + 3 - 1 = 4.
   \]
   
   Compute $|\vec{d}|^2$:
   
   \[
   |\vec{d}|^2 = (1)^2 + (1)^2 + (1)^2 = 1 + 1 + 1 = 3.
   \]
   
   Substitute:
   
   \[
   \vec{v}_{\parallel} = \left( \frac{4}{3} \right) \langle 1, 1, 1 \rangle = \left\langle \frac{4}{3}, \frac{4}{3}, \frac{4}{3} \right\rangle.
   \]

2. **Perpendicular Component**:
   
   \[
   \vec{v}_{\perp} = \vec{v} - \vec{v}_{\parallel}.
   \]
   
   Substitute:
   
   \[
   \vec{v}_{\perp} = \langle 2, 3, -1 \rangle - \left\langle \frac{4}{3}, \frac{4}{3}, \frac{4}{3} \right\rangle = \left\langle \frac{2}{3}, \frac{5}{3}, -\frac{7}{3} \right\rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\left\langle \frac{4}{3}, \frac{4}{3}, \frac{4}{3} \right\rangle} $.
- Perpendicular Component: $ \boxed{\left\langle \frac{2}{3}, \frac{5}{3}, -\frac{7}{3} \right\rangle} $.

</details>

---

#### Ex7.
A force vector $\vec{F} = \langle 6, -8, 3 \rangle \, \text{N}$ acts on an object. Resolve this force into components parallel and perpendicular to the direction vector $\vec{d} = \langle 1, -1, 1 \rangle$.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Parallel Component**:

   \[
   \vec{F}_{\parallel} = \left( \frac{\vec{F} \cdot \vec{d}}{|\vec{d}|^2} \right) \vec{d}.
   \]

   Compute the dot product:

   \[
   \vec{F} \cdot \vec{d} = (6)(1) + (-8)(-1) + (3)(1) = 6 + 8 + 3 = 17.
   \]

   Compute $|\vec{d}|^2$:

   \[
   |\vec{d}|^2 = (1)^2 + (-1)^2 + (1)^2 = 1 + 1 + 1 = 3.
   \]

   Substitute:

   \[
   \vec{F}_{\parallel} = \left( \frac{17}{3} \right) \langle 1, -1, 1 \rangle = \left\langle \frac{17}{3}, -\frac{17}{3}, \frac{17}{3} \right\rangle.
   \]

2. **Perpendicular Component**:

   \[
   \vec{F}_{\perp} = \vec{F} - \vec{F}_{\parallel}.
   \]

   Substitute:

   \[
   \vec{F}_{\perp} = \langle 6, -8, 3 \rangle - \left\langle \frac{17}{3}, -\frac{17}{3}, \frac{17}{3} \right\rangle = \left\langle \frac{1}{3}, -\frac{7}{3}, -\frac{8}{3} \right\rangle.
   \]

**Answer**:
- Parallel Component: $ \boxed{\left\langle \frac{17}{3}, -\frac{17}{3}, \frac{17}{3} \right\rangle} $.
- Perpendicular Component: $ \boxed{\left\langle \frac{1}{3}, -\frac{7}{3}, -\frac{8}{3} \right\rangle} $.

</details>


<iframe src="https://script.google.com/macros/s/AKfycbw3a7tx6wOMEGAuWemh_Nr3kQ6WBjRjoyYIiHrqSPwCB-d-tkzHQBMcdb7dFlJZOnFa/exec" width="80%" height="1200px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>



