+++
title = "3.6 Mixed Derivatives"
weight = 6
+++

### Overview

In this section, we expand our toolkit by combining various derivative rules to handle functions that include both transcendental and algebraic components. These functions often arise in real-world applications, such as physics, engineering, and economics. By mastering the integration of rules like the Power Rule, Product Rule, Quotient Rule, and Chain Rule, you'll be equipped to differentiate even the most complex expressions.

By the end of this section, you will confidently apply these techniques to solve problems involving mixed derivatives.

---

### Why Combine Derivative Rules?

Real-world problems frequently involve functions that combine multiple mathematical operations, such as:
- Products of polynomials and exponential functions.
- Quotients involving logarithmic or trigonometric functions.
- Compositions of transcendental and algebraic functions.

To tackle these scenarios, we must seamlessly integrate the derivative rules we've learned. This skill is essential for solving a wide range of calculus problems.

---

### Key Concepts and Strategies

1. **Analyze the Function Structure**: Before differentiating, carefully examine the function to determine which rules are required.
   - Identify products, quotients, powers, or compositions.
   
2. **Apply Appropriate Rules**:
   - Use the **Power Rule** for polynomial terms.
   - Use the **Product Rule** for products of functions.
   - Use the **Quotient Rule** for ratios of functions.
   - Use the **Chain Rule** for composite functions.

3. **Combine Rules When Necessary**: If a function requires multiple rules, proceed step-by-step:
   - Differentiate the outermost operation first.
   - Move inward, applying additional rules as needed.

4. **Simplify Your Answer**: After computing the derivative, simplify it to make it easier to interpret.

---

### Example 1: Combining Rules for a Product with a Transcendental Function

Let’s consider the function:
\[
f(x) = x^2 \cdot e^{3x} \cdot \cos(x)
\]

#### Step 1: Recognize the Structure
This is a product of three functions:
- \( u(x) = x^2 \),
- \( v(x) = e^{3x} \),
- \( w(x) = \cos(x) \).

We’ll use the **Product Rule** twice since there are three factors.

#### Step 2: Apply the Product Rule
The Product Rule for three functions is:
\[
\frac{d}{dx}[u \cdot v \cdot w] = u'vw + uv'w + uvw'
\]

#### Step 3: Differentiate Each Component
- For \( u(x) = x^2 \):
  \[
  u'(x) = 2x
  \]

- For \( v(x) = e^{3x} \):
  \[
  v'(x) = 3e^{3x}
  \]

- For \( w(x) = \cos(x) \):
  \[
  w'(x) = -\sin(x)
  \]

#### Step 4: Substitute into the Product Rule
\[
f'(x) = (2x)(e^{3x})(\cos(x)) + (x^2)(3e^{3x})(\cos(x)) + (x^2)(e^{3x})(-\sin(x))
\]

#### Step 5: Simplify
Factor out common terms:
\[
f'(x) = e^{3x} \big[ 2x\cos(x) + 3x^2\cos(x) - x^2\sin(x) \big]
\]

Thus, the derivative is:
\[
\boxed{f'(x) = e^{3x} \big[ 2x\cos(x) + 3x^2\cos(x) - x^2\sin(x) \big]}
\]

---

### Example 2: A Quotient Involving Logarithms and Exponentials

Consider the function:
\[
g(x) = \frac{\ln(x)}{e^{2x}}
\]

#### Step 1: Recognize the Structure
This is a quotient of two functions:
- Numerator: \( u(x) = \ln(x) \),
- Denominator: \( v(x) = e^{2x} \).

We’ll use the **Quotient Rule**.

#### Step 2: Apply the Quotient Rule
The Quotient Rule states:
\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}
\]

#### Step 3: Differentiate Each Component
- For \( u(x) = \ln(x) \):
  \[
  u'(x) = \frac{1}{x}
  \]

- For \( v(x) = e^{2x} \):
  \[
  v'(x) = 2e^{2x}
  \]

#### Step 4: Substitute into the Quotient Rule
\[
g'(x) = \frac{\left(\frac{1}{x}\right)e^{2x} - (\ln(x))(2e^{2x})}{(e^{2x})^2}
\]

#### Step 5: Simplify
Factor out \( e^{2x} \) from the numerator:
\[
g'(x) = \frac{e^{2x} \left(\frac{1}{x} - 2\ln(x)\right)}{e^{4x}}
\]
\[
g'(x) = \frac{\frac{1}{x} - 2\ln(x)}{e^{2x}}
\]

Thus, the derivative is:
\[
\boxed{g'(x) = \frac{\frac{1}{x} - 2\ln(x)}{e^{2x}}}
\]

---

### Example 3: A Composite Function with Trigonometric and Polynomial Components

Consider the function:
\[
h(x) = \sin(x^2 + 1)
\]

#### Step 1: Recognize the Structure
This is a composite function where:
- Outer function: \( \sin(u) \), where \( u = x^2 + 1 \).
- Inner function: \( u(x) = x^2 + 1 \).

We’ll use the **Chain Rule**.

#### Step 2: Apply the Chain Rule
The Chain Rule states:
\[
\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)
\]

#### Step 3: Differentiate Each Component
- For \( f(u) = \sin(u) \):
  \[
  f'(u) = \cos(u)
  \]

- For \( u(x) = x^2 + 1 \):
  \[
  u'(x) = 2x
  \]

#### Step 4: Substitute into the Chain Rule
\[
h'(x) = \cos(x^2 + 1) \cdot 2x
\]

Thus, the derivative is:
\[
\boxed{h'(x) = 2x \cos(x^2 + 1)}
\]

---

### Learning Objectives

By the end of this section, students will:
1. Understand how to identify when multiple derivative rules are required for transcendental and algebraic functions.
2. Apply the Power Rule, Product Rule, Quotient Rule, and Chain Rule in combination to differentiate complex functions.
3. Solve problems involving mixed derivatives with confidence.
4. Simplify derivatives effectively to ensure clarity and correctness.