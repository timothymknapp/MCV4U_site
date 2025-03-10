+++
title = '1.1 Average Rates of Change'
weight = 1
+++



The **Average Rate of Change** AROC of a function measures how the function's output value changes, on average, between two input values. This concept is analogous to finding the slope of the straight line (called the secant line) that connects two points on the function's graph.

## Formula

The formula for the average rate of change of a function \( f(x) \) between two points \( x = a \) and \( x = b \) is:

\[
\text{AROC} = \frac{f(b) - f(a)}{b - a}
\]

### Explanation of the Formula

At closer inspection you can see that this is essintially the slope formula but written with function notation.

\[
\text{AROC} = \frac{f(b) - f(a)}{b - a} = \frac{\text{Change in y}}{\text{Change in x}}=\frac{\Delta y}{\Delta x}
\]

- \( f(a) \): The y-value of the function at \( x = a \).
- \( f(b) \): The y-value of the function at \( x = b \).
- \( b - a \): The change in the input (x) values.

This formula calculates the ratio of the change in the output (y) (\( f(b) - f(a) \)) to the change in the input (x) (\( b - a \)).

## Example

Suppose \( f(x) = x^2 \). Find the average rate of change of \( f(x) \) from \( x = 1 \) to \( x = 3 \).

### Solution
Using the formula:

\[
\text{Average Rate of Change} = \frac{f(3) - f(1)}{3 - 1}
\]

1. Calculate \( f(3) \) and \( f(1) \):
   - \( f(3) = 3^2 = 9 \)
   - \( f(1) = 1^2 = 1 \)

2. Substitute into the formula:
   \[
   \text{Average Rate of Change} = \frac{9 - 1}{3 - 1} = \frac{8}{2} = 4
   \]

Thus, the average rate of change of \( f(x) = x^2 \) from \( x = 1 \) to \( x = 3 \) is 4.

## Visual Interpretation


On the graph of \( f(x) = x^2 \), the average rate of change represents the slope of the straight line connecting the points \( (1, 1) \) and \( (3, 9) \).  NOTE that this will be called a secant line.  
![Graph of Function 1](/images/MCV4U1_1a.png)

## Interactive secant line graph

<div style="text-align: center;">
    <iframe src="https://www.desmos.com/calculator/1cpbp7jzsx" width="500" height="500" style="border: 1px solid #ccc;" frameborder="0"></iframe>
</div>
