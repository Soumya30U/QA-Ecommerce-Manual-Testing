# Test Cases

Application: OpenCart Demo Website
URL: https://demo.opencart.com
Testing Type: Manual Functional Testing
Browser: Chrome
OS: Windows 10

---

## Module: Login

### TC_001 – Verify login with valid credentials

Precondition:
User account must exist.

Steps:
1. Navigate to My Account → Login
2. Enter valid registered email
3. Enter correct password
4. Click Login

Expected Result:
User should successfully log into the account dashboard.

Priority: High


### TC_002 – Verify login fails with incorrect password

Steps:
1. Navigate to Login page
2. Enter valid email
3. Enter incorrect password
4. Click Login

Expected Result:
System should display error message:
"Warning: No match for E-Mail Address and/or Password."

Priority: High


### TC_003 – Verify login validation for empty fields

Steps:
1. Open login page
2. Leave email field empty
3. Leave password field empty
4. Click Login

Expected Result:
System should display validation error message.

Priority: Medium

---

## Module: Product Search

### TC_004 – Verify search returns results for existing product

Steps:
1. Enter "MacBook" in search bar
2. Click Search

Expected Result:
Product search results page should display MacBook related items.

Priority: High


### TC_005 – Verify search with partial keyword

Steps:
1. Enter "Mac" in search bar
2. Click Search

Expected Result:
Products containing the keyword should appear in results.

Priority: Medium


### TC_006 – Verify search for non-existing product

Steps:
1. Enter random keyword such as "xyz123"
2. Click Search

Expected Result:
Message displayed: "There is no product that matches the search criteria."

Priority: Medium

---

## Module: Cart

### TC_007 – Verify product can be added to cart

Steps:
1. Navigate to any product page
2. Click Add to Cart

Expected Result:
Success message appears and cart total increases.

Priority: High


### TC_008 – Verify cart displays correct product information

Steps:
1. Add product to cart
2. Open cart dropdown

Expected Result:
Cart should display:
- Product name
- Quantity
- Price

Priority: High


### TC_009 – Verify product removal from cart

Steps:
1. Add product to cart
2. Open cart
3. Click remove icon

Expected Result:
Product should be removed from cart.

Priority: High

---

## Module: Checkout

### TC_010 – Verify checkout page loads

Steps:
1. Add product to cart
2. Navigate to cart page
3. Click Checkout

Expected Result:
Checkout page should load successfully.

Priority: High


### TC_011 – Verify checkout requires login

Steps:
1. Add product to cart
2. Click checkout without logging in

Expected Result:
User should be prompted to login or register.

Priority: High

### TC_012 – Verify checkout displays correct cart summary

Preconditions:
Product added to cart.

Steps:
1. Add a product to cart
2. Navigate to checkout page
3. Observe order summary section

Expected Result:
Order summary should correctly display:
- Product name
- Quantity
- Individual price
- Total order amount

### TC_013 – Verify user can update quantity before checkout

Steps:
1. Add product to cart
2. Navigate to cart page
3. Increase product quantity
4. Click update

Expected Result:
Cart total and item quantity should update correctly.

### TC_014 – Verify checkout prevents order submission with missing mandatory fields

Steps:
1. Add product to cart
2. Navigate to checkout
3. Leave required fields empty (e.g., address, city)
4. Attempt to proceed

Expected Result:
System should display validation messages for required fields.

### TC_015 – Verify order confirmation page appears after successful checkout

Preconditions:
User is logged in and checkout details are filled.

Steps:
1. Add product to cart
2. Proceed to checkout
3. Fill billing and shipping details
4. Confirm order

Expected Result:
System should display order confirmation page with order ID and success message.
