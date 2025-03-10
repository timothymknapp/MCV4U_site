+++
title = '3.5 Practice'
weight = 2
+++

## Practice with Transcendental Functions and Tangent Lines:

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
y = \ln(x^2 + 1)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **chain rule**:
   - Let \( u(x) = x^2 + 1 \), so \( u'(x) = 2x \).
   - Then \( y = \ln(u) \), so \( \frac{dy}{dx} = \frac{u'(x)}{u(x)} \).

   Substituting:
   \[
   \frac{dy}{dx} = \frac{2x}{x^2 + 1}
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = \ln(2) \):
   - \( u(\ln(2)) = (\ln(2))^2 + 1 \).
   - \( u'(\ln(2)) = 2\ln(2) \).

   Substituting into the derivative:
   \[
   \frac{dy}{dx} = \frac{2\ln(2)}{(\ln(2))^2 + 1}
   \]

Thus, the slope of the tangent line is:

\[
\boxed{\frac{2\ln(2)}{(\ln(2))^2 + 1}}
\]

</details>

---

#### Ex3.
Find the \( x \)-coordinates where the slope of the tangent line is \( 0 \):

\[
y = e^x \cdot \cos(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **product rule**:
   - First factor: \( u(x) = e^x \), so \( u'(x) = e^x \).
   - Second factor: \( v(x) = \cos(x) \), so \( v'(x) = -\sin(x) \).

   The derivative is:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]
   Substituting:
   \[
   \frac{dy}{dx} = (e^x)\cos(x) + (e^x)(-\sin(x))
   \]
   Simplify:
   \[
   \frac{dy}{dx} = e^x(\cos(x) - \sin(x))
   \]

2. Set \( \frac{dy}{dx} = 0 \):
   - Since \( e^x > 0 \) for all \( x \), we solve \( \cos(x) - \sin(x) = 0 \).
   - Rearrange: \( \cos(x) = \sin(x) \).
   - Divide by \( \cos(x) \) (assuming \( \cos(x) \neq 0 \)): \( \tan(x) = 1 \).
   - Solve: \( x = \frac{\pi}{4} + n\pi \), where \( n \) is an integer.

Thus, the \( x \)-coordinates are:

\[
\boxed{x = \frac{\pi}{4} + n\pi, \, n \in \mathbb{Z}}
\]

</details>

---

#### Ex4.
Find the equation of the tangent line to the curve at \( x = \frac{\pi}{6} \):

\[
y = \ln(\sin(x))
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Differentiate \( y \) using the **chain rule**:
   - Let \( u(x) = \sin(x) \), so \( u'(x) = \cos(x) \).
   - Then \( y = \ln(u) \), so \( \frac{dy}{dx} = \frac{u'(x)}{u(x)} \).

   Substituting:
   \[
   \frac{dy}{dx} = \frac{\cos(x)}{\sin(x)} = \cot(x)
   \]

2. Evaluate \( \frac{dy}{dx} \) at \( x = \frac{\pi}{6} \):
   - \( \cot\left(\frac{\pi}{6}\right) = \frac{\cos\left(\frac{\pi}{6}\right)}{\sin\left(\frac{\pi}{6}\right)} = \frac{\sqrt{3}/2}{1/2} = \sqrt{3} \).

3. Find \( y \)-coordinate at \( x = \frac{\pi}{6} \):
   \[
   y = \ln\left(\sin\left(\frac{\pi}{6}\right)\right) = \ln\left(\frac{1}{2}\right) = -\ln(2)
   \]

4. Use the point-slope form of the equation of a line:
   \[
   y - y_1 = m(x - x_1)
   \]
   Substituting \( m = \sqrt{3} \), \( x_1 = \frac{\pi}{6} \), and \( y_1 = -\ln(2) \):
   \[
   y + \ln(2) = \sqrt{3}\left(x - \frac{\pi}{6}\right)
   \]
   Simplify:
   \[
   y = \sqrt{3}x - \frac{\sqrt{3}\pi}{6} - \ln(2)
   \]

Thus, the equation of the tangent line is:

\[
\boxed{y = \sqrt{3}x - \frac{\sqrt{3}\pi}{6} - \ln(2)}
\]

</details>


<iframe src="https://script.google.com/macros/s/AKfycbwq7b15ovoTjGqSgoyuS_QmGS1XIQgP9r4p5J9CTZfh_Z7wZ6CIKFTB0EyA4NrUWc9VRQ/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>