# Test Cases — SauceDemo Cart Basics

**Application:** https://www.saucedemo.com/  
**Test type:** Manual functional testing

## TC-001 — Verify product catalog information

**Preconditions**
- The user is signed in.
- The inventory/catalog page is open.

**Steps**
1. Review the products displayed on the catalog page.
2. Check the visible product names.
3. Check the product images.
4. Check the displayed prices.
5. Check that product action buttons are present.

**Expected result**
- Product names, images, prices, and action buttons are displayed correctly.

## TC-002 — Verify cart badge after adding a product

**Preconditions**
- The user is signed in.
- The catalog is open.
- The cart is empty.

**Steps**
1. Click `Add to cart` for one product.
2. Observe the cart badge.

**Expected result**
- The cart badge displays `1`.

## TC-003 — Verify product action button state

**Preconditions**
- The catalog is open.
- A product has not yet been added to the cart.

**Steps**
1. Click `Add to cart` for a product.
2. Observe the button for that product.

**Expected result**
- The button changes from `Add to cart` to `Remove`.

## TC-004 — Verify selected product in cart

**Preconditions**
- One product has been added to the cart.

**Steps**
1. Open the cart.
2. Check the listed product.
3. Compare its displayed price with the price shown in the catalog.

**Expected result**
- The selected product appears in the cart and its displayed price matches the catalog price.

## TC-005 — Verify product removal from cart

**Preconditions**
- One product is in the cart.

**Steps**
1. Click `Remove` for the selected product using the available removal control.
2. Observe the cart contents.
3. Observe the cart badge if displayed.

**Expected result**
- The product is removed from the cart and the cart badge updates accordingly (for a single-item cart, the badge is no longer displayed or no longer shows `1`).

## Execution status
See [Test Execution Report](test-execution-report.md) for the recorded results.
