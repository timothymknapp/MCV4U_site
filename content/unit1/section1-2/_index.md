+++
title = '1.2 Instantaneous Rates of Change'
weight = 1
+++

The **Instantaneous Rate of Change** of a function measures how the function's output value changes at a specific point in time. This concept is analogous to finding the slope of the tangent line to the function's graph at a particular point.

## Formula

The formula for the instantaneous rate of change of a function \( f(x) \) at a point \( x = a \) is:



\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
\]



### Explanation of the Formula
- \( f(a) \): The y-value of the function at \( x = a \).
- \( f(a + h) \): The y-value of the function at \( x = a + h \). Note: This y-value will be ever so slightly to the right of \( f(a) \).
- \( h \): A small change to the x-value. This change is intended to be the smallest possible value.

This formula calculates the average rate of change as \( h \) approaches zero, effectively making the average rate of change take place over such a small interval that it can be considered an instantaneous rate of change. The vocabulary for this new line is a tangent line at \( x = a \), rather than calling it a secant line as we did with the average rate of change.

## Example

Suppose \( f(x) = x^2 \). Find the instantaneous rate of change of \( f(x) \) at \( x = 2 \).

### Solution

Using the formula:

1. **Let \( h \) approach zero**: The limit essentially allows us to let \( h = 0 \).


\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{f(2 + h) - f(2)}{h} = \frac{f(2 + 0) - f(2)}{0} = \frac{0}{0}
\]

Notice above that if we directly plug in zero for \( h \), and 2 for x we get a limit of indeterminate form \( \frac{0}{0} \). To find the true value, we generally need to apply algebra and simplification to these limits.  We will explote these types of limits a bit more next section as we delve a little deeper in this new concept of limits.

1.  Instead of subing zero for h as a first step we need to do the following:

2. Calculate \( f(2 + h) \) and \( f(2) \):
   - \( f(2 + h) = (2 + h)^2 = 4 + 4h + h^2 \)
   - \( f(2) = 2^2 = 4 \)

3. Substitute into the formula:



\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{(4 + 4h + h^2) - 4}{h} = \lim_{{h \to 0}} \frac{4h + h^2}{h}
\]



4. Simplify the expression:



\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{h(4 + h)}{h} = \lim_{{h \to 0}} (4 + h)
\]



5. **Plug in zero for \( h \)**:



\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} (4 + h) = 4
\]





Thus, the instantaneous rate of change of \( f(x) = x^2 \) at \( x = 2 \) is 4.

## Visual Interpretation

On the graph of \( f(x) = x^2 \), the instantaneous rate of change at \( x = 2 \) represents the slope of the tangent line to the curve at that point.
<div style="text-align: center;">
   <iframe src="https://www.desmos.com/calculator/wtnz4as7wj?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>


## Interactive Tangent line graph

<div style="text-align: center;">
    <iframe src="https://www.desmos.com/calculator/ipkmqkcg7e" width="500" height="500" style="border: 1px solid #ccc;" frameborder="0"></iframe>
</div>

## Summary

In this section, we learned how starting with an average rate of change and making the size of the \( x \)-interval extremely small, we can effectively turn it into an instantaneous rate of change. This is achieved using a new concept called the **limit**. Consider the following equation: 

\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
\]

It is very important to note that this equation and its concept will be used in a wide variety of situations throughout this course. It will take on many names, including but not limited to:

- The First Principles Definition
- Instantaneous rate of change
- IROC
- Slope of the tangent line
- \( f'(x) \)
- \( \frac{dy}{dx} \)
- "f prime"
- "The derivative"
