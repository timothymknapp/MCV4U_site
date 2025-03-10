+++
title = '1.4 Limits in Algebra'
weight =4
+++

## Algebraic Techniques for Solving Limits

To calculate limits algebraically, we use simplification techniques such as factoring, rationalizing, or applying special limit rules. Below is an example of solving a limit.

### Example 1: Basic Limit
Find \( \lim_{{x \to 3}} (2x + 1) \).

Substitute \( x = 3 \) directly into the function:
\[
\lim_{{x \to 3}} (2x + 1) = 2(3) + 1 = 7.
\]
Thus, the limit is 7.

### Example 2: Indeterminate Form
Evaluate \( \lim_{{x \to 2}} \frac{x^2 - 4}{x - 2} \).

1. Direct substitution leads to:
   \[
   \lim_{{x \to 2}} \frac{x^2 - 4}{x - 2} = \frac{2^2 - 4}{2 - 2} = \frac{0}{0}.
   \]
   This is an indeterminate form, so further simplification is needed.

2. Factor the numerator:
   \[
   \frac{x^2 - 4}{x - 2} = \frac{(x - 2)(x + 2)}{x - 2}.
   \]

3. Cancel the common factor \( x - 2 \) (valid since \( x \neq 2 \)):
   \[
   \lim_{{x \to 2}} \frac{(x - 2)(x + 2)}{x - 2} = \lim_{{x \to 2}} (x + 2).
   \]

4. Substitute \( x = 2 \):
   \[
   \lim_{{x \to 2}} (x + 2) = 2 + 2 = 4.
   \]

Thus, the limit is 4.


## Limits at Infinity

When we consider limits as \( x \to \infty \) or \( x \to -\infty \), we analyze the behavior of a function as the input becomes arbitrarily large (positive or negative). Limits at infinity help us understand end behavior and asymptotes.

### Example 3: Limit does not Exist
Evaluate \( \lim_{{x \to \infty}} \sin(x) \).


The sine function oscillates between \(-1\) and \(1\) indefinitely as \( x \to \infty \). Therefore, it does not approach a single value:
\[
\lim_{{x \to \infty}} \sin(x) \text{ does not exist.}
\]

### Example 4: Limit Equals Zero
Evaluate \( \lim_{{x \to \infty}} \frac{1}{x} \).


As \( x \to \infty \), the denominator grows arbitrarily large, causing the fraction to approach zero:
\[
\lim_{{x \to \infty}} \frac{1}{x} = 0.
\]

## Limits of Piecewise-Defined Functions

For piecewise functions, the limit at a point depends on the behavior of the function from both the left and the right. If the left-hand limit and right-hand limit are equal, the overall limit exists. Otherwise, the limit does not exist.

### Example 5: Piecewise Limit
Evaluate \( \lim_{{x \to 1}} f(x) \), where:
\[
f(x) = \begin{cases} 
2x + 1 & \text{if } x < 1, \\
3 - x & \text{if } x \geq 1.
\end{cases}
\]


1. **Left-Hand Limit:**
   When \( x \to 1^- \), use the first piece \( f(x) = 2x + 1 \):
   \[
   \lim_{{x \to 1^-}} f(x) = 2(1) + 1 = 3.
   \]

2. **Right-Hand Limit:**
   When \( x \to 1^+ \), use the second piece \( f(x) = 3 - x \):
   \[
   \lim_{{x \to 1^+}} f(x) = 3 - 1 = 2.
   \]

3. **Compare the Limits:**
   The left-hand limit (3) and the right-hand limit (2) are not equal:
   \[
   \lim_{{x \to 1}} f(x) \text{ does not exist.}
   \]

## Summary

In this section, we explored, basic limits, inderterminate limits, limits at infinity and piecewise-defined limits, including cases where the limit does not exist. These concepts are essential for understanding more complex behaviors in functions.

### Key Takeaways:
- Basic Limits can be solved with simple substitution.
-limits of indeterminate form require some kind of algebraic intervention.
- Limits at infinity describe the end behavior of a function.
- Oscillating functions like \( \sin(x) \) may not have a limit at infinity.
- Piecewise functions require evaluating limits from both sides to determine if the overall limit exists.

