# Test Plan — SauceDemo Manual Functional Testing

## 1. Objective
Verify selected basic shopping-cart behaviors in the SauceDemo demo e-commerce application and document the observed results.

## 2. Application under test
- Name: SauceDemo
- URL: https://www.saucedemo.com/

## 3. Scope

### In scope
1. Product catalog displays product names, images, prices, and action buttons.
2. Adding a product updates the cart badge.
3. The product action button changes from `Add to cart` to `Remove`.
4. The cart displays the selected product and its displayed price.
5. Removing the product removes it from the cart and updates the badge.

### Out of scope
- Checkout and order completion
- Payment processing
- Authentication negative scenarios
- API testing
- Security, accessibility, performance, and load testing
- Cross-browser and cross-device compatibility

## 4. Test approach
Manual functional testing using the web UI. Each check is compared with the expected visible behavior. Results are recorded as Pass, Fail, or Not Run.

## 5. Test environment
- Application: SauceDemo demo website
- Browser and version: not recorded
- Operating system: not recorded
- Test account: demo account used to access the application; credentials are intentionally not stored in this repository
- Execution date: not recorded

## 6. Entry criteria
- The application is accessible.
- The tester can sign in with an available demo account.
- The product catalog is displayed.

## 7. Exit criteria
- All planned checks have an execution status.
- Any observed failures are documented with reproducible steps and evidence where available.

## 8. Risks and limitations
- A demo environment may change over time.
- Results represent only the specific checks performed in the recorded run.
- Browser, operating system, and exact test date were not captured.

## 9. Deliverables
- Test plan
- Test cases
- Test execution report
