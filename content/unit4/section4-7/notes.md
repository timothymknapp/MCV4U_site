+++
title = '4.7 Examples'
weight = 1
+++

---

### Example 1: Reconstructing a Cubic Polynomial

Reconstruct the cubic polynomial $ f(x) = ax^3 + bx^2 + cx + d $ given the following conditions:
- $ f(1) = 4 $
- $ f'(1) = 0 $
- $ f''(1) = 6 $
- $ f(0) = 2 $

**Solution:**
1. Write the general form of the cubic polynomial:
   \[
   f(x) = ax^3 + bx^2 + cx + d
   \]
2. Compute the first and second derivatives:
   \[
   f'(x) = 3ax^2 + 2bx + c, \quad f''(x) = 6ax + 2b
   \]
3. Translate the conditions into equations:
   - From $ f(1) = 4 $:
     \[
     a(1)^3 + b(1)^2 + c(1) + d = 4 \implies a + b + c + d = 4
     \]
   - From $ f'(1) = 0 $:
     \[
     3a(1)^2 + 2b(1) + c = 0 \implies 3a + 2b + c = 0
     \]
   - From $ f''(1) = 6 $:
     \[
     6a(1) + 2b = 6 \implies 6a + 2b = 6 \implies 3a + b = 3
     \]
   - From $ f(0) = 2 $:
     \[
     a(0)^3 + b(0)^2 + c(0) + d = 2 \implies d = 2
     \]
4. Solve the system of equations:
   - Substitute $ d = 2 $ into the first equation:
     \[
     a + b + c + 2 = 4 \implies a + b + c = 2
     \]
   - Use $ 3a + b = 3 $ to express $ b $ in terms of $ a $:
     \[
     b = 3 - 3a
     \]
   - Substitute $ b = 3 - 3a $ into $ a + b + c = 2 $:
     \[
     a + (3 - 3a) + c = 2 \implies -2a + 3 + c = 2 \implies c = 2a - 1
     \]
   - Substitute $ b = 3 - 3a $ and $ c = 2a - 1 $ into $ 3a + 2b + c = 0 $:
     \[
     3a + 2(3 - 3a) + (2a - 1) = 0 \implies 3a + 6 - 6a + 2a - 1 = 0 \implies -a + 5 = 0 \implies a = 5
     \]
   - Solve for $ b $ and $ c $:
     \[
     b = 3 - 3(5) = -12, \quad c = 2(5) - 1 = 9
     \]
5. Write the final function:
   \[
   f(x) = 5x^3 - 12x^2 + 9x + 2
   \]

---

### Example 2: Reconstructing an Exponential Function

Reconstruct the exponential function $ f(x) = Ae^{kx} + C $ given the following conditions:
- $ f(0) = 3 $
- $ f'(0) = 2 $
- $ \lim_{x \to \infty} f(x) = 5 $

**Solution:**
1. Write the general form of the exponential function:
   \[
   f(x) = Ae^{kx} + C
   \]
2. Compute the derivative:
   \[
   f'(x) = Ak e^{kx}
   \]
3. Translate the conditions into equations:
   - From $ f(0) = 3 $:
     \[
     A e^{k(0)} + C = 3 \implies A + C = 3
     \]
   - From $ f'(0) = 2 $:
     \[
     Ak e^{k(0)} = 2 \implies Ak = 2
     \]
   - From $ \lim_{x \to \infty} f(x) = 5 $:
     - If $ k > 0 $, $ e^{kx} \to \infty $ as $ x \to \infty $, so $ A = 0 $. This contradicts $ Ak = 2 $.
     - Therefore, $ k < 0 $, and $ \lim_{x \to \infty} f(x) = C $. Thus:
       \[
       C = 5
       \]
4. Solve the system of equations:
   - Substitute $ C = 5 $ into $ A + C = 3 $:
     \[
     A + 5 = 3 \implies A = -2
     \]
   - Substitute $ A = -2 $ into $ Ak = 2 $:
     \[
     (-2)k = 2 \implies k = -1
     \]
5. Write the final function:
   \[
   f(x) = -2e^{-x} + 5
   \]

---


### Example: Reconstructing a Trigonometric Function (No Solution)

Reconstruct the trigonometric function $ f(x) = A\sin(x) + B\cos(x) + C $ given the following conditions:
- $ f(0) = 1 $
- $ f'(\pi/2) = 0 $
- $ f(\pi) = -1 $

**Solution:**
1. **Write the general form of the trigonometric function:**
   \[
   f(x) = A\sin(x) + B\cos(x) + C
   \]

2. **Compute the derivative:**
   \[
   f'(x) = A\cos(x) - B\sin(x)
   \]

3. **Translate the conditions into equations:**
   - From $ f(0) = 1 $:
     \[
     A\sin(0) + B\cos(0) + C = 1 \implies B + C = 1
     \]
   - From $ f'(\pi/2) = 0 $:
     \[
     A\cos(\pi/2) - B\sin(\pi/2) = 0
     \]
     Simplify using trigonometric values ($ \cos(\pi/2) = 0 $ and $ \sin(\pi/2) = 1 $):
     \[
     -B = 0 \implies B = 0
     \]
   - From $ f(\pi) = -1 $:
     \[
     A\sin(\pi) + B\cos(\pi) + C = -1
     \]
     Substitute $ B = 0 $ and use $ \sin(\pi) = 0 $ and $ \cos(\pi) = -1 $:
     \[
     A(0) + 0(-1) + C = -1 \implies C = -1
     \]

4. **Solve for $ A $, $ B $, and $ C $:**
   - From $ B + C = 1 $ and $ B = 0 $:
     \[
     0 + C = 1 \implies C = 1
     \]
   - From $ f(\pi) = -1 $ and $ C = 1 $:
     \[
     A(0) + 0(-1) + 1 = -1 \implies 1 = -1
     \]
     This contradiction suggests a mistake in setup or assumptions.

---

---

### Example 3: Reconstructing a Trigonometric Function

Reconstruct the trigonometric function $ f(x) = A\sin(x) + B\cos(x) + C $ given the following conditions:
- $ f(0) = 2 $
- $ f'(\pi/2) = -1 $
- $ f(\pi) = 0 $

**Solution:**
1. **Write the general form of the trigonometric function:**
   \[
   f(x) = A\sin(x) + B\cos(x) + C
   \]

2. **Compute the derivative:**
   \[
   f'(x) = A\cos(x) - B\sin(x)
   \]

3. **Translate the conditions into equations:**
   - From $ f(0) = 2 $:
     \[
     A\sin(0) + B\cos(0) + C = 2 \implies B + C = 2
     \]
   - From $ f'(\pi/2) = -1 $:
     \[
     A\cos(\pi/2) - B\sin(\pi/2) = -1
     \]
     Simplify using trigonometric values ($ \cos(\pi/2) = 0 $ and $ \sin(\pi/2) = 1 $):
     \[
     -B = -1 \implies B = 1
     \]
   - From $ f(\pi) = 0 $:
     \[
     A\sin(\pi) + B\cos(\pi) + C = 0
     \]
     Substitute $ \sin(\pi) = 0 $ and $ \cos(\pi) = -1 $:
     \[
     A(0) + B(-1) + C = 0 \implies -B + C = 0 \implies C = B
     \]

4. **Solve for $ A $, $ B $, and $ C $:**
   - From $ B + C = 2 $ and $ C = B $:
     \[
     B + B = 2 \implies 2B = 2 \implies B = 1
     \]
     Since $ C = B $, we have:
     \[
     C = 1
     \]
   - Substitute $ B = 1 $ and $ C = 1 $ into the general form and solve for $ A $. Use $ f(\pi) = 0 $:
     \[
     A\sin(\pi) + B\cos(\pi) + C = 0 \implies A(0) + 1(-1) + 1 = 0 \implies -1 + 1 = 0
     \]
     This condition is satisfied regardless of $ A $, so $ A $ can be any value. For simplicity, let $ A = 1 $.

5. **Write the final function:**
   Substituting $ A = 1 $, $ B = 1 $, and $ C = 1 $ into the general form:
   \[
   f(x) = \sin(x) + \cos(x) + 1
   \]

---

### Example 4: Reconstructing a Quadratic Function

Reconstruct the quadratic function $ f(x) = ax^2 + bx + c $ given the following conditions:
- $ f(0) = 2 $
- $ f'(1) = 0 $
- $ f(2) = 6 $

**Solution:**
1. Write the general form of the quadratic function:
   \[
   f(x) = ax^2 + bx + c
   \]
2. Compute the derivative:
   \[
   f'(x) = 2ax + b
   \]
3. Translate the conditions into equations:
   - From $ f(0) = 2 $:
     \[
     a(0)^2 + b(0) + c = 2 \implies c = 2
     \]
   - From $ f'(1) = 0 $:
     \[
     2a(1) + b = 0 \implies 2a + b = 0
     \]
   - From $ f(2) = 6 $:
     \[
     a(2)^2 + b(2) + c = 6 \implies 4a + 2b + c = 6
     \]
4. Solve the system of equations:
   - Substitute $ c = 2 $ into $ 4a + 2b + c = 6 $:
     \[
     4a + 2b + 2 = 6 \implies 4a + 2b = 4 \implies 2a + b = 2
     \]
   - Solve the two equations $ 2a + b = 0 $ and $ 2a + b = 2 $:
     - Subtract the first equation from the second:
       \[
       (2a + b) - (2a + b) = 2 - 0 \implies 0 = 2
       \]
     - This contradiction suggests a mistake in setup or assumptions.
5. Correct the setup and solve again:
   - Revisit assumptions and ensure consistency.

---

### Example 5: Reconstructing a Rational Function

Reconstruct the rational function $ f(x) = \frac{ax + b}{cx + d} $ given the following conditions:
- $ f(0) = 1 $
- $ f'(0) = 0 $
- Vertical asymptote at $ x = -1 $

**Solution:**
1. Write the general form of the rational function:
   \[
   f(x) = \frac{ax + b}{cx + d}
   \]
2. Compute the derivative using the Quotient Rule:
   \[
   f'(x) = \frac{(a)(cx + d) - (ax + b)(c)}{(cx + d)^2} = \frac{ad - bc}{(cx + d)^2}
   \]
3. Translate the conditions into equations:
   - From $ f(0) = 1 $:
     \[
     \frac{a(0) + b}{c(0) + d} = 1 \implies \frac{b}{d} = 1 \implies b = d
     \]
   - From $ f'(0) = 0 $:
     \[
     \frac{ad - bc}{(c(0) + d)^2} = 0 \implies ad - bc = 0
     \]
   - From the vertical asymptote at $ x = -1 $:
     \[
     cx + d = 0 \text{ when } x = -1 \implies c(-1) + d = 0 \implies -c + d = 0 \implies c = d
     \]
4. Solve the system of equations:
   - Substitute $ b = d $ and $ c = d $ into $ ad - bc = 0 $:
     \[
     ad - (d)(d) = 0 \implies ad - d^2 = 0 \implies d(a - d) = 0
     \]
     - If $ d = 0 $, the function becomes undefined. Thus:
       \[
       a = d
       \]
   - Let $ d = 1 $ (scaling factor):
     \[
     a = 1, \, b = 1, \, c = 1
     \]
5. Write the final function:
   \[
   f(x) = \frac{x + 1}{x + 1}
   \]

---

### Example 6: Reconstructing a Logarithmic Function

Reconstruct the logarithmic function $ f(x) = A\ln(x) + B $ given the following conditions:
- $ f(1) = 0 $
- $ f'(e) = 1 $
- Horizontal asymptote as $ x \to 0^+ $

**Solution:**
1. Write the general form of the logarithmic function:
   \[
   f(x) = A\ln(x) + B
   \]
2. Compute the derivative:
   \[
   f'(x) = \frac{A}{x}
   \]
3. Translate the conditions into equations:
   - From $ f(1) = 0 $:
     \[
     A\ln(1) + B = 0 \implies 0 + B = 0 \implies B = 0
     \]
   - From $ f'(e) = 1 $:
     \[
     \frac{A}{e} = 1 \implies A = e
     \]
   - From the horizontal asymptote as $ x \to 0^+ $:
     - The logarithmic term $ \ln(x) \to -\infty $ as $ x \to 0^+ $, so the function has the desired behavior.
4. Write the final function:
   \[
   f(x) = e\ln(x)
   \]

---


### Example 7: Reconstructing a Quadratic Function (No Solution)

Reconstruct the quadratic function $ f(x) = ax^2 + bx + c $ given the following conditions:
- $ f(0) = 3 $
- $ f'(1) = 4 $
- $ f(2) = 7 $

**Solution:**
1. Identify the structure of the function:
   - This is a quadratic function: $ f(x) = ax^2 + bx + c $.
2. Compute the derivative:
   
   \[
   f'(x) = 2ax + b
   \]
   
   3. Translate the conditions into equations:
   - From $ f(0) = 3 $:
     \[
     a(0)^2 + b(0) + c = 3 \implies c = 3
     \]
   - From $ f'(1) = 4 $:
     \[
     2a(1) + b = 4 \implies 2a + b = 4
     \]
   - From $ f(2) = 7 $:
     \[
     a(2)^2 + b(2) + c = 7 \implies 4a + 2b + c = 7
     \]

4. Solve the system of equations:
   - Substitute $ c = 3 $ into $ 4a + 2b + c = 7 $:
     
     \[
     4a + 2b + 3 = 7 \implies 4a + 2b = 4 \implies 2a + b = 2
     \]
   
   - Solve the two remaining equations $ 2a + b = 4 $ and $ 2a + b = 2 $:
     - Using the elimination method, Subtract the second equation from the first:
       
       \[
       (2a + b) - (2a + b) = 4 - 2 \implies 0 = 2
       \]
     
     - Since both of the remaining variables on the left side disapear we conclude that there is **No Solution**.

5. There is no quadratic function that can satisfy the three above conditions:

---

### Example 8: Reconstructing an Exponential Function

Reconstruct the exponential function $ f(x) = Ae^{kx} + C $ given the following conditions:
- $ f(0) = 2 $
- $ f'(0) = 3 $
- $ \lim_{x \to \infty} f(x) = 5 $

**Solution:**
1. Identify the structure of the function:
   - This is an exponential function: $ f(x) = Ae^{kx} + C $.
2. Compute the derivative:

   \[
   f'(x) = Ak e^{kx}
   \]

3. Translate the conditions into equations:
   - From $ f(0) = 2 $:

     \[
     A e^{k(0)} + C = 2 \implies A + C = 2
     \]

   - From $ f'(0) = 3 $:

     \[
     Ak e^{k(0)} = 3 \implies Ak = 3
     \]

   - From $ \lim_{x \to \infty} f(x) = 5 $:
     - If $ k > 0 $, $ e^{kx} \to \infty $ as $ x \to \infty $, so $ A = 0 $. This contradicts $ Ak = 3 $.
     - Therefore, $ k < 0 $, and $ \lim_{x \to \infty} f(x) = C $. Thus:

       \[
       C = 5
       \]

4. Solve the system of equations:
   - Substitute $ C = 5 $ into $ A + C = 2 $:

     \[
     A + 5 = 2 \implies A = -3
     \]

   - Substitute $ A = -3 $ into $ Ak = 3 $:

     \[
     (-3)k = 3 \implies k = -1
     \]

5. Write the final function:

   \[
   f(x) = -3e^{-x} + 5
   \]

---

### Example 9: Reconstructing a Trigonometric Function

Reconstruct the trigonometric function $ f(x) = A\sin(x) + B\cos(x) + C $ given the following conditions:
- $ f(0) = 2 $
- $ f'(\pi/2) = -1 $
- $ f(\pi) = 0 $

**Solution:**
1. Identify the structure of the function:
   - This is a trigonometric function: $ f(x) = A\sin(x) + B\cos(x) + C $.

2. Compute the derivative:

   \[
   f'(x) = A\cos(x) - B\sin(x)
   \]

3. Translate the conditions into equations:
   - From $ f(0) = 2 $:

     \[
     A\sin(0) + B\cos(0) + C = 2 \implies B + C = 2
     \]

   - From $ f'(\pi/2) = -1 $:

     \[
     A\cos(\pi/2) - B\sin(\pi/2) = -1
     \]

     Simplify using trigonometric values ($ \cos(\pi/2) = 0 $ and $ \sin(\pi/2) = 1 $):

     \[
     -B = -1 \implies B = 1
     \]

   - From $ f(\pi) = 0 $:

     \[
     A\sin(\pi) + B\cos(\pi) + C = 0
     \]

     Substitute $ \sin(\pi) = 0 $ and $ \cos(\pi) = -1 $:

     \[
     A(0) + B(-1) + C = 0 \implies -B + C = 0 \implies C = B
     \]

4. Solve for $ A $, $ B $, and $ C $:
   - From $ B + C = 2 $ and $ C = B $:

     \[
     B + B = 2 \implies 2B = 2 \implies B = 1
     \]

     Since $ C = B $, we have:

     \[
     C = 1
     \]

   - Substitute $ B = 1 $ and $ C = 1 $ into the general form and solve for $ A $. Use $ f(\pi) = 0 $:

     \[
     A\sin(\pi) + B\cos(\pi) + C = 0 \implies A(0) + 1(-1) + 1 = 0 \implies -1 + 1 = 0
     \]

     This condition is satisfied regardless of $ A $, so $ A $ can be any value. For simplicity, let $ A = 1 $.
5. Write the final function:
   Substituting $ A = 1 $, $ B = 1 $, and $ C = 1 $ into the general form:

   \[
   f(x) = \sin(x) + \cos(x) + 1
   \]

---
