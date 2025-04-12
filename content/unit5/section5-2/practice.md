+++
title = '5.2 Practice'
weight = 2
+++

---

#### Ex1.
A conical tank with a radius of $ 4 \, \text{m} $ and a height of $ 10 \, \text{m} $ is being filled with water at a rate of $ 2 \, \text{m}^3/\text{min} $. How fast is the water level rising when the water is $ 5 \, \text{m} $ deep?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Relate the variables using similar triangles:
   The radius $ r $ and height $ h $ of the water are proportional:
   $$
   \frac{r}{h} = \frac{4}{10} = \frac{2}{5}.
   $$
   Thus:
   $$
   r = \frac{2}{5}h.
   $$

2. Write the volume formula for a cone:
   $$
   V = \frac{1}{3} \pi r^2 h.
   $$
   Substitute $ r = \frac{2}{5}h $:
   $$
   V = \frac{1}{3} \pi \left(\frac{2}{5}h\right)^2 h = \frac{1}{3} \pi \cdot \frac{4}{25} h^3 = \frac{4}{75} \pi h^3.
   $$

3. Differentiate with respect to time:
   $$
   \frac{dV}{dt} = \frac{4}{75} \pi \cdot 3h^2 \frac{dh}{dt}.
   $$
   Simplify:
   $$
   \frac{dV}{dt} = \frac{4}{25} \pi h^2 \frac{dh}{dt}.
   $$

4. Solve for $ \frac{dh}{dt} $:
   $$
   \frac{dh}{dt} = \frac{\frac{dV}{dt}}{\frac{4}{25} \pi h^2}.
   $$

5. Substitute known values ($ \frac{dV}{dt} = 2 $, $ h = 5 $):
   $$
   \frac{dh}{dt} = \frac{2}{\frac{4}{25} \pi (5)^2} = \frac{2}{\frac{4}{25} \pi (25)} = \frac{2}{4 \pi} = \frac{1}{2 \pi} \, \text{m/min}.
   $$

Thus, the water level is rising at a rate of:
$$
\boxed{\frac{1}{2 \pi} \, \text{m/min} \, \text{(or approximately } 0.159 \, \text{m/min)}}.
$$

</details>

---

#### Ex2.
A spherical balloon is being inflated at a rate of $ 8 \, \text{cm}^3/\text{s} $. How fast is the radius increasing when the radius is $ 6 \, \text{cm} $?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Write the volume formula for a sphere:
   $$
   V = \frac{4}{3} \pi r^3.
   $$

2. Differentiate with respect to time:
   $$
   \frac{dV}{dt} = 4 \pi r^2 \frac{dr}{dt}.
   $$

3. Solve for $ \frac{dr}{dt} $:
   $$
   \frac{dr}{dt} = \frac{\frac{dV}{dt}}{4 \pi r^2}.
   $$

4. Substitute known values ($ \frac{dV}{dt} = 8 $, $ r = 6 $):
   $$
   \frac{dr}{dt} = \frac{8}{4 \pi (6)^2} = \frac{8}{4 \pi (36)} = \frac{8}{144 \pi} = \frac{1}{18 \pi} \, \text{cm/s}.
   $$

Thus, the radius is increasing at a rate of:
$$
\boxed{\frac{1}{18 \pi} \, \text{cm/s} \, \text{(or approximately } 0.0177 \, \text{cm/s)}}.
$$

</details>

---

#### Ex3.
A ladder $ 13 \, \text{ft} $ long leans against a vertical wall. If the bottom of the ladder slides away from the wall at $ 2 \, \text{ft/s} $, how fast is the top of the ladder sliding down the wall when the bottom is $ 5 \, \text{ft} $ from the wall?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Relate the variables using the Pythagorean theorem:
   $$
   x^2 + y^2 = 13^2.
   $$

2. Differentiate with respect to time:
   $$
   2x \frac{dx}{dt} + 2y \frac{dy}{dt} = 0.
   $$
   Simplify:
   $$
   x \frac{dx}{dt} + y \frac{dy}{dt} = 0.
   $$

3. Solve for $ \frac{dy}{dt} $:
   $$
   \frac{dy}{dt} = -\frac{x}{y} \frac{dx}{dt}.
   $$

4. Find $ y $ when $ x = 5 $:
   $$
   x^2 + y^2 = 169 \quad \Rightarrow \quad 5^2 + y^2 = 169 \quad \Rightarrow \quad y^2 = 144 \quad \Rightarrow \quad y = 12.
   $$

5. Substitute known values ($ x = 5 $, $ y = 12 $, $ \frac{dx}{dt} = 2 $):
   $$
   \frac{dy}{dt} = -\frac{5}{12}(2) = -\frac{10}{12} = -\frac{5}{6} \, \text{ft/s}.
   $$

Thus, the top of the ladder is sliding down the wall at a rate of:
$$
\boxed{-\frac{5}{6} \, \text{ft/s}}.
$$

</details>

---

#### Ex4.
A car is traveling west toward an intersection at $ 30 \, \text{mph} $, while another car is traveling north away from the intersection at $ 40 \, \text{mph} $. At a certain moment, the first car is $ 0.4 \, \text{mi} $ east of the intersection, and the second car is $ 0.3 \, \text{mi} $ north of the intersection. How fast is the distance between the two cars changing at that moment?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Let $ x $ be the distance of the first car from the intersection, $ y $ be the distance of the second car from the intersection, and $ z $ be the distance between the two cars. By the Pythagorean theorem:
   $$
   z^2 = x^2 + y^2.
   $$

2. Differentiate with respect to time:
   $$
   2z \frac{dz}{dt} = 2x \frac{dx}{dt} + 2y \frac{dy}{dt}.
   $$
   Simplify:
   $$
   z \frac{dz}{dt} = x \frac{dx}{dt} + y \frac{dy}{dt}.
   $$

3. Find $ z $ when $ x = 0.4 $ and $ y = 0.3 $:
   $$
   z = \sqrt{x^2 + y^2} = \sqrt{(0.4)^2 + (0.3)^2} = \sqrt{0.16 + 0.09} = \sqrt{0.25} = 0.5 \, \text{mi}.
   $$

4. Substitute known values ($ x = 0.4 $, $ y = 0.3 $, $ z = 0.5 $, $ \frac{dx}{dt} = -30 $, $ \frac{dy}{dt} = 40 $):
   $$
   0.5 \frac{dz}{dt} = (0.4)(-30) + (0.3)(40).
   $$
   Simplify:
   $$
   0.5 \frac{dz}{dt} = -12 + 12 = 0.
   $$

5. Solve for $ \frac{dz}{dt} $:
   $$
   \frac{dz}{dt} = \frac{0}{0.5} = 0 \, \text{mph}.
   $$

Thus, the distance between the two cars is not changing at this moment:
$$
\boxed{0 \, \text{mph}}.
$$

</details>


<iframe src="https://script.google.com/macros/s/AKfycbydsx0H6Fl-1xexIcXc0BjuEE007lfP3-upntG7g3F5UDqgWhxei3QCxS2lLwJ3TvtF/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

