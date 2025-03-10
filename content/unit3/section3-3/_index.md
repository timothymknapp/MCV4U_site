+++
title = '3.3 Exponential Derivatives'
weight = 3
+++


In this section, we will explore how to compute the derivatives of exponential functions, including the natural exponential function \( e^x \) and general exponential functions \( a^x \), where \( a > 0 \) and \( a \neq 1 \).

---

## Table of Contents
1. [Basic Derivative Rules](#basic-derivative-rules)
2. [Derivative of the Natural Exponential Function](#derivative-of-the-natural-exponential-function)
3. [Derivative of General Exponential Functions](#derivative-of-general-exponential-functions)

---

## Basic Derivative Rules

Before diving into exponential derivatives, let's recall some basic derivative rules:
- The derivative of a constant is zero: \( \frac{d}{dx}[c] = 0 \)
- The power rule: \( \frac{d}{dx}[x^n] = n x^{n-1} \)
- The chain rule: \( \frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x) \)

---

## Derivative of the Natural Exponential Function

The derivative of the natural exponential function \( e^x \) is one of the most fundamental results in calculus:

\[
\frac{d}{dx}[e^x] = e^x
\]

### Proof of the Derivative of \( e^x \)

To prove that the derivative of \( e^x \) is \( e^x \), we use the **limit definition of the derivative**:

\[
f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
\]

For \( f(x) = e^x \), this becomes:

\[
\frac{d}{dx}[e^x] = \lim_{h \to 0} \frac{e^{x+h} - e^x}{h}
\]

#### Step 1: Factor out \( e^x \)
Using the property of exponents \( e^{x+h} = e^x e^h \), we can rewrite the numerator:

\[
\frac{d}{dx}[e^x] = \lim_{h \to 0} \frac{e^x e^h - e^x}{h}
\]

Factor \( e^x \) out of the terms:

\[
\frac{d}{dx}[e^x] = \lim_{h \to 0} \left[ e^x \cdot \frac{e^h - 1}{h} \right]
\]

#### Step 2: Evaluate the limit
It is a well-known result in calculus that:

\[
\lim_{h \to 0} \frac{e^h - 1}{h} = 1
\]

Substitute this result back into the equation:

\[
\frac{d}{dx}[e^x] = e^x \cdot 1
\]

Simplify:

\[
\frac{d}{dx}[e^x] = e^x
\]

---

## Conclusion

We have proven that the derivative of \( e^x \) is \( e^x \). This result is unique to the natural exponential function and is widely used in various applications of calculus.

\[
\boxed{\frac{d}{dx}[e^x] = e^x}
\]

---

## Derivative of General Exponential Functions

For a general exponential function \( a^x \), where \( a > 0 \) and \( a \neq 1 \), the derivative is given by:

\[
\frac{d}{dx}[a^x] = a^x \ln(a)
\]

### Proof of the Derivative of \( a^x \)

To derive this result, we use the relationship between exponential functions and the natural logarithm. Recall that:

\[
a^x = e^{x \ln(a)}
\]

Now, apply the chain rule to differentiate \( e^{x \ln(a)} \):

\[
\frac{d}{dx}[a^x] = \frac{d}{dx}[e^{x \ln(a)}] = e^{x \ln(a)} \cdot \ln(a)
\]

Since \( e^{x \ln(a)} = a^x \), we have:

\[
\frac{d}{dx}[a^x] = a^x \ln(a)
\]

---

## Conclusion

We have derived the formula for the derivative of a general exponential function \( a^x \), which is \( a^x \ln(a) \). This result extends the concept of exponential differentiation beyond the natural base \( e \).

\[
\boxed{\frac{d}{dx}[a^x] = a^x \ln(a)}
\]

---

In this lesson, we learned the derivatives of exponential functions, including the natural exponential function \( e^x \) and general exponential functions \( a^x \). These derivatives are essential tools in calculus and are widely used in physics, engineering, and other fields. Move on to the next section to see some solved examples of exponential derivatives.