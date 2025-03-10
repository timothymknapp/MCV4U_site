+++
title = '1.3 Limits on Graphs'
weight = 3
+++

The concept of a **limit** is fundamental in calculus, providing a way to describe the behavior of a function as its input approaches a specific value. Limits are used to define derivatives, integrals, and continuity. In this lesson, we will clarify the concept of a limit, explore its graphical interpretation, and solve some algebraic limits, including an example involving an indeterminate form.

## What is a Limit?

A limit describes the value that a function approaches as its input gets arbitrarily close to a specific point. For a function \( f(x) \), the limit as \( x \) approaches a value \( a \) is written as:

\[
\lim_{{x \to a}} f(x)
\]

For the limit \( \lim_{{x \to a}} f(x) \) to exist, the **left-hand limit**, \( \lim_{{x \to a^-}} f(x) \), and the **right-hand limit**, \( \lim_{{x \to a^+}} f(x) \), must both exist and be equal to each other. You can see this concept written mathamatical below. It means that as \( x \) gets closer and closer to \( a \) from both sides, the function values approach the same number.  

\[
\lim_{{x \to a}} f(x) = \lim_{{x \to a^-}} f(x) = \lim_{{x \to a^+}} f(x).
\]

The above mathamatics can be verbalized: "The limit of the function f of x as x approachs a is equal to the the limit of the function f of x as x appraoches a from the left and euqal to the limit of the function f of x as x appraoches a from the right!" Wow that is a mouthful!

## Graphical Interpretation of Limits

Graphically, a limit represents the value a function approaches on a graph as the input moves closer to a particular \( x \)-value from either side. Consider the following examples:

1. **Limit Exists:** The graph of the function smoothly approaches the same value from both the left and right as \( x \to a \).
2. **Limit Does Not Exist:** The function diverges, oscillates, or approaches different values from the left and right.

## Example 1

On the below graph you can see that the limit at \( x=3 \) **exists** becuse;

\[
\lim_{{x \to 1^-}} f(x) = \lim_{{x \to 1^+}} f(x) = \lim_{{x \to 1}} f(x) 
\]

<div style="text-align: center;">
   <iframe src="https://www.desmos.com/calculator/sct9iflyyr?embed" width="300" height="300" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>

You can form the conclusion that the limit exists by the following logic:

1. The left hand limt is 3:  \( \lim_{{x \to 1^-}} f(x) = 3 \)
2. The right hand limt is 3:  \( \lim_{{x \to 1^+}} f(x) = 3 \)
3. Since the left hand and the right hand limits are equal we conclude the the limit of the function both exists and its value is 3: 
\[ 
   \lim_{{x \to 1}} f(x) = 3 
\]

## Example 2

On the below graph you can see that the limit at \( x=-5 \) **exists** becuse;

\[
\lim_{{x \to -5^-}} f(x) = \lim_{{x \to -5^+}} f(x) = \lim_{{x \to -5}} f(x) 
\]

<div style="text-align: center;">
   <iframe src="https://www.desmos.com/calculator/scl5pmglfk?embed" width="300" height="300" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>

You can form the conclusion that the limit exists by the following logic:

1. The left hand limt is 4:  \( \lim_{{x \to -5^-}} f(x) = 4 \)
2. The right hand limt is 4:  \( \lim_{{x \to -5^+}} f(x) =4 \)
4. Since the left hand and the right hand limits are equal we conclude the the limit of the function both exists and its value is 4: 
\[
   \lim_{{x \to -5}} f(x) = 4 
\]

## Example 3

On the below graph you can see that the limit at \( x=-5 \) **does not exist** becuse;

\[
\lim_{{x \to -4^-}} f(x) \neq \lim_{{x \to -4^+}} f(x)
\]

<div style="text-align: center;">
   <iframe src="https://www.desmos.com/calculator/aczlqc4yw6?embed" width="300" height="300" style="border: 1px solid #ccc" frameborder=0></iframe>
</div>

You can form the conclusion that the limit does not exist by the following logic:

1. The left hand limt is 5:  \( \lim_{{x \to -4^-}} f(x) = 5 \)
2. The right hand limt is 0:  \( \lim_{{x \to -4^+}} f(x) = 0 \)
3. Since the left hand and the right hand limits are not equal we conclude the the limit of the function at e equals -4 does not exist. 

\[ 
   \lim_{{x \to -4}} f(x) \quad \nexists 
\]

<div style="text-align: center;">
  <div style="border: 2px solid red; display: inline-block; padding: 10px;">
    Note: The symbol, \( \nexists \) is sometimes written DNE
  </div>
</div>

### Key Takeaways:
- Limits describe the behavior of a function as the input approaches a specific value.
- Graphical interpretations help visualize the concept of limits.
- Algebraic techniques, such as factoring and rationalizing, are used to solve limits, including those involving indeterminate forms.

In future sections we will explore how limits are used to define the concept of **continuity** a property closely tied to the **derivative** and essential for understanding smoothness of functions.  But first, we will explore the **algebraic interpretation** of limits.
