+++
title = '1.4 Practice'
weight = 2
+++

### 1.4 Algebraic Limits

####  Ex1
Evaluate the limit:

\[ \lim_{{x \to 3}} (2x + 5) \]

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Since the expression \(2x + 5\) is a polynomial, we can directly substitute \(x = 3\) into the expression:

\[
\lim_{{x \to 3}} (2x + 5) = 2(3) + 5 = 6 + 5 = 11
\]

So, the limit is:

\[
\boxed{11}
\]

</details>

---

#### Ex2
Evaluate the limit:


\[ \lim_{{x \to 2}} \frac{x^2 + 1}{x - 1} \]

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Since the expression \(\frac{x^2 + 1}{x - 1}\) is a rational function and the denominator does not approach zero as \(x\) approaches 2, we can directly substitute \(x = 2\) into the expression:

\[
\lim_{{x \to 2}} \frac{x^2 + 1}{x - 1} = \frac{2^2 + 1}{2 - 1} = \frac{4 + 1}{1} = \frac{5}{1} = 5
\]

So, the limit is:

\[
\boxed{5}
\]

</details>

---

#### Ex3
Evaluate the following limit:

$$\lim_{{x \to 2}} \frac{x^2 - 4}{x - 2}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Notice the indeterminate form**:
   - As \(x\) approaches 2, both the numerator and the denominator approach 0, creating an indeterminate form \(\frac{0}{0}\).

2. **Factor the numerator**:
   - Recognize that \(x^2 - 4\) is a difference of squares, which can be factored as \((x - 2)(x + 2)\).


\[
   x^2 - 4 = (x - 2)(x + 2)
   \]


3. **Substitute the factored form back into the limit**:

\[
   \lim_{{x \to 2}} \frac{(x - 2)(x + 2)}{x - 2}
   \]

4. **Cancel the common factor**:

\[
   \lim_{{x \to 2}} \frac{(x - 2)(x + 2)}{x - 2} = \lim_{{x \to 2}} (x + 2)
   \]

5. **Evaluate the limit**:
   - As \(x\) approaches 2, the expression \(x + 2\) approaches \(2 + 2 = 4\).

   Therefore:

\[
   \lim_{{x \to 2}} (x + 2) = 4
   \]

So, the limit is:

\[
\boxed{4}
\]

</details>

---

#### Ex4
Evaluate the following limit:

$$\lim_{{x \to 0}} \frac{9 - \sqrt{x^2 + 81}}{x}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Multiply by the conjugate of the numerator**:
   - The conjugate of \(9 - \sqrt{x^2 + 81}\) is \(9 + \sqrt{x^2 + 81}\).
   - Multiply the numerator and the denominator by the conjugate:

\[
   \lim_{{x \to 0}} \frac{(9 - \sqrt{x^2 + 81})(9 + \sqrt{x^2 + 81})}{x (9 + \sqrt{x^2 + 81})}
   \]

2. **Simplify the numerator**:
   - Use the difference of squares formula:

   

\[
   (9 - \sqrt{x^2 + 81})(9 + \sqrt{x^2 + 81}) = 9^2 - (\sqrt{x^2 + 81})^2 = 81 - (x^2 + 81) = 81 - x^2 - 81 = -x^2
   \]



   - So the expression becomes:

   

\[
   \lim_{{x \to 0}} \frac{-x^2}{x (9 + \sqrt{x^2 + 81})}
   \]



3. **Cancel out \(x\) in the numerator and the denominator**:

\[
   \lim_{{x \to 0}} \frac{-x^2}{x (9 + \sqrt{x^2 + 81})} = \lim_{{x \to 0}} \frac{-x}{9 + \sqrt{x^2 + 81}}
   \]

4. **Evaluate the limit**:
   - As \(x \to 0\), the expression inside the square root \(\sqrt{x^2 + 81}\) approaches \(\sqrt{81} = 9\).

   Therefore:

\[
   \lim_{{x \to 0}} \frac{-x}{9 + \sqrt{x^2 + 81}} = \frac{0}{9 + 9} = 0
   \]

So, the limit is:

\[
\boxed{0}
\]

</details>

---

#### Ex5

Evaluate the following limit:

$$\lim_{{x \to 0}} \frac{7 - \sqrt{x^2 + 49}}{x^2}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Multiply by the conjugate of the numerator**:
   - The conjugate of \(7 - \sqrt{x^2 + 49}\) is \(7 + \sqrt{x^2 + 49}\).
   - Multiply the numerator and the denominator by the conjugate:


\[
   \lim_{{x \to 0}} \frac{(7 - \sqrt{x^2 + 49})(7 + \sqrt{x^2 + 49})}{x^2 (7 + \sqrt{x^2 + 49})}
   \]


2. **Simplify the numerator**:
   - Use the difference of squares formula:


\[
   (7 - \sqrt{x^2 + 49})(7 + \sqrt{x^2 + 49}) = 7^2 - (\sqrt{x^2 + 49})^2 = 49 - (x^2 + 49) = 49 - x^2 - 49 = -x^2
   \]

   - So the expression becomes:


\[
   \lim_{{x \to 0}} \frac{-x^2}{x^2 (7 + \sqrt{x^2 + 49})}
   \]

3. **Cancel out \(x^2\) in the numerator and the denominator**:


\[
   \lim_{{x \to 0}} \frac{-x^2}{x^2 (7 + \sqrt{x^2 + 49})} = \lim_{{x \to 0}} \frac{-1}{7 + \sqrt{x^2 + 49}}
   \]

4. **Evaluate the limit**:
   - As \(x \to 0\), the expression inside the square root \(\sqrt{x^2 + 49}\) approaches \(\sqrt{49} = 7\).

   Therefore: 

\[
   \lim_{{x \to 0}} \frac{-1}{7 + \sqrt{x^2 + 49}} = \frac{-1}{7 + 7} = \frac{-1}{14}
   \]

So, the limit is:

\[
\boxed{-\frac{1}{14}}
\]

</details>

---

#### Ex6

Evaluate the following limit:

$$\lim_{{s \to 0}} \frac{8 - \sqrt{s^2 + 64}}{s^2}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Multiply by the conjugate of the numerator**:
   - The conjugate of \(8 - \sqrt{s^2 + 64}\) is \(8 + \sqrt{s^2 + 64}\).
   - Multiply the numerator and the denominator by the conjugate:

\[
   \lim_{{s \to 0}} \frac{(8 - \sqrt{s^2 + 64})(8 + \sqrt{s^2 + 64})}{s^2 (8 + \sqrt{s^2 + 64})}
   \]

2. **Simplify the numerator**:
   - Use the difference of squares formula:

\[
   (8 - \sqrt{s^2 + 64})(8 + \sqrt{s^2 + 64}) = 8^2 - (\sqrt{s^2 + 64})^2 = 64 - (s^2 + 64) = 64 - s^2 - 64 = -s^2
   \]

   - So the expression becomes:

\[
   \lim_{{s \to 0}} \frac{-s^2}{s^2 (8 + \sqrt{s^2 + 64})}
   \]

3. **Cancel out \(s^2\) in the numerator and the denominator**:

\[
   \lim_{{s \to 0}} \frac{-s^2}{s^2 (8 + \sqrt{s^2 + 64})} = \lim_{{s \to 0}} \frac{-1}{8 + \sqrt{s^2 + 64}}
   \]

4. **Evaluate the limit**:
   - As \(s \to 0\), the expression inside the square root \(\sqrt{s^2 + 64}\) approaches \(\sqrt{64} = 8\).

   Therefore:

\[
   \lim_{{s \to 0}} \frac{-1}{8 + \sqrt{s^2 + 64}} = \frac{-1}{8 + 8} = \frac{-1}{16}
   \]

So, the limit is:

\[
\boxed{-\frac{1}{16}}
\]

</details>


---

#### Ex7

Evaluate the following limit:

$$\lim_{{x \to \infty}} \frac{3x^2 + 2x + 1}{5x^2 - x + 4}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>

1. **Identify the highest power of \(x\) in the numerator and denominator**:
   - The highest power of \(x\) is \(x^2\).

2. **Divide every term by \(x^2\)**:

\[
\lim_{{x \to \infty}} \frac{3x^2 + 2x + 1}{5x^2 - x + 4} = \lim_{{x \to \infty}} \frac{\frac{3x^2}{x^2} + \frac{2x}{x^2} + \frac{1}{x^2}}{\frac{5x^2}{x^2} - \frac{x}{x^2} + \frac{4}{x^2}}
\]

Simplify each term:

\[
= \lim_{{x \to \infty}} \frac{3 + \frac{2}{x} + \frac{1}{x^2}}{5 - \frac{1}{x} + \frac{4}{x^2}}
\]

3. **Evaluate the limit as \(x \to \infty\)**:
   - As \(x \to \infty\), \(\frac{2}{x} \to 0\), \(\frac{1}{x^2} \to 0\), and \(\frac{1}{x} \to 0\).

   Therefore, the limit becomes:

\[
\frac{3 + 0 + 0}{5 - 0 + 0} = \frac{3}{5}
\]

So, the limit is:

\[
\boxed{\frac{3}{5}}
\]

</details>

---

#### Ex8

Evaluate the following limit:

$$\lim_{{x \to \infty}} \frac{\sqrt{x^4 + 3x}}{x^2 + 2}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>

1. **Factor \(x^4\) from the square root in the numerator**:

\[
\sqrt{x^4 + 3x} = \sqrt{x^4(1 + \frac{3}{x^3})} = x^2\sqrt{1 + \frac{3}{x^3}}
\]

So, the expression becomes:

\[
\lim_{{x \to \infty}} \frac{\sqrt{x^4 + 3x}}{x^2 + 2} = \lim_{{x \to \infty}} \frac{x^2\sqrt{1 + \frac{3}{x^3}}}{x^2 + 2}
\]

2. **Divide numerator and denominator by \(x^2\)**:

\[
= \lim_{{x \to \infty}} \frac{x^2\sqrt{1 + \frac{3}{x^3}}}{x^2(1 + \frac{2}{x^2})}
\]

Simplify:

\[
= \lim_{{x \to \infty}} \frac{\sqrt{1 + \frac{3}{x^3}}}{1 + \frac{2}{x^2}}
\]

3. **Evaluate the limit as \(x \to \infty\)**:
   - As \(x \to \infty\), \(\frac{3}{x^3} \to 0\) and \(\frac{2}{x^2} \to 0\).

   Therefore, the limit becomes:

\[
\frac{\sqrt{1 + 0}}{1 + 0} = \frac{1}{1} = 1
\]

So, the limit is:

\[
\boxed{1}
\]

</details>

---

#### Ex9

Evaluate the following limit:

$$\lim_{{x \to -\infty}} \frac{5x^3 + 2}{-3x^3 + 7x}$$

<details>
<summary>
    <strong id="solution-title">Solution</strong>
</summary>

1. **Identify the highest power of \(x\) in the numerator and denominator**:
   - The highest power of \(x\) is \(x^3\).

2. **Divide every term by \(x^3\)**:

\[
\lim_{{x \to -\infty}} \frac{5x^3 + 2}{-3x^3 + 7x} = \lim_{{x \to -\infty}} \frac{\frac{5x^3}{x^3} + \frac{2}{x^3}}{\frac{-3x^3}{x^3} + \frac{7x}{x^3}}
\]

Simplify each term:

\[
= \lim_{{x \to -\infty}} \frac{5 + \frac{2}{x^3}}{-3 + \frac{7}{x^2}}
\]

3. **Evaluate the limit as \(x \to -\infty\)**:
   - As \(x \to -\infty\), \(\frac{2}{x^3} \to 0\) and \(\frac{7}{x^2} \to 0\).

   Therefore, the limit becomes:

\[
\frac{5 + 0}{-3 + 0} = \frac{5}{-3} = -\frac{5}{3}
\]

So, the limit is:

\[
\boxed{-\frac{5}{3}}
\]

</details>

---


#### Ex10

Evaluate \( \lim_{{x \to 2}} f(x) \), where:

\[
f(x) = \begin{cases} 
x^2 & \text{if } x < 2, \\
4x - x^2 & \text{if } x \geq 2.
\end{cases}
\]

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Left-Hand Limit:**
   When \( x \to 2^- \), use the first piece \( f(x) = x^2 \):
   \[
   \lim_{{x \to 2^-}} f(x) = (2)^2 = 4.
   \]

2. **Right-Hand Limit:**
   When \( x \to 2^+ \), use the second piece \( f(x) = 4x - x^2 \):
   \[
   \lim_{{x \to 2^+}} f(x) = 4(2) - (2)^2 = 8 - 4 = 4.
   \]

3. **Compare the Limits:**
   The left-hand limit (4) and the right-hand limit (4) are equal:
   \[
   \lim_{{x \to 2}} f(x) = 4.
   \]

</details>

---


#### Ex11
Evaluate \( \lim_{{x \to 0}} f(x) \), where:

\[
f(x) = \begin{cases} 
x + 1 & \text{if } x < 0, \\
1 - x & \text{if } x \geq 0.
\end{cases}
\]

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Left-Hand Limit:**
   When \( x \to 0^- \), use the first piece \( f(x) = x + 1 \):
   \[
   \lim_{{x \to 0^-}} f(x) = 0 + 1 = 1.
   \]

2. **Right-Hand Limit:**
   When \( x \to 0^+ \), use the second piece \( f(x) = 1 - x \):
   \[
   \lim_{{x \to 0^+}} f(x) = 1 - 0 = 1.
   \]

3. **Compare the Limits:**
   The left-hand limit (1) and the right-hand limit (1) are equal:
   \[
   \lim_{{x \to 0}} f(x) = 1.
   \]
</details>

---

#### Ex12
Evaluate \( \lim_{{x \to 3}} f(x) \), where:

\[
f(x) = \begin{cases} 
x - 1 & \text{if } x < 3, \\
x + 1 & \text{if } x \geq 3.
\end{cases}
\]

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Left-Hand Limit:**
   When \( x \to 3^- \), use the first piece \( f(x) = x - 1 \):
   \[
   \lim_{{x \to 3^-}} f(x) = 3 - 1 = 2.
   \]

2. **Right-Hand Limit:**
   When \( x \to 3^+ \), use the second piece \( f(x) = x + 1 \):
   \[
   \lim_{{x \to 3^+}} f(x) = 3 + 1 = 4.
   \]

3. **Compare the Limits:**
   The left-hand limit (2) and the right-hand limit (4) are not equal:
   \[
   \lim_{{x \to 3}} f(x) \text{ does not exist.}
   \]
</details>

---

<iframe src="https://script.google.com/macros/s/AKfycbzBewl8KLaJHnvXduljIILRmStsuTRdwjqhtnQE7sFddrydSNU_niSi26natp9qHFfd/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
