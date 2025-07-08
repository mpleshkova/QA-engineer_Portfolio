# 👤 User Profile Test Cases

Test cases covering personal data management, password change, preferences, and address handling.

---

### ✅ TC001: Update Personal Information  
**Type:** Positive, Functional  
**Steps:**  
1. Log in to the user account  
2. Go to “My Profile”  
3. Edit personal details (e.g., name, phone number)  
4. Click “Save”  

**Expected:** Changes are saved, and confirmation message appears

---

### ✅ TC002: Change Password with Valid Credentials  
**Type:** Positive, Functional  
**Steps:**  
1. Log in to the user account  
2. Go to “Change Password”  
3. Enter current password and new password  
4. Click “Save”  

**Expected:** Password is changed successfully, user is prompted to log in again

---

### ❌ TC003: Change Password with Incorrect Current Password  
**Type:** Negative, Validation  
**Steps:**  
1. Go to “Change Password”  
2. Enter incorrect current password and new password  
3. Click “Save”  

**Expected:** Error message is displayed: "Incorrect current password"

---

### ✅ TC004: Add New Address  
**Type:** Positive, Functional  
**Steps:**  
1. Navigate to “My Addresses”  
2. Click “Add New Address”  
3. Fill in address details  
4. Save the address  

**Expected:** Address is added and listed under saved addresses

---

### ❌ TC005: Add Address with Missing Required Fields  
**Type:** Negative, Validation  
**Steps:**  
1. Go to “Add New Address”  
2. Leave required fields (e.g., ZIP code) empty  
3. Click “Save”  

**Expected:** Validation error message appears, preventing form submission

---

### ✅ TC006: Enable or Disable Email Notifications  
**Type:** Positive, Functional  
**Steps:**  
1. Go to “Notification Settings”  
2. Toggle the email notifications option  
3. Click “Save”  

**Expected:** Preferences are saved, and user receives feedback confirmation

---

### ✅ TC007: View Order History  
**Type:** Positive, Functional  
**Steps:**  
1. Log in to the user account  
2. Go to “Order History”  

**Expected:** List of past orders is displayed with status and details

---

### ❌ TC008: Access Profile Without Logging In  
**Type:** Negative, Security  
**Steps:**  
1. Try to access the profile page via direct URL without being logged in  

**Expected:** User is redirected to login page with an access restriction message
