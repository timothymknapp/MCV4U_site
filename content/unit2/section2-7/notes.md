+++
title = "2.7 Examples"
weight = 1
+++

### Overview
In this section, we will work through examples that demonstrate how to find the equation of a tangent line using the point-slope form of a linear equation and the concept of finding x-values where a function has a specific slope. These examples will reinforce your understanding of derivatives and their application in determining tangent lines.

---

### Example 1: Finding the Equation of a Tangent Line

#### Problem:
Find the equation of the tangent line to the curve \( y = x^3 - 2x + 1 \) at \( x = 2 \).

#### Solution:
1. **Compute the derivative**:
   The derivative \( f'(x) \) represents the slope of the tangent line.
   \[
   f'(x) = \frac{d}{dx}(x^3 - 2x + 1) = 3x^2 - 2
   \]

2. **Evaluate the derivative at \( x = 2 \)**:
   \[
   f'(2) = 3(2)^2 - 2 = 3(4) - 2 = 12 - 2 = 10
   \]
   Thus, the slope of the tangent line at \( x = 2 \) is \( m = 10 \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = 2 \):
   \[
   f(2) = (2)^3 - 2(2) + 1 = 8 - 4 + 1 = 5
   \]
   The point of tangency is \( (2, 5) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = 10 \), \( x_1 = 2 \), and \( y_1 = 5 \):
   \[
   y - 5 = 10(x - 2)
   \]
   Simplify:
   \[
   y = 10x - 20 + 5
   \]
   \[
   y = 10x - 15
   \]

Thus, the equation of the tangent line is:
\[
\boxed{y = 10x - 15}
\]

---

### Example 2: Finding x-Values with a Specific Slope

#### Problem:
Find the x-values where the slope of the tangent line to the curve \( y = x^2 - 4x + 3 \) is equal to 2.

#### Solution:
1. **Compute the derivative**:
   The derivative \( f'(x) \) gives the slope of the tangent line.
   \[
   f'(x) = \frac{d}{dx}(x^2 - 4x + 3) = 2x - 4
   \]

2. **Set the derivative equal to the given slope**:
   Solve for \( x \) when \( f'(x) = 2 \):
   \[
   2x - 4 = 2
   \]
   Add 4 to both sides:
   \[
   2x = 6
   \]
   Divide by 2:
   \[
   x = 3
   \]

Thus, the x-value where the slope of the tangent line is 2 is:
\[
\boxed{x = 3}
\]

---

### Example 3: Tangent Line to a Composite Function

#### Problem:
Find the equation of the tangent line to the curve \( y = (x^2 + 1)^3 \) at \( x = 1 \).

#### Solution:
1. **Compute the derivative**:
   Use the Chain Rule to differentiate \( y = (x^2 + 1)^3 \):
   - Outer function: \( u^3 \), where \( u = x^2 + 1 \).
   - Inner function: \( u(x) = x^2 + 1 \).
   Differentiate the outer function:
   \[
   \frac{dy}{du} = 3u^2
   \]
   Differentiate the inner function:
   \[
   \frac{du}{dx} = 2x
   \]
   Multiply the derivatives:
   \[
   f'(x) = 3(x^2 + 1)^2 \cdot 2x = 6x(x^2 + 1)^2
   \]

2. **Evaluate the derivative at \( x = 1 \)**:
   \[
   f'(1) = 6(1)((1)^2 + 1)^2 = 6(1)(1 + 1)^2 = 6(1)(2)^2 = 6(4) = 24
   \]
   Thus, the slope of the tangent line at \( x = 1 \) is \( m = 24 \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = 1 \):
   \[
   f(1) = (1^2 + 1)^3 = (1 + 1)^3 = 2^3 = 8
   \]
   The point of tangency is \( (1, 8) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = 24 \), \( x_1 = 1 \), and \( y_1 = 8 \):
   \[
   y - 8 = 24(x - 1)
   \]
   Simplify:
   \[
   y = 24x - 24 + 8
   \]
   \[
   y = 24x - 16
   \]

Thus, the equation of the tangent line is:
\[
\boxed{y = 24x - 16}
\]

---

### Example 4: Tangent Line with a Rational Function

#### Problem:
Find the equation of the tangent line to the curve \( y = \frac{x^2}{x + 1} \) at \( x = 2 \).

#### Solution:
1. **Compute the derivative**:
   Use the Quotient Rule to differentiate \( y = \frac{x^2}{x + 1} \):
   \[
   \frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}
   \]
   Let \( u = x^2 \) and \( v = x + 1 \):
   \[
   u' = 2x, \quad v' = 1
   \]
   Substitute into the Quotient Rule:
   \[
   f'(x) = \frac{(2x)(x + 1) - (x^2)(1)}{(x + 1)^2}
   \]
   Simplify:
   \[
   f'(x) = \frac{2x^2 + 2x - x^2}{(x + 1)^2} = \frac{x^2 + 2x}{(x + 1)^2}
   \]

2. **Evaluate the derivative at \( x = 2 \)**:
   \[
   f'(2) = \frac{(2)^2 + 2(2)}{(2 + 1)^2} = \frac{4 + 4}{3^2} = \frac{8}{9}
   \]
   Thus, the slope of the tangent line at \( x = 2 \) is \( m = \frac{8}{9} \).

3. **Find the point of tangency**:
   Evaluate \( f(x) \) at \( x = 2 \):
   \[
   f(2) = \frac{(2)^2}{2 + 1} = \frac{4}{3}
   \]
   The point of tangency is \( \left(2, \frac{4}{3}\right) \).

4. **Write the equation of the tangent line**:
   Use the point-slope form of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = \frac{8}{9} \), \( x_1 = 2 \), and \( y_1 = \frac{4}{3} \):
   \[
   y - \frac{4}{3} = \frac{8}{9}(x - 2)
   \]
   Simplify:
   \[
   y = \frac{8}{9}x - \frac{16}{9} + \frac{4}{3}
   \]
   Convert \( \frac{4}{3} \) to a denominator of 9:
   \[
   y = \frac{8}{9}x - \frac{16}{9} + \frac{12}{9}
   \]
   \[
   y = \frac{8}{9}x - \frac{4}{9}
   \]

Thus, the equation of the tangent line is:
\[
\boxed{y = \frac{8}{9}x - \frac{4}{9}}
\]

---



### Example 5: Finding x-Values Where the Slope is Zero

#### Problem:
Find the x-values where the slope of the tangent line to the curve 
\[
y = x^4 - 4x^3 + 6x^2 - 4x + 1
\]
is zero.

#### Solution:
1. **Compute the derivative**:
   The slope of the tangent line is given by the derivative \( f'(x) \). Differentiate \( y = x^4 - 4x^3 + 6x^2 - 4x + 1 \):
   \[
   f'(x) = \frac{d}{dx}(x^4 - 4x^3 + 6x^2 - 4x + 1)
   \]
   Apply the Power Rule term by term:
   \[
   f'(x) = 4x^3 - 12x^2 + 12x - 4
   \]

2. **Set the derivative equal to zero**:
   To find the x-values where the slope is zero, solve the equation:
   \[
   f'(x) = 4x^3 - 12x^2 + 12x - 4 = 0
   \]

3. **Factor the cubic polynomial**:
   Factor out the greatest common factor (GCF), if possible:
   \[
   f'(x) = 4(x^3 - 3x^2 + 3x - 1)
   \]
   Notice that \( x^3 - 3x^2 + 3x - 1 \) is a perfect cube:
   \[
   x^3 - 3x^2 + 3x - 1 = (x - 1)^3
   \]
   Therefore:
   \[
   f'(x) = 4(x - 1)^3
   \]

4. **Solve for \( x \)**:
   Set \( f'(x) = 0 \):
   \[
   4(x - 1)^3 = 0
   \]
   Divide both sides by 4:
   \[
   (x - 1)^3 = 0
   \]
   Take the cube root of both sides:
   \[
   x - 1 = 0
   \]
   Solve for \( x \):
   \[
   x = 1
   \]

5. **Verify the solution**:
   Substitute \( x = 1 \) back into the original function to confirm it is a valid solution:
   \[
   f(1) = (1)^4 - 4(1)^3 + 6(1)^2 - 4(1) + 1 = 1 - 4 + 6 - 4 + 1 = 0
   \]
   The point \( (1, 0) \) lies on the curve, and the slope of the tangent line at \( x = 1 \) is indeed zero.

Thus, the x-value where the slope of the tangent line is zero is:
\[
\boxed{x = 1}
\]

---



### Learning Objectives
By the end of this section, students will:
1. Be able to compute the equation of a tangent line using the point-slope form.
2. Understand how to find x-values where a function has a specific slope.
3. Apply derivative rules (such as the Chain Rule and Quotient Rule) to solve problems involving tangent lines.