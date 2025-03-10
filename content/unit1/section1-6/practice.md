+++
title = '1.6 Practice'
weight = 2
+++

### 1.6 Differentiability

#### Ex1.

Determine whether the function \( f(x) = |x - 1| \) is differentiable at \( x = 1 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check Continuity:**
   - The function \( f(x) = |x - 1| \) is continuous for all \( x \), including \( x = 1 \).  
     \[
     f(1) = |1 - 1| = 0, \quad \text{and } \lim_{{x \to 1}} f(x) = 0.
     \]
     Thus, \( f(x) \) is continuous at \( x = 1 \).

2. **Compute the Left-Hand Derivative:**
   - For \( x < 1 \), \( f(x) = -(x - 1) \). Using the derivative definition:
     \[
     f'(1^-) = \lim_{{h \to 0^-}} \frac{f(1 + h) - f(1)}{h} = \lim_{{h \to 0^-}} \frac{-(h)}{h} = -1.
     \]

3. **Compute the Right-Hand Derivative:**
   - For \( x > 1 \), \( f(x) = x - 1 \). Using the derivative definition:
     \[
     f'(1^+) = \lim_{{h \to 0^+}} \frac{f(1 + h) - f(1)}{h} = \lim_{{h \to 0^+}} \frac{h}{h} = 1.
     \]

4. **Compare Left-Hand and Right-Hand Derivatives:**
   - The left-hand derivative is \( -1 \), and the right-hand derivative is \( 1 \). Since these are not equal, the derivative does not exist at \( x = 1 \).

**Conclusion:**
The function \( f(x) = |x - 1| \) is **not differentiable** at \( x = 1 \) due to a sharp corner.

</details>

---

#### Ex2.

Determine if the piecewise function  
\[
g(x) = \begin{cases} 
x^2 & \text{if } x \leq 1, \\
2x - 1 & \text{if } x > 1 
\end{cases}
\]  
is differentiable at \( x = 1 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check Continuity:**
   - The function is continuous if the left-hand limit, right-hand limit, and \( g(1) \) are equal:
     \[
     g(1^-) = (1)^2 = 1, \quad g(1^+) = 2(1) - 1 = 1, \quad g(1) = 1.
     \]
     Thus, \( g(x) \) is continuous at \( x = 1 \).

2. **Compute the Left-Hand Derivative:**
   - For \( x \leq 1 \), \( g(x) = x^2 \). Using the derivative definition:
     \[
     g'(1^-) = \lim_{{h \to 0^-}} \frac{g(1 + h) - g(1)}{h} = \lim_{{h \to 0^-}} \frac{(1 + h)^2 - 1}{h} = \lim_{{h \to 0^-}} \frac{2h + h^2}{h} = 2.
     \]

3. **Compute the Right-Hand Derivative:**
   - For \( x > 1 \), \( g(x) = 2x - 1 \). Using the derivative definition:
     \[
     g'(1^+) = \lim_{{h \to 0^+}} \frac{g(1 + h) - g(1)}{h} = \lim_{{h \to 0^+}} \frac{2(1 + h) - 1 - 1}{h} = \lim_{{h \to 0^+}} 2 = 2.
     \]

4. **Compare Left-Hand and Right-Hand Derivatives:**
   - Both the left-hand and right-hand derivatives are \( 2 \).

**Conclusion:**
The function \( g(x) \) is **differentiable** at \( x = 1 \).

</details>

---

#### Ex3.

The function \( h(x) = x^{2/3} \) is given. Is it differentiable at \( x = 0 \)?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check Continuity:**
   - The function \( h(x) = x^{2/3} \) is continuous for all \( x \), including \( x = 0 \).  
     \[
     h(0) = 0, \quad \text{and } \lim_{{x \to 0}} h(x) = 0.
     \]
     Thus, \( h(x) \) is continuous at \( x = 0 \).

2. **Compute the Derivative:**
   - The derivative is \( h'(x) = \frac{2}{3}x^{-1/3} \). At \( x = 0 \), this becomes:
     \[
     h'(0) = \frac{2}{3}(0)^{-1/3},
     \]
     which is undefined due to division by zero.

**Conclusion:**
The function \( h(x) = x^{2/3} \) is **not differentiable** at \( x = 0 \) due to the vertical tangent.

</details>

---

#### Ex4.

Analyze the differentiability of the function \( k(x) = \begin{cases} 
x^2, & \text{if } x \leq 2, \\
x + 2, & \text{if } x > 2 
\end{cases} \) at \( x = 2 \).

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. **Check Continuity:**
   - Evaluate \( k(2) \), \( \lim_{{x \to 2^-}} k(x) \), and \( \lim_{{x \to 2^+}} k(x) \):
     \[
     k(2) = 2^2 = 4, \quad \lim_{{x \to 2^-}} k(x) = 4, \quad \lim_{{x \to 2^+}} k(x) = 2 + 2 = 4.
     \]
     Since all are equal, \( k(x) \) is continuous at \( x = 2 \).

2. **Compute the Left-Hand Derivative:**
   - For \( x \leq 2 \), \( k'(x) = 2x \):
     \[
     k'(2^-) = 2(2) = 4.
     \]

3. **Compute the Right-Hand Derivative:**
   - For \( x > 2 \), \( k'(x) = 1 \):
     \[
     k'(2^+) = 1.
     \]

4. **Compare Left-Hand and Right-Hand Derivatives:**
   - The left-hand derivative is \( 4 \), and the right-hand derivative is \( 1 \). These are not equal.

**Conclusion:**
The function \( k(x) \) is **not differentiable** at \( x = 2 \) due to a discontinuity in the derivative.

</details>

---

#### Ex5.
Determine if the piecewise function is differentiable at \( x = 0 \).

\[
q(x) = \begin{cases} 
x^2 & \text{if } x \leq 0, \\
x^2 + 2x & \text{if } x > 0 
\end{cases}
\]  


<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

 
1. **Check Continuity:**  
   - The function is continuous if the left-hand limit, right-hand limit, and \( q(0) \) are equal:  
     \[
      q(0^-) = (0)^2 = 0
     \] 
     \[
      q(0^+) = (0)^2 + 2(0) = 0
      \]
     \[
      q(0) = 0.
     \]  
     Since all three values are equal, \( q(x) \) is **continuous** at \( x = 0 \).

2. **Compute the Derivative for Each Piece:**  
   - For \( x \leq 0 \), \( q(x) = x^2 \). The derivative is:
     \[
     q'(x) = 2x.
     \]
   - For \( x > 0 \), \( q(x) = x^2 + 2x \). The derivative is:
     \[
     q'(x) = 2x + 2.
     \]

3. **Evaluate the Left-Hand Limit of the Derivative:**  
   - For \( x \leq 0 \), the derivative is \( q'(x) = 2x \). Evaluate the limit as \( x \to 0^- \):
     \[
     \lim_{{x \to 0^-}} q'(x) = \lim_{{x \to 0^-}} 2x = 0.
     \]

4. **Evaluate the Right-Hand Limit of the Derivative:**  
   - For \( x > 0 \), the derivative is \( q'(x) = 2x + 2 \). Evaluate the limit as \( x \to 0^+ \):
     \[
     \lim_{{x \to 0^+}} q'(x) = \lim_{{x \to 0^+}} (2x + 2) = 2.
     \]

5. **Compare the Limits of the Derivatives:**  
   - The left-hand limit of the derivative is \( 0 \), and the right-hand limit of the derivative is \( 2 \). These are not equal.

**Conclusion:**  
The function \( q(x) \) is **not differentiable** at \( x = 0 \) because the left-hand and right-hand limits of the derivative do not match, even though the function is continuous at \( x = 0 \). This creates a "kink" in the graph at \( x = 0 \).

</details>

---

#### Ex6.
Determine if the piecewise function is differentiable at \( x = -3 \).

\[
q(x) = \begin{cases} 
6x+10 & \text{if } x \leq -3, \\
-x^2 + 1 & \text{if } x > -3 
\end{cases}
\]  


<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

 
1. **Check Continuity:**  
   - The function is continuous if the left-hand limit, right-hand limit, and \( q(0) \) are equal:  
    
     \[
     q(-3^-) = 6(-3)+10 = -8 
     \]

     \[
     q(-3^+) = -(-3)^2 + 1 = -8  
     \]
    
     \[ 
     q(-3) = -8
     \]  
    
     Since all three values are equal, \( q(x) \) is **continuous** at \( x = -3 \).

2. **Compute the Derivative for Each Piece:**  
   - For \( x \leq -3 \), \( q(x) = 6x+10 \). The derivative is:
     \[
     q'(x) = 6.
     \]
   - For \( x > -3 \), \( q(x) = -x^2 + 1 \). The derivative is:
     \[
     q'(x) = -2x.
     \]

3. **Evaluate the Left-Hand Limit of the Derivative:**  
   - For \( x \leq -3 \), the derivative is \( q'(x) = 6 \). Evaluate the limit as \( x \to 0^- \):
     \[
     \lim_{{x \to -3^-}} q'(x) = \lim_{{x \to -3^-}} 6 = 6.
     \]

4. **Evaluate the Right-Hand Limit of the Derivative:**  
   - For \( x > -3 \), the derivative is \( q'(x) = -2x \). Evaluate the limit as \( x \to 0^+ \):
     \[
     \lim_{{x \to -3^+}} q'(x) = \lim_{{x \to -3^+}} (-2(-3)) = 6.
     \]

5. **Compare the Limits of the Derivatives:**  
   - The left-hand limit of the derivative is \( 6 \), and the right-hand limit of the derivative is \( 6 \). These are equal.

**Conclusion:**  
The function \( q(x) \) is **differentiable** at \( x = -3 \) because the left-hand and right-hand limits of the derivative do match, and the function is continuous at \( x = -3 \). This indicates taht we can place a tangent line at  \( x = -3 \) and use its slope as an Instantanious rate of change.

</details>

---




<iframe src="https://script.google.com/macros/s/AKfycbz7OEevkWkxZncryLgjso9o_yTsqgwpAzV7NVlwG9kg90_xIza2xP8NAp049MMXMd76/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>


