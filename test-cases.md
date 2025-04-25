# QA Analyst Take-Home – Linq

## End-to-End Test Case: Create Profile and Save Contact Info

### Test Case ID: 12345
**Description:** Verify user is able to create a profile and save contact information in the Linq application.

---

**Steps and Expected Results:**

1. **Step:** Login to the Linq application as an authorized user  
   **Expected Result:** User is able to login to the Linq application  

2. **Step:** On Linq application, verify Phone number field is displayed  
   **Expected Result:** Phone number field is displayed  

3. **Step:** Do not enter a value in the phone number field and click Continue  
   **Expected Result:** Error "phone number is required" is displayed  

4. **Step:** Verify user is able to enter only numbers in the phone number field  
   **Expected Result:** Phone number field is numeric and user is not able to enter alphanumeric value  

5. **Step:** Enter more than 10 digits in the phone number and click on Continue  
   **Expected Result:** Error "please enter a valid phone number" is displayed  

6. **Step:** Enter a valid phone number and click on Continue  
   **Expected Result:** Sign up page is displayed  

7. **Step:** On Sign up page, Enter First and Last name, Email, and click on Continue  
   **Expected Result:** Phone number is autopopulated in the phone number field  
   **Then:** Professional details page is displayed  

8. **Step:** On Professional details page, select/enter the requested details and click Continue  
   **Expected Result:** Profile Image page is displayed  

9. **Step:** On Profile Image page, click Add Profile Image, take photo, save, and click Create Page  
   **Expected Result:** LinqOne page is displayed with Get Started button  

10. **Step:** Click Close on LinqOne page  
    **Expected Result:** Quick Actions are displayed with Edit Profile  

11. **Step:** Click Edit Profile and verify the profile details  
    **Expected Result:** Profile details are displayed correctly  

12. **Step:** Navigate to previous page and verify Add your first contact radio button is displayed under Next Steps  
    **Expected Result:** "Add your first contact" radio button is displayed  

13. **Step:** Select "Add your first contact" radio button  
    **Expected Result:** New Contact page is displayed  

14. **Step:** On New Contact page, enter requested details and click Save Changes  
    **Expected Result:** Contact info is saved successfully