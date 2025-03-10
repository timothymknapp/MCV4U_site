+++
title = '1.5 Practice'
weight = 2
+++


### 1.5 Continuity

#### Ex1.

Determine whether the function \( f(x) = \frac{x^2 - 4}{x - 2} \) is continuous at \( x = 2 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check if \( f(2) \) is defined:**
   - Substituting \( x = 2 \):
     \[
     f(2) = \frac{2^2 - 4}{2 - 2} = \frac{0}{0},
     \]
     which is undefined. Thus, \( f(x) \) is not defined at \( x = 2 \).

2. **Simplify the function:**
   - Factor the numerator:
     \[
     f(x) = \frac{x^2 - 4}{x - 2} = \frac{(x - 2)(x + 2)}{x - 2}.
     \]
   - Cancel \( x - 2 \):
     \[
     f(x) = x + 2, \quad \text{for } x \neq 2.
     \]

3. **Evaluate the limit as \( x \to 2 \):**
   - \( \lim_{{x \to 2}} f(x) = \lim_{{x \to 2}} (x + 2) = 2 + 2 = 4. \)

Since \( f(2) \) is undefined, the function is **not continuous** at \( x = 2 \).

</details>

---

#### Ex2.

The function \( g(x) = \begin{cases} 
  x + 1 & \text{if } x < 1, \\
  3 & \text{if } x = 1, \\
  2x - 1 & \text{if } x > 1.
\end{cases} \) is given. Determine whether \( g(x) \) is continuous at \( x = 1 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check if \( g(1) \) is defined:**
   - From the definition, \( g(1) = 3 \). Thus, the function is defined at \( x = 1 \).

2. **Evaluate the left-hand limit:**
   - For \( x \to 1^- \), use \( g(x) = x + 1 \):
     \[
     \lim_{{x \to 1^-}} g(x) = 1 + 1 = 2.
     \]

3. **Evaluate the right-hand limit:**
   - For \( x \to 1^+ \), use \( g(x) = 2x - 1 \):
     \[
     \lim_{{x \to 1^+}} g(x) = 2(1) - 1 = 1.
     \]

4. **Compare the limits and \( g(1) \):**
   - The left-hand limit \( (2) \), right-hand limit \( (1) \), and \( g(1) = 3 \) are not equal.

Thus, \( g(x) \) is **not continuous** at \( x = 1 \) and exhibits a **jump discontinuity**.

</details>

---

#### Ex3.

Analyze the continuity of \( h(x) = \frac{1}{x - 1} \) at \( x = 1 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check if \( h(1) \) is defined:**
   - Substituting \( x = 1 \):
     \[
     h(1) = \frac{1}{1 - 1} = \frac{1}{0},
     \]
     which is undefined. Thus, \( h(x) \) is not defined at \( x = 1 \).

2. **Evaluate the left-hand limit:**
   - For \( x \to 1^- \):
     \[
     \lim_{{x \to 1^-}} h(x) = \lim_{{x \to 1^-}} \frac{1}{x - 1} = -\infty.
     \]

3. **Evaluate the right-hand limit:**
   - For \( x \to 1^+ \):
     \[
     \lim_{{x \to 1^+}} h(x) = \lim_{{x \to 1^+}} \frac{1}{x - 1} = \infty.
     \]

4. **Compare the limits:**
   - The left-hand limit is \( -\infty \), and the right-hand limit is \( \infty \). They are not equal, and the function diverges at \( x = 1 \).

Thus, \( h(x) \) has an **infinite discontinuity** at \( x = 1 \).

</details>

---


<iframe src="https://script.google.com/macros/s/AKfycbw_nXdONbsIeKqM2L8JgHdPukn1jvwI3r7xtQlUDHoo2O8ZEkUaDSKpSl0H8RWKjb52Ow/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
