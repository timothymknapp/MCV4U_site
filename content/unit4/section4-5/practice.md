+++
title = '4.5 Practice'
weight = 2
+++

Ex1.
Analyze and sketch the graph of the function \( f(x) = x^3 - 6x^2 + 9x + 2 \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = x^3 - 6x^2 + 9x + 2 \]

### Step 1: Domain
The domain of \( f(x) \) is all real numbers: \( (-\infty, \infty) \).

### Step 2: Intercepts
- **\( y \)-intercept**: Set \( x = 0 \): \[ f(0) = (0)^3 - 6(0)^2 + 9(0) + 2 = 2 \] (\( y \)-intercept is \( (0, 2) \)).
- **\( x \)-intercepts**: Solve \( f(x) = 0 \). Factoring may be challenging here, so numerical or graphical methods can be used.

### Step 3: First Derivative Test
Compute the first derivative: \[ f'(x) = 3x^2 - 12x + 9 \]  
Set \( f'(x) = 0 \) to find critical points: \[ 3x^2 - 12x + 9 = 0 \implies x^2 - 4x + 3 = 0 \implies (x - 3)(x - 1) = 0 \]  
Critical points: \( x = 1 \) and \( x = 3 \).  

Use the first derivative test to determine intervals of increase/decrease:
- For \( x < 1 \), choose \( x = 0 \): \[ f'(0) = 3(0)^2 - 12(0) + 9 = 9 > 0 \] (\( f(x) \) is increasing).
- For \( 1 < x < 3 \), choose \( x = 2 \): \[ f'(2) = 3(2)^2 - 12(2) + 9 = 12 - 24 + 9 = -3 < 0 \] (\( f(x) \) is decreasing).
- For \( x > 3 \), choose \( x = 4 \): \[ f'(4) = 3(4)^2 - 12(4) + 9 = 48 - 48 + 9 = 9 > 0 \] (\( f(x) \) is increasing).

Thus:
- \( f(x) \) is increasing on \( (-\infty, 1) \cup (3, \infty) \).
- \( f(x) \) is decreasing on \( (1, 3) \).

From the first derivative test:
- At \( x = 1 \), \( f(x) \) changes from increasing to decreasing → **local maximum**.
- At \( x = 3 \), \( f(x) \) changes from decreasing to increasing → **local minimum**.

Evaluate \( f(x) \) at the critical points:
- \( f(1) = (1)^3 - 6(1)^2 + 9(1) + 2 = 1 - 6 + 9 + 2 = 6 \) (local maximum).
- \( f(3) = (3)^3 - 6(3)^2 + 9(3) + 2 = 27 - 54 + 27 + 2 = 2 \) (local minimum).

### Step 4: Second Derivative Test
Compute the second derivative: \[ f''(x) = 6x - 12 \]  
Set \( f''(x) = 0 \) to find potential points of inflection: \[ 6x - 12 = 0 \implies x = 2 \]  

Check the concavity around \( x = 2 \):
- For \( x < 2 \), choose \( x = 1 \): \[ f''(1) = 6(1) - 12 = -6 < 0 \] (\( f(x) \) is concave down).
- For \( x > 2 \), choose \( x = 3 \): \[ f''(3) = 6(3) - 12 = 6 > 0 \] (\( f(x) \) is concave up).

Since the concavity changes at \( x = 2 \), it is a **point of inflection**.

Find the \( y \)-coordinate at \( x = 2 \): \[ f(2) = (2)^3 - 6(2)^2 + 9(2) + 2 = 8 - 24 + 18 + 2 = 4 \]

Thus:
- \( f(x) \) is concave down on \( (-\infty, 2) \).
- \( f(x) \) is concave up on \( (2, \infty) \).
- Point of inflection: \( (2, 4) \).

### Step 5: Asymptotes
There are no vertical or horizontal asymptotes since \( f(x) \) is a polynomial.

### Step 6: Sketch the Graph
Using the information above:
- Local maximum: \( (1, 6) \).
- Local minimum: \( (3, 2) \).
- Point of inflection: \( (2, 4) \).
- Increasing on \( (-\infty, 1) \cup (3, \infty) \).
- Decreasing on \( (1, 3) \).
- Concave down on \( (-\infty, 2) \).
- Concave up on \( (2, \infty) \).

Sketch the curve accordingly.

\[ \boxed{\text{Graph sketched using the above analysis.}} \]
</details>

---

Ex2.
Analyze and sketch the graph of the function \( f(x) = \frac{x}{x^2 + 1} \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>
Write the given function: \[ f(x) = \frac{x}{x^2 + 1} \]

### Step 1: Domain
The domain of \( f(x) \) is all real numbers: \( (-\infty, \infty) \).

### Step 2: Intercepts
- **\( y \)-intercept**: Set \( x = 0 \): \[ f(0) = \frac{0}{0^2 + 1} = 0 \] (\( y \)-intercept is \( (0, 0) \)).
- **\( x \)-intercept**: Solve \( f(x) = 0 \): \[ \frac{x}{x^2 + 1} = 0 \implies x = 0 \] (\( x \)-intercept is \( (0, 0) \)).

### Step 3: First Derivative Test
Compute the first derivative using the quotient rule: 
\[ f'(x) = \frac{(x^2 + 1)(1) - x(2x)}{(x^2 + 1)^2} = \frac{-x^2 + 1}{(x^2 + 1)^2} \]  
Set \( f'(x) = 0 \) to find critical points: \[ -x^2 + 1 = 0 \implies x^2 = 1 \implies x = \pm 1 \]  
Critical points: \( x = -1 \) and \( x = 1 \).  

Use the first derivative test to determine intervals of increase/decrease:
- For \( x < -1 \), choose \( x = -2 \): \[ f'(-2) = \frac{-(-2)^2 + 1}{((-2)^2 + 1)^2} = \frac{-4 + 1}{(4 + 1)^2} = \frac{-3}{25} < 0 \] (\( f(x) \) is decreasing).
- For \( -1 < x < 1 \), choose \( x = 0 \): \[ f'(0) = \frac{-(0)^2 + 1}{((0)^2 + 1)^2} = \frac{1}{1} = 1 > 0 \] (\( f(x) \) is increasing).
- For \( x > 1 \), choose \( x = 2 \): \[ f'(2) = \frac{-(2)^2 + 1}{((2)^2 + 1)^2} = \frac{-4 + 1}{(4 + 1)^2} = \frac{-3}{25} < 0 \] (\( f(x) \) is decreasing).

Thus:
- \( f(x) \) is increasing on \( (-1, 1) \).
- \( f(x) \) is decreasing on \( (-\infty, -1) \cup (1, \infty) \).

From the first derivative test:
- At \( x = -1 \), \( f(x) \) changes from decreasing to increasing → **local minimum**.
- At \( x = 1 \), \( f(x) \) changes from increasing to decreasing → **local maximum**.

Evaluate \( f(x) \) at the critical points:
- \( f(-1) = \frac{-1}{(-1)^2 + 1} = \frac{-1}{2} = -\frac{1}{2} \) (local minimum).
- \( f(1) = \frac{1}{(1)^2 + 1} = \frac{1}{2} \) (local maximum).

### Step 4: Second Derivative Test
Compute the second derivative using the quotient rule again: 
\[ f''(x) = \frac{(x^2 + 1)^2(-2x) - (-x^2 + 1)(2)(x^2 + 1)(2x)}{(x^2 + 1)^4} \]  
Simplify: 
\[ f''(x) = \frac{-2x(x^2 + 1) + 4x(x^2 - 1)}{(x^2 + 1)^3} = \frac{-2x^3 - 2x + 4x^3 - 4x}{(x^2 + 1)^3} = \frac{2x^3 - 6x}{(x^2 + 1)^3} \]  
Factorize: 
\[ f''(x) = \frac{2x(x^2 - 3)}{(x^2 + 1)^3} \]  
Set \( f''(x) = 0 \): \[ 2x(x^2 - 3) = 0 \implies x = 0, \pm\sqrt{3} \]  

Check the concavity around the critical points:
- For \( x < -\sqrt{3} \), choose \( x = -2 \): \[ f''(-2) = \frac{2(-2)((-2)^2 - 3)}{((-2)^2 + 1)^3} = \frac{-4(4 - 3)}{(4 + 1)^3} = \frac{-4}{125} < 0 \] (\( f(x) \) is concave down).
- For \( -\sqrt{3} < x < 0 \), choose \( x = -1 \): \[ f''(-1) = \frac{2(-1)((-1)^2 - 3)}{((-1)^2 + 1)^3} = \frac{-2(1 - 3)}{(1 + 1)^3} = \frac{-2(-2)}{8} = \frac{4}{8} > 0 \] (\( f(x) \) is concave up).
- For \( 0 < x < \sqrt{3} \), choose \( x = 1 \): \[ f''(1) = \frac{2(1)((1)^2 - 3)}{((1)^2 + 1)^3} = \frac{2(1 - 3)}{(1 + 1)^3} = \frac{2(-2)}{8} = \frac{-4}{8} < 0 \] (\( f(x) \) is concave down).
- For \( x > \sqrt{3} \), choose \( x = 2 \): \[ f''(2) = \frac{2(2)((2)^2 - 3)}{((2)^2 + 1)^3} = \frac{4(4 - 3)}{(4 + 1)^3} = \frac{4}{125} > 0 \] (\( f(x) \) is concave up).

Thus:
- \( f(x) \) is concave down on \( (-\infty, -\sqrt{3}) \cup (0, \sqrt{3}) \).
- \( f(x) \) is concave up on \( (-\sqrt{3}, 0) \cup (\sqrt{3}, \infty) \).
- Points of inflection: \( (-\sqrt{3}, f(-\sqrt{3})) \), \( (0, f(0)) \), \( (\sqrt{3}, f(\sqrt{3})) \).

### Step 5: Asymptotes
- Horizontal asymptote: As \( x \to \pm\infty \), \( f(x) \to 0 \) (horizontal asymptote at \( y = 0 \)).
- No vertical asymptotes.

### Step 6: Sketch the Graph
Using the information above:
- Local minimum: \( (-1, -\frac{1}{2}) \).
- Local maximum: \( (1, \frac{1}{2}) \).
- Points of inflection: \( (-\sqrt{3}, f(-\sqrt{3})) \), \( (0, 0) \), \( (\sqrt{3}, f(\sqrt{3})) \).
- Increasing on \( (-1, 1) \).
- Decreasing on \( (-\infty, -1) \cup (1, \infty) \).
- Concave down on \( (-\infty, -\sqrt{3}) \cup (0, \sqrt{3}) \).
- Concave up on \( (-\sqrt{3}, 0) \cup (\sqrt{3}, \infty) \).

Sketch the curve accordingly.

\[ \boxed{\text{Graph sketched using the above analysis.}} \]
</details>