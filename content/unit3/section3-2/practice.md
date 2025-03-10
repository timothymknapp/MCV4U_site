+++
title = '3.2 Practice'
weight = 2
+++


## 3.2 Natural Logarithm and the Number \( e \)

### Ex1.

Simplify the following exponential expression:

\[
(e^{4x})(e^{7x})
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the rule \( e^a \cdot e^b = e^{a+b} \):

\[
(e^{4x})(e^{7x}) = e^{4x+7x} = e^{11x}
\]

</details>

---

### Ex2.

Simplify the following logarithmic expression:

\[
\ln(3x) + \ln(4x)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the rule \( \ln(ab) = \ln(a) + \ln(b) \):

\[
\ln(3x) + \ln(4x) = \ln(3x \cdot 4x) = \ln(12x^2)
\]

</details>

---

### Ex3.

Simplify the following logarithmic expression:

\[
5\log_3(x) - 2\log_3(y)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the rules \( a\log_b(c) = \log_b(c^a) \) and \( \log_b(a) - \log_b(b) = \log_b\left(\frac{a}{b}\right) \):

\[
5\log_3(x) - 2\log_3(y) = \log_3(x^5) - \log_3(y^2) = \log_3\left(\frac{x^5}{y^2}\right)
\]

</details>

---

### Ex4.

Solve the equation:

\[
e^{3x} = 16
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Take the natural logarithm of both sides:

\[
3x = \ln(16) \implies x = \frac{\ln(16)}{3}
\]

</details>

---

### Ex5.

Solve the equation:

\[
\ln(x) = 5
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Exponentiate both sides:

\[
x = e^5
\]

</details>

---


### Ex6.

Expand the logarithmic expression:

\[
\ln\left(\sqrt[3]{\frac{x^2}{y}}\right)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the rule \( \ln\left(\sqrt[n]{a}\right) = \frac{1}{n}\ln(a) \):

\[
\ln\left(\sqrt[3]{\frac{x^2}{y}}\right) = \frac{1}{3}\ln\left(\frac{x^2}{y}\right) = \frac{1}{3}[\ln(x^2) - \ln(y)] = \frac{1}{3}[2\ln(x) - \ln(y)]
\]

</details>

---

### Ex7.

Condense the logarithmic expression into a single logarithm:

\[
2\ln(x) - 3\ln(y) + \ln(z)
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the rules \( a\ln(b) = \ln(b^a) \), \( \ln(a) - \ln(b) = \ln\left(\frac{a}{b}\right) \), and \( \ln(a) + \ln(b) = \ln(ab) \):

\[
2\ln(x) - 3\ln(y) + \ln(z) = \ln(x^2) - \ln(y^3) + \ln(z) = \ln\left(\frac{x^2z}{y^3}\right)
\]

</details>

---

### Ex8.

Rewrite \( e^{5x} = 10 \) in logarithmic form.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

\[
5x = \ln(10) \implies x = \frac{\ln(10)}{5}
\]

</details>

---


### Ex9.

Solve the equation:

\[
e^{2x+1} = 8
\]

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Take the natural logarithm of both sides:

\[
2x+1 = \ln(8) \implies 2x = \ln(8) - 1 \implies x = \frac{\ln(8) - 1}{2}
\]

</details>

---

### Ex10.

Simplify \( \ln(e^{4x}) \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Using the property \( \ln(e^a) = a \):

\[
\ln(e^{4x}) = 4x
\]

</details>

---


### Ex11.

Solve \( e^{3x} - 2e^{x} - 8 = 0 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

Let \( u = e^x \), so the equation becomes:

\[
u^3 - 2u - 8 = 0
\]

Factoring the cubic polynomial:

\[
(u-2)(u^2 + 2u + 4) = 0
\]

The quadratic factor \( u^2 + 2u + 4 \) has no real roots (discriminant \( 2^2 - 4(1)(4) = -12 < 0 \)). Thus, \( u = 2 \):

\[
e^x = 2 \implies x = \ln(2)
\]

</details>

---

See the below Quiz

<iframe src="https://script.google.com/macros/s/AKfycbzzT8pCGyeVnHZrMyGvHUKAnqYe_RBsD8lZKDN0WN8jLGktXz_HS3DF2EQJvRcl_dUX/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>