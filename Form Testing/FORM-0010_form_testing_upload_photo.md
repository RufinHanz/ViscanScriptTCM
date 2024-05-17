## **FORM-0010:** Form testing - Upload Photo

> **Summary:** Verify that `Upload Photo` field in Binding Request Form is accessible and configured successfully.  <br>

**Preconditions:**
- The user is logged in and navigates to the binding request form page.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |The user logs in to the system.      | Verify that log-in page must show.   |
 |  2 |The user clicks `Form`      | Verify that `Form` page is clickable.   |
 |  3 |Log-in through the app      | Verify that log-in page pops and shows up.   | 
 |  4 |	| Verify that the system displays the binding request form page.   |   
 |  5 |Click on `Choose File` under `Upload Photo` field	| Verify that the system accesses to your file directory.   |
 |  6 |		| Verify and select the photo in `.jpg`, `.jpeg` or `.png` format to be uploaded.   |   

**Post-conditions:**  
- The user successfully accesses the binding request form page.