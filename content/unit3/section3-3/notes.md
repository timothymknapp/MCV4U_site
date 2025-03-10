+++
title = '3.3 Examples'
weight = 2
+++

## 3.3 Exponential Derivatives: Examples

### Ex1.
Differentiate \( f(x) = e^{3x} \)

**Solution**:
The derivative of \( e^u \) with respect to \( x \) is \( e^u \cdot u' \), where \( u = 3x \).
1. Differentiate \( u(x) = 3x \):  
   \( u'(x) = 3 \)
Now apply the chain rule:
\[
f'(x) = e^{3x} \cdot 3
\]
Thus, the derivative is:
\[
f'(x) = 3e^{3x}
\] 

---

### Ex2.
Differentiate \( f(x) = x^2 \cdot e^{2x} \)

**Solution**:
We use the product rule here. Let \( u(x) = x^2 \) and \( v(x) = e^{2x} \).
1. Differentiate \( u(x) = x^2 \):  
   \( u'(x) = 2x \)
2. Differentiate \( v(x) = e^{2x} \) using the chain rule:  
   \( v'(x) = e^{2x} \cdot 2 = 2e^{2x} \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = (2x) \cdot e^{2x} + (x^2) \cdot (2e^{2x})
\]
Simplifying:
\[
f'(x) = 2xe^{2x} + 2x^2e^{2x}
\]
Factoring out \( 2e^{2x} \):
\[
f'(x) = 2e^{2x}(x + x^2)
\]

---

### Ex3.
Differentiate \( f(x) = \frac{e^x}{x} \)

**Solution**:
We use the quotient rule here. Let \( u(x) = e^x \) and \( v(x) = x \).
1. Differentiate \( u(x) = e^x \):  
   \( u'(x) = e^x \)
2. Differentiate \( v(x) = x \):  
   \( v'(x) = 1 \)
Now apply the quotient rule:
\[
f'(x) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
\]
\[
f'(x) = \frac{e^x \cdot x - e^x \cdot 1}{x^2}
\]
Simplifying:
\[
f'(x) = \frac{xe^x - e^x}{x^2}
\]
Factoring out \( e^x \):
\[
f'(x) = \frac{e^x(x - 1)}{x^2}
\]

---

### Ex4.
Differentiate \( f(x) = e^{x^2} \)

**Solution**:
The derivative of \( e^u \) with respect to \( x \) is \( e^u \cdot u' \), where \( u = x^2 \).
1. Differentiate \( u(x) = x^2 \):  
   \( u'(x) = 2x \)
Now apply the chain rule:
\[
f'(x) = e^{x^2} \cdot 2x
\]
Thus, the derivative is:
\[
f'(x) = 2xe^{x^2}
\]

---

### Ex5.
Differentiate \( f(x) = (e^x + 1)^3 \)

**Solution**:
We use the chain rule here. Let \( u(x) = e^x + 1 \), so \( f(x) = [u(x)]^3 \).
1. Differentiate \( u(x) = e^x + 1 \):  
   \( u'(x) = e^x \)
2. Apply the power rule and chain rule:
\[
f'(x) = 3[u(x)]^2 \cdot u'(x)
\]
\[
f'(x) = 3(e^x + 1)^2 \cdot e^x
\]
Thus, the derivative is:
\[
f'(x) = 3e^x(e^x + 1)^2
\]

---


### Ex 6  
**Differentiate \( f(x) = 5e^{-2x} \)**  

**Solution**:  
The derivative of \( e^u \) with respect to \( x \) is \( e^u \cdot u' \), where \( u = -2x \).  
1. Differentiate \( u(x) = -2x \):  
   \( u'(x) = -2 \)  
2. Apply the chain rule:  
   \[
   f'(x) = 5e^{-2x} \cdot (-2)
   \]  
3. Simplify:  
   \[
   f'(x) = -10e^{-2x}
   \]  

Thus, the derivative is:  
\[
f'(x) = -10e^{-2x}
\]

---

### Ex 7  
**Differentiate \( f(x) = e^{x^3 + 2x} \)**  

**Solution**:  
The derivative of \( e^u \) with respect to \( x \) is \( e^u \cdot u' \), where \( u = x^3 + 2x \).  
1. Differentiate \( u(x) = x^3 + 2x \):  
   \( u'(x) = 3x^2 + 2 \)  
2. Apply the chain rule:  
   \[
   f'(x) = e^{x^3 + 2x} \cdot (3x^2 + 2)
   \]  

Thus, the derivative is:  
\[
f'(x) = (3x^2 + 2)e^{x^3 + 2x}
\]

---

### Ex 8  
**Differentiate \( f(x) = 2^x \)**  

**Solution**:  
The derivative of \( a^x \) with respect to \( x \) is \( a^x \ln(a) \), where \( a = 2 \).  
1. Apply the formula:  
   \[
   f'(x) = 2^x \ln(2)
   \]  

Thus, the derivative is:  
\[
f'(x) = 2^x \ln(2)
\]

---

### Ex 9  
**Differentiate \( f(x) = 3^{2x} \)**  

**Solution**:  
The derivative of \( a^u \) with respect to \( x \) is \( a^u \ln(a) \cdot u' \), where \( a = 3 \) and \( u = 2x \).  
1. Differentiate \( u(x) = 2x \):  
   \( u'(x) = 2 \)  
2. Apply the chain rule:  
   \[
   f'(x) = 3^{2x} \ln(3) \cdot 2
   \]  
3. Simplify:  
   \[
   f'(x) = 2 \cdot 3^{2x} \ln(3)
   \]  

Thus, the derivative is:  
\[
f'(x) = 2 \cdot 3^{2x} \ln(3)
\]

---

These examples provide further practice in differentiating exponential functions, including cases with bases other than \( e \).