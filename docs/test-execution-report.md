# Test Execution Report — SauceDemo Cart Basics

## 1. Summary

| Item | Value |
|---|---|
| Application | SauceDemo — https://www.saucedemo.com/ |
| Test type | Manual functional testing |
| Test cases executed | 5 |
| Passed | 5 |
| Failed | 0 |
| Not run | 0 |
| Pass rate | 100% |
| Overall result | All listed checks passed |

## 2. Execution results

| Test Case | Check | Status | Observed result |
|---|---|---|---|
| TC-001 | Catalog names, images, prices, and buttons | PASS | The catalog information and buttons appeared correct. |
| TC-002 | Cart badge after adding one product | PASS | The cart badge showed `1`. |
| TC-003 | Product button state after adding | PASS | The button changed from `Add to cart` to `Remove`. |
| TC-004 | Selected product and price in cart | PASS | The selected product and expected displayed price were shown in the cart. |
| TC-005 | Remove product and update cart badge | PASS | The product disappeared after removal and the cart count updated. |

## 3. Defects
No defects were reported during these five checks.

This means no issues were observed in the tested scenarios; it does not mean the entire application is defect-free.

## 4. Limitations
- Browser, browser version, operating system, and exact execution date were not recorded.
- The report is based on the tester's recorded results; screenshots or other evidence were not provided.
- Testing was limited to the five checks listed above.
- Checkout, payment, API, security, accessibility, performance, and cross-browser behavior were not tested as part of this run.

## 5. Conclusion
All five executed checks passed according to the recorded observations. The results support the basic catalog and cart interactions tested in this run. Additional testing would be required to assess other application features and edge cases.
