**Mission:**  
Explore the cart and discount coupon flow on KaBuM! focusing on SFDPOT heuristics (Data, Operations, Time) to identify issues related to pricing, coupon behavior, and checkout consistency.

**Focus Areas:**  
- Add/remove products from cart  
- Apply and validate discount coupons  
- Checkout flow behavior  

**Heuristic Focus (SFDPOT):**  
- **Data:** Coupon codes, product prices, shipping values  
- **Operations:** Add/remove items, update quantities, apply/remove coupons  
- **Time:** Coupon expiration, stock changes during checkout  

**Test Data Variations:**  
- Valid and expired coupons  
- Coupons with different rules (percentage, fixed discount, minimum value)  
- Products with varying prices  
- Different quantities (1, multiple, high volume)  

**Activities:**  
- Add products to cart and modify quantities  
- Apply valid and invalid coupons  
- Attempt to use expired coupons  
- Observe changes in total price and shipping cost  
- Proceed to checkout with edge cases (e.g., stock changes)  

**(What to Check):**  
- Correct calculation of discounts and totals  
- Prevention of negative values (e.g., shipping or total price)  
- Proper handling of expired or invalid coupons  
- Stock validation during checkout  
- Consistency of cart updates in real time  

