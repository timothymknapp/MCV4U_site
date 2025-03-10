+++
title = '3.1 Practice:'
weight = 3
+++

## 3.1 Derivatives of Trigonometric Functions

### Ex1.
Differentiate the following function:

\[
f(x) = \sin(3x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the chain rule:

\[
\frac{d}{dx}[\sin(u)] = \cos(u) \cdot u'
\]

Let \( u = 3x \). Then \( u' = 3 \).

1. Apply the chain rule:
   \[
   f'(x) = \cos(3x) \cdot 3
   \]
2. Final derivative:
   \[
   f'(x) = 3\cos(3x)
   \]
</details>

---

### Ex2.
Differentiate the following function:

\[
f(x) = x^2 \cos(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


Using the product rule:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x^2 \) and \( v = \cos(x) \).

1. Find \( u' \) and \( v' \):
   \[
   u' = 2x, \quad v' = -\sin(x)
   \]
2. Apply the product rule:
   \[
   f'(x) = (2x)(\cos(x)) + (x^2)(-\sin(x))
   \]
3. Simplify:
   \[
   f'(x) = 2x\cos(x) - x^2\sin(x)
   \]
</details>

---

### Ex3.
Differentiate the following function:

\[
f(x) = \tan(2x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


Using the chain rule:

\[
\frac{d}{dx}[\tan(u)] = \sec^2(u) \cdot u'
\]

Let \( u = 2x \). Then \( u' = 2 \).

1. Apply the chain rule:
   \[
   f'(x) = \sec^2(2x) \cdot 2
   \]
2. Final derivative:
   \[
   f'(x) = 2\sec^2(2x)
   \]
</details>

---

### Ex4.
Differentiate the following function:

\[
f(x) = \frac{\sin(x)}{\cos(x)}
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


Using the quotient rule:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \sin(x) \) and \( v = \cos(x) \).

1. Find \( u' \) and \( v' \):
   \[
   u' = \cos(x), \quad v' = -\sin(x)
   \]
2. Apply the quotient rule:
   \[
   f'(x) = \frac{\cos(x) \cdot \cos(x) - \sin(x) \cdot (-\sin(x))}{\cos^2(x)}
   \]
3. Simplify the numerator:
   \[
   \cos^2(x) + \sin^2(x) = 1
   \]
4. Final derivative:
   \[
   f'(x) = \frac{1}{\cos^2(x)} = \sec^2(x)
   \]
</details>

---

### Ex5.
Differentiate the following function:

\[
f(x) = \sec(x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>


Using the derivative formula for secant:

\[
\frac{d}{dx}[\sec(x)] = \sec(x)\tan(x)
\]

1. Final derivative:
   \[
   f'(x) = \sec(x)\tan(x)
   \]
</details>

---


### Ex 6: Combining Chain Rule and Product Rule

#### Problem:
Differentiate \( f(x) = x^2 \sin(3x) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = x^2 \) and \( v = \sin(3x) \).

1. Differentiate \( u = x^2 \):
   \[
   u' = 2x
   \]

2. Differentiate \( v = \sin(3x) \) using the **chain rule**:
   \[
   v' = \cos(3x) \cdot 3 = 3\cos(3x)
   \]

3. Apply the product rule:
   \[
   f'(x) = (2x)(\sin(3x)) + (x^2)(3\cos(3x))
   \]

4. Simplify:
   \[
   f'(x) = 2x\sin(3x) + 3x^2\cos(3x)
   \]

**Final Answer:**

\[
\boxed{f'(x) = 2x\sin(3x) + 3x^2\cos(3x)}
\]
</details>

---

### Ex 7: Combining Chain Rule and Quotient Rule

#### Problem:

Differentiate \( f(x) = \frac{\tan(2x)}{x^2} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \tan(2x) \) and \( v = x^2 \).

1. Differentiate \( u = \tan(2x) \) using the **chain rule**:
   \[
   u' = \sec^2(2x) \cdot 2 = 2\sec^2(2x)
   \]

2. Differentiate \( v = x^2 \):
   \[
   v' = 2x
   \]

3. Apply the quotient rule:
   \[
   f'(x) = \frac{(x^2)(2\sec^2(2x)) - (\tan(2x))(2x)}{(x^2)^2}
   \]

4. Simplify:
   \[
   f'(x) = \frac{2x^2\sec^2(2x) - 2x\tan(2x)}{x^4}
   \]

5. Factor out \( 2x \) from the numerator:
   \[
   f'(x) = \frac{2x(x\sec^2(2x) - \tan(2x))}{x^4}
   \]

6. Simplify further:
   \[
   f'(x) = \frac{2(x\sec^2(2x) - \tan(2x))}{x^3}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{2(x\sec^2(2x) - \tan(2x))}{x^3}}
\]
</details>

---

### Ex 8: Combining Product Rule, Chain Rule, and Trigonometric Identities

#### Problem:
Differentiate \( f(x) = \sin(x)\cos(2x) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **product rule**:

\[
\frac{d}{dx}[u \cdot v] = u'v + uv'
\]

Let \( u = \sin(x) \) and \( v = \cos(2x) \).

1. Differentiate \( u = \sin(x) \):
   \[
   u' = \cos(x)
   \]

2. Differentiate \( v = \cos(2x) \) using the **chain rule**:
   \[
   v' = -\sin(2x) \cdot 2 = -2\sin(2x)
   \]

3. Apply the product rule:
   \[
   f'(x) = (\cos(x))(\cos(2x)) + (\sin(x))(-2\sin(2x))
   \]

4. Simplify:
   \[
   f'(x) = \cos(x)\cos(2x) - 2\sin(x)\sin(2x)
   \]

5. Use the trigonometric identity \( \sin(2x) = 2\sin(x)\cos(x) \):
   \[
   f'(x) = \cos(x)\cos(2x) - 2\sin(x)(2\sin(x)\cos(x))
   \]

6. Simplify further:
   \[
   f'(x) = \cos(x)\cos(2x) - 4\sin^2(x)\cos(x)
   \]

7. Factor out \( \cos(x) \):
   \[
   f'(x) = \cos(x)(\cos(2x) - 4\sin^2(x))
   \]

**Final Answer:**

\[
\boxed{f'(x) = \cos(x)(\cos(2x) - 4\sin^2(x))}
\]

</details>

---

### Ex 9: Combining Chain Rule, Quotient Rule, and Trigonometric Functions

#### Problem:
Differentiate \( f(x) = \frac{\sec(x)}{\sin(3x)} \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

We use the **quotient rule**:

\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \cdot u' - u \cdot v'}{v^2}
\]

Let \( u = \sec(x) \) and \( v = \sin(3x) \).

1. Differentiate \( u = \sec(x) \):
   \[
   u' = \sec(x)\tan(x)
   \]

2. Differentiate \( v = \sin(3x) \) using the **chain rule**:
   \[
   v' = \cos(3x) \cdot 3 = 3\cos(3x)
   \]

3. Apply the quotient rule:
   \[
   f'(x) = \frac{(\sin(3x))(\sec(x)\tan(x)) - (\sec(x))(3\cos(3x))}{(\sin(3x))^2}
   \]

4. Simplify:
   \[
   f'(x) = \frac{\sin(3x)\sec(x)\tan(x) - 3\sec(x)\cos(3x)}{\sin^2(3x)}
   \]

5. Factor out \( \sec(x) \) from the numerator:
   \[
   f'(x) = \frac{\sec(x)(\sin(3x)\tan(x) - 3\cos(3x))}{\sin^2(3x)}
   \]

**Final Answer:**

\[
\boxed{f'(x) = \frac{\sec(x)(\sin(3x)\tan(x) - 3\cos(3x))}{\sin^2(3x)}}
\]

</details>

---

See the below Quiz

<iframe src="https://script.google.com/macros/s/AKfycbyapCzd5KOsu4h9KEs5Tf7yDVgJnPsVThDkrCXNIYlet9KrGFeczeJygHUrou_E7OCv/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>