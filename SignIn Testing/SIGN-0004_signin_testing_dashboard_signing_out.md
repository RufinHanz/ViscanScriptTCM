## **SIGN-0004:** SignIn testing - Dashboard Signing Out

> **Summary:** Verify that `SignIn Form` page is shown and configured successfully.  <br>

**Preconditions:** 
- The user must access the LogIn page.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |The user logs in to the system.      | Verify that log-in page must show. |   
 |  2 |The user clicks on `Dashboard`     | Verify that `Dashboard` page is clickable and accessible. |  
 |  3 |The user chooses his/her 'VSU' Email Address       | Verify that email addresses to be chosen in vsu student email format.   |  
 |  4 |      | Verify that page redirects the user to `Dashboard` page. | 
 |  5 |The user clicks the `Signout` button on the top corner of the screen      | Verify that page redirects the user to back to the `SignIn` page. |

**Post-conditions:**  
- The user is redirected back to thee `SignIn` Page.