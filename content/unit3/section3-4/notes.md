+++
title = '3.4 Examples'
weight = 1
+++

### 3.4 Logarithmic Derivatives: Examples

#### Ex1.
Differentiate \( f(x) = \ln(5x) \)

**Solution**:  
The derivative of \( \ln(u) \) with respect to \( x \) is \( \frac{1}{u} \cdot u' \), where \( u = 5x \).  
1. Differentiate \( u(x) = 5x \):  
   \( u'(x) = 5 \)  
2. Apply the chain rule:  
   \[
   f'(x) = \frac{1}{5x} \cdot 5
   \]  
3. Simplify:  
   \[
   f'(x) = \frac{5}{5x} = \frac{1}{x}
   \]  

Thus, the derivative is:  
\[
f'(x) = \frac{1}{x}
\]

---

#### Ex2.
Differentiate \( f(x) = \ln(x^2 + 1) \)

**Solution**:  
The derivative of \( \ln(u) \) with respect to \( x \) is \( \frac{1}{u} \cdot u' \), where \( u = x^2 + 1 \).  
1. Differentiate \( u(x) = x^2 + 1 \):  
   \( u'(x) = 2x \)  
2. Apply the chain rule:  
   \[
   f'(x) = \frac{1}{x^2 + 1} \cdot 2x
   \]  
3. Simplify:  
   \[
   f'(x) = \frac{2x}{x^2 + 1}
   \]  

Thus, the derivative is:  
\[
f'(x) = \frac{2x}{x^2 + 1}
\]

---

#### Ex3.
Differentiate \( f(x) = x \ln(x) \)

**Solution**:  
We use the product rule here. Let \( u(x) = x \) and \( v(x) = \ln(x) \).  
1. Differentiate \( u(x) = x \):  
   \( u'(x) = 1 \)  
2. Differentiate \( v(x) = \ln(x) \):  
   \( v'(x) = \frac{1}{x} \)  
3. Apply the product rule:  
   \[
   f'(x) = u'(x)v(x) + u(x)v'(x)
   \]  
   \[
   f'(x) = (1)(\ln(x)) + (x)\left(\frac{1}{x}\right)
   \]  
4. Simplify:  
   \[
   f'(x) = \ln(x) + 1
   \]  

Thus, the derivative is:  
\[
f'(x) = \ln(x) + 1
\]

---

#### Ex4.
Differentiate \( f(x) = \ln(\sin(x)) \)

**Solution**:  
The derivative of \( \ln(u) \) with respect to \( x \) is \( \frac{1}{u} \cdot u' \), where \( u = \sin(x) \).  
1. Differentiate \( u(x) = \sin(x) \):  
   \( u'(x) = \cos(x) \)  
2. Apply the chain rule:  
   \[
   f'(x) = \frac{1}{\sin(x)} \cdot \cos(x)
   \]  
3. Simplify using the identity \( \frac{\cos(x)}{\sin(x)} = \cot(x) \):  
   \[
   f'(x) = \cot(x)
   \]  

Thus, the derivative is:  
\[
f'(x) = \cot(x)
\]

---

#### Ex5.
Differentiate \( f(x) = \ln\left(\frac{x}{x+1}\right) \)

**Solution**:  
We can simplify the logarithm using the property \( \ln\left(\frac{a}{b}\right) = \ln(a) - \ln(b) \). Thus:  
\[
f(x) = \ln(x) - \ln(x+1)
\]  
Now differentiate each term separately.  
1. Differentiate \( \ln(x) \):  
   \( \frac{d}{dx}[\ln(x)] = \frac{1}{x} \)  
2. Differentiate \( \ln(x+1) \):  
   \( \frac{d}{dx}[\ln(x+1)] = \frac{1}{x+1} \)  
3. Combine the results:  
   \[
   f'(x) = \frac{1}{x} - \frac{1}{x+1}
   \]  
4. Simplify the expression by finding a common denominator:  
   \[
   f'(x) = \frac{(x+1) - x}{x(x+1)} = \frac{1}{x(x+1)}
   \]  

Thus, the derivative is:  
\[
f'(x) = \frac{1}{x(x+1)}
\]
---

These examples demonstrate the application of logarithmic differentiation rules and techniques, preparing students for more complex problems involving transcendental functions. Move on to the next section for further practice and applications.
