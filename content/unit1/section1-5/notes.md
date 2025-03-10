+++
title = '1.5 Examples'
weight = 1
+++


### Example 1: Jump Discontinuity

Determine if the following function is continuous at \( x = 2 \):

\[
f(x) = \begin{cases} 
2x + 1 & \text{if } x < 2, \\
4 & \text{if } x = 2, \\
x^2 - 3 & \text{if } x > 2.
\end{cases}
\]

**Solution:**

1. **Check if \( f(2) \) is defined:**
   - \( f(2) = 4 \). Thus, the function is defined at \( x = 2 \).

2. **Evaluate the left-hand limit:**
   - When \( x \to 2^- \), use \( f(x) = 2x + 1 \):
     \[
     \lim_{{x \to 2^-}} f(x) = 2(2) + 1 = 5.
     \]

3. **Evaluate the right-hand limit:**
   - When \( x \to 2^+ \), use \( f(x) = x^2 - 3 \):
     \[
     \lim_{{x \to 2^+}} f(x) = (2)^2 - 3 = 1.
     \]

4. **Compare the limits and the function value:**
   - The left-hand limit \( (5) \), right-hand limit \( (1) \), and \( f(2) = 4 \) are not equal.

Thus, the function is **not continuous** at \( x = 2 \).

---

### Example 2: Removable Discontinuity 

Determine whether the function \( g(x) = \frac{x^2 - 9}{x - 3} \) is continuous at \( x = 3 \).

**Solution:**

1. **Check if \( g(3) \) is defined:**
   - Substituting \( x = 3 \) results in \( \frac{3^2 - 9}{3 - 3} = \frac{0}{0} \), which is undefined.

   Thus, \( g(x) \) is not defined at \( x = 3 \).

2. **Simplify the function:**
   - Factor the numerator:
     \[
     g(x) = \frac{x^2 - 9}{x - 3} = \frac{(x - 3)(x + 3)}{x - 3}.
     \]
   - Cancel \( x - 3 \):
     \[
     g(x) = x + 3, \quad \text{for } x \neq 3.
     \]

3. **Evaluate the limit as \( x \to 3 \):**
   - \( \lim_{{x \to 3}} g(x) = \lim_{{x \to 3}} (x + 3) = 6. \)

Since \( g(3) \) is undefined, the function is **not continuous** at \( x = 3 \).

---


### Example 3: Infinite Discontinuity

Analyze the continuity of \( h(x) = \frac{1}{x - 2} \) at \( x = 2 \).

**Solution:**

1. **Check if \( h(2) \) is defined:**
   - Substituting \( x = 2 \) into \( h(x) \):
     \[
     h(2) = \frac{1}{2 - 2} = \frac{1}{0},
     \]
     which is undefined.

   Thus, \( h(x) \) is not defined at \( x = 2 \).

2. **Evaluate the left-hand limit:**
   - When \( x \to 2^- \):
     \[
     \lim_{{x \to 2^-}} h(x) = \lim_{{x \to 2^-}} \frac{1}{x - 2} = -\infty.
     \]

3. **Evaluate the right-hand limit:**
   - When \( x \to 2^+ \):
     \[
     \lim_{{x \to 2^+}} h(x) = \lim_{{x \to 2^+}} \frac{1}{x - 2} = \infty.
     \]

4. **Compare the limits:**
   - The left-hand limit is \( -\infty \), and the right-hand limit is \( \infty \). They are not equal, and the function diverges at \( x = 2 \).

Thus, \( h(x) \) has an **infinite discontinuity** at \( x = 2 \).

---

### Example 4: Discontinuities on Graphs

Identify and Discontinuiteis on the below graph, and use the definition of continuity as justifictaion.

<div style="margin: 0 auto; width: fit-content;">
    <iframe src="https://www.desmos.com/calculator/gyfxygujxc?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>



**Solution:**

1. The function is discontinuous at \( x = -1 \) 
   
   Justification; \( f(-1) \) is undefined.

2. The function is discontinuous at \( x = 1 \) 
   
   Justification; 
    \[
    \lim_{{x \to 1^-}} f(x) \neq \lim_{{x \to 1^+}} f(x).
    \]

1. The function is discontinuous at \( x = 2 \) 
   
   Justification; \( f(2) \) is undefined.


---
