+++
title = '3.1 Trigonometric Derivatives'
weight = 1
+++


In this section, we will explore how to compute the derivatives of common trigonometric functions such as sine, cosine, tangent, cotangent, secant, and cosecant.

---

## Table of Contents
1. [Basic Derivative Rules](#basic-derivative-rules)
2. [Derivatives of Sine and Cosine](#derivatives-of-sine-and-cosine)
3. [Derivatives of Tangent and Cotangent](#derivatives-of-tangent-and-cotangent)
4. [Derivatives of Secant and Cosecant](#derivatives-of-secant-and-cosecant)


---

## Basic Derivative Rules

Before diving into trigonometric derivatives, let's recall some basic derivative rules:
- The derivative of a constant is zero: $$ \frac{d}{dx}[c] = 0 $$
- The power rule: $$ \frac{d}{dx}[x^n] = n x^{n-1} $$
- The chain rule: $$ \frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x) $$

---

## Derivatives of Sine and Cosine

The derivatives of the sine and cosine functions are fundamental in calculus:

$$
\frac{d}{dx}[\sin(x)] = \cos(x)
$$

$$
\frac{d}{dx}[\cos(x)] = -\sin(x)
$$

<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( sin(x) \) </strong>
  </summary>


To prove that the derivative of $ \sin(x) $ is $ \cos(x) $, we will use the **limit definition of the derivative**:

$$
f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
$$

For $$ f(x) = \sin(x) $$, this becomes:

$$
\frac{d}{dx}[\sin(x)] = \lim_{h \to 0} \frac{\sin(x+h) - \sin(x)}{h}
$$

### Step 1: Expand $$ \sin(x+h) $$ using the angle addition formula
Using the trigonometric identity for the sine of a sum:

$$
\sin(x+h) = \sin(x)\cos(h) + \cos(x)\sin(h)
$$

Substitute this into the limit expression:

$$
\frac{d}{dx}[\sin(x)] = \lim_{h \to 0} \frac{\sin(x)\cos(h) + \cos(x)\sin(h) - \sin(x)}{h}
$$

### Step 2: Simplify the numerator
Factor out $ \sin(x) $ from the terms involving $ \sin(x) $:

$$
\frac{d}{dx}[\sin(x)] = \lim_{h \to 0} \frac{\sin(x)(\cos(h) - 1) + \cos(x)\sin(h)}{h}
$$

This can be split into two separate limits:

$$
\frac{d}{dx}[\sin(x)] = \lim_{h \to 0} \left[ \sin(x) \cdot \frac{\cos(h) - 1}{h} \right] + \lim_{h \to 0} \left[ \cos(x) \cdot \frac{\sin(h)}{h} \right]
$$

### Step 3: Evaluate the limits
#### Limit 1: $$ \lim_{h \to 0} \frac{\cos(h) - 1}{h} $$
Using the small-angle approximation or L'Hôpital's Rule, it can be shown that:

$$
\lim_{h \to 0} \frac{\cos(h) - 1}{h} = 0
$$

#### Limit 2: $$ \lim_{h \to 0} \frac{\sin(h)}{h} $$
It is a well-known result in calculus that:

$$
\lim_{h \to 0} \frac{\sin(h)}{h} = 1
$$

### Step 4: Substitute the results back
Now substitute these results into the original equation:

$$
\frac{d}{dx}[\sin(x)] = \sin(x) \cdot 0 + \cos(x) \cdot 1
$$

Simplify:

$$
\frac{d}{dx}[\sin(x)] = \cos(x)
$$

---

## Conclusion

We have proven that the derivative of $$ \sin(x) $$ is $$ \cos(x) $$. This result is fundamental in calculus and is used extensively in various applications.

$$
\boxed{\frac{d}{dx}[\sin(x)] = \cos(x)}
$$

</details>

<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( cos(x) \) </strong>
  </summary>


We know from the complound angle formulas:

$$
\cos(x) = \sin\left(\frac{\pi}{2} - x\right)
$$

Using the chain rule and the derivative of $ \sin(x) $, we can compute the derivative of $ \cos(x) $.

### Step 1: Apply the chain rule
Let $ u = \frac{\pi}{2} - x $. Then $ \cos(x) = \sin(u) $, and by the chain rule:

$$
\frac{d}{dx}[\cos(x)] = \frac{d}{du}[\sin(u)] \cdot \frac{du}{dx}
$$

From the derivative of $ \sin(u) $, we know:

$$
\frac{d}{du}[\sin(u)] = \cos(u)
$$

And since $ u = \frac{\pi}{2} - x $, we have:

$$
\frac{du}{dx} = \frac{d}{dx}\left(\frac{\pi}{2} - x\right) = -1
$$

Substitute these into the chain rule expression:

$$
\frac{d}{dx}[\cos(x)] = \cos(u) \cdot (-1)
$$

### Step 2: Substitute back $ u = \frac{\pi}{2} - x $
Recall that $ u = \frac{\pi}{2} - x $. Therefore:

$$
\cos(u) = \cos\left(\frac{\pi}{2} - x\right)
$$

Using the co-function identity $ \cos\left(\frac{\pi}{2} - x\right) = \sin(x) $, we get:

$$
\frac{d}{dx}[\cos(x)] = \sin(x) \cdot (-1)
$$

Simplify:

$$
\frac{d}{dx}[\cos(x)] = -\sin(x)
$$

---

## Conclusion

We have proven that the derivative of $ \cos(x) $ is $ -\sin(x) $. This result aligns with the fundamental derivatives of trigonometric functions.

$$
\boxed{\frac{d}{dx}[\cos(x)] = -\sin(x)}
$$



</details>


---

## Derivatives of Tangent and Cotangent

The tangent and cotangent functions have the following derivatives:

$$
\frac{d}{dx}[\tan(x)] = \sec^2(x)
$$

$$
\frac{d}{dx}[\cot(x)] = -\csc^2(x)
$$

<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( tan(x) \) </strong>
  </summary>


The tangent function is defined as:

$$
\tan(x) = \frac{\sin(x)}{\cos(x)}
$$

To find the derivative, we apply the **quotient rule**, which states:

$$
\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}
$$

Here:
- $ f(x) = \sin(x) $, so $ f'(x) = \cos(x) $
- $ g(x) = \cos(x) $, so $ g'(x) = -\sin(x) $

### Step 1: Apply the quotient rule
Substitute $ f(x) $, $ f'(x) $, $ g(x) $, and $ g'(x) $ into the quotient rule formula:

$$
\frac{d}{dx}[\tan(x)] = \frac{\cos(x)\cos(x) - \sin(x)(-\sin(x))}{[\cos(x)]^2}
$$

Simplify the numerator:

$$
\frac{d}{dx}[\tan(x)] = \frac{\cos^2(x) + \sin^2(x)}{\cos^2(x)}
$$

### Step 2: Use the Pythagorean identity
Recall the Pythagorean identity:

$$
\cos^2(x) + \sin^2(x) = 1
$$

Substitute this into the expression:

$$
\frac{d}{dx}[\tan(x)] = \frac{1}{\cos^2(x)}
$$

### Step 3: Simplify using a trigonometric identity
The reciprocal of $ \cos^2(x) $ is $ \sec^2(x) $. Therefore:

$$
\frac{d}{dx}[\tan(x)] = \sec^2(x)
$$

---

## Conclusion

We have proven that the derivative of $ \tan(x) $ is $ \sec^2(x) $.

$$
\boxed{\frac{d}{dx}[\tan(x)] = \sec^2(x)}
$$




</details>

<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( cot(x) \) </strong>
  </summary>

## Proof of the Derivative of $ \cot(x) $

The cotangent function is defined as:

$$
\cot(x) = \frac{\cos(x)}{\sin(x)}
$$

To find the derivative, we apply the **quotient rule**, which states:

$$
\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}
$$

Here:
- $ f(x) = \cos(x) $, so $ f'(x) = -\sin(x) $
- $ g(x) = \sin(x) $, so $ g'(x) = \cos(x) $

### Step 1: Apply the quotient rule
Substitute $ f(x) $, $ f'(x) $, $ g(x) $, and $ g'(x) $ into the quotient rule formula:

$$
\frac{d}{dx}[\cot(x)] = \frac{(-\sin(x))\sin(x) - \cos(x)\cos(x)}{[\sin(x)]^2}
$$

Simplify the numerator:

$$
\frac{d}{dx}[\cot(x)] = \frac{-\sin^2(x) - \cos^2(x)}{\sin^2(x)}
$$

### Step 2: Use the Pythagorean identity
Recall the Pythagorean identity:

$$
\sin^2(x) + \cos^2(x) = 1
$$

Thus:

$$
-\sin^2(x) - \cos^2(x) = -1
$$

Substitute this into the expression:

$$
\frac{d}{dx}[\cot(x)] = \frac{-1}{\sin^2(x)}
$$

### Step 3: Simplify using a trigonometric identity
The reciprocal of $ \sin^2(x) $ is $ \csc^2(x) $. Therefore:

$$
\frac{d}{dx}[\cot(x)] = -\csc^2(x)
$$

---

## Conclusion

We have proven that the derivative of $ \cot(x) $ is $ -\csc^2(x) $.

$$
\boxed{\frac{d}{dx}[\cot(x)] = -\csc^2(x)}
$$




</details>

---

## Derivatives of Secant and Cosecant

The secant and cosecant functions have the following derivatives:

$$
\frac{d}{dx}[\sec(x)] = \sec(x) \tan(x)
$$

$$
\frac{d}{dx}[\csc(x)] = -\csc(x) \cot(x)
$$



<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( sec(x) \) </strong>
  </summary>

## Proof of the Derivative of $ \sec(x) $

The secant function is defined as:

$$
\sec(x) = \frac{1}{\cos(x)}
$$

To find the derivative, we can rewrite it as:

$$
\sec(x) = (\cos(x))^{-1}
$$

Now, we apply the **chain rule**. Recall that the derivative of $ u^{-1} $ is $ -u^{-2} \cdot u' $.

### Step 1: Apply the chain rule
Let $ u = \cos(x) $, so $ \sec(x) = u^{-1} $. Then:

$$
\frac{d}{dx}[\sec(x)] = \frac{d}{du}[u^{-1}] \cdot \frac{du}{dx}
$$

The derivative of $ u^{-1} $ is:

$$
\frac{d}{du}[u^{-1}] = -u^{-2}
$$

And since $ u = \cos(x) $, we have:

$$
\frac{du}{dx} = \frac{d}{dx}[\cos(x)] = -\sin(x)
$$

Substitute these into the chain rule expression:

$$
\frac{d}{dx}[\sec(x)] = -(\cos(x))^{-2} \cdot (-\sin(x))
$$

Simplify:

$$
\frac{d}{dx}[\sec(x)] = \frac{\sin(x)}{\cos^2(x)}
$$

### Step 2: Rewrite using trigonometric identities
Recall that $ \sec(x) = \frac{1}{\cos(x)} $ and $ \tan(x) = \frac{\sin(x)}{\cos(x)} $. Therefore:

$$
\frac{\sin(x)}{\cos^2(x)} = \sec(x)\tan(x)
$$

Thus:

$$
\frac{d}{dx}[\sec(x)] = \sec(x)\tan(x)
$$

---

## Conclusion

We have proven that the derivative of $ \sec(x) $ is $ \sec(x)\tan(x) $.

$$
\boxed{\frac{d}{dx}[\sec(x)] = \sec(x)\tan(x)}
$$


</details>

<details>
  <summary>
    <strong id="solution-title">Proof of the derivative of \( csc(x) \) </strong>
  </summary>

## Proof of the Derivative of $ \csc(x) $

The cosecant function is defined as:

$$
\csc(x) = \frac{1}{\sin(x)}
$$

To find the derivative, we can rewrite it as:

$$
\csc(x) = (\sin(x))^{-1}
$$

Now, we apply the **chain rule**. Recall that the derivative of $ u^{-1} $ is $ -u^{-2} \cdot u' $.

### Step 1: Apply the chain rule
Let $ u = \sin(x) $, so $ \csc(x) = u^{-1} $. Then:

$$
\frac{d}{dx}[\csc(x)] = \frac{d}{du}[u^{-1}] \cdot \frac{du}{dx}
$$

The derivative of $ u^{-1} $ is:

$$
\frac{d}{du}[u^{-1}] = -u^{-2}
$$

And since $ u = \sin(x) $, we have:

$$
\frac{du}{dx} = \frac{d}{dx}[\sin(x)] = \cos(x)
$$

Substitute these into the chain rule expression:

$$
\frac{d}{dx}[\csc(x)] = -(\sin(x))^{-2} \cdot \cos(x)
$$

Simplify:

$$
\frac{d}{dx}[\csc(x)] = -\frac{\cos(x)}{\sin^2(x)}
$$

### Step 2: Rewrite using trigonometric identities
Recall that $ \csc(x) = \frac{1}{\sin(x)} $ and $ \cot(x) = \frac{\cos(x)}{\sin(x)} $. Therefore:

$$
-\frac{\cos(x)}{\sin^2(x)} = -\csc(x)\cot(x)
$$

Thus:

$$
\frac{d}{dx}[\csc(x)] = -\csc(x)\cot(x)
$$

---

## Conclusion

We have proven that the derivative of $ \csc(x) $ is $ -\csc(x)\cot(x) $.

$$
\boxed{\frac{d}{dx}[\csc(x)] = -\csc(x)\cot(x)}
$$

</details>

---


In this lesson, we learned the derivatives of the six primary trigonometric functions: sine, cosine, tangent, cotangent, secant, and cosecant. These derivatives are essential tools in calculus and are widely used in physics, engineering, and other fields, move on tot he next section to see some solved exampels of trigonometric derivatives.

---