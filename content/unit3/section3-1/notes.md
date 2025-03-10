+++
title = '3.1 Examples'
weight = 1
+++

## 3.1 Trigonometric Derivatives: Examples

### Ex1.
Differentiate \( f(x) = \sin(x) \cdot \cos(2x) \)

**Solution**:
We define \( u(x) = \sin(x) \) and \( v(x) = \cos(2x) \).
1. Differentiate \( u(x) = \sin(x) \):  
   \( u'(x) = \cos(x) \)
2. Differentiate \( v(x) = \cos(2x) \) using the chain rule:  
   \( v'(x) = -\sin(2x) \cdot 2 = -2\sin(2x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = \cos(x) \cdot \cos(2x) + \sin(x) \cdot (-2\sin(2x))
\]
Simplifying:
\[
f'(x) = \cos(x)\cos(2x) - 2\sin(x)\sin(2x)
\]
Using the double-angle identity \( \sin(2x) = 2\sin(x)\cos(x) \):
\[
f'(x) = \cos(x)\cos(2x) - 2\sin(x)(2\sin(x)\cos(x))
\]
\[
f'(x) = \cos(x)\cos(2x) - 4\sin^2(x)\cos(x)
\]
Factoring out \( \cos(x) \):
\[
f'(x) = \cos(x) \left(\cos(2x) - 4\sin^2(x)\right)
\]

---

### Ex2.
Differentiate \( f(x) = \tan^3(x) \)

**Solution**:
We use the power rule and chain rule here. Let \( u(x) = \tan(x) \), so \( f(x) = [u(x)]^3 \).
1. Differentiate \( u(x) = \tan(x) \):  
   \( u'(x) = \sec^2(x) \)
2. Apply the power rule:
\[
f'(x) = 3[\tan(x)]^2 \cdot \sec^2(x)
\]
Thus, the derivative is:
\[
f'(x) = 3\tan^2(x)\sec^2(x)
\]

---

### Ex3.
Differentiate \( f(x) = \frac{\sin(x)}{1 + \cos(x)} \)

**Solution**:
We use the quotient rule here. Let \( u(x) = \sin(x) \) and \( v(x) = 1 + \cos(x) \).
1. Differentiate \( u(x) = \sin(x) \):  
   \( u'(x) = \cos(x) \)
2. Differentiate \( v(x) = 1 + \cos(x) \):  
   \( v'(x) = -\sin(x) \)
Now apply the quotient rule:
\[
f'(x) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
\]
\[
f'(x) = \frac{\cos(x)(1 + \cos(x)) - \sin(x)(-\sin(x))}{(1 + \cos(x))^2}
\]
Simplify the numerator:
\[
f'(x) = \frac{\cos(x) + \cos^2(x) + \sin^2(x)}{(1 + \cos(x))^2}
\]
Using the Pythagorean identity \( \cos^2(x) + \sin^2(x) = 1 \):
\[
f'(x) = \frac{\cos(x) + 1}{(1 + \cos(x))^2}
\]
Simplify further:
\[
f'(x) = \frac{1}{1 + \cos(x)}
\]

---

### Ex4.
Differentiate \( f(x) = \sec(x) \cdot \tan(3x) \)

**Solution**:
We use the product rule here. Let \( u(x) = \sec(x) \) and \( v(x) = \tan(3x) \).
1. Differentiate \( u(x) = \sec(x) \):  
   \( u'(x) = \sec(x)\tan(x) \)
2. Differentiate \( v(x) = \tan(3x) \) using the chain rule:  
   \( v'(x) = \sec^2(3x) \cdot 3 = 3\sec^2(3x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = \sec(x)\tan(x) \cdot \tan(3x) + \sec(x) \cdot 3\sec^2(3x)
\]
Simplify:
\[
f'(x) = \sec(x)\tan(x)\tan(3x) + 3\sec(x)\sec^2(3x)
\]

---

### Ex5.
Differentiate \( f(x) = \sin^2(x) \cdot \cos(x) \)

**Solution**:
We use the product rule here. Let \( u(x) = \sin^2(x) \) and \( v(x) = \cos(x) \).
1. Differentiate \( u(x) = \sin^2(x) \) using the chain rule:  
   \( u'(x) = 2\sin(x)\cos(x) \)
2. Differentiate \( v(x) = \cos(x) \):  
   \( v'(x) = -\sin(x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = (2\sin(x)\cos(x)) \cdot \cos(x) + (\sin^2(x)) \cdot (-\sin(x))
\]
Simplify:
\[
f'(x) = 2\sin(x)\cos^2(x) - \sin^3(x)
\]
Factor out \( \sin(x) \):
\[
f'(x) = \sin(x)(2\cos^2(x) - \sin^2(x))
\]
Using the Pythagorean identity \( \sin^2(x) = 1 - \cos^2(x) \):
\[
f'(x) = \sin(x)(2\cos^2(x) - (1 - \cos^2(x)))
\]
\[
f'(x) = \sin(x)(3\cos^2(x) - 1)
\]

#### Ex6.
Differentiate \( f(x) = \sin(x) \cdot \cos(3x) \)

**Solution**:
We define \( u(x) = \sin(x) \) and \( v(x) = \cos(3x) \).
1. Differentiate \( u(x) = \sin(x) \):  
   \( u'(x) = \cos(x) \)
2. Differentiate \( v(x) = \cos(3x) \) using the chain rule:  
   \( v'(x) = -\sin(3x) \cdot 3 = -3\sin(3x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = \cos(x) \cdot \cos(3x) + \sin(x) \cdot (-3\sin(3x))
\]
Simplifying:
\[
f'(x) = \cos(x)\cos(3x) - 3\sin(x)\sin(3x)
\]

---

#### Ex7.
Differentiate \( f(x) = \tan^2(x) \cdot \sec(x) \)

**Solution**:
We use the product rule here. Let \( u(x) = \tan^2(x) \) and \( v(x) = \sec(x) \).
1. Differentiate \( u(x) = \tan^2(x) \) using the chain rule:  
   \( u'(x) = 2\tan(x) \cdot \sec^2(x) \)
2. Differentiate \( v(x) = \sec(x) \):  
   \( v'(x) = \sec(x)\tan(x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = [2\tan(x)\sec^2(x)] \cdot \sec(x) + [\tan^2(x)] \cdot [\sec(x)\tan(x)]
\]
Simplifying:
\[
f'(x) = 2\tan(x)\sec^3(x) + \tan^3(x)\sec(x)
\]

---

#### Ex8.
Differentiate \( f(x) = \frac{\sin(2x)}{\cos(x)} \)

**Solution**:
We use the quotient rule here. Let \( u(x) = \sin(2x) \) and \( v(x) = \cos(x) \).
1. Differentiate \( u(x) = \sin(2x) \) using the chain rule:  
   \( u'(x) = \cos(2x) \cdot 2 = 2\cos(2x) \)
2. Differentiate \( v(x) = \cos(x) \):  
   \( v'(x) = -\sin(x) \)
Now apply the quotient rule:
\[
f'(x) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
\]
\[
f'(x) = \frac{(2\cos(2x))(\cos(x)) - (\sin(2x))(-\sin(x))}{\cos^2(x)}
\]
Simplifying:
\[
f'(x) = \frac{2\cos(2x)\cos(x) + \sin(2x)\sin(x)}{\cos^2(x)}
\]
Using the double-angle identity \( \sin(2x) = 2\sin(x)\cos(x) \):
\[
f'(x) = \frac{2\cos(2x)\cos(x) + 2\sin^2(x)\cos(x)}{\cos^2(x)}
\]
Factoring out \( \cos(x) \):
\[
f'(x) = \frac{\cos(x)[2\cos(2x) + 2\sin^2(x)]}{\cos^2(x)}
\]
\[
f'(x) = \frac{2\cos(2x) + 2\sin^2(x)}{\cos(x)}
\]

---

#### Ex9.
Differentiate \( f(x) = \csc(x) \cdot \cot(2x) \)

**Solution**:
We use the product rule here. Let \( u(x) = \csc(x) \) and \( v(x) = \cot(2x) \).
1. Differentiate \( u(x) = \csc(x) \):  
   \( u'(x) = -\csc(x)\cot(x) \)
2. Differentiate \( v(x) = \cot(2x) \) using the chain rule:  
   \( v'(x) = -\csc^2(2x) \cdot 2 = -2\csc^2(2x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = [-\csc(x)\cot(x)] \cdot \cot(2x) + [\csc(x)] \cdot [-2\csc^2(2x)]
\]
Simplifying:
\[
f'(x) = -\csc(x)\cot(x)\cot(2x) - 2\csc(x)\csc^2(2x)
\]

---

#### Ex10.
Differentiate \( f(x) = \cos^3(x) \cdot \sin(4x) \)

**Solution**:
We use the product rule here. Let \( u(x) = \cos^3(x) \) and \( v(x) = \sin(4x) \).
1. Differentiate \( u(x) = \cos^3(x) \) using the chain rule:  
   \( u'(x) = 3\cos^2(x) \cdot (-\sin(x)) = -3\cos^2(x)\sin(x) \)
2. Differentiate \( v(x) = \sin(4x) \) using the chain rule:  
   \( v'(x) = \cos(4x) \cdot 4 = 4\cos(4x) \)
Now apply the product rule:
\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]
\[
f'(x) = [-3\cos^2(x)\sin(x)] \cdot \sin(4x) + [\cos^3(x)] \cdot [4\cos(4x)]
\]
Simplifying:
\[
f'(x) = -3\cos^2(x)\sin(x)\sin(4x) + 4\cos^3(x)\cos(4x)
\]