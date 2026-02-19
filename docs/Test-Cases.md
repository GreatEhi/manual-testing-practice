| TC_001 | Valid Login | ... | user1 / Pass123 | Redirect to dashboard | User redirected to dashboard | Pass | 2026-02-19 |
| TC_002 | Invalid Password | ... | user1 / Wrong123 | Error message appears, access denied | Error shown, access denied | Pass | 2026-02-19 |
| TC_003 | Empty Fields | ... | N/A | Validation message appears | No message displayed | Fail | 2026-02-19 |
| TC_004 | Password Masking | ... | Pass123 | Password is masked | Password masked | Pass | 2026-02-19 |
| TC_005 | SQL Injection Attempt | 1. Enter ' OR '1'='1 in username 2. Enter any password 3. Click login | ' OR '1'='1 | Login should fail and system should handle input securely | TBD | Not Executed | TBD |
| TC_006 | Very Long Input | 1. Enter 300+ characters in username field 2. Click login | 300-character string | System should either restrict input or show validation message | TBD | Not Executed | TBD |
| TC_007 | Special Characters | 1. Enter special characters (!@#$%) in username 2. Click login | !@#$% | System should validate input properly | TBD | Not Executed | TBD |
| TC_008 | Case Sensitivity Check | 1. Enter correct username but wrong case 2. Click login | USER1 / Pass123 | System should respect case rules as designed | TBD | Not Executed | TBD |
