+++
title = '4.4 Examples'
weight = 1
+++

Intervals of Concavity
In this section, we will work through examples that demonstrate how to determine the intervals where a function is concave up or concave down using the second derivative test. These examples will include polynomial, rational, trigonometric, and exponential functions. By the end of this section, students will:
- Understand how to compute the second derivative of a function.
- Use the second derivative test to classify intervals of concavity.
- Solve problems involving various types of functions.

---

### Example 1: Polynomial Function
Determine the intervals where the function \( f(x) = x^3 - 6x^2 + 9x + 2 \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = x^3 - 6x^2 + 9x + 2 \]  

Compute the first derivative:  
\[ f'(x) = 3x^2 - 12x + 9 \]  

Compute the second derivative:  
\[ f''(x) = 6x - 12 \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ 6x - 12 = 0 \implies x = 2 \]  

Check the concavity around \( x = 2 \):
- For \( x < 2 \), choose \( x = 1 \):  
  \[ f''(1) = 6(1) - 12 = -6 < 0 \] (\( f(x) \) is concave down).
- For \( x > 2 \), choose \( x = 3 \):  
  \[ f''(3) = 6(3) - 12 = 6 > 0 \] (\( f(x) \) is concave up).

Thus, the function is:
- Concave down on \( (-\infty, 2) \).
- Concave up on \( (2, \infty) \).

\[ \boxed{\text{Concave Down: } (-\infty, 2), \text{ Concave Up: } (2, \infty)} \]
</details>

---

### Example 2: Rational Function
Determine the intervals where the function \( f(x) = \frac{x}{x^2 + 1} \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = \frac{x}{x^2 + 1} \]  

Compute the first derivative using the quotient rule:  
\[ f'(x) = \frac{(x^2 + 1)(1) - x(2x)}{(x^2 + 1)^2} = \frac{-x^2 + 1}{(x^2 + 1)^2} \]  

Compute the second derivative using the quotient rule again:  
\[ f''(x) = \frac{(x^2 + 1)^2(-2x) - (-x^2 + 1)(2)(x^2 + 1)(2x)}{(x^2 + 1)^4} \]  
Simplify:  
\[ f''(x) = \frac{-2x(x^2 + 1) + 4x(x^2 - 1)}{(x^2 + 1)^3} = \frac{-2x^3 - 2x + 4x^3 - 4x}{(x^2 + 1)^3} = \frac{2x^3 - 6x}{(x^2 + 1)^3} \]  
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

Thus, the function is:
- Concave down on \( (-\infty, -\sqrt{3}) \cup (0, \sqrt{3}) \).
- Concave up on \( (-\sqrt{3}, 0) \cup (\sqrt{3}, \infty) \).

\[ \boxed{\text{Concave Down: } (-\infty, -\sqrt{3}) \cup (0, \sqrt{3}), \text{ Concave Up: } (-\sqrt{3}, 0) \cup (\sqrt{3}, \infty)} \]
</details>

---

### Example 3: Trigonometric Function
Determine the intervals where the function \( f(x) = \sin(x) \) is concave up or concave down on the interval \( [0, 2\pi] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = \sin(x) \]  

Compute the first derivative:  
\[ f'(x) = \cos(x) \]  

Compute the second derivative:  
\[ f''(x) = -\sin(x) \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ -\sin(x) = 0 \implies x = 0, \pi, 2\pi \]  

Check the concavity around the critical points:
- For \( 0 < x < \pi \), choose \( x = \frac{\pi}{2} \):  
  \[ f''\left(\frac{\pi}{2}\right) = -\sin\left(\frac{\pi}{2}\right) = -1 < 0 \] (\( f(x) \) is concave down).
- For \( \pi < x < 2\pi \), choose \( x = \frac{3\pi}{2} \):  
  \[ f''\left(\frac{3\pi}{2}\right) = -\sin\left(\frac{3\pi}{2}\right) = 1 > 0 \] (\( f(x) \) is concave up).

Thus, the function is:
- Concave down on \( (0, \pi) \).
- Concave up on \( (\pi, 2\pi) \).

\[ \boxed{\text{Concave Down: } (0, \pi), \text{ Concave Up: } (\pi, 2\pi)} \]
</details>

---

### Example 4: Exponential Function
Determine the intervals where the function \( f(x) = e^{-x^2} \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = e^{-x^2} \]  

Compute the first derivative using the chain rule:  
\[ f'(x) = -2x e^{-x^2} \]  

Compute the second derivative using the product rule:  
\[ f''(x) = (-2x)(-2x e^{-x^2}) + (-2)(e^{-x^2}) = 4x^2 e^{-x^2} - 2e^{-x^2} \]  
Factorize:  
\[ f''(x) = e^{-x^2}(4x^2 - 2) \]  

Set \( f''(x) = 0 \):  
Since \( e^{-x^2} > 0 \) for all \( x \), solve \( 4x^2 - 2 = 0 \):  
\[ 4x^2 = 2 \implies x^2 = \frac{1}{2} \implies x = \pm \frac{1}{\sqrt{2}} \]  

Check the concavity around the critical points:
- For \( x < -\frac{1}{\sqrt{2}} \), choose \( x = -1 \):  
  \[ f''(-1) = e^{-(-1)^2}(4(-1)^2 - 2) = e^{-1}(4 - 2) = 2e^{-1} > 0 \] (\( f(x) \) is concave up).
- For \( -\frac{1}{\sqrt{2}} < x < \frac{1}{\sqrt{2}} \), choose \( x = 0 \):  
  \[ f''(0) = e^{-(0)^2}(4(0)^2 - 2) = -2 < 0 \] (\( f(x) \) is concave down).
- For \( x > \frac{1}{\sqrt{2}} \), choose \( x = 1 \):  
  \[ f''(1) = e^{-(1)^2}(4(1)^2 - 2) = e^{-1}(4 - 2) = 2e^{-1} > 0 \] (\( f(x) \) is concave up).

Thus, the function is:
- Concave down on \( \left(-\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right) \).
- Concave up on \( \left(-\infty, -\frac{1}{\sqrt{2}}\right) \cup \left(\frac{1}{\sqrt{2}}, \infty\right) \).

\[ \boxed{\text{Concave Down: } \left(-\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right), \text{ Concave Up: } \left(-\infty, -\frac{1}{\sqrt{2}}\right) \cup \left(\frac{1}{\sqrt{2}}, \infty\right)} \]
</details>