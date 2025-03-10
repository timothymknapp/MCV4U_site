+++
title = "2.6 Examples"
weight = 2
+++

## Mixing Derivative Rules:
In this section, we will work through examples that require combining multiple derivative rules, such as the Power Rule, Product Rule, Quotient Rule, and Chain Rule. These examples will help you develop a deeper understanding of how to approach complex differentiation problems.

---

### Example 1: Product of Two Functions with a Composite Function
Differentiate the following function:
\[
y = x^3(2x^2 + 3)^4
\]

**Solution:**
1. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = x^3 \) and \( v(x) = (2x^2 + 3)^4 \).
2. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
3. Differentiate \( u(x) = x^3 \):
   \[
   u'(x) = 3x^2
   \]
4. Differentiate \( v(x) = (2x^2 + 3)^4 \) using the **Chain Rule**:
   - Outer function: \( w^4 \), where \( w = 2x^2 + 3 \).
   - Inner function: \( w(x) = 2x^2 + 3 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dw} = 4w^3
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 4x
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 4(2x^2 + 3)^3 \cdot 4x = 16x(2x^2 + 3)^3
     \]
5. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = (3x^2)(2x^2 + 3)^4 + (x^3)(16x)(2x^2 + 3)^3
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = 3x^2(2x^2 + 3)^4 + 16x^4(2x^2 + 3)^3
   \]

---

### Example 2: Quotient of Two Functions with a Composite Function
Differentiate the following function:
\[
y = \frac{(x^2 + 1)^3}{x^4}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a quotient of two functions, where the numerator is a composite function \( u(w(x)) = (x^2 + 1)^3 \) andthe denominator is a power function: \( v(x) = x^4 \).

2. Apply the **Quotient Rule**:
   
   \[
   y = \frac{(x^2 + 1)^3}{x^4} = \left(\frac{u(w(x))}{v(x)}\right)
    \]

   \[
   \frac{d}{dx}\left(\frac{u(w(x))}{v(x)}\right) = \frac{u'(w(x))w'(x)v(x) - u(w(x))v'(x)}{[v(x)]^2}
    \]

3. To differentiate \( u(w(x)) = (x^2 + 1)^3 \) we note that \(u(w(x))\) is a composition of an outer cubic function and a inner qadratic, we will use the **Chain Rule**:
   - \( u(w(x) =  (x^2 + 1)^3 \) 
   - \( \frac{d}{dx} u(w(x) = u'(w(x))w'(x) = 3(x^2+1)^2 \cdot 2x \)

4. Substitute these results into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{\big(3(x^2 + 1)^2\big)2x(x^4) - (x^2 + 1)^3(4x^3)}{(x^4)^2}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = \frac{6x^5(x^2 + 1)^2 - 4x^3(x^2 + 1)^3}{x^8}
   \]
   Factor out common terms:
   \[
   \frac{dy}{dx} = \frac{2x^3(x^2 + 1)^2\big(3x^2 - 2(x^2 + 1)\big)}{x^8}
   \]
   Simplify further:
   \[
   \frac{dy}{dx} = \frac{2x^3(x^2 + 1)^2(x^2 - 2)}{x^8}
   \]

---

### Example 3: Nested Powers and Products
Differentiate the following function:
\[
y = (x^2 + 3x)(x^3 - 2)^2
\]

**Solution:**
1. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = x^2 + 3x \) and \( v(x) = (x^3 - 2)^2 \).
2. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
3. Differentiate \( u(x) = x^2 + 3x \):
   \[
   u'(x) = 2x + 3
   \]
4. Differentiate \( v(x) = (x^3 - 2)^2 \) using the **Chain Rule**:
   - Outer function: \( w^2 \), where \( w = x^3 - 2 \).
   - Inner function: \( w(x) = x^3 - 2 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dw} = 2w
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 3x^2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 2(x^3 - 2) \cdot 3x^2 = 6x^2(x^3 - 2)
     \]
5. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = (2x + 3)(x^3 - 2)^2 + (x^2 + 3x)(6x^2)(x^3 - 2)
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = (2x + 3)(x^3 - 2)^2 + 6x^2(x^2 + 3x)(x^3 - 2)
   \]

---

### Example 4: Rational Function with a Composite Denominator
Differentiate the following function:
\[
y = \frac{x^2}{(x^3 + 1)^2}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a quotient of two functions: \( u(x) = x^2 \) and \( v(x) = (x^3 + 1)^2 \).
2. Apply the **Quotient Rule**:
   \[
   \frac{d}{dx}\left(\frac{u(x)}{v(x)}\right) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
3. Differentiate \( u(x) = x^2 \):
   \[
   u'(x) = 2x
   \]
4. Differentiate \( v(x) = (x^3 + 1)^2 \) using the **Chain Rule**:
   - Outer function: \( w^2 \), where \( w = x^3 + 1 \).
   - Inner function: \( w(x) = x^3 + 1 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dw} = 2w
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 3x^2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 2(x^3 + 1) \cdot 3x^2 = 6x^2(x^3 + 1)
     \]
5. Substitute into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{(2x)(x^3 + 1)^2 - (x^2)(6x^2)(x^3 + 1)}{[(x^3 + 1)^2]^2}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = \frac{2x(x^3 + 1)^2 - 6x^4(x^3 + 1)}{(x^3 + 1)^4}
   \]
   Factor out common terms:
   \[
   \frac{dy}{dx} = \frac{2x(x^3 + 1)\big((x^3 + 1) - 3x^3\big)}{(x^3 + 1)^4}
   \]
   Simplify further:
   \[
   \frac{dy}{dx} = \frac{2x(1 - 2x^3)}{(x^3 + 1)^3}
   \]

---


### Example 4: Product and Chain Rule
Differentiate the following function:


\[ y = (3x^2 + 2x)(5x^3 + 1)^4 \]



**Solution:**
1. Identify the outer and inner functions for the Chain Rule:
   - Outer function: \( u(v) = v^4 \), where \( v = 5x^3 + 1 \).
   - Inner function: \( v(x) = 5x^3 + 1 \).

2. Differentiate the outer function with respect to \( v \):
   

\[
   \frac{du}{dv} = 4v^3
   \]



3. Differentiate the inner function with respect to \( x \):
   

\[
   \frac{dv}{dx} = 15x^3
   \]



4. Apply the Product Rule: \( \frac{d}{dx} (uv) = u'v + uv' \)
   

\[
   u = 3x^2 + 2x, \quad v = (5x^3 + 1)^4
   \]


   

\[
   u' = 6x + 2, \quad v' = 4(5x^3 + 1)^3 \cdot 15x^2
   \]



5. Combine the results:
   

\[
   \frac{dy}{dx} = (6x + 2)(5x^3 + 1)^4 + (3x^2 + 2x) \cdot 4(5x^3 + 1)^3 \cdot 15x^2
   \]



---

### Example 5: Quotient and Chain Rule
Differentiate the following function:


\[ y = \frac{(2x^2 - 3)^5}{4x^3 + x} \]



**Solution:**
1. Identify the outer and inner functions for the Chain Rule:
   - Outer function: \( a(b) = b^5 \), where \( b = 2x^2 - 3 \).
   - Inner function: \( b(x) = 2x^2 - 3 \).

2. Differentiate the outer function with respect to \( b \):
   

\[
   \frac{da}{db} = 5b^4
   \]



3. Differentiate the inner function with respect to \( x \):
   

\[
   \frac{db}{dx} = 4x
   \]

\[
   \frac{da}{dx} = a' = 5(2x^2 - 3)^4 \cdot 4x
   \]


4. Apply the Quotient Rule: \( \frac{d}{dx} \left( \frac{a}{c} \right) = \frac{a'c - ac'}{c^2} \)
   

\[
   a = (2x^2 - 3)^5, \quad c = 4x^3 + x
   \]


   

\[
   a' = 5(2x^2 - 3)^4 \cdot 4x, \quad c' = 12x^2 + 1
   \]



5. Combine the results:
   

\[
   \frac{dy}{dx} = \frac{5(2x^2 - 3)^4 \cdot 4x \cdot (4x^3 + x) - (2x^2 - 3)^5 \cdot (12x^2 + 1)}{(4x^3 + x)^2}
   \]



---

### Example 7: Power and Chain Rule
Differentiate the following function:


\[ y = (6x^3 - x^2 + 4)^7 \]



**Solution:**
1. Identify the outer and inner functions for the Chain Rule:
   - Outer function: \( u(v) = v^7 \), where \( v = 6x^3 - x^2 + 4 \).
   - Inner function: \( v(x) = 6x^3 - x^2 + 4 \).

2. Differentiate the outer function with respect to \( v \):
   

\[
   \frac{du}{dv} = 7v^6
   \]



3. Differentiate the inner function with respect to \( x \):
   

\[
   \frac{dv}{dx} = 18x^2 - 2x
   \]



4. Combine the results:
   

\[
   \frac{dy}{dx} = 7(6x^3 - x^2 + 4)^6 \cdot (18x^2 - 2x)
   \]



---

### Example 8: Product and Quotient Rule
Differentiate the following function:


\[ y = (x^2 + 1) \cdot \frac{3x - 5}{2x^2 + 1} \]



**Solution:**
1.  Identify the general format of the function and plan out our approach.

\[ \text{Let: } u = x^2 + 1, \quad a = 3x - 5, \quad b = 2x^2 + 1 \]

\[ \text{Therefore: } y = u \cdot \frac{a}{b} \]

2. Apply the Product Rule to \( y \): 

\[ 
    \frac{d}{dx} ( u \cdot \frac{a}{b} ) = \frac{d}{dx} u \cdot \frac{a}{b} + u \cdot \frac{d}{dx} \left( \frac{a}{b} \right)
\] 

3.  Now apply the quotient rule to \( \frac{a}{b} \) :

\[
   \frac{d}{dx} \left( \frac{a}{b} \right) = \frac{a'b - ab'}{b^2}  
\]

4.  Put these two rules together: noting that \( \frac{d}{dx} u = u'\) 

\[ 
    \frac{d}{dx} y =u' \cdot \frac{a}{b} + u \cdot \frac{a'b - ab'}{b^2}
\] 
 
5.  Now let's differentiante \( u \), \( a \) and \( b \).



\[
   u = x^2 + 1, \quad a = 3x - 5, \quad b = 2x^2 + 1
\]

   
\[u' = 2x, \quad, a' = 3, \quad b'= 4x \]



4. Combine the results:
   

\[
   \frac{d}{dx} \left( \frac{a}{b} \right) = \frac{a'b - ab'}{b^2}   = (2x) \cdot \frac{3x - 5}{2x^2 + 1} + (x^2 + 1) \cdot \frac{-6x^2 + 20x + 3}{(2x^2 + 1)^2}
   \]



---

### Example 9: Nested Powers with a Product
Differentiate the following function:
\[
y = (x^3 + 2x)(x^2 - 1)^4
\]

**Solution:**
1. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = x^3 + 2x \) and \( v(x) = (x^2 - 1)^4 \).
2. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
3. Differentiate \( u(x) = x^3 + 2x \):
   \[
   u'(x) = 3x^2 + 2
   \]
4. Differentiate \( v(x) = (x^2 - 1)^4 \) using the **Chain Rule**:
   - Outer function: \( w^4 \), where \( w = x^2 - 1 \).
   - Inner function: \( w(x) = x^2 - 1 \).
   - Differentiate the outer function:
     \[
     \frac{dv}{dw} = 4w^3
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 2x
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 4(x^2 - 1)^3 \cdot 2x = 8x(x^2 - 1)^3
     \]
5. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = (3x^2 + 2)(x^2 - 1)^4 + (x^3 + 2x)(8x)(x^2 - 1)^3
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = (3x^2 + 2)(x^2 - 1)^4 + 8x(x^3 + 2x)(x^2 - 1)^3
   \]

---

### Example 10: Rational Function with a Composite Numerator
Differentiate the following function:
\[
y = \frac{(x^2 + 3)^3}{x^5}
\]

**Solution:**
1. Identify the structure of the function:
   - This is a quotient of two functions: \( u(x) = (x^2 + 3)^3 \) and \( v(x) = x^5 \).
2. Apply the **Quotient Rule**:
   \[
   \frac{d}{dx}\left(\frac{u(x)}{v(x)}\right) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]
3. Differentiate \( u(x) = (x^2 + 3)^3 \) using the **Chain Rule**:
   - Outer function: \( w^3 \), where \( w = x^2 + 3 \).
   - Inner function: \( w(x) = x^2 + 3 \).
   - Differentiate the outer function:
     \[
     \frac{du}{dw} = 3w^2
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 2x
     \]
   - Multiply the derivatives:
     \[
     u'(x) = 3(x^2 + 3)^2 \cdot 2x = 6x(x^2 + 3)^2
     \]
4. Differentiate \( v(x) = x^5 \):
   \[
   v'(x) = 5x^4
   \]
5. Substitute into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{\big(6x(x^2 + 3)^2\big)(x^5) - (x^2 + 3)^3(5x^4)}{(x^5)^2}
   \]
6. Simplify:
   \[
   \frac{dy}{dx} = \frac{6x^6(x^2 + 3)^2 - 5x^4(x^2 + 3)^3}{x^{10}}
   \]
   Factor out common terms:
   \[
   \frac{dy}{dx} = \frac{x^4(x^2 + 3)^2\big(6x^2 - 5(x^2 + 3)\big)}{x^{10}}
   \]
   Simplify further:
   \[
   \frac{dy}{dx} = \frac{(x^2 + 3)^2(x^2 - 15)}{x^6}
   \]

---

### Example 11: Square Root with a Product
Differentiate the following function:
\[
y = \sqrt{x^3 + 2x}(x^2 + 1)
\]

**Solution:**
1. Rewrite the square root as a power:
   \[
   y = (x^3 + 2x)^{\frac{1}{2}}(x^2 + 1)
   \]
2. Identify the structure of the function:
   - This is a product of two functions: \( u(x) = (x^3 + 2x)^{\frac{1}{2}} \) and \( v(x) = x^2 + 1 \).
3. Apply the **Product Rule**:
   \[
   \frac{d}{dx}[u(x)v(x)] = u'(x)v(x) + u(x)v'(x)
   \]
4. Differentiate \( u(x) = (x^3 + 2x)^{\frac{1}{2}} \) using the **Chain Rule**:
   - Outer function: \( w^{\frac{1}{2}} \), where \( w = x^3 + 2x \).
   - Inner function: \( w(x) = x^3 + 2x \).
   - Differentiate the outer function:
     \[
     \frac{du}{dw} = \frac{1}{2}w^{-\frac{1}{2}}
     \]
   - Differentiate the inner function:
     \[
     \frac{dw}{dx} = 3x^2 + 2
     \]
   - Multiply the derivatives:
     \[
     u'(x) = \frac{1}{2}(x^3 + 2x)^{-\frac{1}{2}} \cdot (3x^2 + 2) = \frac{3x^2 + 2}{2\sqrt{x^3 + 2x}}
     \]
5. Differentiate \( v(x) = x^2 + 1 \):
   \[
   v'(x) = 2x
   \]
6. Substitute into the Product Rule:
   \[
   \frac{dy}{dx} = \frac{3x^2 + 2}{2\sqrt{x^3 + 2x}}(x^2 + 1) + \sqrt{x^3 + 2x}(2x)
   \]
7. Simplify:
   \[
   \frac{dy}{dx} = \frac{(3x^2 + 2)(x^2 + 1)}{2\sqrt{x^3 + 2x}} + 2x\sqrt{x^3 + 2x}
   \]

---

### Example 12: Nested Roots with a Quotient

Differentiate the following function:
\[
y = \frac{\sqrt{x^2 + 1}}{(x^3 - 2)^2}
\]

**Solution:**

1. Rewrite the square root as a power:
   \[
   y = \frac{(x^2 + 1)^{\frac{1}{2}}}{(x^3 - 2)^2}
   \]

2. Identify the structure of the function:
   - This is a quotient of two functions: \( u(x) = (x^2 + 1)^{\frac{1}{2}} \) and \( v(x) = (x^3 - 2)^2 \).

3. Apply the **Quotient Rule**:
   \[
   \frac{d}{dx}\left(\frac{u(x)}{v(x)}\right) = \frac{u'(x)v(x) - u(x)v'(x)}{[v(x)]^2}
   \]

4. Differentiate \( u(x) = (x^2 + 1)^{\frac{1}{2}} \) using the **Chain Rule**:
   - Outer function: \( f(g) = g^{\frac{1}{2}} \), where \( g = x^2 + 1 \).
   - Inner function: \( g(x) = x^2 + 1 \).
   - Differentiate the outer function:
     \[
     \frac{df}{dg} = \frac{1}{2}g^{-\frac{1}{2}}
     \]
   - Differentiate the inner function:
     \[
     \frac{dg}{dx} = 2x
     \]
   - Multiply the derivatives:
     \[
     u'(x) = \frac{1}{2}(x^2 + 1)^{-\frac{1}{2}} \cdot 2x = \frac{x}{\sqrt{x^2 + 1}}
     \]

5. Differentiate \( v(x) = (x^3 - 2)^2 \) using the **Chain Rule**:
   - Outer function: \( h(k) = k^2 \), where \( k = x^3 - 2 \).
   - Inner function: \( k(x) = x^3 - 2 \).
   - Differentiate the outer function:
     \[
     \frac{dh}{dk} = 2k
     \]
   - Differentiate the inner function:
     \[
     \frac{dk}{dx} = 3x^2
     \]
   - Multiply the derivatives:
     \[
     v'(x) = 2(x^3 - 2) \cdot 3x^2 = 6x^2(x^3 - 2)
     \]

6. Substitute into the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{\left(\frac{x}{\sqrt{x^2 + 1}}\right)(x^3 - 2)^2 - (x^2 + 1)^{\frac{1}{2}}(6x^2)(x^3 - 2)}{[(x^3 - 2)^2]^2}
   \]

7. Simplify:
   \[
   \frac{dy}{dx} = \frac{x(x^3 - 2)^2 - 6x^2(x^2 + 1)^{\frac{1}{2}}(x^3 - 2)}{(x^3 - 2)^4\sqrt{x^2 + 1}}
   \]
   Factor out common terms:
   \[
   \frac{dy}{dx} = \frac{x(x^3 - 2)\big((x^3 - 2) - 6x(x^2 + 1)^{\frac{1}{2}}\big)}{(x^3 - 2)^4\sqrt{x^2 + 1}}
   \]

The final derivative is:

\[
\boxed{\frac{dy}{dx} = \frac{x(x^3 - 2)\big((x^3 - 2) - 6x\sqrt{x^2 + 1}\big)}{(x^3 - 2)^4\sqrt{x^2 + 1}}}
\]

---
### Example 13: Chain and Product Rule

Differentiate the following function:

\[ y = (4x^3 - 2x^2) \cdot (x^4 + x)^3 \]

**Solution:**

1. Identify the outer and inner functions for the **Chain Rule**:
   - Outer function: $$ f(g) = g^3 $$, where $$ g = x^4 + x $$.
   - Inner function: $$ g(x) = x^4 + x $$.

2. Differentiate the outer function with respect to $ g $:
   \[
   \frac{df}{dg} = 3g^2
   \]

3. Differentiate the inner function with respect to $ x $:
   \[
   \frac{dg}{dx} = 4x^3 + 1
   \]

4. Combine the results using the **Chain Rule**:
   \[
   \frac{d}{dx} \big( (x^4 + x)^3 \big) = 3(x^4 + x)^2 \cdot (4x^3 + 1)
   \]

5. Apply the **Product Rule**: $ \frac{d}{dx} (pq) = p'q + pq' $

   Let:
   \[
   p = 4x^3 - 2x^2, \quad q = (x^4 + x)^3
   \]
   
   Then:
   \[
   p' = 12x^2 - 4x, \quad q' = 3(x^4 + x)^2 \cdot (4x^3 + 1)
   \]

6. Combine the results using the Product Rule:
   \[
   \frac{dy}{dx} = p'q + pq'
   \]
   Substitute \( p = 4x^3 - 2x^2 \), \( p' = 12x^2 - 4x \), \( q = (x^4 + x)^3 \), and \( q' = 3(x^4 + x)^2 \cdot (4x^3 + 1) \):
   \[
   \frac{dy}{dx} = (12x^2 - 4x) \cdot (x^4 + x)^3 + (4x^3 - 2x^2) \cdot 3(x^4 + x)^2 \cdot (4x^3 + 1)
   \]

The final derivative is:

\[
\boxed{\frac{dy}{dx} = (12x^2 - 4x) \cdot (x^4 + x)^3 + (4x^3 - 2x^2) \cdot 3(x^4 + x)^2 \cdot (4x^3 + 1)}
\]

---

### Example 14: Quotient and Chain Rule

Differentiate the following function:

\[ y = \frac{(5x^2 - 3x)^4}{3x^2 + 2} \]

**Solution:**

1. Identify the outer and inner functions for the **Chain Rule**:
   - Outer function: \( f(g) = g^4 \) , where \( g = 5x^2 - 3x \).
   - Inner function: \( g(x) = 5x^2 - 3x \).

2. Differentiate the outer function with respect to $ g $:
   \[
   \frac{df}{dg} = 4g^3
   \]

3. Differentiate the inner function with respect to $ x $:
   \[
   \frac{dg}{dx} = 10x - 3
   \]

4. Combine the results using the **Chain Rule**:
   \[
   \frac{d}{dx} \big( (5x^2 - 3x)^4 \big) = 4(5x^2 - 3x)^3 \cdot (10x - 3)
   \]

5. Apply the **Quotient Rule**: \( \frac{d}{dx} \left( \frac{p}{q} \right) = \frac{p'q - pq'}{q^2} \)

   Let:
   \[
   p = (5x^2 - 3x)^4, \quad q = 3x^2 + 2
   \]
   
   Then:
   \[
   p' = 4(5x^2 - 3x)^3 \cdot (10x - 3), \quad q' = 6x
   \]

6. Combine the results using the Quotient Rule:
   \[
   \frac{dy}{dx} = \frac{p'q - pq'}{q^2}
   \]
   Substitute $ p = (5x^2 - 3x)^4 $, $ p' = 4(5x^2 - 3x)^3 \cdot (10x - 3) $, $ q = 3x^2 + 2 $, and $ q' = 6x $:
   \[
   \frac{dy}{dx} = \frac{\big( 4(5x^2 - 3x)^3 \cdot (10x - 3) \big) \cdot (3x^2 + 2) - (5x^2 - 3x)^4 \cdot 6x}{(3x^2 + 2)^2}
   \]

The final derivative is:

\[
\boxed{\frac{dy}{dx} = \frac{\big( 4(5x^2 - 3x)^3 \cdot (10x - 3) \big) \cdot (3x^2 + 2) - (5x^2 - 3x)^4 \cdot 6x}{(3x^2 + 2)^2}}
\]


---

### Example 15: Power and Chain Rule
Differentiate the following function:


\[ y = (7x^3 - x + 2)^5 \]



**Solution:**
1. Identify the outer and inner functions for the Chain Rule:
   - Outer function: \( u(v) = v^5 \), where \( v = 7x^3 - x + 2 \).
   - Inner function: \( v(x) = 7x^3 - x + 2 \).

2. Differentiate the outer function with respect to \( v \):
   

\[
   \frac{du}{dv} = 5v^4
   \]



3. Differentiate the inner function with respect to \( x \):
   

\[
   \frac{dv}{dx} = 21x^2 - 1
   \]



4. Combine the results:
   

\[
   \frac{dy}{dx} = 5(7x^3 - x + 2)^4 \cdot (21x^2 - 1)
   \]



---

### Example 16: Product and Quotient Rule

Differentiate the following function:

\[ y = (x^2 + 3x) \cdot \frac{2x - 1}{x^2 + 4} \]

**Solution:**

1. Apply the **Product Rule**: $ \frac{d}{dx} (fg) = f'g + fg' $

   Let:
   \[
   f = x^2 + 3x, \quad g = \frac{2x - 1}{x^2 + 4}
   \]
   
   Then:
   \[
   f' = 2x + 3
   \]

2. Differentiate $ g $ using the **Quotient Rule**: $ \frac{d}{dx} \left( \frac{p}{q} \right) = \frac{p'q - pq'}{q^2} $

   Let:
   \[
   p = 2x - 1, \quad q = x^2 + 4
   \]
   
   Then:
   \[
   p' = 2, \quad q' = 2x
   \]

   Now compute $ g' $:
   \[
   g' = \frac{(2)(x^2 + 4) - (2x - 1)(2x)}{(x^2 + 4)^2}
   \]
   Simplify the numerator:
   \[
   (2)(x^2 + 4) - (2x - 1)(2x) = 2x^2 + 8 - (4x^2 - 2x) = 2x^2 + 8 - 4x^2 + 2x = -2x^2 + 2x + 8
   \]
   So:
   \[
   g' = \frac{-2x^2 + 2x + 8}{(x^2 + 4)^2}
   \]

3. Combine the results using the Product Rule:
   \[
   \frac{dy}{dx} = f'g + fg'
   \]
   Substitute $ f = x^2 + 3x $, $ f' = 2x + 3 $, $ g = \frac{2x - 1}{x^2 + 4} $, and $ g' = \frac{-2x^2 + 2x + 8}{(x^2 + 4)^2} $:
   \[
   \frac{dy}{dx} = (2x + 3) \cdot \frac{2x - 1}{x^2 + 4} + (x^2 + 3x) \cdot \frac{-2x^2 + 2x + 8}{(x^2 + 4)^2}
   \]

The final derivative is:

\[
\boxed{\frac{dy}{dx} = (2x + 3) \cdot \frac{2x - 1}{x^2 + 4} + (x^2 + 3x) \cdot \frac{-2x^2 + 2x + 8}{(x^2 + 4)^2}}
\]


---

