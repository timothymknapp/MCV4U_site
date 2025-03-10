+++
title = '1.2 Examples'
weight = 1
+++
## Instantaneous Rate of Change given an Equation

### Example 1: Quadratic Function

Let's find the instantaneous rate of change of the function \( f(x) = x^2 - 2x + 1 \) at \( x = 3 \) using the first principles definition.

1. **Definition of the instantaneous rate of change**:



\[
\lim_{{h \to 0}} \frac{f(x+h) - f(x)}{h}
\]



2. **Plug in the function and point**:



\[
\lim_{{h \to 0}} \frac{(3+h)^2 - 2(3+h) + 1 - (3^2 - 2(3) + 1)}{h}
\]



3. **Simplify the expression**:



\[
= \lim_{{h \to 0}} \frac{(9 + 6h + h^2 - 6 - 2h + 1) - (9 - 6 + 1)}{h}
\]





\[
= \lim_{{h \to 0}} \frac{9 + 6h + h^2 - 6 - 2h + 1 - 9 + 6 - 1}{h}
\]





\[
= \lim_{{h \to 0}} \frac{6h + h^2 - 2h}{h}
\]





\[
= \lim_{{h \to 0}} \frac{4h + h^2}{h}
\]





\[
= \lim_{{h \to 0}} 4 + h
\]



4. **Take the limit as \( h \) approaches 0**:



\[
= 4
\]



So, the instantaneous rate of change of the function \( f(x) = x^2 - 2x + 1 \) at \( x = 3 \) is 4.

---

### Example 2: Cubic Function

Let's find the instantaneous rate of change of the function \( g(x) = x^3 - 3x^2 + 2x \) at \( x = 2 \) using the first principles definition.

1. **Definition of the instantaneous rate of change**:



\[
\lim_{{h \to 0}} \frac{g(x+h) - g(x)}{h}
\]



2. **Plug in the function and point**:



\[
\lim_{{h \to 0}} \frac{(2+h)^3 - 3(2+h)^2 + 2(2+h) - (2^3 - 3(2)^2 + 2(2))}{h}
\]



3. **Simplify the expression**:



\[
= \lim_{{h \to 0}} \frac{(8 + 12h + 6h^2 + h^3 - 12 - 12h - 3h^2 + 4 + 2h) - (8 - 12 + 4)}{h}
\]





\[
= \lim_{{h \to 0}} \frac{8 + 12h + 6h^2 + h^3 - 12 - 12h - 3h^2 + 4 + 2h - 8 + 12 - 4}{h}
\]





\[
= \lim_{{h \to 0}} \frac{12h + 3h^2 + h^3}{h}
\]





\[
= \lim_{{h \to 0}} \frac{h(12 + 3h + h^2)}{h}
\]





\[
= \lim_{{h \to 0}} (12 + 3h + h^2)
\]



4. **Take the limit as \( h \) approaches 0**:



\[
= 12
\]



So, the instantaneous rate of change of the function \( g(x) = x^3 - 3x^2 + 2x \) at \( x = 2 \) is 12.

---

## Instantaneous Rate of Change given a Graph

### Example 3: 

Let's find the instantaneous rate of change of the function \( y = x^2 + 1 \) at \( x = 1 \) using the graph.

<iframe src="https://www.desmos.com/calculator/htal49csdq?embed" width="300" height="300" style="border: 1px solid #ccc" frameborder=0></iframe>

1. **Draw the tangent line**: 
   
   Draw a tangent line to the curve at the point \( (1, 2) \) on the graph.

2. **Identify another point on the tangent line**: 
   
   Find another point on the tangent line. For example, let's use the point \( (2, 4) \).

3. **Use the slope formula**:
   
   The slope \( m \) of the tangent line (which represents the instantaneous rate of change) is calculated using the slope formula:
   
   

\[
   m = \frac{y_2 - y_1}{x_2 - x_1}
   \]


   
   where \( (x_1, y_1) = (1, 2) \) and \( (x_2, y_2) = (2, 4) \).

4. **Calculate the slope**:
   
   

\[
   m = \frac{4 - 2}{2 - 1} = \frac{2}{1} = 2
   \]


   
   So, the slope of the tangent line at \( x = 1 \) is 2.

Therefore, the instantaneous rate of change of the function \( y = x^2 + 1 \) at \( x = 1 \) is 2.
