+++
title = '5.1 Pcractice'
weight = 2
+++

---

#### Ex1.
A particle moves along a straight line with its position at time $ t $ given by the function:

\[
 s(t) = t^3 - 6t^2 + 9t + 2
\]

Find:
- The velocity function $ v(t) $.
- The acceleration function $ a(t) $.
- The time(s) when the particle is at rest.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Compute the velocity function:

\[
   v(t) = s'(t) = 3t^2 - 12t + 9
\]

2. Compute the acceleration function:

\[
   a(t) = v'(t) = 6t - 12
\]

3. Find when the particle is at rest by solving $ v(t) = 0 $:

\[
   3t^2 - 12t + 9 = 0
\]

   Factor:

\[
   3(t - 3)(t - 1) = 0
\]

\[
   t = 1, 3
\]
   
Thus, the particle is at rest at $ t = 1 $ and $ t = 3 $.

</details>

---

#### Ex2.
A ball is thrown vertically with an initial velocity of $ 20 \text{ m/s} $. Its height at time $ t $ is given by:

\[
 h(t) = 20t - 5t^2
\]

Find:
- The velocity function $ v(t) $.
- The acceleration function $ a(t) $.
- The time when the ball reaches its highest point.
- The maximum height.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Compute the velocity function:

\[
   v(t) = h'(t) = 20 - 10t
\]

2. Compute the acceleration function:

\[
   a(t) = v'(t) = -10
\]

3. The highest point is when $ v(t) = 0 $:

\[
   20 - 10t = 0
\]

\[
   t = 2 \text{ seconds}
\]

4. Find the maximum height by evaluating $ h(2) $:

\[
   h(2) = 20(2) - 5(2)^2 = 40 - 20 = 20 \text{ m}
\]
   
Thus, the ball reaches its highest point at $ t = 2 $ sec, with a maximum height of $ 20 $ m.

</details>

---

#### Ex3.
A car moves along a straight road with its velocity given by:

\[
 v(t) = 6t - 18
\]

Find:
- The time when the car comes to a stop.
- The time intervals when the car moves forward or backward.
- The change in velocity from $ t = 0 $ to $ t = 5 $.

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Find when the car stops by solving $ v(t) = 0 $:

\[
   6t - 18 = 0
\]

\[
   t = 3 \text{ seconds}
\]

2. Determine motion direction:
   - If $ v(t) > 0 $, the car moves forward.
   - If $ v(t) < 0 $, the car moves backward.
   - Analyze $ v(t) = 6t - 18 $:
     - For $ 0 \leq t < 3 $, $ v(t) < 0 $ (moving backward).
     - For $ t > 3 $, $ v(t) > 0 $ (moving forward).

3. Compute the change in velocity from $ t = 0 $ to $ t = 5 $:

\[
   v(5) - v(0)
\]

\[
   (6(5) - 18) - (6(0) - 18)
\]

\[
   (30 - 18) - (0 - 18)
\]

\[
   12 + 18 = 30
\]
   
Thus, the car stops at $ t = 3 $ sec, moves backward for $ 0 \leq t < 3 $, and moves forward for $ t > 3 $. The change in velocity from $ t = 0 $ to $ t = 5 $ is $ 30 $ m/s.

</details>


<iframe src="https://script.google.com/macros/s/AKfycbzcuRpYzGlg9agiWzxXmwz9wOH3MeJDybpNW4Oll0kXe_A3_BNLkntrUiZ3sMPX8aK-/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>


