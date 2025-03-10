+++
title = "2.6 Practice"
weight = 2
+++

## Mixed Derivative Problems:

#### Ex1.
Differentiate the following function using the product and chain rules:
\[
y = (x^3 + 2x)(4x^2 - 3)^5
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Identify the two factors in the product:
   - First factor: \( u(x) = x^3 + 2x \)
   - Second factor: \( v(x) = (4x^2 - 3)^5 \)

2. Apply the **product rule**:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]

3. Differentiate \( u(x) \):
   \[
   u'(x) = 3x^2 + 2
   \]

4. Differentiate \( v(x) \) using the **chain rule**:
   - Outer function: \( w(z) = z^5 \), where \( z = 4x^2 - 3 \).
   - Inner function: \( z(x) = 4x^2 - 3 \).
   - Differentiate the outer function:
     \[
     \frac{dw}{dz} = 5z^4
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = 8x
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 5(4x^2 - 3)^4 \cdot 8x = 40x(4x^2 - 3)^4
     \]

5. Substitute into the product rule formula:
   \[
   \frac{dy}{dx} = (3x^2 + 2)(4x^2 - 3)^5 + (x^3 + 2x) \cdot 40x(4x^2 - 3)^4
   \]

6. Simplify if desired:
   \[
   \frac{dy}{dx} = (3x^2 + 2)(4x^2 - 3)^5 + 40x^2(x^3 + 2x)(4x^2 - 3)^4
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = (3x^2 + 2)(4x^2 - 3)^5 + 40x^2(x^3 + 2x)(4x^2 - 3)^4}
\]
</details>

---

#### Ex2.
Differentiate the following function using the quotient and chain rules:
\[
y = \frac{(2x^2 + 1)^3}{x^4 - 5x + 7}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Identify the numerator and denominator:
   - Numerator: \( u(x) = (2x^2 + 1)^3 \)
   - Denominator: \( v(x) = x^4 - 5x + 7 \)

2. Apply the **quotient rule**:
   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]

3. Differentiate \( u(x) \) using the **chain rule**:
   - Outer function: \( w(z) = z^3 \), where \( z = 2x^2 + 1 \).
   - Inner function: \( z(x) = 2x^2 + 1 \).
   - Differentiate the outer function:
     \[
     \frac{dw}{dz} = 3z^2
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = 4x
     \]
   - Multiply the derivatives:
     \[
     u'(x) = 3(2x^2 + 1)^2 \cdot 4x = 12x(2x^2 + 1)^2
     \]

4. Differentiate \( v(x) \):
   \[
   v'(x) = 4x^3 - 5
   \]

5. Substitute into the quotient rule formula:
   \[
   \frac{dy}{dx} = \frac{[12x(2x^2 + 1)^2](x^4 - 5x + 7) - [(2x^2 + 1)^3](4x^3 - 5)}{(x^4 - 5x + 7)^2}
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = \frac{12x(2x^2 + 1)^2(x^4 - 5x + 7) - (2x^2 + 1)^3(4x^3 - 5)}{(x^4 - 5x + 7)^2}}
\]
</details>

---

#### Ex3.
Differentiate the following function using the power, product, and chain rules:
\[
y = x^2 \cdot \sqrt{x^3 + 4}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Rewrite the square root as a power:
   \[
   y = x^2 \cdot (x^3 + 4)^{\frac{1}{2}}
   \]

2. Identify the two factors in the product:
   - First factor: \( u(x) = x^2 \)
   - Second factor: \( v(x) = (x^3 + 4)^{\frac{1}{2}} \)

3. Apply the **product rule**:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]

4. Differentiate \( u(x) \):
   \[
   u'(x) = 2x
   \]

5. Differentiate \( v(x) \) using the **chain rule**:
   - Outer function: \( w(z) = z^{\frac{1}{2}} \), where \( z = x^3 + 4 \).
   - Inner function: \( z(x) = x^3 + 4 \).
   - Differentiate the outer function:
     \[
     \frac{dw}{dz} = \frac{1}{2}z^{-\frac{1}{2}}
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = 3x^2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = \frac{1}{2}(x^3 + 4)^{-\frac{1}{2}} \cdot 3x^2 = \frac{3x^2}{2\sqrt{x^3 + 4}}
     \]

6. Substitute into the product rule formula:
   \[
   \frac{dy}{dx} = 2x \cdot (x^3 + 4)^{\frac{1}{2}} + x^2 \cdot \frac{3x^2}{2\sqrt{x^3 + 4}}
   \]

7. Simplify:
   \[
   \frac{dy}{dx} = 2x\sqrt{x^3 + 4} + \frac{3x^4}{2\sqrt{x^3 + 4}}
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = 2x\sqrt{x^3 + 4} + \frac{3x^4}{2\sqrt{x^3 + 4}}}
\]
</details>

---

## Mixed Derivative Problems:

#### Ex4.
Differentiate the following function using the product and chain rules:
\[
y = (3x^2 + 5x)(2x - 1)^3
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>
**Solution:**
1. Identify the two factors in the product:
   - First factor: \( u(x) = 3x^2 + 5x \)
   - Second factor: \( v(x) = (2x - 1)^3 \)

2. Apply the **product rule**:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]

3. Differentiate \( u(x) \):
   \[
   u'(x) = 6x + 5
   \]

4. Differentiate \( v(x) \) using the **chain rule**:
   - Outer function: \( w(z) = z^3 \), where \( z = 2x - 1 \).
   - Inner function: \( z(x) = 2x - 1 \).
   - Differentiate the outer function:
     \[
     \frac{dw}{dz} = 3z^2
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = 2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 3(2x - 1)^2 \cdot 2 = 6(2x - 1)^2
     \]

5. Substitute into the product rule formula:
   \[
   \frac{dy}{dx} = (6x + 5)(2x - 1)^3 + (3x^2 + 5x) \cdot 6(2x - 1)^2
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = (6x + 5)(2x - 1)^3 + 6(3x^2 + 5x)(2x - 1)^2}
\]
</details>

---

#### Ex5.
Differentiate the following function using the quotient and chain rules:
\[
y = \frac{(x^2 + 3x)}{(x^3 - 2x + 1)}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>
**Solution:**
1. Identify the numerator and denominator:
   - Numerator: \( u(x) = x^2 + 3x \)
   - Denominator: \( v(x) = x^3 - 2x + 1 \)

2. Apply the **quotient rule**:
   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]

3. Differentiate \( u(x) \):
   \[
   u'(x) = 2x + 3
   \]

4. Differentiate \( v(x) \):
   \[
   v'(x) = 3x^2 - 2
   \]

5. Substitute into the quotient rule formula:
   \[
   \frac{dy}{dx} = \frac{(2x + 3)(x^3 - 2x + 1) - (x^2 + 3x)(3x^2 - 2)}{(x^3 - 2x + 1)^2}
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = \frac{(2x + 3)(x^3 - 2x + 1) - (x^2 + 3x)(3x^2 - 2)}{(x^3 - 2x + 1)^2}}
\]
</details>

---

#### Ex6.
Differentiate the following function using the product and chain rules:
\[
y = (x^2 - 4x)(x^3 + x - 5)^2
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>
**Solution:**
1. Identify the two factors in the product:
   - First factor: \( u(x) = x^2 - 4x \)
   - Second factor: \( v(x) = (x^3 + x - 5)^2 \)

2. Apply the **product rule**:
   \[
   \frac{dy}{dx} = u'(x)v(x) + u(x)v'(x)
   \]

3. Differentiate \( u(x) \):
   \[
   u'(x) = 2x - 4
   \]

4. Differentiate \( v(x) \) using the **chain rule**:
   - Outer function: \( w(z) = z^2 \), where \( z = x^3 + x - 5 \).
   - Inner function: \( z(x) = x^3 + x - 5 \).
   - Differentiate the outer function:
     \[
     \frac{dw}{dz} = 2z
     \]
   - Differentiate the inner function:
     \[
     \frac{dz}{dx} = 3x^2 + 1
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 2(x^3 + x - 5) \cdot (3x^2 + 1) = 2(3x^2 + 1)(x^3 + x - 5)
     \]

5. Substitute into the product rule formula:
   \[
   \frac{dy}{dx} = (2x - 4)(x^3 + x - 5)^2 + (x^2 - 4x) \cdot 2(3x^2 + 1)(x^3 + x - 5)
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = (2x - 4)(x^3 + x - 5)^2 + 2(x^2 - 4x)(3x^2 + 1)(x^3 + x - 5)}
\]
</details>

---

#### Ex7.
Differentiate the following function using the quotient and chain rules:
\[
y = \frac{(x^2 - 3x + 2)}{(x^2 + x - 6)}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>
**Solution:**
1. Identify the numerator and denominator:
   - Numerator: \( u(x) = x^2 - 3x + 2 \)
   - Denominator: \( v(x) = x^2 + x - 6 \)

2. Apply the **quotient rule**:
   \[
   \frac{dy}{dx} = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]

3. Differentiate \( u(x) \):
   \[
   u'(x) = 2x - 3
   \]

4. Differentiate \( v(x) \):
   \[
   v'(x) = 2x + 1
   \]

5. Substitute into the quotient rule formula:
   \[
   \frac{dy}{dx} = \frac{(2x - 3)(x^2 + x - 6) - (x^2 - 3x + 2)(2x + 1)}{(x^2 + x - 6)^2}
   \]

Thus, the derivative is:
\[
\boxed{\frac{dy}{dx} = \frac{(2x - 3)(x^2 + x - 6) - (x^2 - 3x + 2)(2x + 1)}{(x^2 + x - 6)^2}}
\]
</details>

---

<iframe src="https://script.google.com/macros/s/AKfycbyz4Hkw7kMgJd9n60pZfUzpr2UFDbNPfZEE7-U72kf2eOmky8UkBoihAWHF81BRmRA28g/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>