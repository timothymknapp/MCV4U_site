+++
title = '4.3 Examples'
weight = 1
+++


### Example 1: Polynomial Function
Determine the points of inflection for the function \( f(x) = x^3 + x - 3 \).

#### Solution:
Write the given function:  

\[ f(x) = x^3 + x - 3 \]  

Compute the first derivative:  

\[ f'(x) = 3x^2 + 1 \]  

Compute the second derivative:  

\[ f''(x) = 6x \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  

\[ 6x = 0 \implies x = 0 \]  

Check the concavity around \( x = 0 \):

- For \( x < 0 \), choose \( x = -1 \):  

  \[ f''(-1) = 6(-1) = -6 < 0 \] (\( f(x) \) is concave down).

- For \( x > 0 \), choose \( x = 1 \):  

  \[ f''(1) = 6(1) = 6 > 0 \] (\( f(x) \) is concave up).

Since the concavity changes at \( x = 0 \), it is a **point of inflection**.

Find the \( y \)-coordinate at \( x = 0 \):  

\[ f(0) = (0)^3 + (0) - 3 = -3 \]

Thus, the point of inflection is:  

\[ \boxed{(0, -3)} \]

---

### Example 2: Rational Function
Determine the points of inflection for the function \( f(x) = \frac{x}{x^2 + 1} \).

#### Solution:
Write the given function:  

\[ f(x) = \frac{x}{x^2 + 1} \]  

Compute the first derivative using the quotient rule:  

\[ f'(x) = \frac{(x^2 + 1)(1) - x(2x)}{(x^2 + 1)^2} = \frac{-x^2 + 1}{(x^2 + 1)^2} \]  

Compute the second derivative using the quotient rule again:  

\[ f''(x) = \frac{(x^2 + 1)^2(-2x) - (-x^2 + 1)(2)(x^2 + 1)(2x)}{(x^2 + 1)^4} \]  

Simplify:  

\[ f''(x) = \frac{-2x(x^2 + 1) + 4x(x^2 - 1)}{(x^2 + 1)^3} = \frac{2x^3 - 6x}{(x^2 + 1)^3} \]  

Factorize:  

\[ f''(x) = \frac{2x(x^2 - 3)}{(x^2 + 1)^3} \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  

\[ 2x(x^2 - 3) = 0 \implies x = 0, \pm\sqrt{3} \]  

Check the concavity around the critical points:
- For \( x < -\sqrt{3} \), choose \( x = -2 \):  

  \[ f''(-2) = \frac{2(-2)((-2)^2 - 3)}{((-2)^2 + 1)^3} = \frac{-4(4 - 3)}{(4 + 1)^3} = \frac{-4}{125} < 0 \] (\( f(x) \) is concave down).

- For \( -\sqrt{3} < x < 0 \), choose \( x = -1 \):  

  \[ f''(-1) = \frac{2(-1)((-1)^2 - 3)}{((-1)^2 + 1)^3} = \frac{-2(1 - 3)}{(1 + 1)^3} = \frac{-2(-2)}{8} = \frac{4}{8} > 0 \] (\( f(x) \) is concave up).

- For \( 0 < x < \sqrt{3} \), choose \( x = 1 \):  

  \[ f''(1) = \frac{2(1)((1)^2 - 3)}{((1)^2 + 1)^3} = \frac{2(1 - 3)}{(1 + 1)^3} = \frac{2(-2)}{8} = \frac{-4}{8} < 0 \] (\( f(x) \) is concave down).

- For \( x > \sqrt{3} \), choose \( x = 2 \):  

  \[ f''(2) = \frac{2(2)((2)^2 - 3)}{((2)^2 + 1)^3} = \frac{4(4 - 3)}{(4 + 1)^3} = \frac{4}{125} > 0 \] (\( f(x) \) is concave up).

Since the concavity changes at \( x = -\sqrt{3}, 0, \sqrt{3} \), these are **points of inflection**.

Find the \( y \)-coordinates:
- At \( x = -\sqrt{3} \):  
  \[ f(-\sqrt{3}) = \frac{-\sqrt{3}}{(-\sqrt{3})^2 + 1} = \frac{-\sqrt{3}}{3 + 1} = \frac{-\sqrt{3}}{4} \]
- At \( x = 0 \):  
  \[ f(0) = \frac{0}{0^2 + 1} = 0 \]
- At \( x = \sqrt{3} \):  
  \[ f(\sqrt{3}) = \frac{\sqrt{3}}{(\sqrt{3})^2 + 1} = \frac{\sqrt{3}}{3 + 1} = \frac{\sqrt{3}}{4} \]

Thus, the points of inflection are:  
\[ \boxed{\left(-\sqrt{3}, \frac{-\sqrt{3}}{4}\right), (0, 0), \left(\sqrt{3}, \frac{\sqrt{3}}{4}\right)} \]

---

### Example 3: Trigonometric Function
Determine the points of inflection for the function \( f(x) = \sin(x) + \cos(x) \) on the interval \( [0, 2\pi] \).

#### Solution:
Write the given function:  

\[ f(x) = \sin(x) + \cos(x) \]  

Compute the first derivative:  

\[ f'(x) = \cos(x) - \sin(x) \]  

Compute the second derivative:  

\[ f''(x) = -\sin(x) - \cos(x) \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  

\[ -\sin(x) - \cos(x) = 0 \implies \sin(x) + \cos(x) = 0 \]  

Divide through by \( \cos(x) \) (valid since \( \cos(x) \neq 0 \)):  

\[ \tan(x) = -1 \]  

Solve for \( x \): \( x = \frac{3\pi}{4}, \frac{7\pi}{4} \) (in the interval \( [0, 2\pi] \)).

Check the concavity around the critical points:
- For \( x = \frac{3\pi}{4} \):
  - For \( x < \frac{3\pi}{4} \), choose \( x = \frac{\pi}{2} \):  

    \[ f''\left(\frac{\pi}{2}\right) = -\sin\left(\frac{\pi}{2}\right) - \cos\left(\frac{\pi}{2}\right) = -1 < 0 \] (\( f(x) \) is concave down).
  - For \( x > \frac{3\pi}{4} \), choose \( x = \pi \):  

    \[ f''(\pi) = -\sin(\pi) - \cos(\pi) = 0 - (-1) = 1 > 0 \] (\( f(x) \) is concave up).

- For \( x = \frac{7\pi}{4} \):
  - For \( x < \frac{7\pi}{4} \), choose \( x = \frac{3\pi}{2} \):  

    \[ f''\left(\frac{3\pi}{2}\right) = -\sin\left(\frac{3\pi}{2}\right) - \cos\left(\frac{3\pi}{2}\right) = 1 > 0 \] (\( f(x) \) is concave up).

  - For \( x > \frac{7\pi}{4} \), choose \( x = 2\pi \):  

    \[ f''(2\pi) = -\sin(2\pi) - \cos(2\pi) = 0 - 1 = -1 < 0 \] (\( f(x) \) is concave down).

Since the concavity changes at \( x = \frac{3\pi}{4} \) and \( x = \frac{7\pi}{4} \), these are **points of inflection**.

Find the \( y \)-coordinates:
- At \( x = \frac{3\pi}{4} \):  

  \[ f\left(\frac{3\pi}{4}\right) = \sin\left(\frac{3\pi}{4}\right) + \cos\left(\frac{3\pi}{4}\right) = \frac{\sqrt{2}}{2} - \frac{\sqrt{2}}{2} = 0 \]
- At \( x = \frac{7\pi}{4} \):  

  \[ f\left(\frac{7\pi}{4}\right) = \sin\left(\frac{7\pi}{4}\right) + \cos\left(\frac{7\pi}{4}\right) = -\frac{\sqrt{2}}{2} + \frac{\sqrt{2}}{2} = 0 \]

Thus, the points of inflection are:  
\[ \boxed{\left(\frac{3\pi}{4}, 0\right), \left(\frac{7\pi}{4}, 0\right)} \]

---

### Example 4: Exponential Function
Determine the points of inflection for the function \( f(x) = 3^{4x^2} \).

#### Solution:
Write the given function:  

\[ f(x) = 3^{4x^2} \]  

Compute the first derivative using the chain rule:  

\[ f'(x) = 3^{4x^2} \cdot \ln(3) \cdot \frac{d}{dx}(4x^2) = 3^{4x^2} \cdot \ln(3) \cdot 8x \]  

Simplify:  

\[ f'(x) = 8x \cdot 3^{4x^2} \cdot \ln(3) \]  

Compute the second derivative using the product rule:  

\[ f''(x) = \frac{d}{dx}(8x) \cdot 3^{4x^2} \cdot \ln(3) + 8x \cdot \frac{d}{dx}\left(3^{4x^2} \cdot \ln(3)\right) \]  

Differentiate \( 3^{4x^2} \cdot \ln(3) \) using the chain rule:  

\[ \frac{d}{dx}\left(3^{4x^2}\right) = 3^{4x^2} \cdot \ln(3) \cdot 8x \]  

Substitute into the product rule:  

\[ f''(x) = 8 \cdot 3^{4x^2} \cdot \ln(3) + 8x \cdot \left(3^{4x^2} \cdot \ln(3) \cdot 8x \cdot \ln(3)\right) \]  

Simplify:  

\[ f''(x) = 8 \cdot 3^{4x^2} \cdot \ln(3) + 64x^2 \cdot 3^{4x^2} \cdot (\ln(3))^2 \]  

Factorize:  

\[ f''(x) = 3^{4x^2} \cdot \ln(3) \cdot \left(8 + 64x^2 \cdot \ln(3)\right) \]  

Set \( f''(x) = 0 \):  
Since \( 3^{4x^2} > 0 \) and \( \ln(3) > 0 \) for all \( x \), solve \( 8 + 64x^2 \cdot \ln(3) = 0 \):  

\[ 64x^2 \cdot \ln(3) = -8 \implies x^2 = -\frac{8}{64 \cdot \ln(3)} \]  

This equation has no real solutions because \( x^2 \geq 0 \) for all \( x \).  

Thus, there are **no points of inflection** for this function.

Conclusion:  
\[ \boxed{\text{No points of inflection}} \]
