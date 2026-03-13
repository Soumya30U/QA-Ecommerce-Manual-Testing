# Test Cases

## Login Module

### TC_001 – Login with Valid Credentials

Steps:
1. Navigate to the login page
2. Enter valid email
3. Enter valid password
4. Click Login

Expected Result:
User should be logged into the account successfully.


### TC_002 – Login with Invalid Password

Steps:
1. Navigate to the login page
2. Enter valid email
3. Enter incorrect password
4. Click Login

Expected Result:
Error message should appear indicating invalid login credentials.


### TC_003 – Login with Empty Fields

Steps:
1. Navigate to the login page
2. Leave email and password fields empty
3. Click Login

Expected Result:
Validation message should appear asking the user to fill required fields.



## Product Search Module

### TC_004 – Search for Existing Product

Steps:
1. Enter product name in the search bar
2. Click search button

Expected Result:
Relevant products should appear in search results.


### TC_005 – Search with Partial Product Name

Steps:
1. Enter partial product name in the search bar
2. Click search

Expected Result:
Products containing the keyword should appear.


### TC_006 – Search for Non-Existing Product

Steps:
1. Enter a random product name
2. Click search

Expected Result:
Message should appear indicating no products found.



## Product Page Module

### TC_007 – Open Product Details Page

Steps:
1. Navigate to any product from homepage
2. Click on the product

Expected Result:
Product details page should open with product information.


### TC_008 – Verify Product Information

Steps:
1. Open product page
2. Observe product details

Expected Result:
Product name, price, description, and images should be displayed correctly.



## Cart Module

### TC_009 – Add Product to Cart

Steps:
1. Navigate to product page
2. Click "Add to Cart"

Expected Result:
Product should be added to the cart successfully.


### TC_010 – Verify Cart Icon Update

Steps:
1. Add product to cart
2. Observe cart icon

Expected Result:
Cart icon should display updated item count.


### TC_011 – Remove Product from Cart

Steps:
1. Open cart page
2. Remove product

Expected Result:
Product should be removed from cart successfully.



## Checkout Module

### TC_012 – Open Checkout Page

Steps:
1. Add product to cart
2. Navigate to cart
3. Click Checkout

Expected Result:
User should be redirected to checkout page.


### TC_013 – Proceed Through Checkout Steps

Steps:
1. Open checkout page
2. Fill required details
3. Continue through checkout steps

Expected Result:
User should be able to proceed through checkout process without errors.
