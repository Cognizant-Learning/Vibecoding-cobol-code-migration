# Test Plan for COBOL Application

This test plan outlines the business logic and scenarios that need to be validated with the business stakeholders. Once validated, you can use this plan to create unit tests and integration tests for the Node.js application.

## Test Plan Table

| Test Case ID | Test Case Description                          | Pre-conditions       | Test Steps                                                                 | Expected Result                                                                 | Actual Result | Status (Pass/Fail) | Comments |
|--------------|------------------------------------------------|----------------------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------|----------------|--------------------|----------|
| TC-1.1       | View Current Balance                           | Application started  | 1. Start the application. <br> 2. Select option 1 to view the balance.     | The application should display the current balance.                            |                |                    |          |
| TC-2.1       | Credit Account with Valid Amount               | Application started  | 1. Start the application. <br> 2. Select option 2 to credit the account. <br> 3. Enter a valid credit amount (e.g., 100.00). | The application should display the new balance after adding the credit amount. |                |                    |          |
| TC-2.2       | Credit Account with Zero Amount                | Application started  | 1. Start the application. <br> 2. Select option 2 to credit the account. <br> 3. Enter 0.00 as the credit amount. | The application should display the same balance as before.                     |                |                    |          |
| TC-3.1       | Debit Account with Valid Amount                | Application started  | 1. Start the application. <br> 2. Select option 3 to debit the account. <br> 3. Enter a valid debit amount that is less than or equal to the current balance (e.g., 50.00). | The application should display the new balance after subtracting the debit amount. |                |                    |          |
| TC-3.2       | Debit Account with Amount Greater Than Balance | Application started  | 1. Start the application. <br> 2. Select option 3 to debit the account. <br> 3. Enter a debit amount that is greater than the current balance (e.g., 2000.00). | The application should display an "Insufficient funds" message and the balance should remain unchanged. |                |                    |          |
| TC-3.3       | Debit Account with Zero Amount                 | Application started  | 1. Start the application. <br> 2. Select option 3 to debit the account. <br> 3. Enter 0.00 as the debit amount. | The application should display the same balance as before.                     |                |                    |          |
| TC-4.1       | Exit the Application                           | Application started  | 1. Start the application. <br> 2. Select option 4 to exit the application. | The application should display an exit message and terminate.                  |                |                    |          |

## Test Cases

### Test Case TC-1.1: View Current Balance

**Description:** Verify that the current balance is displayed correctly.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 1 to view the balance.

**Expected Result:** The application should display the current balance.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-2.1: Credit Account with Valid Amount

**Description:** Verify that the account is credited with a valid amount.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 2 to credit the account.
3. Enter a valid credit amount (e.g., 100.00).

**Expected Result:** The application should display the new balance after adding the credit amount.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-2.2: Credit Account with Zero Amount

**Description:** Verify that the account balance remains unchanged when credited with zero amount.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 2 to credit the account.
3. Enter 0.00 as the credit amount.

**Expected Result:** The application should display the same balance as before.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-3.1: Debit Account with Valid Amount

**Description:** Verify that the account is debited with a valid amount.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 3 to debit the account.
3. Enter a valid debit amount that is less than or equal to the current balance (e.g., 50.00).

**Expected Result:** The application should display the new balance after subtracting the debit amount.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-3.2: Debit Account with Amount Greater Than Balance

**Description:** Verify that the application prevents debiting an amount greater than the current balance.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 3 to debit the account.
3. Enter a debit amount that is greater than the current balance (e.g., 2000.00).

**Expected Result:** The application should display an "Insufficient funds" message and the balance should remain unchanged.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-3.3: Debit Account with Zero Amount

**Description:** Verify that the account balance remains unchanged when debited with zero amount.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 3 to debit the account.
3. Enter 0.00 as the debit amount.

**Expected Result:** The application should display the same balance as before.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

### Test Case TC-4.1: Exit the Application

**Description:** Verify that the application exits correctly.

**Pre-conditions:** Application started.

**Test Steps:**

1. Start the application.
2. Select option 4 to exit the application.

**Expected Result:** The application should display an exit message and terminate.

**Actual Result:** 

**Status (Pass/Fail):** 

**Comments:** 

---

## Summary

This test plan covers the main functionalities of the COBOL application, including viewing the balance, crediting the account, debiting the account, and exiting the application. Validate this test plan with the business stakeholders to ensure it meets the business requirements. Once validated, you can use this plan to create corresponding unit tests and integration tests for the Node.js application.
