+++
title = "2.1 Power Rule"
weight = 2
+++


### Overview

In this section, we will explore the **Power Rule** for differentiation, a key rule for differentiating polynomial and rational functions. We will also introduce the **Constant Multiple Rule**, which helps simplify the process when a function includes a constant multiplied by a term.

### Power Rule

The Power Rule allows us to differentiate functions of the form \( f(x) = x^n \), where \( n \) is any real number (integer, fraction, or negative). The rule is simple:

\[
f'(x) = n \cdot x^{n-1}
\]

This rule can be applied directly to differentiate monomials.

### Constant Multiple Rule

The **Constant Multiple Rule** states that if a function is the product of a constant and another function, the derivative of the function is simply the constant multiplied by the derivative of the other function. In mathematical terms:

\[
\frac{d}{dx} [c \cdot f(x)] = c \cdot f'(x)
\]

Where \( c \) is a constant. This rule helps when a function includes a constant factor, simplifying the process of differentiation.

### Applying Both Rules

When a function involves both a constant and a power of \( x \), you can apply both the Power Rule and the Constant Multiple Rule. For example, if we want to differentiate \( f(x) = 5x^3 \):

1. First, apply the Constant Multiple Rule:  
   \[
   f'(x) = 5 \cdot \frac{d}{dx}[x^3]
   \]

2. Then, apply the Power Rule to differentiate \( x^3 \):  
   \[
   f'(x) = 5 \cdot 3x^{3-1} = 15x^2
   \]

Thus, \( f'(x) = 15x^2 \).

---

### Example 1: First-Principles Derivation

To better understand the Power Rule, let’s derive it using the **First Principles** definition of the derivative for two functions:

#### Example 1.1: \( f(x) = x^2 \)

We use the definition of the derivative:
\[
f'(x) = \lim_{{h \to 0}} \frac{f(x + h) - f(x)}{h}
\]

Substitute \( f(x) = x^2 \):
\[
f'(x) = \lim_{{h \to 0}} \frac{(x+h)^2 - x^2}{h}
\]
Simplifying the numerator:
\[
f'(x) = \lim_{{h \to 0}} \frac{x^2 + 2xh + h^2 - x^2}{h} = \lim_{{h \to 0}} \frac{2xh + h^2}{h}
\]
Factor out \( h \) from the numerator:
\[
f'(x) = \lim_{{h \to 0}} \frac{h(2x + h)}{h}
\]
Cancel \( h \) from the numerator and denominator:
\[
f'(x) = \lim_{{h \to 0}} (2x + h)
\]
As \( h \to 0 \), we get:
\[
f'(x) = 2x
\]

Thus, the derivative of \( f(x) = x^2 \) is \( f'(x) = 2x \), which is the result predicted by the Power Rule.

#### Example 1.2: \( f(x) = x^{1/2} \)

Now, let’s apply the first-principles definition to \( f(x) = x^{1/2} \):

\[
f'(x) = \lim_{{h \to 0}} \frac{(x+h)^{1/2} - x^{1/2}}{h}
\]
This can be simplified using algebraic methods (multiplying by the conjugate), but it’s generally a bit more involved. Nonetheless, after simplifying, we get the derivative:
\[
f'(x) = \frac{1}{2\sqrt{x}}
\]

This is the result we expect from applying the Power Rule to \( f(x) = x^{1/2} \), as the Power Rule predicts \( f'(x) = \frac{1}{2} \cdot x^{-1/2} \).

---

### Summary

In this section, we:
- Learned how to differentiate using the **Power Rule** for functions of the form \( f(x) = x^n \).
- Introduced the **Constant Multiple Rule** to handle constant factors in functions.
- Applied both rules in examples and saw how to differentiate polynomials and rational functions efficiently.

By the end of this section, you'll be able to differentiate a wide variety of functions using these two key rules.
