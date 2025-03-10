+++
title = '3.2 Examples'
weight = 2
+++

## 3.2 Introduction to the Natural Logarithm and the Number \( e \) Examples

#### Ex1: Simplify the following exponential expressions:

a) \( (e^{3x})(e^{5x}) \)  
**Solution**:  

Using the rule \( e^a \cdot e^b = e^{a+b} \):  

\[
(e^{3x})(e^{5x}) = e^{3x+5x} = e^{8x}
\]

b) \( \frac{e^{4x}}{e^{2x}} \)  

**Solution**:  

Using the rule \( \frac{e^a}{e^b} = e^{a-b} \):  

\[
\frac{e^{4x}}{e^{2x}} = e^{4x-2x} = e^{2x}
\]

c) \( (e^{2x})^3 \)  

**Solution**:  

Using the rule \( (e^a)^b = e^{ab} \):  

\[
(e^{2x})^3 = e^{2x \cdot 3} = e^{6x}
\]

---

#### Ex2: Simplify the following logarithmic expressions:

a) \( \ln(5x) + \ln(2x) \)  

**Solution**:  

Using the rule \( \ln(ab) = \ln(a) + \ln(b) \):  

\[
\ln(5x) + \ln(2x) = \ln(5x \cdot 2x) = \ln(10x^2)
\]

b) \( 3\log_2(x) + 2\log_2(y) \)  

**Solution**:  

Using the rule \( a\log_b(c) = \log_b(c^a) \):  

\[
3\log_2(x) + 2\log_2(y) = \log_2(x^3) + \log_2(y^2) = \log_2(x^3y^2)
\]

c) \( 3\log(x) + 2\log(y) \)  

**Solution**:  

Using the same rule as above:  

\[
3\log(x) + 2\log(y) = \log(x^3) + \log(y^2) = \log(x^3y^2)
\]

d) \( \ln(x^3) - \ln(x) \)  

**Solution**:  

Using the rule \( \ln(a) - \ln(b) = \ln\left(\frac{a}{b}\right) \):  

\[
\ln(x^3) - \ln(x) = \ln\left(\frac{x^3}{x}\right) = \ln(x^2)
\]

---

#### Ex3: Expand the following logarithmic expressions:

a) \( \ln\left(\sqrt{\frac{x}{y}}\right) \)  

**Solution**:  

Using the rule \( \ln\left(\sqrt{a}\right) = \frac{1}{2}\ln(a) \):  

\[
\ln\left(\sqrt{\frac{x}{y}}\right) = \frac{1}{2}\ln\left(\frac{x}{y}\right) = \frac{1}{2}[\ln(x) - \ln(y)]
\]

b) \( \ln\left((x^2 + 1)^3\right) \)  

**Solution**:  

Using the rule \( \ln(a^b) = b\ln(a) \):  

\[
\ln\left((x^2 + 1)^3\right) = 3\ln(x^2 + 1)
\]

c) \( \ln\left(\frac{x^3}{y^2z}\right) \)  

**Solution**:  

Using the rule \( \ln\left(\frac{a}{b}\right) = \ln(a) - \ln(b) \):  

\[
\ln\left(\frac{x^3}{y^2z}\right) = \ln(x^3) - \ln(y^2z) = \ln(x^3) - [\ln(y^2) + \ln(z)] = 3\ln(x) - 2\ln(y) - \ln(z)
\]

d) \( \ln(3xy^2) \)  

**Solution**:  

Using the rule \( \ln(ab) = \ln(a) + \ln(b) \):  

\[
\ln(3xy^2) = \ln(3) + \ln(x) + \ln(y^2) = \ln(3) + \ln(x) + 2\ln(y)
\]

---

#### Ex4: Condense the following logarithmic expressions into a single logarithm:

a) \( \ln(x) + \ln(y) - \ln(z) \)  

**Solution**:  

Using the rules \( \ln(a) + \ln(b) = \ln(ab) \) and \( \ln(a) - \ln(b) = \ln\left(\frac{a}{b}\right) \):  

\[
\ln(x) + \ln(y) - \ln(z) = \ln(xy) - \ln(z) = \ln\left(\frac{xy}{z}\right)
\]

b) \( 2\ln(x) + 3\ln(y) \)  

**Solution**:  

Using the rule \( a\ln(b) = \ln(b^a) \):  

\[
2\ln(x) + 3\ln(y) = \ln(x^2) + \ln(y^3) = \ln(x^2y^3)
\]

c) \( \ln(x^2) - \ln(y^3) + \ln(z) \)  

**Solution**:  

Using the same rules as above:  

\[
\ln(x^2) - \ln(y^3) + \ln(z) = \ln\left(\frac{x^2}{y^3}\right) + \ln(z) = \ln\left(\frac{x^2z}{y^3}\right)
\]

d) \( \frac{1}{2}\ln(x) - \ln(y) \)  

**Solution**:  

Using the rule \( a\ln(b) = \ln(b^a) \):  

\[
\frac{1}{2}\ln(x) - \ln(y) = \ln(x^{1/2}) - \ln(y) = \ln\left(\frac{\sqrt{x}}{y}\right)
\]

---

#### Ex5: Rewrite the following expressions in the specified form:

a) Rewrite \( e^{2x} = 7 \) in logarithmic form.  

**Solution**:  

\[
2x = \ln(7) \implies x = \frac{\ln(7)}{2}
\]

b) Rewrite \( \ln(x) = 3 \) in exponential form.  

**Solution**:  

\[
x = e^3
\]

c) Rewrite \( 5 = \log_b(25) \) in exponential form.  

**Solution**:  

\[
b^5 = 25 \implies b = \sqrt[5]{25}
\]

d) Rewrite \( b^3 = 8 \) in logarithmic form.  
**Solution**:  

\[
3 = \log_b(8)
\]

---

#### Ex6: Solve the following equations:
a) \( e^{2x} = 9 \)  

**Solution**:  

Take the natural logarithm of both sides:  

\[
2x = \ln(9) \implies x = \frac{\ln(9)}{2}
\]

b) \( \ln(x) = 4 \)  

**Solution**:  

Exponentiate both sides:  

\[
x = e^4
\]

c) \( \log_2(x) = 5 \)  

**Solution**:  

Rewrite in exponential form:  

\[
x = 2^5 = 32
\]

d) \( e^{x+1} = 10 \)  

**Solution**:  

Take the natural logarithm of both sides:  

\[
x+1 = \ln(10) \implies x = \ln(10) - 1
\]

---

#### Ex7: Combine skills to simplify and solve:

a) Simplify \( \ln(e^{3x}) \).  

**Solution**:  

Using the property \( \ln(e^a) = a \):  

\[
\ln(e^{3x}) = 3x
\]

b) Simplify \( e^{\ln(5x)} \).  

**Solution**:  

Using the property \( e^{\ln(a)} = a \):  

\[
e^{\ln(5x)} = 5x
\]

c) Solve \( \ln(x^2) = 4 \).  

**Solution**:  

Using the property \( \ln(a^b) = b\ln(a) \):  

\[
2\ln(x) = 4 \implies \ln(x) = 2 \implies x = e^2
\]

d) Solve \( e^{2x} - e^x - 6 = 0 \).  

**Solution**:  

Let \( u = e^x \), so the equation becomes:  

\[
u^2 - u - 6 = 0 \implies (u-3)(u+2) = 0
\]

Thus, \( u = 3 \) or \( u = -2 \). Since \( u = e^x > 0 \), we have \( u = 3 \):  

\[
e^x = 3 \implies x = \ln(3)
\]

---
