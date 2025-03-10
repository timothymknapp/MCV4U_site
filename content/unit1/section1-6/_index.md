+++
title = '1.6 Differentiability'
weight = 6
+++

## Understanding Differentiability

A function \( f(x) \) is **differentiable** at a point \( x = a \) if its derivative exists at that point. This means that the slope of the tangent line to the graph of \( f(x) \) at \( x = a \) is well-defined and finite.

Formally, a function is differentiable at \( x = a \) if the following conditions are satisfied:

- **Continuity at \( x = a \):** The function \( f(x) \) must be continuous at \( x = a \). In other words, \( \lim_{{x \to a}} f(x) = f(a) \).
- **Existence of Left-Hand and Right-Hand Limits of the Derivative:**
  - The left-hand derivative \( \lim_{{h \to 0^-}} \frac{f(a + h) - f(a)}{h} \) must exist.
  - The right-hand derivative \( \lim_{{h \to 0^+}} \frac{f(a + h) - f(a)}{h} \) must also exist.
- **Equality of Left-Hand and Right-Hand Limits:**
  - The left-hand and right-hand derivatives must be equal:
    \[
    \lim_{{h \to 0^-}} \frac{f(a + h) - f(a)}{h} = \lim_{{h \to 0^+}} \frac{f(a + h) - f(a)}{h}.
    \]

If any of these conditions are not met, the function is **non-differentiable** at \( x = a \).

Differentiability implies continuity, meaning that if a function is differentiable at \( x = a \), it must also be continuous at \( x = a \). However, continuity alone does not guarantee differentiability.

---

## Understanding Non-Differentiability

Non-differentiability occurs at points where a function fails to have a defined derivative. This can happen for several reasons, each corresponding to specific behaviors of the function at a given point.

### When is a Function Non-Differentiable?

A function \( f(x) \) is **non-differentiable** at a point \( x = c \) if it fails to meet the conditions for differentiability. The main causes of non-differentiability are as follows:

1. **Sharp Corners or Cusps:**
   - The graph of the function has a sudden change in direction, resulting in no well-defined tangent line at \( x = c \).
   - Example: \( f(x) = |x| \) is non-differentiable at \( x = 0 \).

2. **Vertical Tangent Lines:**
   - At \( x = c \), the slope of the tangent line becomes infinitely steep, making the derivative undefined.
   - Example: \( f(x) = \sqrt[3]{x} \) has a vertical tangent at \( x = 0 \).

3. **Discontinuity:**
   - If a function is discontinuous at \( x = c \), it cannot have a derivative there, as differentiability implies continuity.
   - Example: A step function like \( f(x) = \lfloor x \rfloor \) is non-differentiable at integer values of \( x \).

4. **Oscillatory Behavior:**
   - The function oscillates infinitely near \( x = c \), making it impossible to define a single slope.
   - Example: \( f(x) = \sin(1/x) \) near \( x = 0 \).

---

### Examples of Non-Differentiability

The following scenarios illustrate non-differentiability:

1. **Sharp Corners or Cusps:**
   - The slope of the function changes abruptly.
2. **Vertical Tangent Lines:**
   - The tangent becomes infinitely steep.
3. **Discontinuities:**
   - The function is broken or has jumps at certain points.

![Graph of Non-Differentiability](/images/MCV4U1_6a.png)

---

### Testing for Differentiability

To analyze whether a function is differentiable at \( x = c \), follow these steps:

1. **Check for Continuity:**
   - If \( f(x) \) is discontinuous at \( x = c \), it is automatically non-differentiable.

2. **Evaluate the Limit Definition:**
   - Use the derivative definition:
     \[
     f'(c) = \lim_{{h \to 0}} \frac{f(c + h) - f(c)}{h}
     \]
   - If the left-hand and right-hand limits do not exist or are not equal, the function is non-differentiable.

3. **Inspect the Graph:**
   - Look for sharp corners, cusps, vertical tangents, or discontinuities.

---

### Summary of Key Concepts

- A function is **differentiable** at a point if its derivative exists, which requires a smooth and continuous graph without breaks or abrupt changes.
- A function is **non-differentiable** at points where it fails to have a well-defined tangent line.
- Common causes of non-differentiability include sharp corners, vertical tangents, discontinuities, and oscillatory behavior.
- Differentiability implies continuity, but continuity does not guarantee differentiability.
