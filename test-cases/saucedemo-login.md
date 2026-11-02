# Test Cases: Saucedemo Login

| ID | Scenario | Steps | Expected Result | Actual Result | Status |
|----|----------|-------|-----------------|---------------|--------|
| TC01 | Valid login | Enter standard_user / secret_sauce, click Login | Products page opens | | |
| TC02 | Wrong password | Enter standard_user / wrong, click Login | Error message shown | | |
| TC03 | Empty username | Leave username empty, click Login | "Username is required" | | |
| TC04 | Empty password | Enter username only, click Login | "Password is required" | | |
| TC05 | Locked user | Enter locked_out_user / secret_sauce | Locked out error | | |
