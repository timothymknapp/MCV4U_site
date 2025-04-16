+++
title = '5.4 Practice'
weight = 2
+++


#### Ex1.

A company currently sells 500 units of a product at a price of $ \text{\$20}$ per unit. A survey shows that for every \$1 increase in price, the company will sell 20 fewer units. The cost function is:

$$
C(q) = 3000 + 5q,
$$

where $ q $ is the number of units sold. What price should the company charge to **maximize profit**?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Let $ x $ be the number of **$1 price increases**.  
   Then:
   - New price = $ 20 + x $
   - New quantity = $ 500 - 20x $

2. Revenue function:
   
   $$
   R(x) = \text{price} \times \text{quantity} = (20 + x)(500 - 20x).
   $$

3. Cost function in terms of $ x $:
   
   $$
   q = 500 - 20x \quad \Rightarrow \quad C(x) = 3000 + 5(500 - 20x) = 3000 + 2500 - 100x = 5500 - 100x.
   $$

4. Profit function:
   
   $$
   P(x) = R(x) - C(x) = (20 + x)(500 - 20x) - (5500 - 100x).
   $$

5. Expand and simplify:
   
   $$
   (20 + x)(500 - 20x) = 10000 - 400x + 500x - 20x^2 = 10000 + 100x - 20x^2,
   $$
   
   $$
   P(x) = (10000 + 100x - 20x^2) - (5500 - 100x) = 10000 + 100x - 20x^2 - 5500 + 100x = 4500 + 200x - 20x^2.
   $$

6. Maximize profit:
   
   $$
   \frac{dP}{dx} = 200 - 40x = 0 \Rightarrow x = 5.
   $$

7. Final answers:
   - Price = $ 20 + 5 = \boxed{\$25} $ 
   - Quantity = $ 500 - 20(5) = 400 $  
   - Max profit = optional but:
     
     $$
     P(5) = 4500 + 200(5) - 20(25) = 4500 + 1000 - 500 = \boxed{5000}.
     $$

</details>

---

#### Ex2.

A bakery currently sells 1000 croissants per week at a price of $ \text{ \$ 2.50}$. Market research shows that for every \$ 0.10 increase, the bakery will sell 30 fewer croissants. The weekly cost function is:

$$
C(q) = 400 + 1.2q.
$$

What price should be charged to **maximize weekly profit**?

<details>
  <summary>
    <strong id="solution-title">Solution</strong>
  </summary>

1. Let $ x $ be the number of **$0.10 increases** in price:  
   - New price = $ 2.50 + 0.10x $  
   - New quantity = $ 1000 - 30x $

2. Revenue:
   
   $$
   R(x) = (2.50 + 0.10x)(1000 - 30x).
   $$

3. Cost function in terms of $ x $:
  
   $$
   q = 1000 - 30x \quad \Rightarrow \quad C(x) = 400 + 1.2(1000 - 30x) = 400 + 1200 - 36x = 1600 - 36x.
   $$

4. Profit function:
  
   $$
   P(x) = R(x) - C(x) = (2.50 + 0.10x)(1000 - 30x) - (1600 - 36x).
   $$

5. Expand:
  
   $$
   (2.50 + 0.10x)(1000 - 30x) = 2500 - 75x + 100x - 3x^2 = 2500 + 25x - 3x^2,
   $$
  
   $$
   P(x) = (2500 + 25x - 3x^2) - (1600 - 36x) = 2500 + 25x - 3x^2 - 1600 + 36x = 900 + 61x - 3x^2.
   $$

6. Maximize:
  
   $$
   \frac{dP}{dx} = 61 - 6x = 0 \Rightarrow x = \frac{61}{6} \approx 10.17.
   $$

7. Final answer:
   - Price = $ 2.50 + 0.10 \cdot 10.17 = \boxed{\$3.52} $
   - Quantity = $ 1000 - 30(10.17) \approx 694.9 \approx 695 $  
   - Max profit (optional): plug into $ P(x) $

</details>



<iframe src="https://script.google.com/macros/s/AKfycbyVZSVGIQVQIZE_6kIYprBQYxZN9teivQZezeRgX-D5mZeNNx4JC_c7fKu-EY9QCeqkUA/exec" width="80%" height="1000px" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
