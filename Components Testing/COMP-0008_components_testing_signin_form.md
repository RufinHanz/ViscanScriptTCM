## **COMP-0008:** Components testing - SignIn Form  

> **Summary:** Verify that the sign-in form is shown and working successfully.  <br>

**Preconditions:**
- The User Login Page component is rendered.
- The user is not authenticated.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |Launch the app.     | Verify that the application works   | 
 |  2 |The User Login Page component is rendered.      | Verify that the login page UI is displayed, including the VSU Script logo, sign-up card, and VSU banner.  | 
 |  3 |The user attempts to sign in.      | Verify if the user is already authenticated, the user's authorization is checked, and the user is redirected accordingly.   |  
 |  4 |      |Verify if the user is not authenticated, the user is prompted to sign in with their Google account.    |  
 |  5 |The user clicks on the `Sign in with Google` button.      | Verify that the user is redirected to the Google authentication page.  |  
 |  6 |The user successfully signs in.      | Verify if the sign-in is successful, the user's authorization is checked, and the user is redirected accordingly.   |  
 |  7 |      | Verify if the sign-in fails, an error message is displayed indicating the failure.   |  


**Post-conditions:**  
- The login page UI is displayed.
- The user can sign in using Google authentication.
