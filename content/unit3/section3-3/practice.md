+++
title = '3.3 Practice:'
weight = 2
+++

## 3.3 Derivatives of Exponential Functions

### Ex1.
Differentiate the following function:

\[
f(x) = e^{2x}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>
Using the chain rule:

\[
\frac{d}{dx}[e^u] = e^u \cdot u'
\]

Let \( u = 2x \). Then \( u' = 2 \).

1. Apply the chain rule:
   \[
   f'(x) = e^{2x} \cdot 2
   \]
2. Final derivative:
   \[
   f'(x) = 2e^{2x}
   \]
</details>

---

### Ex2.
Differentiate the following function:

\[
f(x) = x^3 e^x
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the product rule:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x^3 \) and \( v = e^x \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 3x^2, \quad v' = e^x
   \]
2. Apply the product rule:
   \[
   f'(x) = (3x^2)(e^x) + (x^3)(e^x)
   \]
3. Simplify:
   \[
   f'(x) = e^x(3x^2 + x^3)
   \]
</details>

---

### Ex3.
Differentiate the following function:

\[
f(x) = e^{-x^2}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[e^u] = e^u \cdot u'
\]

Let \( u = -x^2 \). Then \( u' = -2x \).

1. Apply the chain rule:
   \[
   f'(x) = e^{-x^2} \cdot (-2x)
   \]
2. Final derivative:
   \[
   f'(x) = -2x e^{-x^2}
   \]
</details>

---

### Ex4.
Differentiate the following function:

\[
f(x) = \frac{e^x}{x}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the quotient rule:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}

\]
Let \( u = e^x \) and \( v = x \).

1. Find \( u' \) and \( v' \):
   \[
   u' = e^x, \quad v' = 1
   \]
2. Apply the quotient rule:
   \[
   f'(x) = \frac{x \cdot e^x - e^x \cdot 1}{x^2}
   \]
3. Simplify:
   \[
   f'(x) = \frac{xe^x - e^x}{x^2} = \frac{e^x(x - 1)}{x^2}
   \]
</details>

---

### Ex5.

Differentiate the following function:

\[
f(x) = e^{x^2 + 3x}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[e^u] = e^u \cdot u'
\]

Let \( u = x^2 + 3x \). Then \( u' = 2x + 3 \).

1. Apply the chain rule:
   \[
   f'(x) = e^{x^2 + 3x} \cdot (2x + 3)
   \]
2. Final derivative:
   \[
   f'(x) = (2x + 3)e^{x^2 + 3x}
   \]
</details>

---

### Ex6: Combining Chain Rule and Product Rule
#### Problem:
Differentiate \( f(x) = x^2 e^{3x} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x^2 \) and \( v = e^{3x} \).

1. Differentiate \( u = x^2 \):
   \[
   u' = 2x
   \]
2. Differentiate \( v = e^{3x} \) using the **chain rule**:
   \[
   v' = e^{3x} \cdot 3 = 3e^{3x}
   \]
3. Apply the product rule:
   \[
   f'(x) = (2x)(e^{3x}) + (x^2)(3e^{3x})
   \]
4. Simplify:
   \[
   f'(x) = e^{3x}(2x + 3x^2)
   \]

**Final Answer:**

\[
\boxed{f'(x) = e^{3x}(2x + 3x^2)}
\]

</details>

---

### Ex7: Combining Chain Rule and Quotient Rule
#### Problem:

Differentiate \( f(x) = \frac{e^{2x}}{x^3} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = e^{2x} \) and \( v = x^3 \).

1. Differentiate \( u = e^{2x} \) using the **chain rule**:
   \[
   u' = e^{2x} \cdot 2 = 2e^{2x}
   \]
2. Differentiate \( v = x^3 \):
   \[
   v' = 3x^2
   \]
3. Apply the quotient rule:
   \[
   f'(x) = \frac{(x^3)(2e^{2x}) - (e^{2x})(3x^2)}{(x^3)^2}
   \]
4. Simplify:
   \[
   f'(x) = \frac{2x^3e^{2x} - 3x^2e^{2x}}{x^6}
   \]
5. Factor out \( x^2e^{2x} \) from the numerator:
   \[
   f'(x) = \frac{x^2e^{2x}(2x - 3)}{x^6}
   \]
6. Simplify further:
   \[
   f'(x) = \frac{e^{2x}(2x - 3)}{x^4}
   \]
**Final Answer:**

\[
\boxed{f'(x) = \frac{e^{2x}(2x - 3)}{x^4}}
\]

</details>

---

### Ex8: Combining Product Rule, Chain Rule, and Exponential Identities
#### Problem:

Differentiate \( f(x) = e^x \sin(x) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = e^x \) and \( v = \sin(x) \).

1. Differentiate \( u = e^x \):
   \[
   u' = e^x
   \]
2. Differentiate \( v = \sin(x) \):
   \[
   v' = \cos(x)
   \]
3. Apply the product rule:
   \[
   f'(x) = (e^x)(\sin(x)) + (e^x)(\cos(x))
   \]
4. Simplify:
   \[
   f'(x) = e^x(\sin(x) + \cos(x))
   \]

**Final Answer:**

\[
\boxed{f'(x) = e^x(\sin(x) + \cos(x))}
\]
</details>

---

### Ex9: Combining Chain Rule, Quotient Rule, and Exponential Functions
#### Problem:

Differentiate \( f(x) = \frac{e^{x^2}}{\cos(x)} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = e^{x^2} \) and \( v = \cos(x) \).

1. Differentiate \( u = e^{x^2} \) using the **chain rule**:
   \[
   u' = e^{x^2} \cdot 2x = 2x e^{x^2}
   \]
2. Differentiate \( v = \cos(x) \):
   \[
   v' = -\sin(x)
   \]
3. Apply the quotient rule:
   \[
   f'(x) = \frac{(\cos(x))(2x e^{x^2}) - (e^{x^2})(-\sin(x))}{\cos^2(x)}
   \]
4. Simplify:
   \[
   f'(x) = \frac{2x e^{x^2} \cos(x) + e^{x^2} \sin(x)}{\cos^2(x)}
   \]
5. Factor out \( e^{x^2} \) from the numerator:
   \[
   f'(x) = \frac{e^{x^2}(2x \cos(x) + \sin(x))}{\cos^2(x)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{e^{x^2}(2x \cos(x) + \sin(x))}{\cos^2(x)}}
\]

</details>

---

Check out the Below Quiz:

<iframe src="https://script.google.com/macros/s/AKfycbxYtCH8_DstKODkS4RmSCrGLTXrFrbPrP3W635Iuq-KanWwtGDXOFFupbO7_wuh-e2LxA/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>