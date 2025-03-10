+++
title = '3.4 Practice:'
weight = 2
+++

## 3.4 Derivatives of Logarithmic Functions

### Ex1.
Differentiate the following function:

\[
f(x) = \ln(4x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\ln(u)] = \frac{1}{u} \cdot u'
\]

Let \( u = 4x \). Then \( u' = 4 \).

1. Apply the chain rule:
   \[
   f'(x) = \frac{1}{4x} \cdot 4
   \]
2. Simplify:
   \[
   f'(x) = \frac{4}{4x} = \frac{1}{x}
   \]
</details>

---

### Ex2.

Differentiate the following function:

\[
f(x) = x^2 \ln(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the product rule:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x^2 \) and \( v = \ln(x) \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 2x, \quad v' = \frac{1}{x}
   \]
2. Apply the product rule:
   \[
   f'(x) = (2x)(\ln(x)) + (x^2)\left(\frac{1}{x}\right)
   \]
3. Simplify:
   \[
   f'(x) = 2x\ln(x) + x
   \]
</details>

---

### Ex3.

Differentiate the following function:

\[
f(x) = \ln(\sin(x))
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\ln(u)] = \frac{1}{u} \cdot u'
\]

Let \( u = \sin(x) \). Then \( u' = \cos(x) \).

1. Apply the chain rule:
   \[
   f'(x) = \frac{1}{\sin(x)} \cdot \cos(x)
   \]
2. Simplify using the identity \( \frac{\cos(x)}{\sin(x)} = \cot(x) \):
   \[
   f'(x) = \cot(x)
   \]
</details>

---

### Ex4.

Differentiate the following function:

\[
f(x) = \frac{\ln(x)}{x}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the quotient rule:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \ln(x) \) and \( v = x \).

1. Find \( u' \) and \( v' \):
   \[
   u' = \frac{1}{x}, \quad v' = 1
   \]
2. Apply the quotient rule:
   \[
   f'(x) = \frac{x \cdot \frac{1}{x} - \ln(x) \cdot 1}{x^2}
   \]
3. Simplify:
   \[
   f'(x) = \frac{1 - \ln(x)}{x^2}
   \]
</details>

---

### Ex5.

Differentiate the following function:

\[
f(x) = \ln(x^2 + 1)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\ln(u)] = \frac{1}{u} \cdot u'
\]

Let \( u = x^2 + 1 \). Then \( u' = 2x \).

1. Apply the chain rule:
   \[
   f'(x) = \frac{1}{x^2 + 1} \cdot 2x
   \]
2. Simplify:
   \[
   f'(x) = \frac{2x}{x^2 + 1}
   \]
</details>

---

### Ex6: Combining Chain Rule and Product Rule
#### Problem:

Differentiate \( f(x) = x \ln(3x) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x \) and \( v = \ln(3x) \).

1. Differentiate \( u = x \):
   \[
   u' = 1
   \]
2. Differentiate \( v = \ln(3x) \) using the **chain rule**:
   \[
   v' = \frac{1}{3x} \cdot 3 = \frac{1}{x}
   \]
3. Apply the product rule:
   \[
   f'(x) = (1)(\ln(3x)) + (x)\left(\frac{1}{x}\right)
   \]
4. Simplify:
   \[
   f'(x) = \ln(3x) + 1
   \]

**Final Answer:**

\[
\boxed{f'(x) = \ln(3x) + 1}
\]

</details>

---

### Ex7: Combining Chain Rule and Quotient Rule
#### Problem:

Differentiate \( f(x) = \frac{\ln(x)}{\sqrt{x}} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \ln(x) \) and \( v = \sqrt{x} = x^{1/2} \).

1. Differentiate \( u = \ln(x) \):
   \[
   u' = \frac{1}{x}
   \]
2. Differentiate \( v = x^{1/2} \):
   \[
   v' = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}
   \]
3. Apply the quotient rule:
   \[
   f'(x) = \frac{(\sqrt{x})\left(\frac{1}{x}\right) - (\ln(x))\left(\frac{1}{2\sqrt{x}}\right)}{(\sqrt{x})^2}
   \]
4. Simplify the numerator:
   \[
   f'(x) = \frac{\frac{\sqrt{x}}{x} - \frac{\ln(x)}{2\sqrt{x}}}{x}
   \]
5. Combine terms in the numerator:
   \[
   f'(x) = \frac{\frac{1}{\sqrt{x}} - \frac{\ln(x)}{2\sqrt{x}}}{x}
   \]
6. Factor out \( \frac{1}{\sqrt{x}} \) from the numerator:
   \[
   f'(x) = \frac{\frac{1}{\sqrt{x}}\left(1 - \frac{\ln(x)}{2}\right)}{x}
   \]
7. Simplify further:
   \[
   f'(x) = \frac{1 - \frac{\ln(x)}{2}}{x\sqrt{x}}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{1 - \frac{\ln(x)}{2}}{x\sqrt{x}}}
\]

</details>

---

### Ex8: Combining Product Rule, Chain Rule, and Logarithmic Identities
#### Problem:

Differentiate \( f(x) = \ln(x) \sin(x) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = \ln(x) \) and \( v = \sin(x) \).

1. Differentiate \( u = \ln(x) \):
   \[
   u' = \frac{1}{x}
   \]
2. Differentiate \( v = \sin(x) \):
   \[
   v' = \cos(x)
   \]
3. Apply the product rule:
   \[
   f'(x) = \left(\frac{1}{x}\right)(\sin(x)) + (\ln(x))(\cos(x))
   \]
4. Simplify:
   \[
   f'(x) = \frac{\sin(x)}{x} + \ln(x)\cos(x)
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{\sin(x)}{x} + \ln(x)\cos(x)}
\]

</details>

---

### Ex9: Combining Chain Rule, Quotient Rule, and Logarithmic Functions
#### Problem:

Differentiate \( f(x) = \frac{\ln(x^2)}{\cos(x)} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \ln(x^2) \) and \( v = \cos(x) \).

1. Differentiate \( u = \ln(x^2) \) using the **chain rule**:
   \[
   u' = \frac{1}{x^2} \cdot 2x = \frac{2}{x}
   \]
2. Differentiate \( v = \cos(x) \):
   \[
   v' = -\sin(x)
   \]
3. Apply the quotient rule:
   \[
   f'(x) = \frac{(\cos(x))\left(\frac{2}{x}\right) - (\ln(x^2))(-\sin(x))}{\cos^2(x)}
   \]
4. Simplify:
   \[
   f'(x) = \frac{\frac{2\cos(x)}{x} + \ln(x^2)\sin(x)}{\cos^2(x)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{\frac{2\cos(x)}{x} + \ln(x^2)\sin(x)}{\cos^2(x)}}
\]

</details>

---

### Ex10.

Differentiate the following function:

\[
f(x) = \log_2(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the formula for the derivative of a logarithm with base \( a \):

\[
\frac{d}{dx}[\log_a(x)] = \frac{1}{x \ln(a)}
\]

Here, \( a = 2 \).

1. Apply the formula:
   \[
   f'(x) = \frac{1}{x \ln(2)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{1}{x \ln(2)}}
\]

</details>

---

### Ex11.

Differentiate the following function:

\[
f(x) = x \log_{10}(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the product rule:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x \) and \( v = \log_{10}(x) \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 1, \quad v' = \frac{1}{x \ln(10)}
   \]
2. Apply the product rule:
   \[
   f'(x) = (1)(\log_{10}(x)) + (x)\left(\frac{1}{x \ln(10)}\right)
   \]
3. Simplify:
   \[
   f'(x) = \log_{10}(x) + \frac{1}{\ln(10)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \log_{10}(x) + \frac{1}{\ln(10)}}
\]

</details>

---

### Ex12.

Differentiate the following function:

\[
f(x) = \log_2(x^2 + 1)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\log_a(u)] = \frac{1}{u \ln(a)} \cdot u'
\]

Let \( u = x^2 + 1 \). Then \( u' = 2x \).

1. Apply the chain rule:
   \[
   f'(x) = \frac{1}{(x^2 + 1) \ln(2)} \cdot 2x
   \]
2. Simplify:
   \[
   f'(x) = \frac{2x}{(x^2 + 1) \ln(2)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{2x}{(x^2 + 1) \ln(2)}}
\]

</details>

---

### Ex13.

Differentiate the following function:

\[
f(x) = \frac{\log_{10}(x)}{x}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the quotient rule:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \log_{10}(x) \) and \( v = x \).

1. Find \( u' \) and \( v' \):
   \[
   u' = \frac{1}{x \ln(10)}, \quad v' = 1
   \]
2. Apply the quotient rule:
   \[
   f'(x) = \frac{x \cdot \frac{1}{x \ln(10)} - \log_{10}(x) \cdot 1}{x^2}
   \]
3. Simplify:
   \[
   f'(x) = \frac{\frac{1}{\ln(10)} - \log_{10}(x)}{x^2}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{\frac{1}{\ln(10)} - \log_{10}(x)}{x^2}}
\]

</details>

---

### Ex14.

Differentiate the following function:

\[
f(x) = \log_2(\sin(x))
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\log_a(u)] = \frac{1}{u \ln(a)} \cdot u'
\]

Let \( u = \sin(x) \). Then \( u' = \cos(x) \).

1. Apply the chain rule:
   \[
   f'(x) = \frac{1}{\sin(x) \ln(2)} \cdot \cos(x)
   \]
2. Simplify using the identity \( \frac{\cos(x)}{\sin(x)} = \cot(x) \):
   \[
   f'(x) = \frac{\cot(x)}{\ln(2)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{\cot(x)}{\ln(2)}}
\]

</details>

---

<iframe src="https://script.google.com/macros/s/AKfycbzMfYnkp4aSKiEw0vTUPQRjjuCweSnC163y3NF_jiHAh1Ily0CnsbnPw6uCDPSCygwuGw/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>