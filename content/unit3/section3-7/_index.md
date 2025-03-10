+++
title = "3.7 Derivatives of Graphs"
weight = 7
+++

### Overview

In this section, we transition from symbolic differentiation to a graphical perspective. You will work with given graphs of functions \( f(x) \) and \( g(x) \), and use these to define new functions that involve products, quotients, or compositions of \( f(x) \) and \( g(x) \). Your task will be to determine the derivatives of these new functions by leveraging the derivative rules you've learned so far.

This approach emphasizes the connection between algebraic expressions, their derivatives, and their graphical representations. By the end of this section, you'll develop a deeper understanding of how the behavior of a function's graph influences its derivative.

---

### Why Study Derivatives of Graphs?

Graphical analysis provides an intuitive way to interpret derivatives. For example:
- The value of \( f(a) \) corresponds to the **y-coordinate** of the function at \( x = a \).
- The value of \( f'(a) \) represents the **slope of the tangent line** to the graph of \( f(x) \) at \( x = a \).

Understanding these relationships allows you to analyze complex functions visually and computationally, enhancing your problem-solving skills in calculus.

---

### Key Concepts and Strategies

1. **Interpret Function Values and Slopes**:
   - Recall that \( f(a) \) gives the **output** (or y-value) of the function at \( x = a \).
   - \( f'(a) \) gives the **slope** of the tangent line to the graph of \( f(x) \) at \( x = a \).

2. **Define New Functions**:
   - Use the given graphs of \( f(x) \) and \( g(x) \) to construct new functions such as:
     - Products: \( h(x) = f(x) \cdot g(x) \),
     - Quotients: \( k(x) = \frac{f(x)}{g(x)} \),
     - Compositions: \( m(x) = f(g(x)) \).

3. **Apply Derivative Rules**:
   - Use the **Product Rule**, **Quotient Rule**, and **Chain Rule** to compute the derivatives of these new functions.
   - Carefully identify which rule applies based on the structure of the function.

4. **Use Graphical Information**:
   - Estimate values of \( f(a) \), \( g(a) \), \( f'(a) \), and \( g'(a) \) directly from the graphs.
   - Combine these estimates with the appropriate derivative formulas to calculate the desired results.

5. **Simplify and Interpret**:
   - Simplify your answers where possible.
   - Relate your results back to the original graphs to ensure they make sense geometrically.

---

### Example 1: Derivative of a Product Function

Suppose the graphs of \( f(x) \) and \( g(x) \) are provided, and you are tasked with finding the derivative of \( h(x) = f(x) \cdot g(x) \) at \( x = a \).

#### Step 1: Recall the Product Rule
The derivative of a product is given by:
\[
h'(x) = f'(x)g(x) + f(x)g'(x)
\]

#### Step 2: Extract Values from the Graphs
From the graphs of \( f(x) \) and \( g(x) \), estimate:
- \( f(a) \), the y-value of \( f(x) \) at \( x = a \),
- \( g(a) \), the y-value of \( g(x) \) at \( x = a \),
- \( f'(a) \), the slope of the tangent line to \( f(x) \) at \( x = a \),
- \( g'(a) \), the slope of the tangent line to \( g(x) \) at \( x = a \).

#### Step 3: Substitute into the Product Rule
Using the formula:
\[
h'(a) = f'(a)g(a) + f(a)g'(a)
\]

#### Step 4: Compute the Result
Substitute the estimated values into the formula to find \( h'(a) \).

---

### Example 2: Derivative of a Quotient Function

Now consider \( k(x) = \frac{f(x)}{g(x)} \). Using the **Quotient Rule**:
\[
k'(x) = \frac{f'(x)g(x) - f(x)g'(x)}{(g(x))^2}
\]

#### Step 1: Identify Key Values
From the graphs, estimate:
- \( f(a) \), \( g(a) \),
- \( f'(a) \), \( g'(a) \).

#### Step 2: Substitute into the Quotient Rule
Substitute these values into the formula:
\[
k'(a) = \frac{f'(a)g(a) - f(a)g'(a)}{(g(a))^2}
\]

#### Step 3: Simplify and Interpret
Simplify the result and verify it aligns with the graphical behavior of \( k(x) \).

---

### Example 3: Derivative of a Composite Function

For \( m(x) = f(g(x)) \), use the **Chain Rule**:
\[
m'(x) = f'(g(x)) \cdot g'(x)
\]

#### Step 1: Identify Intermediate Values
From the graphs:
- Estimate \( g(a) \), the input to \( f(x) \),
- Estimate \( f'(g(a)) \), the slope of \( f(x) \) at \( g(a) \),
- Estimate \( g'(a) \), the slope of \( g(x) \) at \( x = a \).

#### Step 2: Apply the Chain Rule
Substitute into the formula:
\[
m'(a) = f'(g(a)) \cdot g'(a)
\]

#### Step 3: Compute the Result
Combine the estimates to find \( m'(a) \).

---

### Learning Objectives

By the end of this section, students will:
1. Understand how to extract function values and slopes from given graphs.
2. Apply the Product Rule, Quotient Rule, and Chain Rule to differentiate combinations of functions defined graphically.
3. Develop proficiency in interpreting derivatives both algebraically and geometrically.
4. Solve problems involving derivatives of products, quotients, and compositions using graphical data.

---

This section bridges the gap between symbolic manipulation and visual reasoning, reinforcing the practical applications of calculus. That we will begin to see more of in the next units.