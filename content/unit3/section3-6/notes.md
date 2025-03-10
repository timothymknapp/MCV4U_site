
+++
title = "3.6 Examples"
weight = 1
+++

### Mixing Derivative Rules with Transcendentals including some Double Chain Rules

In this section, we will work through examples that require combining multiple derivative rules, such as the Power Rule, Product Rule, Quotient Rule, and Chain Rule. These examples will also include transcendental functions and cases where double chain rules are applied (a function within a function within a function). This will deepen your understanding of how to approach complex differentiation problems.

---

### Example 1: Product of Two Functions with Nested Transcendental Functions

Differentiate the following function:
\[
y = x^2 \cdot e^{\sin(x^2)}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = x^2 \) and \( v(x) = e^{\sin(x^2)} \).
2. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
3. Differentiate \( u(x) = x^2 \):
   \[
   u'(x) = 2x
   \]
4. Differentiate \( v(x) = e^{\sin(x^2)} \) using the **Chain Rule** (double chain rule here):
   - Outer function: \( w(z) = e^z \), where \( z = \sin(x^2) \).
   - Middle function: \( z(x) = \sin(x^2) \).
   - Inner function: \( w(x) = x^2 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dz} = e^z
     \]
   - Differentiate the middle function:
     \[
     \frac{dz}{dx} = \cos(x^2) \cdot 2x
     \]
   - Multiply the derivatives:
     \[
     v'(x) = e^{\sin(x^2)} \cdot \cos(x^2) \cdot 2x
     \]
5. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = (2x)e^{\sin(x^2)} + (x^2)e^{\sin(x^2)} \cdot \cos(x^2) \cdot 2x
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = 2x e^{\sin(x^2)} \left(1 + x \cos(x^2)\right)
   \]

---

### Example 2: Quotient of Two Functions with Nested Exponential and Logarithmic Functions

Differentiate the following function:
\[
y = \frac{\ln(e^{x^2} + 1)}{x^3}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a quotient of two functions: \( u(x) = \ln(e^{x^2} + 1) \) and \( v(x) = x^3 \).
2. Apply the **Quotient Rule**:
   \[
   \frac{d}{dx}\left(\frac{u(x)}{v(x)}\right) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
3. Differentiate \( u(x) = \ln(e^{x^2} + 1) \) using the **Chain Rule**:
   - Outer function: \( w(z) = \ln(z) \), where \( z = e^{x^2} + 1 \).
   - Inner function: \( z(x) = e^{x^2} + 1 \).
   - Differentiate the outer function:
     \[
     \frac{du}{dz} = \frac{1}{z}
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = e^{x^2} \cdot 2x
     \]
   - Multiply the derivatives:
     \[
     u'(x) = \frac{e^{x^2} \cdot 2x}{e^{x^2} + 1}
     \]
4. Differentiate \( v(x) = x^3 \):
   \[
   v'(x) = 3x^2
   \]
5. Substitute into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{\left(\frac{e^{x^2} \cdot 2x}{e^{x^2} + 1}\right)(x^3) - (\ln(e^{x^2} + 1))(3x^2)}{(x^3)^2}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = \frac{x^2 \left(\frac{2x e^{x^2}}{e^{x^2} + 1} - 3 \ln(e^{x^2} + 1)\right)}{x^6}
   \]
   \[
   \frac{dy}{dx} = \frac{2x e^{x^2} - 3x^2 \ln(e^{x^2} + 1)(e^{x^2} + 1)}{x^4 (e^{x^2} + 1)}
   \]

---

### Example 3: Double Chain Rule with Trigonometric and Polynomial Functions

Differentiate the following function:
\[
y = \sin^2(e^{x^2})
\]

**Solution:**
1. Identify the structure of the function:
   - This is a composition of three functions: \( u(w) = w^2 \), \( w(z) = \sin(z) \), and \( z(x) = e^{x^2} \).
2. Apply the **Chain Rule** (double chain rule):
   - Outer function: \( u(w) = w^2 \), where \( w = \sin(e^{x^2}) \).
   - Middle function: \( w(z) = \sin(z) \), where \( z = e^{x^2} \).
   - Inner function: \( z(x) = e^{x^2} \).
   - Differentiate the outer function:
     \[
     \frac{du}{dw} = 2w
     \]
   - Differentiate the middle function:
     \[
     \frac{dw}{dz} = \cos(z)
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = e^{x^2} \cdot 2x
     \]
   - Multiply the derivatives:
     \[
     \frac{dy}{dx} = 2\sin(e^{x^2}) \cdot \cos(e^{x^2}) \cdot e^{x^2} \cdot 2x
     \]
3. Simplify:
   \[
   \frac{dy}{dx} = 4x e^{x^2} \sin(e^{x^2}) \cos(e^{x^2})
   \]

---

### Example 4: Product of Functions with Nested Logarithmic and Exponential Functions

Differentiate the following function:
\[
y = (x^2 + 1) \cdot \ln(e^{x^3} + 1)
\]

**Solution:**
1. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = x^2 + 1 \) and \( v(x) = \ln(e^{x^3} + 1) \).
2. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
3. Differentiate \( u(x) = x^2 + 1 \):
   \[
   u'(x) = 2x
   \]
4. Differentiate \( v(x) = \ln(e^{x^3} + 1) \) using the **Chain Rule**:
   - Outer function: \( w(z) = \ln(z) \), where \( z = e^{x^3} + 1 \).
   - Inner function: \( z(x) = e^{x^3} + 1 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dz} = \frac{1}{z}
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = e^{x^3} \cdot 3x^2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = \frac{e^{x^3} \cdot 3x^2}{e^{x^3} + 1}
     \]
5. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = (2x)\ln(e^{x^3} + 1) + (x^2 + 1)\frac{e^{x^3} \cdot 3x^2}{e^{x^3} + 1}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = 2x \ln(e^{x^3} + 1) + \frac{3x^2 (x^2 + 1)e^{x^3}}{e^{x^3} + 1}
   \]

---

### Example 5: Quotient with Nested Trigonometric and Exponential Functions

Differentiate the following function:
\[
y = \frac{\cos(e^{x^2})}{x^2 + 1}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a quotient of two functions: \( u(x) = \cos(e^{x^2}) \) and \( v(x) = x^2 + 1 \).
2. Apply the **Quotient Rule**:
   \[
   \frac{d}{dx}\left(\frac{u(x)}{v(x)}\right) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
3. Differentiate \( u(x) = \cos(e^{x^2}) \) using the **Chain Rule**:
   - Outer function: \( w(z) = \cos(z) \), where \( z = e^{x^2} \).
   - Inner function: \( z(x) = e^{x^2} \).
   - Differentiate the outer function:
     \[
     \frac{du}{dz} = -\sin(z)
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = e^{x^2} \cdot 2x
     \]
   - Multiply the derivatives:
     \[
     u'(x) = -\sin(e^{x^2}) \cdot e^{x^2} \cdot 2x
     \]
4. Differentiate \( v(x) = x^2 + 1 \):
   \[
   v'(x) = 2x
   \]
5. Substitute into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{\left(-\sin(e^{x^2}) \cdot e^{x^2} \cdot 2x\right)(x^2 + 1) - (\cos(e^{x^2}))(2x)}{(x^2 + 1)^2}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = \frac{-2x \sin(e^{x^2}) e^{x^2} (x^2 + 1) - 2x \cos(e^{x^2})}{(x^2 + 1)^2}
   \]

---

### Learning Objectives

By the end of this section, students will:
1. Understand how to combine multiple derivative rules to differentiate complex functions.
2. Apply the Power Rule, Product Rule, Quotient Rule, and Chain Rule in combination.
3. Solve problems involving transcendental functions and double chain rules.
4. Simplify derivatives effectively to ensure clarity and correctness.