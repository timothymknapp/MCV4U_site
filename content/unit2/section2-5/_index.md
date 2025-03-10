+++
title = "2.5 Chain Rule"
weight = 2
+++


### Overview
The Chain Rule is a powerful technique in calculus used to differentiate composite functions. It allows us to differentiate a function that is made up of two or more simpler functions. The basic idea is that if you have a function inside another function, you differentiate the outer function and then multiply it by the derivative of the inner function.

In this section, we will learn how to apply the Chain Rule to find the derivative of composite functions. You’ll practice using the Chain Rule with functions that involve polynomials and rational functions.

### The Chain Rule

The Chain Rule states that if a function \( y \) can be written as a composition of two functions \( u(x) \) and \( v(x) \), i.e.,

\[
y = u(v(x)),
\]

then the derivative of \( y \) with respect to \( x \) is given by:

\[
\frac{dy}{dx} = \frac{du}{dv} \cdot \frac{dv}{dx}
\]

Where:

- \( u(x) \) is the outer function.
- \( v(x) \) is the inner function.

### Key Steps to Apply the Chain Rule

1. **Identify the inner and outer functions.** The outer function is the one that contains the inner function. 
2. **Differentiate the outer function.** Differentiate the outer function as if the inner function were a variable.
3. **Differentiate the inner function.** Take the derivative of the inner function with respect to \( x \).
4. **Multiply the derivatives.** Multiply the derivative of the outer function by the derivative of the inner function.

### Example:

If \( y = (3x^2 + 2)^5 \), we have:
- The outer function is \( u(v) = v^5 \), where \( v = 3x^2 + 2 \).
- The inner function is \( v(x) = 3x^2 + 2 \).

Applying the Chain Rule:

\[
\frac{dy}{dx} = 5v^4 \cdot \frac{d}{dx}(3x^2 + 2) = 5(3x^2 + 2)^4 \cdot 6x
\]

Thus, the derivative is:

\[
\frac{dy}{dx} = 30x(3x^2 + 2)^4
\]

### Learning Objectives
By the end of this section, students will:
1. Understand the concept of the Chain Rule.
2. Apply the Chain Rule to differentiate composite functions involving polynomials and rational functions.
3. Recognize when and how to use the Chain Rule in differentiation.
