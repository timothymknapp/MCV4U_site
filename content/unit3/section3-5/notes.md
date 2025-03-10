+++
title = "3.5 Examples"
weight = 1
+++

### Examples with Transcendental Functions
In this section, we will work through examples that demonstrate how to find the equation of a tangent line using transcendental functions. These examples will reinforce your understanding of derivatives and their application in determining tangent lines for exponential, logarithmic, and trigonometric functions.

---

### Example 1: Tangent Line to an Exponential Function

#### Problem:
Find the equation of the tangent line to the curve \( y = e^{2x} \) at \( x = 0 \).

#### Solution:
1. **Compute the derivative**:
   The derivative \( f'(x) \) represents the slope of the tangent line.
   \[
   f'(x) = \frac{d}{dx}(e^{2x}) = 2e^{2x}
   \]

2. **Evaluate the derivative at \( x = 0 \)**:
   \[
   f'(0) = 2e^{2(0)} = 2e^0 = 2(1) = 2
   \]
   Thus, the slope of the tangent line at \( x = 0 \) is \( m = 2 \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = 0 \):
   \[
   f(0) = e^{2(0)} = e^0 = 1
   \]
   The point of tangency is \( (0, 1) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = 2 \), \( x_1 = 0 \), and \( y_1 = 1 \):
   \[
   y - 1 = 2(x - 0)
   \]
   Simplify:
   \[
   y = 2x + 1
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = 2x + 1}
\]

---

### Example 2: Finding x-Values with a Specific Slope for a Logarithmic Function

#### Problem:

Find the x-values where the slope of the tangent line to the curve \( y = \ln(x) \) is equal to \( \frac{1}{2} \).

#### Solution:

1. **Compute the derivative**:
   The derivative \( f'(x) \) gives the slope of the tangent line.
   \[
   f'(x) = \frac{d}{dx}(\ln(x)) = \frac{1}{x}
   \]

2. **Set the derivative equal to the given slope**:
   Solve for \( x \) when \( f'(x) = \frac{1}{2} \):
   \[
   \frac{1}{x} = \frac{1}{2}
   \]
   Cross-multiply:
   \[
   2 = x
   \]

Thus, the x-value where the slope of the tangent line is \( \frac{1}{2} \) is:

\[
\boxed{x = 2}
\]

---

### Example 3: Tangent Line to a Trigonometric Function


#### Problem:

Find the equation of the tangent line to the curve \( y = \sin(x) \) at \( x = \frac{\pi}{6} \).

#### Solution:
1. **Compute the derivative**:
   The derivative \( f'(x) \) represents the slope of the tangent line.
   \[
   f'(x) = \frac{d}{dx}(\sin(x)) = \cos(x)
   \]

2. **Evaluate the derivative at \( x = \frac{\pi}{6} \)**:
   \[
   f'\left(\frac{\pi}{6}\right) = \cos\left(\frac{\pi}{6}\right) = \frac{\sqrt{3}}{2}
   \]
   Thus, the slope of the tangent line at \( x = \frac{\pi}{6} \) is \( m = \frac{\sqrt{3}}{2} \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = \frac{\pi}{6} \):
   \[
   f\left(\frac{\pi}{6}\right) = \sin\left(\frac{\pi}{6}\right) = \frac{1}{2}
   \]
   The point of tangency is \( \left(\frac{\pi}{6}, \frac{1}{2}\right) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = \frac{\sqrt{3}}{2} \), \( x_1 = \frac{\pi}{6} \), and \( y_1 = \frac{1}{2} \):
   \[
   y - \frac{1}{2} = \frac{\sqrt{3}}{2}\left(x - \frac{\pi}{6}\right)
   \]
   Simplify:
   \[
   y = \frac{\sqrt{3}}{2}x - \frac{\sqrt{3}}{2} \cdot \frac{\pi}{6} + \frac{1}{2}
   \]
   \[
   y = \frac{\sqrt{3}}{2}x - \frac{\sqrt{3}\pi}{12} + \frac{1}{2}
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = \frac{\sqrt{3}}{2}x - \frac{\sqrt{3}\pi}{12} + \frac{1}{2}}
\]

---

### Example 4: Tangent Line to a Composite Transcendental Function

#### Problem:

Find the equation of the tangent line to the curve \( y = e^{\sin(x)} \) at \( x = 0 \).

#### Solution:
1. **Compute the derivative**:
   Use the Chain Rule to differentiate \( y = e^{\sin(x)} \):
   - Outer function: \( e^u \), where \( u = \sin(x) \).
   - Inner function: \( u(x) = \sin(x) \).
   Differentiate the outer function:
   \[
   \frac{dy}{du} = e^u
   \]
   Differentiate the inner function:
   \[
   \frac{du}{dx} = \cos(x)
   \]
   Multiply the derivatives:
   \[
   f'(x) = e^{\sin(x)} \cdot \cos(x)
   \]

2. **Evaluate the derivative at \( x = 0 \)**:
   \[
   f'(0) = e^{\sin(0)} \cdot \cos(0) = e^0 \cdot 1 = 1
   \]
   Thus, the slope of the tangent line at \( x = 0 \) is \( m = 1 \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = 0 \):
   \[
   f(0) = e^{\sin(0)} = e^0 = 1
   \]
   The point of tangency is \( (0, 1) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = 1 \), \( x_1 = 0 \), and \( y_1 = 1 \):
   \[
   y - 1 = 1(x - 0)
   \]
   Simplify:
   \[
   y = x + 1
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = x + 1}
\]

---

### Learning Objectives

By the end of this section, students will:

1. Be able to compute the equation of a tangent line using transcendental functions.
2. Understand how to find x-values where a transcendental function has a specific slope.
3. Apply derivative rules (such as the Chain Rule) to solve problems involving tangent lines for exponential, logarithmic, and trigonometric functions.