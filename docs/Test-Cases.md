# Test Cases – Login Page

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|--------------|--------------|------------|-----------|-----------------|--------|
| TC_001 | Valid Login | 1. Enter valid username 2. Enter valid password 3. Click login | user1 / Pass123 | User should be redirected to dashboard | Not Executed |
| TC_002 | Invalid Password | 1. Enter valid username 2. Enter invalid password 3. Click login | user1 / Wrong123 | Error message should appear | Not Executed |
| TC_003 | Empty Fields | 1. Leave fields empty 2. Click login | N/A | Validation message should appear | Not Executed |
| TC_004 | Password Masking | 1. Type password in password field | Pass123 | Password should appear as dots or asterisks | Not Executed |
