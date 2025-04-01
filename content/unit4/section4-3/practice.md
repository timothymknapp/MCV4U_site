+++
title = '4.3 Practice'
weight = 2
+++



Ex1.
Determine the points of inflection for the function \( f(x) = x^3 - 6x^2 + 9x + 2 \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = x^3 - 6x^2 + 9x + 2 \]  
Compute the first derivative: \[ f'(x) = 3x^2 - 12x + 9 \]  
Compute the second derivative: \[ f''(x) = 6x - 12 \]  
Set \( f''(x) = 0 \) to find potential points of inflection: \[ 6x - 12 = 0 \implies x = 2 \]  

Check the concavity around \( x = 2 \):
- For \( x < 2 \), choose \( x = 1 \): \[ f''(1) = 6(1) - 12 = -6 < 0 \] (\( f(x) \) is concave down).
- For \( x > 2 \), choose \( x = 3 \): \[ f''(3) = 6(3) - 12 = 6 > 0 \] (\( f(x) \) is concave up).

Since the concavity changes at \( x = 2 \), it is a **point of inflection**.

Find the \( y \)-coordinate at \( x = 2 \): \[ f(2) = (2)^3 - 6(2)^2 + 9(2) + 2 = 8 - 24 + 18 + 2 = 4 \]

Thus, the point of inflection is:
\[ \boxed{(2, 4)} \]
</details>

---

Ex2.
Determine the points of inflection for the function \( f(x) = x^4 - 4x^3 + 6x^2 \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = x^4 - 4x^3 + 6x^2 \]  
Compute the first derivative: \[ f'(x) = 4x^3 - 12x^2 + 12x \]  
Compute the second derivative: \[ f''(x) = 12x^2 - 24x + 12 \]  
Factorize \( f''(x) \): \[ f''(x) = 12(x^2 - 2x + 1) = 12(x - 1)^2 \]  
Set \( f''(x) = 0 \) to find potential points of inflection: \[ 12(x - 1)^2 = 0 \implies x = 1 \]  

Check the concavity around \( x = 1 \):
- For \( x < 1 \), choose \( x = 0 \): \[ f''(0) = 12(0 - 1)^2 = 12 > 0 \] (\( f(x) \) is concave up).
- For \( x > 1 \), choose \( x = 2 \): \[ f''(2) = 12(2 - 1)^2 = 12 > 0 \] (\( f(x) \) is concave up).

Since the concavity does not change at \( x = 1 \), it is **not** a point of inflection.

Thus, there are no points of inflection:
\[ \boxed{\text{No points of inflection}} \]
</details>

---

Ex3.
Determine the points of inflection for the function \( f(x) = \sqrt{3}\sin(x) - \cos(x) \) on the interval \( [0, 2\pi] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  

\[ f(x) = \sqrt{3}\sin(x) - \cos(x) \]  

Compute the first derivative:  

\[ f'(x) = \sqrt{3}\cos(x) + \sin(x) \]  

Compute the second derivative:  

\[ f''(x) = -\sqrt{3}\sin(x) + \cos(x) \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ -\sqrt{3}\sin(x) + \cos(x) = 0 \implies \cos(x) = \sqrt{3}\sin(x) \]  

Divide through by \( \cos(x) \) (valid since \( \cos(x) \neq 0 \)):  

\[ \tan(x) = \frac{1}{\sqrt{3}} \]  

Solve for \( x \):  

Using trigonometric properties, we know that \( \tan(x) = \frac{1}{\sqrt{3}} \) corresponds to the special angles:  

\[ x = \frac{\pi}{6}, \quad x = \pi + \frac{\pi}{6} = \frac{7\pi}{6} \]  

These are the two solutions in the interval \( [0, 2\pi] \).

Check the concavity around the critical points:
- For \( x = \frac{\pi}{6} \):
  - For \( x < \frac{\pi}{6} \), choose \( x = 0 \):  
    \[ f''(0) = -\sqrt{3}\sin(0) + \cos(0) = 0 + 1 = 1 > 0 \] (\( f(x) \) is concave up).
  - For \( x > \frac{\pi}{6} \), choose \( x = \frac{\pi}{4} \):  
    \[ f''\left(\frac{\pi}{4}\right) = -\sqrt{3}\sin\left(\frac{\pi}{4}\right) + \cos\left(\frac{\pi}{4}\right) = -\sqrt{3}\left(\frac{\sqrt{2}}{2}\right) + \frac{\sqrt{2}}{2} = \frac{\sqrt{2}}{2}(1 - \sqrt{3}) < 0 \] (\( f(x) \) is concave down).
- For \( x = \frac{7\pi}{6} \):
  - For \( x < \frac{7\pi}{6} \), choose \( x = \pi \):  
    \[ f''(\pi) = -\sqrt{3}\sin(\pi) + \cos(\pi) = -\sqrt{3}(0) + (-1) = -1 < 0 \] (\( f(x) \) is concave down).
  - For \( x > \frac{7\pi}{6} \), choose \( x = 2\pi \):  
    \[ f''(2\pi) = -\sqrt{3}\sin(2\pi) + \cos(2\pi) = -\sqrt{3}(0) + 1 = 1 > 0 \] (\( f(x) \) is concave up).

Since the concavity changes at \( x = \frac{\pi}{6} \) and \( x = \frac{7\pi}{6} \), these are **points of inflection**.

Find the \( y \)-coordinates:
- At \( x = \frac{\pi}{6} \):  
  \[ f\left(\frac{\pi}{6}\right) = \sqrt{3}\sin\left(\frac{\pi}{6}\right) - \cos\left(\frac{\pi}{6}\right) = \sqrt{3}\left(\frac{1}{2}\right) - \frac{\sqrt{3}}{2} = 0 \]
- At \( x = \frac{7\pi}{6} \):  
  \[ f\left(\frac{7\pi}{6}\right) = \sqrt{3}\sin\left(\frac{7\pi}{6}\right) - \cos\left(\frac{7\pi}{6}\right) = \sqrt{3}\left(-\frac{1}{2}\right) - \left(-\frac{\sqrt{3}}{2}\right) = 0 \]

Thus, the points of inflection are:  
\[ \boxed{\left(\frac{\pi}{6}, 0\right), \left(\frac{7\pi}{6}, 0\right)} \]
</details>

---

Ex4.
Determine the points of inflection for the function \( f(x) = e^{-x^2} \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = e^{-x^2} \]  
Compute the first derivative: \[ f'(x) = -2x e^{-x^2} \]  
Compute the second derivative using the product rule: 
\[ f''(x) = (-2x)(-2x e^{-x^2}) + (-2)(e^{-x^2}) = 4x^2 e^{-x^2} - 2e^{-x^2} \]  
Factorize \( f''(x) \): \[ f''(x) = e^{-x^2}(4x^2 - 2) \]  
Set \( f''(x) = 0 \): Since \( e^{-x^2} > 0 \) for all \( x \), solve \( 4x^2 - 2 = 0 \): \[ 4x^2 = 2 \implies x^2 = \frac{1}{2} \implies x = \pm \frac{1}{\sqrt{2}} \]  

Check the concavity around the critical points:
- For \( x = \frac{1}{\sqrt{2}} \):
  - For \( x < \frac{1}{\sqrt{2}} \), choose \( x = 0 \): \[ f''(0) = e^{-(0)^2}(4(0)^2 - 2) = -2 < 0 \] (\( f(x) \) is concave down).
  - For \( x > \frac{1}{\sqrt{2}} \), choose \( x = 1 \): \[ f''(1) = e^{-(1)^2}(4(1)^2 - 2) = e^{-1}(4 - 2) = 2e^{-1} > 0 \] (\( f(x) \) is concave up).
- For \( x = -\frac{1}{\sqrt{2}} \):
  - For \( x < -\frac{1}{\sqrt{2}} \), choose \( x = -1 \): \[ f''(-1) = e^{-(-1)^2}(4(-1)^2 - 2) = e^{-1}(4 - 2) = 2e^{-1} > 0 \] (\( f(x) \) is concave up).
  - For \( x > -\frac{1}{\sqrt{2}} \), choose \( x = 0 \): \[ f''(0) = e^{-(0)^2}(4(0)^2 - 2) = -2 < 0 \] (\( f(x) \) is concave down).

Since the concavity changes at both \( x = \frac{1}{\sqrt{2}} \) and \( x = -\frac{1}{\sqrt{2}} \), these are **points of inflection**.

Find the \( y \)-coordinates:
- At \( x = \frac{1}{\sqrt{2}} \): \[ f\left(\frac{1}{\sqrt{2}}\right) = e^{-\left(\frac{1}{\sqrt{2}}\right)^2} = e^{-\frac{1}{2}} \]
- At \( x = -\frac{1}{\sqrt{2}} \): \[ f\left(-\frac{1}{\sqrt{2}}\right) = e^{-\left(-\frac{1}{\sqrt{2}}\right)^2} = e^{-\frac{1}{2}} \]

Thus, the points of inflection are:
\[ \boxed{\left(\frac{1}{\sqrt{2}}, e^{-\frac{1}{2}}\right) \text{ and } \left(-\frac{1}{\sqrt{2}}, e^{-\frac{1}{2}}\right)} \]
</details>

<iframe src="https://script.google.com/macros/s/AKfycbzhT-nYR3QwPn2ko64sdDApWltyqhsv7pq8J2yddANTkFwIs7zn4mQtUcCG1kVRUI0/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

