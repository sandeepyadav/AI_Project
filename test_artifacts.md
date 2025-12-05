## Test Plan

**Objective**: The primary objective of this test plan is to validate the login functionality, ensuring users can access their dashboard with correct credentials and are appropriately restricted with incorrect credentials. We also aim to confirm that helpful error messages are displayed upon unsuccessful login attempts.

**Scope**: The testing focuses specifically on the login feature – including field validation, successful login, unsuccessful login, and user redirection post-login.

**Responsibilities**: The QA team is responsible for executing and maintaining this plan. The team will report any bugs or discrepancies to the development team for resolution.

## User Scenarios

1. **Scenario 1**: User enters a valid email and password.
    - Expected Result: User is successfully logged in and redirected to the dashboard.
    
2. **Scenario 2**: User enters an incorrect password with a valid email.
   - Expected Result: An error message is displayed indicating that the password is incorrect.

3. **Scenario 3**: User enters an incorrect email and password.
    - Expected Result: An error message is displayed indicating that the credentials are incorrect.

4. **Scenario 4**: User tries to login with empty fields.
    - Expected Result: An error message is displayed indicating that the fields can't be blank.
    
5. **Scenario 5**: User enters an email that doesn't follow proper format.
    - Expected Result: An error message is displayed indicating the email format is incorrect.


## Test Data

1. **Data for Scenario 1**
    - Email: user1@gmail.com
    - Password: Password123

2. **Data for Scenario 2**
    - Email: user1@gmail.com
    - Password: incorrect

3. **Data for Scenario 3**
    - Email: no-user@sample.com
    - Password: NoPassword

4. **Data for Scenario 4**
    - Email: 
    - Password: 

5. **Data for Scenario 5**
    - Email: userwithoutformat
    - Password: Password123
