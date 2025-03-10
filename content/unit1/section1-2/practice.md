+++
title = '1.2 Practice'
weight = 2
+++


### MCV4U 1.2 Instantaneous Rates of Change
#### Ex 1
Consider the quadratic function \( f(x) = x^2 + 2x + 1 \).

**Question:**
Find the instantaneous rate of change of \( f(x) \) at \( x = 2 \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. We can always use the First Princles Definition to find an IROC

\[
\text{Instantaneous Rate of Change} = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
\]



2. Calculate \( f(2 + h) \) and \( f(2) \):
   

\[
   f(2 + h) = (2 + h)^2 + 2(2 + h) + 1 = 4 + 4h + h^2 + 4 + 2h + 1 = h^2 + 6h + 9
   \]


   

\[
   f(2) = 2^2 + 2(2) + 1 = 4 + 4 + 1 = 9
   \]



3. Substitute into the formula and simplify:
   

\[
   \lim_{{h \to 0}} \frac{(h^2 + 6h + 9) - 9}{h} = \lim_{{h \to 0}} \frac{h^2 + 6h}{h} = \lim_{{h \to 0}} (h + 6)
   \]



4. **Plug in zero for \( h \)**:
   

\[
   \lim_{{h \to 0}} (h + 6) = 6
   \]


If we directly plug in zero for \( h \), we get an indeterminate form \( \frac{0}{0} \). To find the true value, we generally need to apply algebraic techniques to these limits.

Thus, the instantaneous rate of change of \( f(x) = x^2 + 2x + 1 \) at \( x = 2 \) is 6.

</details>

---

#### Ex 2
Consider the quadratic function \( f(x) = 2x^2 - 4 \).

**Question:**
Find the slope of the tangent line to the graph of \( f(x) \) at \( x = 2 \).

<details>
<summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. We can always use the First Principles Definition to find the slope of the tangent line:



\[
\text{Slope of the Tangent Line} = \lim_{{h \to 0}} \frac{f(2 + h) - f(2)}{h}
\]



2. Calculate \( f(2 + h) \) and \( f(2) \):



\[
   f(2 + h) = 2(2 + h)^2 - 4 = 2(4 + 4h + h^2) - 4 = 8 + 8h + 2h^2 - 4 = 2h^2 + 8h + 4
\]





\[
   f(2) = 2(2^2) - 4 = 2(4) - 4 = 8 - 4 = 4
\]



3. Substitute into the formula and simplify:



\[
   \lim_{{h \to 0}} \frac{(2h^2 + 8h + 4) - 4}{h} = \lim_{{h \to 0}} \frac{2h^2 + 8h}{h} = \lim_{{h \to 0}} (2h + 8)
\]



4. **Plug in zero for \( h \)**:



\[
   \lim_{{h \to 0}} (2h + 8) = 8
\]



If we directly plug in zero for \( h \), we get an indeterminate form \( \frac{0}{0} \). To find the true value, we generally need to apply algebraic techniques to these limits.

Thus, the slope of the tangent line to the graph of \( f(x) = 2x^2 - 4 \) at \( x = 2 \) is 8.

</details>

---

<iframe src="https://script.google.com/macros/s/AKfycbwZGWJryBIiZBezNJUHe05PqeQXtfj8cQgDlRI6i9SpLEiL14YfwFY7LxiPRuKcqBCn/exec" width="100%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>