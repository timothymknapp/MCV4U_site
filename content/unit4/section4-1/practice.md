+++
title = '4.1 Practice'
weight = 2
+++


Ex1.
Find the maximum and minimum values of the cubic polynomial \( f(x) = x^3 - 3x^2 - 9x + 5 \) using the first derivative test.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = x^3 - 3x^2 - 9x + 5 \]  
Compute the derivative: \[ f'(x) = 3x^2 - 6x - 9 \]  
Set \( f'(x) = 0 \) to find critical points: \[ 3x^2 - 6x - 9 = 0 \implies x^2 - 2x - 3 = 0 \]  
Factorize: \[ (x - 3)(x + 1) = 0 \]  
Critical points: \( x = 3 \) and \( x = -1 \).  

Use the first derivative test to determine the behavior of \( f'(x) \) around the critical points:
- For \( x < -1 \), choose \( x = -2 \): \[ f'(-2) = 3(-2)^2 - 6(-2) - 9 = 12 + 12 - 9 = 15 > 0 \] (\( f(x) \) is increasing).
- For \( -1 < x < 3 \), choose \( x = 0 \): \[ f'(0) = 3(0)^2 - 6(0) - 9 = -9 < 0 \] (\( f(x) \) is decreasing).
- For \( x > 3 \), choose \( x = 4 \): \[ f'(4) = 3(4)^2 - 6(4) - 9 = 48 - 24 - 9 = 15 > 0 \] (\( f(x) \) is increasing).

From the first derivative test:
- At \( x = -1 \), \( f(x) \) changes from increasing to decreasing → **local maximum**.
- At \( x = 3 \), \( f(x) \) changes from decreasing to increasing → **local minimum**.

Evaluate \( f(x) \) at the critical points:
- \( f(-1) = (-1)^3 - 3(-1)^2 - 9(-1) + 5 = -1 - 3 + 9 + 5 = 10 \) (local maximum).
- \( f(3) = (3)^3 - 3(3)^2 - 9(3) + 5 = 27 - 27 - 27 + 5 = -22 \) (local minimum).

Thus, the maximum and minimum values are:
\[ \boxed{\text{Local Maximum: } f(-1) = 10, \text{ Local Minimum: } f(3) = -22} \]
</details>

---

Ex2.
Find the maximum and minimum values of the rational function \( f(x) = \frac{x^2}{x + 2} \) on the interval \( [-4, 0] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = \frac{x^2}{x + 2} \]  
Compute the derivative using the quotient rule: 
\[ f'(x) = \frac{(x + 2)(2x) - x^2(1)}{(x + 2)^2} = \frac{2x^2 + 4x - x^2}{(x + 2)^2} = \frac{x^2 + 4x}{(x + 2)^2} \]  
Set \( f'(x) = 0 \) to find critical points: \[ x^2 + 4x = 0 \implies x(x + 4) = 0 \]  
Critical points: \( x = 0 \) and \( x = -4 \).  

Check the endpoints of the interval \( [-4, 0] \):
- \( f(-4) = \frac{(-4)^2}{-4 + 2} = \frac{16}{-2} = -8 \).
- \( f(0) = \frac{(0)^2}{0 + 2} = 0 \).

Evaluate \( f(x) \) at the critical points:
- \( f(-4) = -8 \) (already computed).
- \( f(0) = 0 \) (already computed).

Compare the values:
- Maximum value: \( f(0) = 0 \).
- Minimum value: \( f(-4) = -8 \).

Thus, the maximum and minimum values are:
\[ \boxed{\text{Maximum: } f(0) = 0, \text{ Minimum: } f(-4) = -8} \]
</details>

---

Ex3.
Find the maximum and minimum values of the trigonometric function \( f(x) = \sin(x) + \cos(x) \) on the interval \( [0, \pi] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = \sin(x) + \cos(x) \]  
Compute the derivative: \[ f'(x) = \cos(x) - \sin(x) \]  
Set \( f'(x) = 0 \) to find critical points: \[ \cos(x) - \sin(x) = 0 \implies \cos(x) = \sin(x) \]  
Divide through by \( \cos(x) \) (valid since \( \cos(x) \neq 0 \)): \[ \tan(x) = 1 \]  
Solve for \( x \): \( x = \frac{\pi}{4} \) (in the interval \( [0, \pi] \)).

Check the endpoints of the interval \( [0, \pi] \):
- \( f(0) = \sin(0) + \cos(0) = 0 + 1 = 1 \).
- \( f(\pi) = \sin(\pi) + \cos(\pi) = 0 - 1 = -1 \).

Evaluate \( f(x) \) at the critical point:
- \( f\left(\frac{\pi}{4}\right) = \sin\left(\frac{\pi}{4}\right) + \cos\left(\frac{\pi}{4}\right) = \frac{\sqrt{2}}{2} + \frac{\sqrt{2}}{2} = \sqrt{2} \).

Compare the values:
- Maximum value: \( f\left(\frac{\pi}{4}\right) = \sqrt{2} \).
- Minimum value: \( f(\pi) = -1 \).

Thus, the maximum and minimum values are:
\[ \boxed{\text{Maximum: } f\left(\frac{\pi}{4}\right) = \sqrt{2}, \text{ Minimum: } f(\pi) = -1} \]
</details>

---

Ex4.
Find the maximum and minimum values of the composite function \( f(x) = e^{x^2 - 4x} \) on the interval \( [0, 4] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = e^{x^2 - 4x} \]  
Compute the derivative using the chain rule: 
\[ f'(x) = e^{x^2 - 4x} \cdot (2x - 4) \]  
Set \( f'(x) = 0 \): \[ e^{x^2 - 4x} \cdot (2x - 4) = 0 \]  
Since \( e^{x^2 - 4x} > 0 \) for all \( x \), solve \( 2x - 4 = 0 \): \[ x = 2 \].

Check the endpoints of the interval \( [0, 4] \):
- \( f(0) = e^{(0)^2 - 4(0)} = e^0 = 1 \).
- \( f(4) = e^{(4)^2 - 4(4)} = e^{16 - 16} = e^0 = 1 \).

Evaluate \( f(x) \) at the critical point:
- \( f(2) = e^{(2)^2 - 4(2)} = e^{4 - 8} = e^{-4} \).

Compare the values:
- Maximum value: \( f(0) = f(4) = 1 \).
- Minimum value: \( f(2) = e^{-4} \).

Thus, the maximum and minimum values are:
\[ \boxed{\text{Maximum: } f(0) = f(4) = 1, \text{ Minimum: } f(2) = e^{-4}} \]
</details>
