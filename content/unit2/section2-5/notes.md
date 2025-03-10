+++
title = "2.5 Examples"
weight = 2
+++

## Chain Rule:

### Example 1: Polynomial Function with a Power

Differentiate the following function using the Chain Rule:

\[
y = (4x^2 + 5x + 3)^6
\]

**Solution:**

1. Identify the outer and inner functions:
   - Outer function: \( u(v) = v^6 \), where \( v = 4x^2 + 5x + 3 \).
   - Inner function: \( v(x) = 4x^2 + 5x + 3 \).

2. Differentiate the outer function with respect to \( v \):
   \[
   \frac{du}{dv} = 6v^5
   \]

3. Differentiate the inner function with respect to \( x \):
   \[
   \frac{dv}{dx} = 8x + 5
   \]

4. Multiply the derivatives:
   \[
   \frac{dy}{dx} = 6(4x^2 + 5x + 3)^5 \cdot (8x + 5)
   \]

Thus, the derivative is:

\[
\frac{dy}{dx} = 6(4x^2 + 5x + 3)^5 (8x + 5)
\]

---

### Example 2: Rational Function

Differentiate the following function using the Chain Rule:

\[
y = \frac{1}{(3x^2 + 2x)^4}
\]

**Solution:**

1. Rewrite the function to simplify the use of the Chain Rule:
   \[
   y = (3x^2 + 2x)^{-4}
   \]

2. Identify the outer and inner functions:
   - Outer function: \( u(v) = v^{-4} \), where \( v = 3x^2 + 2x \).
   - Inner function: \( v(x) = 3x^2 + 2x \).

3. Differentiate the outer function with respect to \( v \):
   \[
   \frac{du}{dv} = -4v^{-5}
   \]

4. Differentiate the inner function with respect to \( x \):
   \[
   \frac{dv}{dx} = 6x + 2
   \]

5. Multiply the derivatives:
   \[
   \frac{dy}{dx} = -4(3x^2 + 2x)^{-5} \cdot (6x + 2)
   \]

Thus, the derivative is:

\[
\frac{dy}{dx} = -4(3x^2 + 2x)^{-5} \cdot (6x + 2)
\]

---

### Example 3: Square Root Function

Differentiate the following function using the Chain Rule:

\[
y = \sqrt{5x^2 - 3x + 1}
\]

**Solution:**

1. Rewrite the function as a power:
   \[
   y = (5x^2 - 3x + 1)^{\frac{1}{2}}
   \]

2. Identify the outer and inner functions:
   - Outer function: \( u(v) = v^{\frac{1}{2}} \), where \( v = 5x^2 - 3x + 1 \).
   - Inner function: \( v(x) = 5x^2 - 3x + 1 \).

3. Differentiate the outer function with respect to \( v \):
   \[
   \frac{du}{dv} = \frac{1}{2}v^{-\frac{1}{2}}
   \]

4. Differentiate the inner function with respect to \( x \):
   \[
   \frac{dv}{dx} = 10x - 3
   \]

5. Multiply the derivatives:
   \[
   \frac{dy}{dx} = \frac{1}{2}(5x^2 - 3x + 1)^{-\frac{1}{2}} \cdot (10x - 3)
   \]

Thus, the derivative is:

\[
\frac{dy}{dx} = \frac{1}{2}(5x^2 - 3x + 1)^{-\frac{1}{2}} \cdot (10x - 3)
\]

---

### Example 4: Polynomial Function with Roots

Differentiate the following function using the Chain Rule:

\[
y = (2x^3 + x)^{\frac{1}{3}}
\]

**Solution:**

1. Identify the outer and inner functions:
   - Outer function: \( u(v) = v^{\frac{1}{3}} \), where \( v = 2x^3 + x \).
   - Inner function: \( v(x) = 2x^3 + x \).

2. Differentiate the outer function with respect to \( v \):
   \[
   \frac{du}{dv} = \frac{1}{3}v^{-\frac{2}{3}}
   \]

3. Differentiate the inner function with respect to \( x \):
   \[
   \frac{dv}{dx} = 6x^2 + 1
   \]

4. Multiply the derivatives:
   \[
   \frac{dy}{dx} = \frac{1}{3}(2x^3 + x)^{-\frac{2}{3}} \cdot (6x^2 + 1)
   \]

Thus, the derivative is:

\[
\frac{dy}{dx} = \frac{1}{3}(2x^3 + x)^{-\frac{2}{3}} \cdot (6x^2 + 1)
\]

---

This examples page provides a variety of problems using polynomials and rational functions, with a focus on applying the Chain Rule. Let me know if you need more examples or adjustments!
