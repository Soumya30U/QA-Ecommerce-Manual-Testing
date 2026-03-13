# Bug Reports

Application: OpenCart Demo Website
URL: https://demo.opencart.com
Environment: Chrome / Windows 10
Testing Type: Manual Functional Testing

---

## BUG_001

Title:
Search results include unrelated products for keyword "Laptop"

Module:
Product Search

Severity:
Medium

Priority:
Medium

Steps to Reproduce:
1. Navigate to homepage
2. Enter "Laptop" in search bar
3. Click Search

Expected Result:
Only laptop-related products should appear.

Actual Result:
Search results include unrelated accessories.

Status:
Open

---

## BUG_002

Title:
Search field accepts extremely long input without validation

Module:
Search

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Enter a very long string (200+ characters) into search field
2. Click search

Expected Result:
Search field should limit input length or validate input.

Actual Result:
Application accepts extremely long input without restriction.

Status:
Open

---

## BUG_003

Title:
Cart dropdown overlaps navigation menu on smaller screen resolution

Module:
Cart UI

Severity:
Low

Priority:
Medium

Steps to Reproduce:
1. Resize browser window to smaller width
2. Add product to cart
3. Open cart dropdown

Expected Result:
Cart dropdown should display correctly below icon.

Actual Result:
Cart dropdown overlaps navigation menu items.

Status:
Open

---

## BUG_004

Title:
Product image loading delay on product page

Module:
Product Page

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Open any product page
2. Refresh the page

Expected Result:
Product images should load immediately.

Actual Result:
Images load slowly after page content.

Status:
Open

---

## BUG_005

Title:
Quantity field allows negative values

Module:
Cart

Severity:
Medium

Priority:
High

Steps to Reproduce:
1. Add product to cart
2. Go to cart page
3. Enter "-1" in quantity field
4. Click update

Expected Result:
System should prevent negative quantity values.

Actual Result:
Negative value is accepted.

Status:
Open

---

## BUG_006

Title:
Cart page does not show clear message when cart is empty

Module:
Cart

Severity:
Low

Priority:
Medium

Steps to Reproduce:
1. Remove all products from cart
2. Open cart page

Expected Result:
User-friendly message indicating cart is empty.

Actual Result:
Page displays minimal information without guidance.

Status:
Open

---

## BUG_007

Title:
Search results page lacks sorting reset option

Module:
Search Results

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Search for product
2. Change sorting option
3. Attempt to reset sorting

Expected Result:
User should have option to reset sorting.

Actual Result:
Sorting cannot be reset easily.

Status:
Open

---

## BUG_008

Title:
Product comparison feature is not clearly visible

Module:
Product Listing

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Browse product listings
2. Look for comparison option

Expected Result:
Product comparison should be clearly accessible.

Actual Result:
Comparison option is difficult to locate.

Status:
Open

---

## BUG_009

Title:
Navigation menu becomes crowded on smaller screens

Module:
UI / Navigation

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Reduce browser window size
2. Observe navigation menu

Expected Result:
Menu should adapt properly to smaller screens.

Actual Result:
Menu items appear crowded.

Status:
Open

---

## BUG_010

Title:
Search results do not highlight matched keyword

Module:
Search

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Search for "MacBook"
2. Observe results

Expected Result:
Search keyword should be highlighted.

Actual Result:
Keyword is not highlighted.

Status:
Open

---

## BUG_011

Title:
Cart page does not confirm item removal clearly

Module:
Cart

Severity:
Low

Priority:
Medium

Steps to Reproduce:
1. Add product to cart
2. Remove product

Expected Result:
System should display confirmation message.

Actual Result:
Product disappears without confirmation.

Status:
Open

---

## BUG_012

Title:
Footer links open without visual feedback

Module:
UI / Footer

Severity:
Low

Priority:
Low

Steps to Reproduce:
1. Scroll to footer
2. Click informational links

Expected Result:
Links should provide visual feedback.

Actual Result:
Minimal visual response when links are clicked.

Status:
Open
