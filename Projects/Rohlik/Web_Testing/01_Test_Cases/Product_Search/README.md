# 🔍 Product Search Test Cases
Test cases covering product search, filters, suggestions, and empty results.

---

### ✅ TC001: Search by Full Product Name  
**Type:** Positive, Functional  
**Steps:**  
1. Navigate to the homepage  
2. Enter full product name (e.g., "Bananas") in the search bar  
3. Press "Enter" or click the search icon
   
**Expected:** Relevant product appears in search results

---

### ✅ TC002: Search by Partial Product Name  
**Type:** Positive, Functional  
**Steps:**  
1. Navigate to the homepage  
2. Enter partial product name (e.g., "Ban")  
3. Press "Enter" or click the search icon
   
**Expected:** List of products matching the partial query appears

---

### ✅ TC003: Search by Category Name  
**Type:** Positive, Functional  
**Steps:**  
1. Navigate to the homepage  
2. Enter category name (e.g., "Fruits")  
3. Press "Enter"
   
**Expected:** List of all products in the selected category appears

---

### ❌ TC004: Search with Special Characters  
**Type:** Negative, Validation  
**Steps:**  
1. Enter special characters (e.g., "@#$%") in the search bar  
2. Press "Enter"

**Expected:** Message shown like "No results found" or validation message

---

### ❌ TC005: Search for Non-Existent Product  
**Type:** Negative, Functional  
**Steps:**  
1. Enter a product name that doesn’t exist (e.g., "xyzabc123")  
2. Press "Enter"

**Expected:** User sees "No results found" or a friendly empty state message

---

### ✅ TC006: Autocomplete Suggestions  
**Type:** Positive, UX  
**Steps:**  
1. Start typing a valid product name  
2. Observe dropdown with suggestions
   
**Expected:** Autocomplete dropdown appears with relevant suggestions

---

### ✅ TC007: Search with Filters (e.g., Price Range, Brand)  
**Type:** Positive, Functional  
**Steps:**  
1. Search for a common term (e.g., "milk")  
2. Apply filters such as price range and brand
   
**Expected:** Product list updates according to selected filters

---

### ✅ TC008: Clear Search Functionality  
**Type:** Positive, UI/UX  
**Steps:**  
1. Enter a query in the search bar  
2. Click the "X" or "Clear" icon
   
**Expected:** Search bar is cleared and product listing resets or search history shown

---

## 📂 Files

| File Name                                       | Description                                |
|------------------------------------------------|--------------------------------------------|
| [`Rohlik_Web_Test_Cases_Product_Search.csv`](./Rohlik_Web_Test_Cases_Product_Search.csv) | Structured test cases in CSV format for easy viewing, editing, and importing into test management tools |

