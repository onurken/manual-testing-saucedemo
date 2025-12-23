Test Cases – SauceDemo Website

TC001 – Valid Login
Precondition: User is on login page  
Steps:
1. Enter valid username
2. Enter valid password
3. Click login button
Expected Result:
User should login successfully

---

TC002 – Invalid Login
Precondition: User is on login page  
Steps:
1. Enter wrong username or password
2. Click login button
Expected Result:
Error message should be displayed

---

TC003 – Add Product to Cart
Precondition: User is logged in  
Steps:
1. Click “Add to Cart” button for any product
2. Go to cart page
Expected Result:
Selected product should be shown in cart

---

TC004 – Remove Product from Cart
Precondition: Product is added to cart  
Steps:
1. Go to cart page
2. Click “Remove” button
Expected Result:
Product should be removed from cart

---

TC005 – Checkout Process
Precondition: Product is added to cart  
Steps:
1. Go to cart page
2. Click Checkout
3. Enter first name
4. Enter last name
5. Enter postal code
6. Click Continue
7. Click Finish
Expected Result:
Order should be completed successfully
