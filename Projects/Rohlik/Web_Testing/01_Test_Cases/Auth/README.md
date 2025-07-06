# 🔐 Authentication Test Cases

Test scenarios validating login, registration, and password recovery flows.

---

### ✅ TC001: Successful Login  
**Type:** Positive, Functional  
**Steps:**  
1. Go to the login page  
2. Enter valid email and valid password  
3. Click "Log In"  

**Expected:** User is logged in and redirected to homepage or previous page  

---

### ❌ TC002: Login with Incorrect Password  
**Type:** Negative, Functional  
**Steps:**  
1. Go to the login page  
2. Enter valid email and incorrect password  
3. Click "Log In"  

**Expected:** Error message displayed: "Invalid email or password"

---

### ❌ TC003: Login with Empty Fields  
**Type:** Negative, UI Validation  
**Steps:**  
1. Go to the login page  
2. Leave email and password fields empty  
3. Click "Log In"  

**Expected:** Form displays validation errors under each field  

---

### ❌ TC004: Login with Invalid Email Format  
**Type:** Negative, UI Validation  
**Steps:**  
1. Go to the login page  
2. Enter email like `user@rohlik` and a random password  
3. Click "Log In"  

**Expected:** Email field shows format validation error  

---

### 🔁 TC005: Password Recovery (Valid Email)  
**Type:** Positive, Functional  
**Steps:**  
1. Go to login page  
2. Click "Forgot Password?"  
3. Enter registered email  
4. Submit form  

**Expected:** Success message: “Reset instructions sent to your email”

---

### ❌ TC006: Password Recovery (Unregistered Email)  
**Type:** Negative, Functional  
**Steps:**  
1. Go to login page and click "Forgot Password?"  
2. Enter unregistered email  
3. Submit form  

**Expected:** Error message: “Email not found”

---

### ✍️ TC007: Successful Registration  
**Type:** Positive, Functional  
**Steps:**  
1. Go to registration page  
2. Fill in required fields with valid data  
3. Accept terms and click "Register"  

**Expected:** User is created and logged in automatically  

---

### ❌ TC008: Registration with Existing Email  
**Type:** Negative, Functional  
**Steps:**  
1. Go to registration page  
2. Enter email already used  
3. Fill in rest of the form  
4. Click "Register"  

**Expected:** Error message: “Email already registered”

---

### ❌ TC009: Registration with Weak Password  
**Type:** Negative, UX Validation  
**Steps:**  
1. Go to registration page  
2. Enter valid email and weak password (e.g. `123`)  
3. Click "Register"  

**Expected:** Password field shows strength error / form is not submitted  

---

## 📂 Files

| File Name                                       | Description                                |
|------------------------------------------------|--------------------------------------------|
| [`Rohlik_Web_Test_Cases_Auth.csv`](./Rohlik_Web_Test_Cases_Auth.csv) | Structured test cases in CSV format for easy viewing, editing, and importing into test management tools |
