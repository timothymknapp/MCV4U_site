+++
title = "5.1 Examples"
weight = 1
+++

## Example Question: Analyzing Motion Using Derivatives

#### Problem Statement:
The position of an object moving along a straight line is given by the function:
$$
s(t) = t^3 - 6t^2 + 9t + 4 \quad \text{(in meters)},
$$
where $ t $ is the time in seconds ($ t \geq 0 $).

1. **Find the velocity and acceleration at $ t = 2 $ seconds.**
2. **At what time(s) is the object at a position of $ s(t) = 10 $ meters?**
3. **At what time(s) is the velocity of the object equal to $ v(t) = 0 $ m/s?**
4. **At what time(s) is the acceleration of the object equal to $ a(t) = 6 $ m/s²?**

---

#### Solution:

##### Step 1: Recall the relationships between position, velocity, and acceleration.
- Velocity is the first derivative of position:  
  $$
  v(t) = \frac{ds}{dt}.
  $$
- Acceleration is the second derivative of position (or the first derivative of velocity):  
  $$
  a(t) = \frac{dv}{dt} = \frac{d^2s}{dt^2}.
  $$

##### Step 2: Compute the derivatives.
Given $ s(t) = t^3 - 6t^2 + 9t + 4 $:
1. **Velocity**:  
   Differentiate $ s(t) $ with respect to $ t $:  
   $$
   v(t) = \frac{ds}{dt} = 3t^2 - 12t + 9.
   $$

2. **Acceleration**:  
   Differentiate $ v(t) $ with respect to $ t $:  
   $$
   a(t) = \frac{dv}{dt} = 6t - 12.
   $$

##### Step 3: Solve each part of the problem.

---

**Part 1: Find the velocity and acceleration at $ t = 2 $ seconds.**

- **Velocity at $ t = 2 $:**  
  Substitute $ t = 2 $ into $ v(t) = 3t^2 - 12t + 9 $:  
  $$
  v(2) = 3(2)^2 - 12(2) + 9 = 3(4) - 24 + 9 = 12 - 24 + 9 = -3 \, \text{m/s}.
  $$

- **Acceleration at $ t = 2 $:**  
  Substitute $ t = 2 $ into $ a(t) = 6t - 12 $:  
  $$
  a(2) = 6(2) - 12 = 12 - 12 = 0 \, \text{m/s}^2.
  $$

**Answer for Part 1:**  
At $ t = 2 $ seconds:  
- Velocity: $ v(2) = -3 \, \text{m/s} $.  
- Acceleration: $ a(2) = 0 \, \text{m/s}^2 $.

---

**Part 2: At what time(s) is the object at a position of $ s(t) = 10 $ meters?**

Set $ s(t) = 10 $:  
$$
t^3 - 6t^2 + 9t + 4 = 10.
$$
Simplify:  
$$
t^3 - 6t^2 + 9t - 6 = 0.
$$

Factorize the cubic equation. Use synthetic division or trial-and-error to find roots:  
- Testing $ t = 1 $:  
  $$
  (1)^3 - 6(1)^2 + 9(1) - 6 = 1 - 6 + 9 - 6 = -2 \neq 0.
  $$
- Testing $ t = 2 $:  
  $$
  (2)^3 - 6(2)^2 + 9(2) - 6 = 8 - 24 + 18 - 6 = -4 \neq 0.
  $$
- Testing $ t = 3 $:  
  $$
  (3)^3 - 6(3)^2 + 9(3) - 6 = 27 - 54 + 27 - 6 = 0.
  $$

Thus, $ t = 3 $ is a root. Factor out $ (t - 3) $:  
$$
t^3 - 6t^2 + 9t - 6 = (t - 3)(t^2 - 3t + 2).
$$

Factor further:  
$$
t^2 - 3t + 2 = (t - 1)(t - 2).
$$

So, the full factorization is:  
$$
t^3 - 6t^2 + 9t - 6 = (t - 3)(t - 1)(t - 2).
$$

**Answer for Part 2:**  
The object is at $ s(t) = 10 $ meters at times:  
$$
t = 1 \, \text{s}, \, t = 2 \, \text{s}, \, t = 3 \, \text{s}.
$$

---

**Part 3: At what time(s) is the velocity of the object equal to $ v(t) = 0 $ m/s?**

Set $ v(t) = 0 $:  
$$
3t^2 - 12t + 9 = 0.
$$
Divide through by 3:  
$$
t^2 - 4t + 3 = 0.
$$

Factorize:  
$$
t^2 - 4t + 3 = (t - 1)(t - 3).
$$

**Answer for Part 3:**  
The velocity is zero at times:  
$$
t = 1 \, \text{s}, \, t = 3 \, \text{s}.
$$

---

**Part 4: At what time(s) is the acceleration of the object equal to $ a(t) = 6 $ m/s²?**

Set $ a(t) = 6 $:  
$$
6t - 12 = 6.
$$
Solve for $ t $:  
$$
6t = 18 \quad \Rightarrow \quad t = 3 \, \text{s}.
$$

**Answer for Part 4:**  
The acceleration is $ 6 \, \text{m/s}^2 $ at time:  
$$
t = 3 \, \text{s}.
$$

---

### Final Summary of Answers:
1. At $ t = 2 $:  
   - Velocity: $ v(2) = -3 \, \text{m/s} $.  
   - Acceleration: $ a(2) = 0 \, \text{m/s}^2 $.  

2. The object is at $ s(t) = 10 $ meters at times:  
   $$
   t = 1 \, \text{s}, \, t = 2 \, \text{s}, \, t = 3 \, \text{s}.
   $$

3. The velocity is zero at times:  
   $$
   t = 1 \, \text{s}, \, t = 3 \, \text{s}.
   $$

4. The acceleration is $ 6 \, \text{m/s}^2 $ at time:  
   $$
   t = 3 \, \text{s}.
   $$


---
---

## Example Question 2: Analyzing Motion with a Rational Position Function

#### Problem Statement:
The position of an object moving along a straight line is given by the function:
$$
s(t) = \frac{t^2 - 4t + 3}{t + 1} \quad \text{(in meters)},
$$
where $ t $ is the time in seconds ($ t \geq 0 $).

1. **Find the velocity and acceleration at $ t = 2 $ seconds.**
2. **At what time(s) is the object at a position of $ s(t) = 0 $ meters?**
3. **At what time(s) is the velocity of the object equal to $ v(t) = 0 $ m/s?**
4. **At what time(s) is the acceleration of the object equal to $ a(t) = 0 $ m/s²?**

---

#### Solution:

##### Step 1: Recall the relationships between position, velocity, and acceleration.
- Velocity is the first derivative of position:  
  $$
  v(t) = \frac{ds}{dt}.
  $$
- Acceleration is the second derivative of position (or the first derivative of velocity):  
  $$
  a(t) = \frac{dv}{dt} = \frac{d^2s}{dt^2}.
  $$

##### Step 2: Compute the derivatives.
Given $ s(t) = \frac{t^2 - 4t + 3}{t + 1} $, use the **quotient rule** to find $ v(t) $. The quotient rule states:
$$
\frac{d}{dt} \left( \frac{u}{v} \right) = \frac{v \cdot u' - u \cdot v'}{v^2}.
$$
Here:
- $ u = t^2 - 4t + 3 $, so $ u' = 2t - 4 $,
- $ v = t + 1 $, so $ v' = 1 $.

Using the quotient rule:
$$
v(t) = \frac{(t + 1)(2t - 4) - (t^2 - 4t + 3)(1)}{(t + 1)^2}.
$$
Simplify the numerator:
$$
(t + 1)(2t - 4) = 2t^2 - 4t + 2t - 4 = 2t^2 - 2t - 4,
$$
and
$$
(t^2 - 4t + 3)(1) = t^2 - 4t + 3.
$$
Thus:
$$
v(t) = \frac{(2t^2 - 2t - 4) - (t^2 - 4t + 3)}{(t + 1)^2}.
$$
Simplify further:
$$
v(t) = \frac{2t^2 - 2t - 4 - t^2 + 4t - 3}{(t + 1)^2} = \frac{t^2 + 2t - 7}{(t + 1)^2}.
$$

Now compute $ a(t) $ by differentiating $ v(t) $ again. Using the quotient rule on $ v(t) $:
$$
a(t) = \frac{(t + 1)^2 \cdot (2t + 2) - (t^2 + 2t - 7) \cdot 2(t + 1)}{(t + 1)^4}.
$$
Factor out $ (t + 1) $ from the numerator:
$$
a(t) = \frac{(t + 1) \big[ (t + 1)(2t + 2) - 2(t^2 + 2t - 7) \big]}{(t + 1)^4}.
$$
Cancel one $ (t + 1) $ term:
$$
a(t) = \frac{(t + 1)(2t + 2) - 2(t^2 + 2t - 7)}{(t + 1)^3}.
$$
Expand the numerator:
$$
(t + 1)(2t + 2) = 2t^2 + 2t + 2t + 2 = 2t^2 + 4t + 2,
$$
and
$$
2(t^2 + 2t - 7) = 2t^2 + 4t - 14.
$$
Thus:
$$
a(t) = \frac{(2t^2 + 4t + 2) - (2t^2 + 4t - 14)}{(t + 1)^3}.
$$
Simplify:
$$
a(t) = \frac{2t^2 + 4t + 2 - 2t^2 - 4t + 14}{(t + 1)^3} = \frac{16}{(t + 1)^3}.
$$

##### Step 3: Solve each part of the problem.

---

**Part 1: Find the velocity and acceleration at $ t = 2 $ seconds.**

- **Velocity at $ t = 2 $:**  
  Substitute $ t = 2 $ into $ v(t) = \frac{t^2 + 2t - 7}{(t + 1)^2} $:  
  $$
  v(2) = \frac{(2)^2 + 2(2) - 7}{(2 + 1)^2} = \frac{4 + 4 - 7}{9} = \frac{1}{9} \, \text{m/s}.
  $$

- **Acceleration at $ t = 2 $:**  
  Substitute $ t = 2 $ into $ a(t) = \frac{16}{(t + 1)^3} $:  
  $$
  a(2) = \frac{16}{(2 + 1)^3} = \frac{16}{27} \, \text{m/s}^2.
  $$

**Answer for Part 1:**  
At $ t = 2 $ seconds:  
- Velocity: $ v(2) = \frac{1}{9} \, \text{m/s} $.  
- Acceleration: $ a(2) = \frac{16}{27} \, \text{m/s}^2 $.

---

**Part 2: At what time(s) is the object at a position of $ s(t) = 0 $ meters?**

Set $ s(t) = 0 $:  
$$
\frac{t^2 - 4t + 3}{t + 1} = 0.
$$
For a fraction to be zero, the numerator must be zero:
$$
t^2 - 4t + 3 = 0.
$$
Factorize:
$$
t^2 - 4t + 3 = (t - 1)(t - 3).
$$

**Answer for Part 2:**  
The object is at $ s(t) = 0 $ meters at times:  
$$
t = 1 \, \text{s}, \, t = 3 \, \text{s}.
$$

---

**Part 3: At what time(s) is the velocity of the object equal to $ v(t) = 0 $ m/s?**

Set $ v(t) = 0 $:  
$$
\frac{t^2 + 2t - 7}{(t + 1)^2} = 0.
$$
For a fraction to be zero, the numerator must be zero:
$$
t^2 + 2t - 7 = 0.
$$
Use the quadratic formula:
$$
t = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}, \quad a = 1, b = 2, c = -7.
$$
$$
t = \frac{-2 \pm \sqrt{2^2 - 4(1)(-7)}}{2(1)} = \frac{-2 \pm \sqrt{4 + 28}}{2} = \frac{-2 \pm \sqrt{32}}{2} = \frac{-2 \pm 4\sqrt{2}}{2} = -1 \pm 2\sqrt{2}.
$$

Since $ t \geq 0 $, we take the positive root:
$$
t = -1 + 2\sqrt{2}.
$$

**Answer for Part 3:**  
The velocity is zero at time:  
$$
t = -1 + 2\sqrt{2} \, \text{s}.
$$

---

**Part 4: At what time(s) is the acceleration of the object equal to $ a(t) = 0 $ m/s²?**

Set $ a(t) = 0 $:  
$$
\frac{16}{(t + 1)^3} = 0.
$$
The numerator is always 16, so $ a(t) \neq 0 $ for any $ t $.

**Answer for Part 4:**  
There is no time when the acceleration is zero.

---

### Final Summary of Answers:
1. At $ t = 2 $:  
   - Velocity: $ v(2) = \frac{1}{9} \, \text{m/s} $.  
   - Acceleration: $ a(2) = \frac{16}{27} \, \text{m/s}^2 $.  

2. The object is at $ s(t) = 0 $ meters at times:  
   $$
   t = 1 \, \text{s}, \, t = 3 \, \text{s}.
   $$

3. The velocity is zero at time:  
   $$
   t = -1 + 2\sqrt{2} \, \text{s}.
   $$

4. There is no time when the acceleration is zero.