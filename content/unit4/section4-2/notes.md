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
Determine the intervals where the function \( f(x) = x^4 - 8x^3 + 18x^2 - 10 \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = x^4 - 8x^3 + 18x^2 - 10 \]  

Compute the derivative:  
\[ f'(x) = 4x^3 - 24x^2 + 36x \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ 4x^3 - 24x^2 + 36x = 0 \implies 4x(x^2 - 6x + 9) = 0 \implies 4x(x - 3)^2 = 0 \]  
Critical points: \( x = 0 \) and \( x = 3 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( x < 0 \), choose \( x = -1 \):  
  \[ f'(-1) = 4(-1)((-1) - 3)^2 = 4(-1)(16) = -64 < 0 \] (\( f(x) \) is decreasing).
- For \( 0 < x < 3 \), choose \( x = 1 \):  
  \[ f'(1) = 4(1)((1) - 3)^2 = 4(1)(4) = 16 > 0 \] (\( f(x) \) is increasing).
- For \( x > 3 \), choose \( x = 4 \):  
  \[ f'(4) = 4(4)((4) - 3)^2 = 4(4)(1) = 16 > 0 \] (\( f(x) \) is increasing).

Thus, the function is:
- Increasing on \( (0, \infty) \).
- Decreasing on \( (-\infty, 0) \).

\[ \boxed{\text{Increasing: } (0, \infty), \text{ Decreasing: } (-\infty, 0)} \]

---

### Example 2: Rational Function
Determine the intervals where the function \( f(x) = \frac{x^2}{x^2 - 4} \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = \frac{x^2}{x^2 - 4} \]  

Compute the derivative using the quotient rule:  
\[ f'(x) = \frac{(x^2 - 4)(2x) - x^2(2x)}{(x^2 - 4)^2} = \frac{-8x}{(x^2 - 4)^2} \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ -8x = 0 \implies x = 0 \]  
Critical point: \( x = 0 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( x < 0 \), choose \( x = -1 \):  
  \[ f'(-1) = \frac{-8(-1)}{((-1)^2 - 4)^2} = \frac{8}{9} > 0 \] (\( f(x) \) is increasing).
- For \( x > 0 \), choose \( x = 1 \):  
  \[ f'(1) = \frac{-8(1)}{((1)^2 - 4)^2} = \frac{-8}{9} < 0 \] (\( f(x) \) is decreasing).

Thus, the function is:
- Increasing on \( (-\infty, 0) \).
- Decreasing on \( (0, \infty) \).

\[ \boxed{\text{Increasing: } (-\infty, 0), \text{ Decreasing: } (0, \infty)} \]

---

### Example 3: Trigonometric Function
Determine the intervals where the function \( f(x) = \cos(x) \) is increasing or decreasing on the interval \( [0, 2\pi] \).

#### Solution:
Write the given function:  
\[ f(x) = \cos(x) \]  

Compute the derivative:  
\[ f'(x) = -\sin(x) \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ -\sin(x) = 0 \implies x = 0, \pi, 2\pi \]  
Critical points: \( x = 0, \pi, 2\pi \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical points:
- For \( 0 < x < \pi \), choose \( x = \frac{\pi}{2} \):  
  \[ f'\left(\frac{\pi}{2}\right) = -\sin\left(\frac{\pi}{2}\right) = -1 < 0 \] (\( f(x) \) is decreasing).
- For \( \pi < x < 2\pi \), choose \( x = \frac{3\pi}{2} \):  
  \[ f'\left(\frac{3\pi}{2}\right) = -\sin\left(\frac{3\pi}{2}\right) = 1 > 0 \] (\( f(x) \) is increasing).

Thus, the function is:
- Increasing on \( (\pi, 2\pi) \).
- Decreasing on \( (0, \pi) \).

\[ \boxed{\text{Increasing: } (\pi, 2\pi), \text{ Decreasing: } (0, \pi)} \]

---

### Example 4: Exponential Function
Determine the intervals where the function \( f(x) = e^{x^2 - 2x} \) is increasing or decreasing.

#### Solution:
Write the given function:  
\[ f(x) = e^{x^2 - 2x} \]  

Compute the derivative using the chain rule:  
\[ f'(x) = e^{x^2 - 2x} \cdot (2x - 2) = (2x - 2)e^{x^2 - 2x} \]  

Set \( f'(x) = 0 \) to find critical points:  
\[ (2x - 2)e^{x^2 - 2x} = 0 \implies 2x - 2 = 0 \implies x = 1 \]  
Critical point: \( x = 1 \).  

Use the first derivative test to determine the sign of \( f'(x) \) around the critical point:
- For \( x < 1 \), choose \( x = 0 \):  
  \[ f'(0) = (2(0) - 2)e^{(0)^2 - 2(0)} = -2e^0 = -2 < 0 \] (\( f(x) \) is decreasing).
- For \( x > 1 \), choose \( x = 2 \):  
  \[ f'(2) = (2(2) - 2)e^{(2)^2 - 2(2)} = (4 - 2)e^{4 - 4} = 2e^0 = 2 > 0 \] (\( f(x) \) is increasing).

Thus, the function is:
- Increasing on \( (1, \infty) \).
- Decreasing on \( (-\infty, 1) \).

\[ \boxed{\text{Increasing: } (1, \infty), \text{ Decreasing: } (-\infty, 1)} \]

---

### Learning Objectives
By the end of this section, students will:
- Understand how to use the first derivative test to determine intervals of increase and decrease.
- Apply the method to polynomial, rational, trigonometric, and exponential functions.
- Solve problems involving critical points and classify intervals effectively.