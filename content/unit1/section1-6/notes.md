+++
title = '1.6 Examples'
weight = 1
+++

### Example 1: Differentiability at a Point

Determine whether the function \( f(x) = |x| \) is differentiable at \( x = 0 \).

**Solution:**

1. **Check Continuity at \( x = 0 \):**
   - The function \( f(x) = |x| \) is continuous for all \( x \), including \( x = 0 \).  
     \[
     f(0) = |0| = 0, \quad \text{and } \lim_{{x \to 0}} f(x) = 0.
     \]
     Thus, \( f(x) \) is continuous at \( x = 0 \).

2. **Compute the Left-Hand Derivative:**
   - For \( x < 0 \), \( f(x) = -x \). Using the definition of the derivative:
     \[
     f'(0^-) = \lim_{{h \to 0^-}} \frac{f(0 + h) - f(0)}{h} = \lim_{{h \to 0^-}} \frac{-h - 0}{h} = -1.
     \]

3. **Compute the Right-Hand Derivative:**
   - For \( x > 0 \), \( f(x) = x \). Using the definition of the derivative:
     \[
     f'(0^+) = \lim_{{h \to 0^+}} \frac{f(0 + h) - f(0)}{h} = \lim_{{h \to 0^+}} \frac{h - 0}{h} = 1.
     \]

4. **Compare Left-Hand and Right-Hand Derivatives:**
   - The left-hand derivative is \( -1 \), and the right-hand derivative is \( 1 \). Since these are not equal, the derivative does not exist at \( x = 0 \).

**Conclusion:**
The function \( f(x) = |x| \) is **not differentiable** at \( x = 0 \) due to a sharp corner at that point.

---

### Example 2: Differentiability with a Vertical Tangent

Determine whether the function \( g(x) = \sqrt[3]{x} \) is differentiable at \( x = 0 \).

**Solution:**

1. **Check Continuity at \( x = 0 \):**
   - The function \( g(x) = \sqrt[3]{x} \) is continuous for all \( x \), including \( x = 0 \).  
     \[
     g(0) = \sqrt[3]{0} = 0, \quad \text{and } \lim_{{x \to 0}} g(x) = 0.
     \]
     Thus, \( g(x) \) is continuous at \( x = 0 \).

2. **Compute the Left-Hand Derivative:**
   - Using the definition of the derivative for \( x < 0 \):
     \[
     g'(0^-) = \lim_{{h \to 0^-}} \frac{g(0 + h) - g(0)}{h} = \lim_{{h \to 0^-}} \frac{\sqrt[3]{h} - 0}{h} = \lim_{{h \to 0^-}} h^{-2/3}.
     \]
     As \( h \to 0^- \), \( h^{-2/3} \to \infty \).

3. **Compute the Right-Hand Derivative:**
   - Using the definition of the derivative for \( x > 0 \):
     \[
     g'(0^+) = \lim_{{h \to 0^+}} \frac{g(0 + h) - g(0)}{h} = \lim_{{h \to 0^+}} \frac{\sqrt[3]{h} - 0}{h} = \lim_{{h \to 0^+}} h^{-2/3}.
     \]
     As \( h \to 0^+ \), \( h^{-2/3} \to \infty \).

4. **Analyze the Derivative:**
   - Both the left-hand and right-hand derivatives diverge to infinity, indicating that the slope of the tangent line is vertical at \( x = 0 \).

**Conclusion:**
The function \( g(x) = \sqrt[3]{x} \) is **not differentiable** at \( x = 0 \) due to a vertical tangent.

---

