# Sample Test Cases

**Project:** Web Platform / FinTech Market Simulator  
**Module:** Order Creation

| Test ID | Description | Steps | Expected Result | Status |
|---------|------------|-------|----------------|--------|
| TC001 | Verify order submission | 1. Login, 2. Open order form, 3. Enter valid data, 4. Submit | Order created with correct values | Pass |
| TC002 | Verify error on empty fields | 1. Login, 2. Open order form, 3. Leave fields empty, 4. Submit | Error messages shown | Pass |
| TC003 | Verify invalid input | 1. Enter invalid symbol, 2. Submit | Error message shown, order not created | Pass |
| TC004 | Verify dashboard updates correctly | 1. Perform transaction, 2. Check dashboard | Data reflects the transaction | Pass |
| TC005 | Verify logout functionality | 1. Click logout | User redirected to login page | Pass |
