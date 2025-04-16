+++
title = '5.3 Practice'
weight = 2
+++


#### Ex1.
A farmer wants to build a rectangular pen using **100 meters of fencing**, and one side of the pen will be along an existing **barn wall** (so it doesn’t need fencing). What dimensions maximize the area of the pen?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Let the length **parallel to the barn** be $ x $ and the width **perpendicular to the barn** be $ y $.  
   Only **three sides** require fencing: one $ x $ and two $ y $:
   $$
   x + 2y = 100.
   $$

2. Solve for $ x $:
   $$
   x = 100 - 2y.
   $$

3. Write the area function:
   $$
   A = x \cdot y = (100 - 2y) \cdot y = 100y - 2y^2.
   $$

4. Find the critical point:
   $$
   \frac{dA}{dy} = 100 - 4y.
   $$  
   Set $ \frac{dA}{dy} = 0 $:
   $$
   100 - 4y = 0 \Rightarrow y = 25.
   $$  
   Then:
   $$
   x = 100 - 2(25) = 50.
   $$

Thus, the dimensions that maximize the area are:
$$
\boxed{50 \, \text{m} \times 25 \, \text{m}}.
$$

</details>

---

#### Ex2.
A box with a **square base and open top** must have a volume of **32,000 cm³**. What dimensions minimize the surface area?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Let the base side length be $ x $ and height be $ h $.  
   Volume:
   $$
   V = x^2 h = 32000 \quad \Rightarrow \quad h = \frac{32000}{x^2}.
   $$

2. Surface area (no top):
   $$
   A = x^2 + 4xh.
   $$  
   Substitute $ h = \frac{32000}{x^2} $:
   $$
   A(x) = x^2 + 4x \cdot \frac{32000}{x^2} = x^2 + \frac{128000}{x}.
   $$

3. Find the critical point:
   $$
   \frac{dA}{dx} = 2x - \frac{128000}{x^2}.
   $$  
   Set $ \frac{dA}{dx} = 0 $:
   $$
   2x = \frac{128000}{x^2} \Rightarrow 2x^3 = 128000 \Rightarrow x^3 = 64000 \Rightarrow x = 40.
   $$  
   Then:
   $$
   h = \frac{32000}{40^2} = \frac{32000}{1600} = 20.
   $$

Thus, the dimensions that minimize surface area are:
$$
\boxed{40 \, \text{cm} \times 40 \, \text{cm} \times 20 \, \text{cm}}.
$$

</details>

---

#### Ex3.
A rectangle is inscribed under the parabola $ y = 9 - x^2 $ and above the x-axis. What is the **maximum area** of such a rectangle?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. The rectangle is symmetric, so place its sides at $ x $ and $ -x $.  
   Height is $ y = 9 - x^2 $.  
   So:
   $$
   \text{Width} = 2x, \quad \text{Height} = 9 - x^2.
   $$

2. Write the area function:
   $$
   A(x) = 2x(9 - x^2) = 18x - 2x^3.
   $$

3. Find the critical point:
   $$
   \frac{dA}{dx} = 18 - 6x^2.
   $$  
   Set $ \frac{dA}{dx} = 0 $:
   $$
   18 = 6x^2 \Rightarrow x^2 = 3 \Rightarrow x = \sqrt{3}.
   $$  
   Then:
   $$
   y = 9 - 3 = 6.
   $$

4. Width = $ 2\sqrt{3} $, Height = $ 6 $.  
   Maximum area:
   $$
   A = 2\sqrt{3} \cdot 6 = 12\sqrt{3}.
   $$

Thus, the maximum area is:
$$
\boxed{12\sqrt{3} \, \text{units}^2 \, \text{(or approximately } 20.78 \, \text{units}^2)}.
$$

</details>



<iframe src="https://script.google.com/macros/s/AKfycbwee9y604QQKsxCNXM2hFXOkbeFZp4U3uEkMMvoIIW1vPzzT_ZRIDI_m7zI5mwdnbLM/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
