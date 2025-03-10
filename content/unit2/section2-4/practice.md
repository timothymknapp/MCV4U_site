+++
title = '2.4 Practice:'
weight = 2
+++

### 2.4 Quotient Rule

#### Ex1.

Differentiate the following function using the quotient rule:


\[
f(x) = \frac{x^3 + 5x}{x^2 - 1}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

**Solution:**

Using the quotient rule:
\[
\frac{d}{dx} \left( \frac{u}{v} \right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]
Let \( u = x^3 + 5x \) and \( v = x^2 - 1 \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 3x^2 + 5, \quad v' = 2x
   \]

2. Apply the quotient rule:
   \[
   f'(x) = \frac{(x^2 - 1)(3x^2 + 5) - (x^3 + 5x)(2x)}{(x^2 - 1)^2}
   \]

3. Simplify the numerator:
   \[
   (x^2 - 1)(3x^2 + 5) = 3x^4 + 5x^2 - 3x^2 - 5 = 3x^4 + 2x^2 - 5
   \]
   \[
   (x^3 + 5x)(2x) = 2x^4 + 10x^2
   \]
   So the numerator is:
   \[
   (3x^4 + 2x^2 - 5) - (2x^4 + 10x^2) = x^4 - 8x^2 - 5
   \]

4. Final derivative:
   \[
   f'(x) = \frac{x^4 - 8x^2 - 5}{(x^2 - 1)^2}
   \]
</details>

---

#### Ex2.

Differentiate the following function:

\[
f(x) = \frac{2x^2 - 3}{x + 4}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

**Solution:**

Using the quotient rule:

Let \( u = 2x^2 - 3 \) and \( v = x + 4 \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 4x, \quad v' = 1
   \]

2. Apply the quotient rule:
   \[
   f'(x) = \frac{(x + 4)(4x) - (2x^2 - 3)(1)}{(x + 4)^2}
   \]

3. Simplify the numerator:
   \[
   (x + 4)(4x) = 4x^2 + 16x
   \]
   \[
   (2x^2 - 3)(1) = 2x^2 - 3
   \]
   So the numerator is:
   \[
   (4x^2 + 16x) - (2x^2 - 3) = 2x^2 + 16x + 3
   \]

4. Final derivative:
   \[
   f'(x) = \frac{2x^2 + 16x + 3}{(x + 4)^2}
   \]
</details>

---

#### Ex3.

Differentiate the following function:

\[
f(x) = \frac{x^4 - x}{x^3 + 2}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

**Solution:**

Using the quotient rule:

Let \( u = x^4 - x \) and \( v = x^3 + 2 \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 4x^3 - 1, \quad v' = 3x^2
   \]

2. Apply the quotient rule:
   \[
   f'(x) = \frac{(x^3 + 2)(4x^3 - 1) - (x^4 - x)(3x^2)}{(x^3 + 2)^2}
   \]

3. Simplify the numerator:
   \[
   (x^3 + 2)(4x^3 - 1) = 4x^6 - x^3 + 8x^3 - 2 = 4x^6 + 7x^3 - 2
   \]
   \[
   (x^4 - x)(3x^2) = 3x^6 - 3x^3
   \]
   So the numerator is:
   \[
   (4x^6 + 7x^3 - 2) - (3x^6 - 3x^3) = x^6 + 10x^3 - 2
   \]

4. Final derivative:
   \[
   f'(x) = \frac{x^6 + 10x^3 - 2}{(x^3 + 2)^2}
   \]
</details>

---

#### Ex4.

Differentiate the following function:

\[
f(x) = \frac{3x^2 + 2}{x - 3}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

**Solution:**

Using the quotient rule:

Let \( u = 3x^2 + 2 \) and \( v = x - 3 \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 6x, \quad v' = 1
   \]

2. Apply the quotient rule:
   \[
   f'(x) = \frac{(x - 3)(6x) - (3x^2 + 2)(1)}{(x - 3)^2}
   \]

3. Simplify the numerator:
   \[
   (x - 3)(6x) = 6x^2 - 18x
   \]
   \[
   (3x^2 + 2)(1) = 3x^2 + 2
   \]
   So the numerator is:
   \[
   (6x^2 - 18x) - (3x^2 + 2) = 3x^2 - 18x - 2
   \]

4. Final derivative:
   \[
   f'(x) = \frac{3x^2 - 18x - 2}{(x - 3)^2}
   \]
</details>

---

#### Ex5.

Differentiate the following function:

\[
f(x) = \frac{\sqrt{x}}{x - 2}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

**Solution:**

Using the quotient rule:

Let \( u = \sqrt{x} = x^{1/2} \) and \( v = x - 2 \).

1. Find \( u' \) and \( v' \):

   - For \( u = x^{1/2} \), apply the power rule:
     \[
     u' = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}
     \]
   - For \( v = x - 2 \), the derivative is:
     \[
     v' = 1
     \]

2. Apply the quotient rule:
   \[
   f'(x) = \frac{(x - 2) \cdot \frac{1}{2\sqrt{x}} - \sqrt{x} \cdot 1}{(x - 2)^2}
   \]

3. Simplify the numerator:
   \[
   f'(x) = \frac{\frac{x - 2}{2\sqrt{x}} - \sqrt{x}}{(x - 2)^2}
   \]

4. Combine terms in the numerator:
   \[
   f'(x) = \frac{\frac{x - 2 - 2x}{2\sqrt{x}}}{(x - 2)^2}
   \]
   Simplify the numerator:
   \[
   f'(x) = \frac{\frac{-x - 2}{2\sqrt{x}}}{(x - 2)^2}
   \]

Thus, the final derivative is:
\[
f'(x) = \frac{-x - 2}{2\sqrt{x}(x - 2)^2}
\]
</details>


<iframe src="https://script.google.com/macros/s/AKfycbwl2QJZ7hzxA7CegRYVkGMIKaggAanI9OfivfN7hULDTsjblW3Nte0RAIw_3395G9ng/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

