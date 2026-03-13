# Test Data

Application: OpenCart Demo Website  
URL: https://demo.opencart.com

This document contains the sample test data used during manual testing.

---

## User Login Data

| Test Case | Email | Password | Expected Result |
|------|------|------|------|
| Valid Login | testuser@example.com | Test@123 | Login successful |
| Invalid Password | testuser@example.com | WrongPass123 | Error message displayed |
| Invalid Email | invalid@email.com | Test@123 | Login failure |
| Empty Fields | (blank) | (blank) | Validation message |

---

## Product Search Data

| Test Case | Search Keyword | Expected Result |
|------|------|------|
| Valid Product Search | MacBook | Relevant products appear |
| Partial Keyword Search | Mac | Matching products appear |
| Non-Existing Product | abcxyz123 | No results message |

---

## Cart Testing Data

| Test Case | Product | Quantity |
|------|------|------|
| Add Product | MacBook | 1 |
| Update Quantity | MacBook | 2 |
| Remove Product | MacBook | Remove from cart |

---

## Checkout Data

| Field | Sample Data |
|------|------|
| First Name | John |
| Last Name | Doe |
| Address | 123 Test Street |
| City | Testville |
| Postcode | 12345 |
| Country | United States |
| Region | California |
