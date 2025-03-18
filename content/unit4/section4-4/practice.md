+++
title = '4.4 Practice'
weight = 2
+++


Ex1.
Determine the intervals where the function \( f(x) = x^3 - 4x^2 + 5x - 1 \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = x^3 - 4x^2 + 5x - 1 \]  

Compute the first derivative:  
\[ f'(x) = 3x^2 - 8x + 5 \]  

Compute the second derivative:  
\[ f''(x) = 6x - 8 \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ 6x - 8 = 0 \implies x = \frac{4}{3} \]  

Check the concavity around \( x = \frac{4}{3} \):
- For \( x < \frac{4}{3} \), choose \( x = 1 \):  
  \[ f''(1) = 6(1) - 8 = -2 < 0 \] (\( f(x) \) is concave down).
- For \( x > \frac{4}{3} \), choose \( x = 2 \):  
  \[ f''(2) = 6(2) - 8 = 4 > 0 \] (\( f(x) \) is concave up).

Thus, the function is:
- Concave down on \( (-\infty, \frac{4}{3}) \).
- Concave up on \( (\frac{4}{3}, \infty) \).

\[ \boxed{\text{Concave Down: } (-\infty, \frac{4}{3}), \text{ Concave Up: } (\frac{4}{3}, \infty)} \]
</details>

---

Ex2.
Determine the intervals where the function \( f(x) = \frac{x^2}{x^2 + 4} \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = \frac{x^2}{x^2 + 4} \]  

Compute the first derivative using the quotient rule:  
\[ f'(x) = \frac{(x^2 + 4)(2x) - x^2(2x)}{(x^2 + 4)^2} = \frac{2x(x^2 + 4) - 2x^3}{(x^2 + 4)^2} = \frac{8x}{(x^2 + 4)^2} \]  

Compute the second derivative using the quotient rule again:  
\[ f''(x) = \frac{(x^2 + 4)^2(8) - (8x)(2)(x^2 + 4)(2x)}{(x^2 + 4)^4} \]  
Simplify:  
\[ f''(x) = \frac{8(x^2 + 4) - 32x^2}{(x^2 + 4)^3} = \frac{-24x^2 + 32}{(x^2 + 4)^3} \]  
Factorize:  
\[ f''(x) = \frac{-8(3x^2 - 4)}{(x^2 + 4)^3} \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ -8(3x^2 - 4) = 0 \implies 3x^2 - 4 = 0 \implies x^2 = \frac{4}{3} \implies x = \pm \frac{2}{\sqrt{3}} \]  

Check the concavity around the critical points:
- For \( x < -\frac{2}{\sqrt{3}} \), choose \( x = -2 \):  
  \[ f''(-2) = \frac{-8(3(-2)^2 - 4)}{((-2)^2 + 4)^3} = \frac{-8(12 - 4)}{(4 + 4)^3} = \frac{-8(8)}{512} = -\frac{64}{512} < 0 \] (\( f(x) \) is concave down).
- For \( -\frac{2}{\sqrt{3}} < x < \frac{2}{\sqrt{3}} \), choose \( x = 0 \):  
  \[ f''(0) = \frac{-8(3(0)^2 - 4)}{((0)^2 + 4)^3} = \frac{-8(-4)}{64} = \frac{32}{64} > 0 \] (\( f(x) \) is concave up).
- For \( x > \frac{2}{\sqrt{3}} \), choose \( x = 2 \):  
  \[ f''(2) = \frac{-8(3(2)^2 - 4)}{((2)^2 + 4)^3} = \frac{-8(12 - 4)}{(4 + 4)^3} = \frac{-8(8)}{512} = -\frac{64}{512} < 0 \] (\( f(x) \) is concave down).

Thus, the function is:
- Concave down on \( (-\infty, -\frac{2}{\sqrt{3}}) \cup (\frac{2}{\sqrt{3}}, \infty) \).
- Concave up on \( (-\frac{2}{\sqrt{3}}, \frac{2}{\sqrt{3}}) \).

\[ \boxed{\text{Concave Down: } (-\infty, -\frac{2}{\sqrt{3}}) \cup (\frac{2}{\sqrt{3}}, \infty), \text{ Concave Up: } (-\frac{2}{\sqrt{3}}, \frac{2}{\sqrt{3}})} \]
</details>

---

Ex3.
Determine the intervals where the function \( f(x) = \cos(x) \) is concave up or concave down on the interval \( [0, 2\pi] \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = \cos(x) \]  

Compute the first derivative:  
\[ f'(x) = -\sin(x) \]  

Compute the second derivative:  
\[ f''(x) = -\cos(x) \]  

Set \( f''(x) = 0 \) to find potential points of inflection:  
\[ -\cos(x) = 0 \implies x = \frac{\pi}{2}, \frac{3\pi}{2} \]  

Check the concavity around the critical points:
- For \( 0 < x < \frac{\pi}{2} \), choose \( x = \frac{\pi}{4} \):  
  \[ f''\left(\frac{\pi}{4}\right) = -\cos\left(\frac{\pi}{4}\right) = -\frac{\sqrt{2}}{2} < 0 \] (\( f(x) \) is concave down).
- For \( \frac{\pi}{2} < x < \frac{3\pi}{2} \), choose \( x = \pi \):  
  \[ f''(\pi) = -\cos(\pi) = -(-1) = 1 > 0 \] (\( f(x) \) is concave up).
- For \( \frac{3\pi}{2} < x < 2\pi \), choose \( x = \frac{7\pi}{4} \):  
  \[ f''\left(\frac{7\pi}{4}\right) = -\cos\left(\frac{7\pi}{4}\right) = -\frac{\sqrt{2}}{2} < 0 \] (\( f(x) \) is concave down).

Thus, the function is:
- Concave down on \( (0, \frac{\pi}{2}) \cup (\frac{3\pi}{2}, 2\pi) \).
- Concave up on \( (\frac{\pi}{2}, \frac{3\pi}{2}) \).

\[ \boxed{\text{Concave Down: } (0, \frac{\pi}{2}) \cup (\frac{3\pi}{2}, 2\pi), \text{ Concave Up: } (\frac{\pi}{2}, \frac{3\pi}{2})} \]
</details>

---

Ex4.
Determine the intervals where the function \( f(x) = e^{-2x^2} \) is concave up or concave down.

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function:  
\[ f(x) = e^{-2x^2} \]  

Compute the first derivative using the chain rule:  
\[ f'(x) = -4x e^{-2x^2} \]  

Compute the second derivative using the product rule:  
\[ f''(x) = (-4x)(-4x e^{-2x^2}) + (-4)(e^{-2x^2}) = 16x^2 e^{-2x^2} - 4e^{-2x^2} \]  
Factorize:  
\[ f''(x) = e^{-2x^2}(16x^2 - 4) \]  

Set \( f''(x) = 0 \): Since \( e^{-2x^2} > 0 \) for all \( x \), solve \( 16x^2 - 4 = 0 \):  
\[ 16x^2 = 4 \implies x^2 = \frac{1}{4} \implies x = \pm \frac{1}{2} \]  

Check the concavity around the critical points:
- For \( x < -\frac{1}{2} \), choose \( x = -1 \):  
  \[ f''(-1) = e^{-2(-1)^2}(16(-1)^2 - 4) = e^{-2}(16 - 4) = 12e^{-2} > 0 \] (\( f(x) \) is concave up).
- For \( -\frac{1}{2} < x < \frac{1}{2} \), choose \( x = 0 \):  
  \[ f''(0) = e^{-2(0)^2}(16(0)^2 - 4) = -4 < 0 \] (\( f(x) \) is concave down).
- For \( x > \frac{1}{2} \), choose \( x = 1 \):  
  \[ f''(1) = e^{-2(1)^2}(16(1)^2 - 4) = e^{-2}(16 - 4) = 12e^{-2} > 0 \] (\( f(x) \) is concave up).

Thus, the function is:
- Concave down on \( \left(-\frac{1}{2}, \frac{1}{2}\right) \).
- Concave up on \( \left(-\infty, -\frac{1}{2}\right) \cup \left(\frac{1}{2}, \infty\right) \).

\[ \boxed{\text{Concave Down: } \left(-\frac{1}{2}, \frac{1}{2}\right), \text{ Concave Up: } \left(-\infty, -\frac{1}{2}\right) \cup \left(\frac{1}{2}, \infty\right)} \]
</details>