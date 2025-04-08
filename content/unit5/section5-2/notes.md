+++
title = "5.2 Examples"
weight = 1
+++

## Example Question: Related Rates - Expanding Balloon

#### Problem Statement:
A spherical balloon is being inflated at a constant rate of $ 8 \, \text{cm}^3/\text{s} $. At what rate is the radius of the balloon increasing when the radius is $ 6 \, \text{cm} $?

---

#### Solution:

##### Step 1: Understand the problem and identify known quantities.
- The volume of a sphere is given by the formula:
  $$
  V = \frac{4}{3} \pi r^3,
  $$
  where $ V $ is the volume and $ r $ is the radius.
- We are given:
  - The rate of change of volume: $ \frac{dV}{dt} = 8 \, \text{cm}^3/\text{s} $.
  - The radius at the moment of interest: $ r = 6 \, \text{cm} $.
- We need to find:
  - The rate of change of the radius: $ \frac{dr}{dt} $.

##### Step 2: Differentiate the volume formula with respect to time.
Using implicit differentiation on $ V = \frac{4}{3} \pi r^3 $, we get:
$$
\frac{dV}{dt} = 4 \pi r^2 \frac{dr}{dt}.
$$

##### Step 3: Solve for $ \frac{dr}{dt} $.
Rearrange the equation to isolate $ \frac{dr}{dt} $:
$$
\frac{dr}{dt} = \frac{\frac{dV}{dt}}{4 \pi r^2}.
$$

##### Step 4: Substitute the known values.
Substitute $ \frac{dV}{dt} = 8 \, \text{cm}^3/\text{s} $ and $ r = 6 \, \text{cm} $ into the equation:
$$
\frac{dr}{dt} = \frac{8}{4 \pi (6)^2}.
$$
Simplify:
$$
\frac{dr}{dt} = \frac{8}{4 \pi (36)} = \frac{8}{144 \pi} = \frac{1}{18 \pi} \, \text{cm/s}.
$$

##### Step 5: Interpret the result.
The radius of the balloon is increasing at a rate of:
$$
\frac{dr}{dt} = \frac{1}{18 \pi} \, \text{cm/s}.
$$
Numerically, this is approximately:
$$
\frac{dr}{dt} \approx 0.0177 \, \text{cm/s}.
$$

---

### Final Answer:
When the radius of the balloon is $ 6 \, \text{cm} $, the radius is increasing at a rate of:
$$
\boxed{\frac{1}{18 \pi} \, \text{cm/s} \, \text{(or approximately } 0.0177 \, \text{cm/s)}}.
$$

---

# Example Question 2: Related Rates - Sliding Ladder

#### Problem Statement:
A 10-foot ladder is leaning against a vertical wall. The bottom of the ladder is being pulled away from the wall at a constant rate of $ 2 \, \text{ft/s} $. How fast is the top of the ladder sliding down the wall when the bottom of the ladder is $ 6 \, \text{ft} $ away from the wall?

---

#### Solution:

##### Step 1: Understand the problem and identify known quantities.
- The ladder, wall, and ground form a right triangle. Let:
  - $ x $ = distance from the bottom of the ladder to the wall (horizontal leg),
  - $ y $ = height of the top of the ladder on the wall (vertical leg),
  - $ L = 10 \, \text{ft} $ = length of the ladder (hypotenuse, constant).
- We are given:
  - The rate at which the bottom of the ladder moves away from the wall: $ \frac{dx}{dt} = 2 \, \text{ft/s} $.
  - The position of the bottom of the ladder: $ x = 6 \, \text{ft} $.
- We need to find:
  - The rate at which the top of the ladder is sliding down the wall: $ \frac{dy}{dt} $.

##### Step 2: Relate the variables using the Pythagorean theorem.
The relationship between $ x $, $ y $, and $ L $ is:
$$
x^2 + y^2 = L^2.
$$
Substitute $ L = 10 $:
$$
x^2 + y^2 = 100.
$$

##### Step 3: Differentiate with respect to time.
Differentiate both sides of $ x^2 + y^2 = 100 $ implicitly with respect to $ t $:
$$
2x \frac{dx}{dt} + 2y \frac{dy}{dt} = 0.
$$
Simplify:
$$
x \frac{dx}{dt} + y \frac{dy}{dt} = 0.
$$

##### Step 4: Solve for $ \frac{dy}{dt} $.
Rearrange the equation to isolate $ \frac{dy}{dt} $:
$$
\frac{dy}{dt} = -\frac{x}{y} \frac{dx}{dt}.
$$

##### Step 5: Find $ y $ when $ x = 6 $.
From the Pythagorean theorem:
$$
x^2 + y^2 = 100.
$$
Substitute $ x = 6 $:
$$
6^2 + y^2 = 100,
$$
$$
36 + y^2 = 100,
$$
$$
y^2 = 64 \quad \Rightarrow \quad y = 8 \, \text{ft}.
$$

##### Step 6: Substitute known values.
Substitute $ x = 6 $, $ y = 8 $, and $ \frac{dx}{dt} = 2 $ into $ \frac{dy}{dt} = -\frac{x}{y} \frac{dx}{dt} $:
$$
\frac{dy}{dt} = -\frac{6}{8}(2) = -\frac{12}{8} = -1.5 \, \text{ft/s}.
$$

##### Step 7: Interpret the result.
The negative sign indicates that the top of the ladder is sliding **down** the wall. Thus, the top of the ladder is sliding down at a rate of:
$$
\boxed{1.5 \, \text{ft/s}}.
$$

---

### Final Answer:
When the bottom of the ladder is $ 6 \, \text{ft} $ away from the wall, the top of the ladder is sliding down the wall at a rate of:
$$
\boxed{1.5 \, \text{ft/s}}.
$$

---

# Example Question 3: Related Rates - Filling a Conical Tank

#### Problem Statement:
Water is being poured into a conical tank at a rate of $ 5 \, \text{m}^3/\text{min} $. The tank has a height of $ 10 \, \text{m} $ and a base radius of $ 4 \, \text{m} $. How fast is the water level rising when the water is $ 6 \, \text{m} $ deep?

---

#### Solution:

##### Step 1: Understand the problem and identify known quantities.
- The tank is a cone. Let:
  - $ V $ = volume of water in the tank,
  - $ h $ = depth (height) of the water,
  - $ r $ = radius of the water surface.
- We are given:
  - The rate at which water is poured into the tank: $ \frac{dV}{dt} = 5 \, \text{m}^3/\text{min} $,
  - The dimensions of the tank: height $ H = 10 \, \text{m} $, base radius $ R = 4 \, \text{m} $,
  - The depth of the water: $ h = 6 \, \text{m} $.
- We need to find:
  - The rate at which the water level is rising: $ \frac{dh}{dt} $.

##### Step 2: Relate the variables using the geometry of the cone.
The volume of a cone is given by:
$$
V = \frac{1}{3} \pi r^2 h.
$$
Since the tank is a cone, the radius $ r $ and height $ h $ are proportional. Using similar triangles:
$$
\frac{r}{h} = \frac{R}{H} = \frac{4}{10} = \frac{2}{5}.
$$
Thus:
$$
r = \frac{2}{5} h.
$$

Substitute $ r = \frac{2}{5} h $ into the volume formula:
$$
V = \frac{1}{3} \pi \left( \frac{2}{5} h \right)^2 h = \frac{1}{3} \pi \cdot \frac{4}{25} h^2 \cdot h = \frac{4}{75} \pi h^3.
$$

##### Step 3: Differentiate with respect to time.
Differentiate $ V = \frac{4}{75} \pi h^3 $ implicitly with respect to $ t $:
$$
\frac{dV}{dt} = \frac{4}{75} \pi \cdot 3h^2 \frac{dh}{dt}.
$$
Simplify:
$$
\frac{dV}{dt} = \frac{4}{25} \pi h^2 \frac{dh}{dt}.
$$

##### Step 4: Solve for $ \frac{dh}{dt} $.
Rearrange the equation to isolate $ \frac{dh}{dt} $:
$$
\frac{dh}{dt} = \frac{\frac{dV}{dt}}{\frac{4}{25} \pi h^2}.
$$

##### Step 5: Substitute known values.
Substitute $ \frac{dV}{dt} = 5 \, \text{m}^3/\text{min} $ and $ h = 6 \, \text{m} $ into the equation:
$$
\frac{dh}{dt} = \frac{5}{\frac{4}{25} \pi (6)^2}.
$$
Simplify:
$$
\frac{dh}{dt} = \frac{5}{\frac{4}{25} \pi (36)} = \frac{5}{\frac{144}{25} \pi} = \frac{5 \cdot 25}{144 \pi} = \frac{125}{144 \pi} \, \text{m/min}.
$$

Numerically, this is approximately:
$$
\frac{dh}{dt} \approx 0.276 \, \text{m/min}.
$$

##### Step 6: Interpret the result.
The water level is rising at a rate of:
$$
\boxed{\frac{125}{144 \pi} \, \text{m/min} \, \text{(or approximately } 0.276 \, \text{m/min)}}.
$$

---

### Final Answer:
When the water is $ 6 \, \text{m} $ deep, the water level is rising at a rate of:
$$
\boxed{\frac{125}{144 \pi} \, \text{m/min} \, \text{(or approximately } 0.276 \, \text{m/min)}}.
$$

---

# Example Question 4: Related Rates - Shadow Lengthening

#### Problem Statement:
A streetlight is mounted at the top of a $ 15 \, \text{ft} $ pole. A man $ 6 \, \text{ft} $ tall walks away from the pole at a speed of $ 4 \, \text{ft/s} $. How fast is the tip of his shadow moving when he is $ 20 \, \text{ft} $ away from the base of the pole?

---

#### Solution:

##### Step 1: Understand the problem and identify known quantities.
- Let:
  - $ x $ = distance from the man to the base of the pole,
  - $ s $ = length of the man's shadow (from the base of the pole to the tip of the shadow).
- We are given:
  - The man's walking speed: $ \frac{dx}{dt} = 4 \, \text{ft/s} $,
  - The height of the streetlight: $ 15 \, \text{ft} $,
  - The height of the man: $ 6 \, \text{ft} $,
  - The man's position: $ x = 20 \, \text{ft} $.
- We need to find:
  - The rate at which the tip of the shadow is moving: $ \frac{ds}{dt} $.

##### Step 2: Relate the variables using similar triangles.
The man, his shadow, and the streetlight form two similar triangles:
1. The larger triangle has height $ 15 \, \text{ft} $ (streetlight) and base $ x + s $ (distance from the pole to the tip of the shadow).
2. The smaller triangle has height $ 6 \, \text{ft} $ (man) and base $ s $ (length of the shadow).

From the similarity of the triangles:
$$
\frac{\text{Height of streetlight}}{\text{Base of large triangle}} = \frac{\text{Height of man}}{\text{Base of small triangle}},
$$
$$
\frac{15}{x + s} = \frac{6}{s}.
$$

##### Step 3: Solve for $ s $ in terms of $ x $.
Cross-multiply:
$$
15s = 6(x + s).
$$
Expand and simplify:
$$
15s = 6x + 6s,
$$
$$
15s - 6s = 6x,
$$
$$
9s = 6x,
$$
$$
s = \frac{2}{3}x.
$$

##### Step 4: Differentiate with respect to time.
Differentiate $ s = \frac{2}{3}x $ implicitly with respect to $ t $:
$$
\frac{ds}{dt} = \frac{2}{3} \frac{dx}{dt}.
$$

##### Step 5: Substitute known values.
Substitute $ \frac{dx}{dt} = 4 \, \text{ft/s} $ into the equation:
$$
\frac{ds}{dt} = \frac{2}{3}(4) = \frac{8}{3} \, \text{ft/s}.
$$

##### Step 6: Interpret the result.
The tip of the shadow is moving at a rate of:
$$
\boxed{\frac{8}{3} \, \text{ft/s} \, \text{(or approximately } 2.67 \, \text{ft/s)}}.
$$

---

### Final Answer:
When the man is $ 20 \, \text{ft} $ away from the base of the pole, the tip of his shadow is moving at a rate of:
$$
\boxed{\frac{8}{3} \, \text{ft/s} \, \text{(or approximately } 2.67 \, \text{ft/s)}}.
$$

---

