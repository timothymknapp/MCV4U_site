+++
title = '2.3 Product Rule'
weight = 2
+++

## 2.3 Product Rule

### Overview
In this section, we will explore the **Product Rule**, a powerful tool for differentiating the product of two functions. Often, when we deal with the derivative of a product of functions, we cannot simply apply the power rule or other basic rules directly. Instead, the **Product Rule** allows us to compute the derivative of the product by differentiating each function individually and then combining the results.

### The Product Rule

The **Product Rule** states that the derivative of the product of two functions \( u(x) \) and \( v(x) \) is given by:

\[
\frac{d}{dx}[u(x) \cdot v(x)] = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]

This means that to differentiate \( u(x) \cdot v(x) \), you:
1. Differentiate the first function \( u(x) \) and multiply it by the second function \( v(x) \).
2. Differentiate the second function \( v(x) \) and multiply it by the first function \( u(x) \).

### Key Concept

- The **Product Rule** is useful when you need to differentiate expressions where two functions are multiplied together, and both depend on \( x \). 
- The rule applies to polynomial functions, rational functions, and other expressions that involve the product of two functions.
  
### Example of Applying the Product Rule

Let’s differentiate the function \( f(x) = x^2 \cdot \sin(x) \).

We define \( u(x) = x^2 \) and \( v(x) = \sin(x) \), and then apply the product rule:

\[
f'(x) = u'(x) \cdot v(x) + u(x) \cdot v'(x)
\]

Here, \( u'(x) = 2x \) and \( v'(x) = \cos(x) \). Thus, applying the rule:

\[
f'(x) = (2x) \cdot \sin(x) + (x^2) \cdot \cos(x)
\]

The derivative of \( f(x) = x^2 \cdot \sin(x) \) is:

\[
f'(x) = 2x \sin(x) + x^2 \cos(x)
\]

### Learning Objectives
By the end of this section, students will:
1. Understand the **Product Rule** and how it applies to differentiating the product of two functions.
2. Be able to differentiate functions involving products of polynomials, trigonometric functions, and other basic functions.
3. Practice applying the product rule in various contexts, including more complex expressions involving products of different types of functions.

The **Product Rule** is a foundational technique in calculus, and mastering it will prepare you for more advanced topics in differentiation.
