+++
title = "3.7 Examples"
weight = 1
+++

### Using Graphical Information to Compute Derivatives

In this section, we will work through examples that demonstrate how to compute derivatives using graphical information. You will use the given graph of two functions \( f(x) \) (red curve) and \( g(x) \) (blue curve) to estimate values and slopes, then apply derivative rules to solve problems.

---

### Example 1: Derivative of a Product Function from Graphs

You are given the graphs of two functions \( f(x) \) (red curve) and \( g(x) \) (blue curve), as shown below:

<div style="margin: 0 auto; width: fit-content;">
<iframe src="https://www.desmos.com/calculator/x8vjr1qqoj?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>

Define a new function \( h(x) = f(x) \cdot g(x) \).

**Task:** Use the graph to estimate \( h'(2) \), the derivative of \( h(x) \) at \( x = 2 \).

---

### Solution for Example 1

To solve this problem, we will use the **Product Rule**, which states:
\[
h'(x) = f'(x)g(x) + f(x)g'(x)
\]

#### Step 1: Identify Key Values from the Graph
From the graph, we extract the following values:
- \( f(2) = 3 \),
- \( g(2) = 4 \),
- \( f'(2) = -1 \),
- \( g'(2) = 2 \).

#### Step 2: Apply the Product Rule
Substitute these values into the formula for \( h'(x) \):
\[
h'(2) = f'(2)g(2) + f(2)g'(2)
\]

#### Step 3: Perform the Calculations
\[
h'(2) = (-1)(4) + (3)(2)
\]
\[
h'(2) = -4 + 6
\]
\[
h'(2) = 2
\]

#### Final Answer:
The derivative of \( h(x) \) at \( x = 2 \) is:
\[
\boxed{h'(2) = 2}
\]

---

### Example 2: Derivative of a Quotient Function from Graphs

Define a new function \( k(x) = \frac{f(x)}{g(x)} \).

**Task:** Use the graph to estimate \( k'(2) \), the derivative of \( k(x) \) at \( x = 2 \).

---

### Solution for Example 2

To solve this problem, we will use the **Quotient Rule**, which states:
\[
k'(x) = \frac{f'(x)g(x) - f(x)g'(x)}{(g(x))^2}
\]

#### Step 1: Identify Key Values from the Graph
From the graph, we extract the following values:
- \( f(2) = 3 \),
- \( g(2) = 4 \),
- \( f'(2) = -1 \),
- \( g'(2) = 2 \).

#### Step 2: Apply the Quotient Rule
Substitute these values into the formula for \( k'(x) \):
\[
k'(2) = \frac{f'(2)g(2) - f(2)g'(2)}{(g(2))^2}
\]

#### Step 3: Perform the Calculations
\[
k'(2) = \frac{(-1)(4) - (3)(2)}{(4)^2}
\]
\[
k'(2) = \frac{-4 - 6}{16}
\]
\[
k'(2) = \frac{-10}{16}
\]
\[
k'(2) = -\frac{5}{8}
\]

#### Final Answer:
The derivative of \( k(x) \) at \( x = 2 \) is:
\[
\boxed{k'(2) = -\frac{5}{8}}
\]

---

### Example 3: Derivative of a Composite Function Using the Chain Rule


Define a new function \( m(x) = f(g(x)) \).

**Task:** Use the graph to estimate \( m'(2) \), the derivative of \( m(x) \) at \( x = 2 \).

---

### Solution for Example 3

To solve this problem, we will use the **Chain Rule**, which states:
\[
m'(x) = f'(g(x)) \cdot g'(x)
\]

#### Step 1: Identify Key Values from the Graph
From the graph, we extract the following values:
- \( g(2) = 4 \),
- \( g'(2) = 2 \),
- From the graph of \( f(x) \), estimate \( f'(4) \). Suppose \( f'(4) = -3 \) based on the slope of the tangent line to \( f(x) \) at \( x = 4 \).

#### Step 2: Apply the Chain Rule
Substitute these values into the formula for \( m'(x) \):
\[
m'(2) = f'(g(2)) \cdot g'(2)
\]

#### Step 3: Perform the Calculations
\[
m'(2) = f'(4) \cdot g'(2)
\]
\[
m'(2) = (-3)(2)
\]
\[
m'(2) = -6
\]

#### Final Answer:
The derivative of \( m(x) \) at \( x = 2 \) is:
\[
\boxed{m'(2) = -6}
\]

---

### Learning Objectives

By the end of this section, students will:
1. Understand how to extract function values and slopes from given graphs.
2. Apply the Product Rule, Quotient Rule, and Chain Rule to differentiate combinations of functions defined graphically.
3. Develop proficiency in interpreting derivatives both algebraically and geometrically.
4. Solve problems involving derivatives of products, quotients, and compositions using graphical data.