+++
title = '2.7 Practice'
weight = 2
+++

## Tangent Line Problems:

#### Ex1.

Determine the equation of the tangent line to the curve at \( x = 1 \):

\[
y = (x^2 + 3x)(2x - 1)^2
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


1. Differentiate \( y \) using the **product rule**:
   - First factor: \( u(x) = x^2 + 3x \), so \( u'(x) = 2x + 3 \).
   - Second factor: \( v(x) = (2x - 1)^2 \). Using the **chain rule**, \( v'(x) = 2(2x - 1) \cdot 2 = 4(2x - 1) \).

   The derivative is:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]
   Substituting:
   \[
   \frac{dy}{dx} = (2x + 3)(2x - 1)^2 + (x^2 + 3x) \cdot 4(2x - 1)
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = 1 \):
   - \( u(1) = 1^2 + 3(1) = 4 \), \( u'(1) = 2(1) + 3 = 5 \).
   - \( v(1) = (2(1) - 1)^2 = 1 \), \( v'(1) = 4(2(1) - 1) = 4 \).

   Substituting into the derivative:
   
   \[
   \frac{dy}{dx} = (5)(1) + (4)(4) = 5 + 16 = 21
   \]


3. Find \( y \)-coordinate at \( x = 1 \):
   
   \[
   y = (1^2 + 3(1))(2(1) - 1)^2 = (4)(1) = 4
   \]

4. Use the point-slope form of the equation of a line:
   
   \[
   y - y_1 = m(x - x_1)
   \]
   
   Substituting \( m = 21 \), \( x_1 = 1 \), and \( y_1 = 4 \):
   
   \[
   y - 4 = 21(x - 1)
   \]
   
   Simplify:
   
   \[
   y = 21x - 17
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = 21x - 17}
\]

</details>

---

#### Ex2.
Find the slope of the tangent line to the curve at \( x = -1 \):

\[
y = \frac{x^2 + 2x}{x^2 - 3x + 2}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **quotient rule**:
   - Numerator: \( u(x) = x^2 + 2x \), so \( u'(x) = 2x + 2 \).
   - Denominator: \( v(x) = x^2 - 3x + 2 \), so \( v'(x) = 2x - 3 \).

   The derivative is:

   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]

   Substituting:

   \[
   \frac{dy}{dx} = \frac{(2x + 2)(x^2 - 3x + 2) - (x^2 + 2x)(2x - 3)}{(x^2 - 3x + 2)^2}
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = -1 \):
   - \( u(-1) = (-1)^2 + 2(-1) = 1 - 2 = -1 \), \( u'(-1) = 2(-1) + 2 = 0 \).
   - \( v(-1) = (-1)^2 - 3(-1) + 2 = 1 + 3 + 2 = 6 \), \( v'(-1) = 2(-1) - 3 = -2 - 3 = -5 \).

   Substituting into the derivative:

   \[
   \frac{dy}{dx} = \frac{(0)(6) - (-1)(-5)}{6^2} = \frac{0 - 5}{36} = -\frac{5}{36}
   \]

Thus, the slope of the tangent line is:

\[
\boxed{-\frac{5}{36}}
\]

</details>

---

#### Ex3.
Find the \( x \)-coordinates where the slope of the tangent line is \( 0 \):

\[
y = (x^2 - 4)(x + 1)^3
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


1. Differentiate \( y \) using the **product rule**:
   - First factor: \( u(x) = x^2 - 4 \), so \( u'(x) = 2x \).
   - Second factor: \( v(x) = (x + 1)^3 \). Using the **chain rule**, \( v'(x) = 3(x + 1)^2 \cdot 1 = 3(x + 1)^2 \).

   The derivative is:
  
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]
  
   Substituting:
 
   \[
   \frac{dy}{dx} = (2x)(x + 1)^3 + (x^2 - 4) \cdot 3(x + 1)^2
   \]

2. Factor out \( (x + 1)^2 \):
  
   \[
   \frac{dy}{dx} = (x + 1)^2 \left[ 2x(x + 1) + 3(x^2 - 4) \right]
   \]
 
   Simplify the terms inside the brackets:
 
   \[
   2x(x + 1) + 3(x^2 - 4) = 2x^2 + 2x + 3x^2 - 12 = 5x^2 + 2x - 12
   \]
 
   So:
 
   \[
   \frac{dy}{dx} = (x + 1)^2 (5x^2 + 2x - 12)
   \]

3. Set \( \frac{dy}{dx} = 0 \):
   - \( (x + 1)^2 = 0 \) gives \( x = -1 \).
   - Solve \( 5x^2 + 2x - 12 = 0 \) using the quadratic formula:
 
     \[
     x = \frac{-2 \pm \sqrt{2^2 - 4(5)(-12)}}{2(5)} = \frac{-2 \pm \sqrt{4 + 240}}{10} = \frac{-2 \pm \sqrt{244}}{10} = \frac{-2 \pm 2\sqrt{61}}{10} = \frac{-1 \pm \sqrt{61}}{5}
     \]

Thus, the \( x \)-coordinates are:

\[
\boxed{x = -1, \, x = \frac{-1 + \sqrt{61}}{5}, \, x = \frac{-1 - \sqrt{61}}{5}}
\]

</details>

---

#### Ex4.
Find the equation of the tangent line to the curve at \( x = 2 \):

\[
y = \frac{x^3 - 2x}{x^2 + 1}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


1. Differentiate \( y \) using the **quotient rule**:
   - Numerator: \( u(x) = x^3 - 2x \), so \( u'(x) = 3x^2 - 2 \).
   - Denominator: \( v(x) = x^2 + 1 \), so \( v'(x) = 2x \).

   The derivative is:
 
   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
 
   Substituting:
 
   \[
   \frac{dy}{dx} = \frac{(3x^2 - 2)(x^2 + 1) - (x^3 - 2x)(2x)}{(x^2 + 1)^2}
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = 2 \):
   - \( u(2) = 2^3 - 2(2) = 8 - 4 = 4 \), \( u'(2) = 3(2^2) - 2 = 12 - 2 = 10 \).
   - \( v(2) = 2^2 + 1 = 4 + 1 = 5 \), \( v'(2) = 2(2) = 4 \).

   Substituting into the derivative:
 
   \[
   \frac{dy}{dx} = \frac{(10)(5) - (4)(4)}{5^2} = \frac{50 - 16}{25} = \frac{34}{25}
   \]

3. Find \( y \)-coordinate at \( x = 2 \):
 
   \[
   y = \frac{2^3 - 2(2)}{2^2 + 1} = \frac{8 - 4}{4 + 1} = \frac{4}{5}
   \]

4. Use the point-slope form of the equation of a line:

   \[
   y - y_1 = m(x - x_1)
   \]
 
   Substituting \( m = \frac{34}{25} \), \( x_1 = 2 \), and \( y_1 = \frac{4}{5} \):

   \[
   y - \frac{4}{5} = \frac{34}{25}(x - 2)
   \]
 
   Simplify:
 
   \[
   y = \frac{34}{25}x - \frac{68}{25} + \frac{4}{5}
   \]
 
   Convert \( \frac{4}{5} \) to \( \frac{20}{25} \):
 
   \[
   y = \frac{34}{25}x - \frac{68}{25} + \frac{20}{25} = \frac{34}{25}x - \frac{48}{25}
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = \frac{34}{25}x - \frac{48}{25}}
\]

</details>


<iframe src="https://script.google.com/macros/s/AKfycbwhPmz2cV8xcB7hC1b711Wj76djNE5xQdilXbo0Pmh83vOlDWWt58Uzj3nSnBQWcPNX4w/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>