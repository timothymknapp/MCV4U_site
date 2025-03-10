+++
title = '3.6 Practice'
weight = 2
+++

## Tangent Line Problems:

#### Ex1.
Determine the equation of the tangent line to the curve at \( x = 0 \):

\[
y = e^{x^2} \cdot \sin(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **product rule**:
   - First factor: \( u(x) = e^{x^2} \), so \( u'(x) = 2x e^{x^2} \).
   - Second factor: \( v(x) = \sin(x) \), so \( v'(x) = \cos(x) \).

   The derivative is:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]
   Substituting:
   \[
   \frac{dy}{dx} = (2x e^{x^2})\sin(x) + (e^{x^2})\cos(x)
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = 0 \):
   - \( u(0) = e^{0^2} = 1 \), \( u'(0) = 2(0)e^{0^2} = 0 \).
   - \( v(0) = \sin(0) = 0 \), \( v'(0) = \cos(0) = 1 \).

   Substituting into the derivative:
   \[
   \frac{dy}{dx} = (0)(0) + (1)(1) = 1
   \]

3. Find \( y \)-coordinate at \( x = 0 \):
   \[
   y = e^{0^2} \cdot \sin(0) = 1 \cdot 0 = 0
   \]

4. Use the point-slope form of the equation of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = 1 \), \( x_1 = 0 \), and \( y_1 = 0 \):
   \[
   y - 0 = 1(x - 0)
   \]
   Simplify:
   \[
   y = x
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = x}
\]

</details>

---

#### Ex2.
Find the slope of the tangent line to the curve at \( x = \ln(2) \):

\[
y = \ln(e^{x^2} + 1)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **chain rule**:
   - Outer function: \( w(z) = \ln(z) \), where \( z = e^{x^2} + 1 \).
   - Inner function: \( z(x) = e^{x^2} + 1 \).

   The derivative is:
   \[
   \frac{dy}{dx} = \frac{1}{z} \cdot \frac{dz}{dx} = \frac{1}{e^{x^2} + 1} \cdot \frac{d}{dx}(e^{x^2})
   \]
   Differentiate \( e^{x^2} \) using the **chain rule**:
   \[
   \frac{d}{dx}(e^{x^2}) = e^{x^2} \cdot 2x
   \]
   Substituting:
   \[
   \frac{dy}{dx} = \frac{e^{x^2} \cdot 2x}{e^{x^2} + 1}
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = \ln(2) \):
   - \( e^{(\ln(2))^2} = e^{\ln^2(2)} \).

   Substituting:
   \[
   \frac{dy}{dx} = \frac{e^{\ln^2(2)} \cdot 2\ln(2)}{e^{\ln^2(2)} + 1}
   \]

Thus, the slope of the tangent line is:

\[
\boxed{\frac{e^{\ln^2(2)} \cdot 2\ln(2)}{e^{\ln^2(2)} + 1}}
\]

</details>

---

#### Ex3.
Find the \( x \)-coordinates where the slope of the tangent line is \( 0 \):

\[
y = e^{\sin(x^2)}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **chain rule**:
   - Outer function: \( w(z) = e^z \), where \( z = \sin(x^2) \).
   - Inner function: \( z(x) = \sin(x^2) \).

   The derivative is:
   \[
   \frac{dy}{dx} = e^{\sin(x^2)} \cdot \frac{d}{dx}(\sin(x^2))
   \]
   Differentiate \( \sin(x^2) \) using the **chain rule**:
   \[
   \frac{d}{dx}(\sin(x^2)) = \cos(x^2) \cdot 2x
   \]
   Substituting:
   \[
   \frac{dy}{dx} = e^{\sin(x^2)} \cdot \cos(x^2) \cdot 2x
   \]

2. Set \( \frac{dy}{dx} = 0 \):
   - Since \( e^{\sin(x^2)} > 0 \), we solve \( \cos(x^2) \cdot 2x = 0 \).
   - This gives \( \cos(x^2) = 0 \) or \( x = 0 \).

   Solve \( \cos(x^2) = 0 \):
   \[
   x^2 = \frac{\pi}{2} + n\pi, \quad n \in \mathbb{Z}
   \]
   \[
   x = \pm\sqrt{\frac{\pi}{2} + n\pi}, \quad n \in \mathbb{Z}
   \]

Thus, the \( x \)-coordinates are:

\[
\boxed{x = 0, \, x = \pm\sqrt{\frac{\pi}{2} + n\pi}, \, n \in \mathbb{Z}}
\]

</details>

---

#### Ex4.
Find the equation of the tangent line to the curve at \( x = \frac{\pi}{4} \):

\[
y = \frac{\ln(\cos(x))}{e^{2x}}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **quotient rule**:
   - Numerator: \( u(x) = \ln(\cos(x)) \), so \( u'(x) = \frac{-\sin(x)}{\cos(x)} = -\tan(x) \).
   - Denominator: \( v(x) = e^{2x} \), so \( v'(x) = 2e^{2x} \).

   The derivative is:
   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
   Substituting:
   \[
   \frac{dy}{dx} = \frac{(-\tan(x))(e^{2x}) - (\ln(\cos(x)))(2e^{2x})}{(e^{2x})^2}
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = \frac{\pi}{4} \):
   - \( u\left(\frac{\pi}{4}\right) = \ln\left(\cos\left(\frac{\pi}{4}\right)\right) = \ln\left(\frac{\sqrt{2}}{2}\right) \).
   - \( u'\left(\frac{\pi}{4}\right) = -\tan\left(\frac{\pi}{4}\right) = -1 \).
   - \( v\left(\frac{\pi}{4}\right) = e^{2\left(\frac{\pi}{4}\right)} = e^{\frac{\pi}{2}} \).
   - \( v'\left(\frac{\pi}{4}\right) = 2e^{\frac{\pi}{2}} \).

   Substituting:
   \[
   \frac{dy}{dx} = \frac{(-1)(e^{\frac{\pi}{2}}) - \left(\ln\left(\frac{\sqrt{2}}{2}\right)\right)(2e^{\frac{\pi}{2}})}{(e^{\frac{\pi}{2}})^2}
   \]

3. Find \( y \)-coordinate at \( x = \frac{\pi}{4} \):
   \[
   y = \frac{\ln\left(\cos\left(\frac{\pi}{4}\right)\right)}{e^{2\left(\frac{\pi}{4}\right)}} = \frac{\ln\left(\frac{\sqrt{2}}{2}\right)}{e^{\frac{\pi}{2}}}
   \]

4. Use the point-slope form of the equation of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m \), \( x_1 = \frac{\pi}{4} \), and \( y_1 = \frac{\ln\left(\frac{\sqrt{2}}{2}\right)}{e^{\frac{\pi}{2}}} \).

Thus, the equation of the tangent line is:

\[
\boxed{y = \text{(Simplified Expression)}}
\]

</details>

<iframe src="https://script.google.com/macros/s/AKfycbxTWmoFuJ8VeLHUtYhR9YWffOZe5nMyFT6NLHjD1CDVezPfsFWoMHYIrm4EBOmcZTyTmQ/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>