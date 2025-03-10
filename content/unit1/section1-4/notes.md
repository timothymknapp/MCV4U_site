+++
title = '1.4 Examples'
weight = 1
+++

### Example 1: Evalute the Limit using the Conjugate

Evaluate the following limit:

$$\lim_{{x \to 0}} \frac{5 - \sqrt{x^2 + 25}}{x^2}$$

1. **Multiply by the conjugate of the numerator**:
   - The conjugate of \(5 - \sqrt{x^2 + 25}\) is \(5 + \sqrt{x^2 + 25}\).
   - Multiply the numerator and the denominator by the conjugate:

   

\[
   \lim_{{x \to 0}} \frac{(5 - \sqrt{x^2 + 25})(5 + \sqrt{x^2 + 25})}{x^2 (5 + \sqrt{x^2 + 25})}
   \]



2. **Simplify the numerator**:
   - Use the difference of squares formula:

   

\[
   (5 - \sqrt{x^2 + 25})(5 + \sqrt{x^2 + 25}) = 5^2 - (\sqrt{x^2 + 25})^2 = 25 - (x^2 + 25) = 25 - x^2 - 25 = -x^2
   \]



   - So the expression becomes:

   

\[
   \lim_{{x \to 0}} \frac{-x^2}{x^2 (5 + \sqrt{x^2 + 25})}
   \]



3. **Cancel out \(x^2\) in the numerator and the denominator**:

\[
   \lim_{{x \to 0}} \frac{-x^2}{x^2 (5 + \sqrt{x^2 + 25})} = \lim_{{x \to 0}} \frac{-1}{5 + \sqrt{x^2 + 25}}
   \]

4. **Evaluate the limit**:
   - As \(x \to 0\), the expression inside the square root \(\sqrt{x^2 + 25}\) approaches \(\sqrt{25} = 5\).

   Therefore:

\[
   \lim_{{x \to 0}} \frac{-1}{5 + \sqrt{x^2 + 25}} = \frac{-1}{5 + 5} = \frac{-1}{10}
   \]

So, the limit is:

\[
\boxed{-\frac{1}{10}}
\]

---

### Example 2: Evalute the Limit at Infinity

Evaluate \( \lim_{{x \to \infty}} \frac{x^2 + 3x}{2x^2 - x + 5} \).

#### Solution:
1. Identify the dominant terms in the numerator and denominator:
   - Numerator: \( x^2 + 3x \) → \( x^2 \) dominates.
   - Denominator: \( 2x^2 - x + 5 \) → \( 2x^2 \) dominates.

2. Simplify the fraction:

   \[
   \frac{x^2 + 3x}{2x^2 - x + 5} \approx \frac{x^2}{2x^2} = \frac{1}{2}.
   \]

 Alternate Approach:

1.  Divide every term by \( x^2 \):

   \[
   \lim_{{x \to \infty}} \frac{x^2 + 3x}{2x^2 - x + 5} = \frac{1 + \frac{3}{x}}{2 - \frac{1}{x} + \frac{5}{x^2}}.
   \]

   
2.   As \( x \to \infty \), all terms with \( \frac{1}{x} \) or \( \frac{1}{x^2} \) approach 0:
   

   \[
   \frac{1 + 0}{2 - 0 + 0} = \frac{1}{2}.
   \]

3.  Thus, \( \lim_{{x \to \infty}} \frac{x^2 + 3x}{2x^2 - x + 5} = \frac{1}{2}. \)

---

### Example 3: Evaluate Limit at Infinity

Evaluate \( \lim_{{x \to -\infty}} \frac{x^3 - 2x^2}{3x^3 + x + 4} \).

#### Solution:
1. Identify the dominant terms:
   - Numerator: \( x^3 - 2x^2 \) → \( x^3 \) dominates.
   - Denominator: \( 3x^3 + x + 4 \) → \( 3x^3 \) dominates.

2. Simplify the fraction:
   \[
   \frac{x^3 - 2x^2}{3x^3 + x + 4} \approx \frac{x^3}{3x^3} = \frac{1}{3}.
   \]

Alternate Approach:
1. Divide every term by \( x^3 \):
   
   \[
   \lim_{{x \to -\infty}} \frac{x^3 - 2x^2}{3x^3 + x + 4} = \frac{1 - \frac{2}{x}}{3 + \frac{1}{x^2} + \frac{4}{x^3}}.
   \]

2.   As \( x \to -\infty \), all terms with \( \frac{1}{x} \), \( \frac{1}{x^2} \), or \( \frac{1}{x^3} \) approach 0:
   
   \[
   \frac{1 - 0}{3 + 0 + 0} = \frac{1}{3}.
   \]

3. Thus, \( \lim_{{x \to -\infty}} \frac{x^3 - 2x^2}{3x^3 + x + 4} = \frac{1}{3}. \)

---

### Example 4: Evaluate the limit of a Piecewise Function:

Consider the graph of a piecewise function:

\[
f(x) = 
\begin{cases} 
x^2 - 1 & \text{if } x < 0, \\
3x + 1 & \text{if } x \geq 0.
\end{cases}
\]

Evaluate \( \lim_{{x \to 0}} f(x) \):

#### Solution:

1. **Left-Hand Limit**:
   When \( x \to 0^- \), use \( f(x) = x^2 - 1 \):
   \[
   \lim_{{x \to 0^-}} f(x) = 0^2 - 1 = -1.
   \]

2. **Right-Hand Limit**:
   When \( x \to 0^+ \), use \( f(x) = 3x + 1 \):
   \[
   \lim_{{x \to 0^+}} f(x) = 3(0) + 1 = 1.
   \]

3. **Compare the Limits**:
   The left-hand limit (\(-1\)) and the right-hand limit (\(1\)) are not equal:
   \[
   \lim_{{x \to 0}} f(x) \text{ does not exist.}
   \]

---
