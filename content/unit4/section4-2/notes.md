+++
title = '4.2 Examples'
weight = 1
+++

Intervals of Increasing and Decreasing Functions
In this section, we will work through examples that demonstrate how to determine the intervals where a function is increasing or decreasing. Using the **first derivative test**, we analyze the critical points and the sign of the derivative to classify the behavior of the function over its domain. By the end of this section, students will:
- Understand how to compute the derivative of a function.
- Identify critical points and use them to determine intervals of increase and decrease.
- Apply the first derivative test effectively to classify the behavior of the function.

---

### Example 1: Polynomial Function
Determine the intervals where the function \( f(x) = x^3 - 6x^2 + 9x + 2 \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = x^3 - 6x^2 + 9x + 2 \]  

Compute the derivative:  
\[ f'(x) = 3x^2 - 12x + 9 \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ 3x^2 - 12x + 9 = 0 \implies x^2 - 4x + 3 = 0 \implies (x - 3)(x - 1) = 0 \]  
Critical points: \( x = 1 \) and \( x = 3 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( x < 1 \), choose \( x = 0 \):  
  \[ f'(0) = 3(0)^2 - 12(0) + 9 = 9 > 0 \] (\( f(x) \) is increasing).
- For \( 1 < x < 3 \), choose \( x = 2 \):  
  \[ f'(2) = 3(2)^2 - 12(2) + 9 = 12 - 24 + 9 = -3 < 0 \] (\( f(x) \) is decreasing).
- For \( x > 3 \), choose \( x = 4 \):  
  \[ f'(4) = 3(4)^2 - 12(4) + 9 = 48 - 48 + 9 = 9 > 0 \] (\( f(x) \) is increasing).

Thus, the function is:
- Increasing on \( (-\infty, 1) \cup (3, \infty) \).
- Decreasing on \( (1, 3) \).

\[ \boxed{\text{Increasing: } (-\infty, 1) \cup (3, \infty), \text{ Decreasing: } (1, 3)} \]

---

### Example 2: Rational Function
Determine the intervals where the function \( f(x) = \frac{x}{x^2 + 1} \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = \frac{x}{x^2 + 1} \]  

Compute the derivative using the quotient rule:  
\[ f'(x) = \frac{(x^2 + 1)(1) - x(2x)}{(x^2 + 1)^2} = \frac{-x^2 + 1}{(x^2 + 1)^2} \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ -x^2 + 1 = 0 \implies x^2 = 1 \implies x = \pm 1 \]  
Critical points: \( x = -1 \) and \( x = 1 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( x < -1 \), choose \( x = -2 \):  
  \[ f'(-2) = \frac{-(-2)^2 + 1}{((-2)^2 + 1)^2} = \frac{-4 + 1}{(4 + 1)^2} = \frac{-3}{25} < 0 \] (\( f(x) \) is decreasing).
- For \( -1 < x < 1 \), choose \( x = 0 \):  
  \[ f'(0) = \frac{-(0)^2 + 1}{((0)^2 + 1)^2} = \frac{1}{1} = 1 > 0 \] (\( f(x) \) is increasing).
- For \( x > 1 \), choose \( x = 2 \):  
  \[ f'(2) = \frac{-(2)^2 + 1}{((2)^2 + 1)^2} = \frac{-4 + 1}{(4 + 1)^2} = \frac{-3}{25} < 0 \] (\( f(x) \) is decreasing).

Thus, the function is:
- Increasing on \( (-1, 1) \).
- Decreasing on \( (-\infty, -1) \cup (1, \infty) \).

\[ \boxed{\text{Increasing: } (-1, 1), \text{ Decreasing: } (-\infty, -1) \cup (1, \infty)} \]

---

### Example 3: Trigonometric Function
Determine the intervals where the function \( f(x) = \sin(x) \) is increasing or decreasing on the interval \( [0, 2\pi] \).

#### Solution:
Write the given function:  
\[ f(x) = \sin(x) \]  

Compute the derivative:  
\[ f'(x) = \cos(x) \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ \cos(x) = 0 \implies x = \frac{\pi}{2}, \frac{3\pi}{2} \]  
Critical points: \( x = \frac{\pi}{2} \) and \( x = \frac{3\pi}{2} \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( 0 < x < \frac{\pi}{2} \), choose \( x = \frac{\pi}{4} \):  
  \[ f'\left(\frac{\pi}{4}\right) = \cos\left(\frac{\pi}{4}\right) = \frac{\sqrt{2}}{2} > 0 \] (\( f(x) \) is increasing).
- For \( \frac{\pi}{2} < x < \frac{3\pi}{2} \), choose \( x = \pi \):  
  \[ f'(\pi) = \cos(\pi) = -1 < 0 \] (\( f(x) \) is decreasing).
- For \( \frac{3\pi}{2} < x < 2\pi \), choose \( x = \frac{7\pi}{4} \):  
  \[ f'\left(\frac{7\pi}{4}\right) = \cos\left(\frac{7\pi}{4}\right) = \frac{\sqrt{2}}{2} > 0 \] (\( f(x) \) is increasing).

Thus, the function is:
- Increasing on \( \left(0, \frac{\pi}{2}\right) \cup \left(\frac{3\pi}{2}, 2\pi\right) \).
- Decreasing on \( \left(\frac{\pi}{2}, \frac{3\pi}{2}\right) \).

\[ \boxed{\text{Increasing: } \left(0, \frac{\pi}{2}\right) \cup \left(\frac{3\pi}{2}, 2\pi\right), \text{ Decreasing: } \left(\frac{\pi}{2}, \frac{3\pi}{2}\right)} \]

---

### Example 4: Exponential Function
Determine the intervals where the function \( f(x) = e^{-x^2} \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = e^{-x^2} \]  

Compute the derivative using the chain rule:  
\[ f'(x) = e^{-x^2} \cdot (-2x) = -2x e^{-x^2} \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ -2x e^{-x^2} = 0 \implies x = 0 \]  
Critical point: \( x = 0 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical point:
- For \( x < 0 \), choose \( x = -1 \):  
  \[ f'(-1) = -2(-1)e^{-(-1)^2} = 2e^{-1} > 0 \] (\( f(x) \) is increasing).
- For \( x > 0 \), choose \( x = 1 \):  
  \[ f'(1) = -2(1)e^{-(1)^2} = -2e^{-1} < 0 \] (\( f(x) \) is decreasing).

Thus, the function is:
- Increasing on \( (-\infty, 0) \).
- Decreasing on \( (0, \infty) \).

\[ \boxed{\text{Increasing: } (-\infty, 0), \text{ Decreasing: } (0, \infty)} \]

---

### Learning Objectives
By the end of this section, students will:
- Understand how to use the first derivative test to determine intervals of increase and decrease.
- Apply the method to polynomial, rational, trigonometric, and exponential functions.
- Solve problems involving critical points and classify intervals effectively.