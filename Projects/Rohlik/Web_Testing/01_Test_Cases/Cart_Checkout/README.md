# 🛒 Cart & Checkout Test Cases

Test cases covering cart actions, delivery selection, and payment flow.

---

### ✅ TC001: Add Product to Cart  
**Type**: Positive, Functional  
**Steps**:  
1. Navigate to the product listing page  
2. Select a product  
3. Click “Add to Cart”  
**Expected**: Product is added to cart, cart icon count increases  

---

### ✅ TC002: Remove Product from Cart  
**Type**: Positive, Functional  
**Steps**:  
1. Open cart  
2. Click “Remove” next to a product  
**Expected**: Product is removed from cart, total is updated  

---

### ✅ TC003: Update Product Quantity in Cart  
**Type**: Positive, Functional  
**Steps**:  
1. Add a product to cart  
2. Change the quantity to 3  
**Expected**: Quantity updates correctly, total price recalculates  

---

### ✅ TC004: Apply Valid Voucher  
**Type**: Positive, Functional  
**Steps**:  
1. Open cart  
2. Enter a valid voucher code  
3. Click “Apply”  
**Expected**: Voucher is accepted, and corresponding discount is applied to the total amount  

---

### ❌ TC005: Apply Invalid Voucher  
**Type**: Negative, Validation  
**Steps**:  
1. Open cart  
2. Enter an invalid or expired voucher code  
3. Click “Apply”  
**Expected**: Error message is displayed indicating the voucher is invalid or expired; no discount is applied  

---

### ✅ TC006: Verify Cart Persists After Page Refresh  
**Type**: Positive, Functional  
**Steps**:  
1. Add one or more products to the cart  
2. Refresh the page (F5 or browser reload)  
3. Open the cart  
**Expected**: Previously added products remain in the cart; quantities and prices are preserved  

---

### ✅ TC007: Select Delivery Option  
**Type**: Positive, Functional  
**Steps**:  
1. Proceed to checkout  
2. Choose from available delivery slots  
**Expected**: Selected slot is saved and shown in order summary  

---

### ✅ TC008: Payment with Valid Card  
**Type**: Positive, Functional  
**Steps**:  
1. On payment page  
2. Enter valid card details  
3. Submit payment  
**Expected**: Payment is processed, user sees confirmation  

---

### ❌ TC009: Payment with Expired Card  
**Type**: Negative, Validation  
**Steps**:  
1. On payment page  
2. Enter expired card details  
3. Submit payment  
**Expected**: Error message appears, payment is not processed  

---

### ❌ TC010: Checkout with Empty Cart  
**Type**: Negative, UI/UX  
**Steps**:  
1. Open cart (empty)  
2. Click “Checkout”  
**Expected**: Warning message appears or button is disabled
