# Bug Reports

## 📌 Overview
This section contains real-style QA defect reports based on ERP and SaaS testing scenarios.

---

## 🧩 Real Testing Context
Bugs were identified during:
- ERP system testing (Inventory, Purchase, CRM)
- API testing (Postman)
- Feature validation based on requirements

---

## 🐞 Sample Bug Reports

🐞 BUG-001
**Title:** System allows creating Purchase Order without selecting Supplier

**Feature:** Purchase Orders  
**Severity:** High  
**Priority:** High  

**Steps to Reproduce:**
1. Open Purchase Orders module
2. Click Create
3. Do not select Supplier
4. Add products
5. Click Save

**Expected Result:**
System should display validation error and prevent saving

**Actual Result:**
Purchase Order is created successfully without Supplier

🐞 BUG-002
**Title:** API accepts invalid OTP format during verification

**Feature:** Authentication API  
**Severity:** Medium  
**Priority:** Medium  

**Steps:**
1. Send OTP verification request via Postman
2. Enter invalid format (string instead of numeric OTP)

**Expected Result:**
System should return validation error (400 Bad Request)

**Actual Result:**
Request is accepted and processed

🐞 BUG-003
**Title:** Inventory quantity not updated after transfer approval

**Feature:** Inventory Management  
**Severity:** High  
**Priority:** High  

**Steps:**
1. Create transfer request
2. Approve transfer
3. Check inventory quantity

**Expected Result:**
Inventory should update correctly after approval

**Actual Result:**
Quantity remains unchanged or incorrect

---

## 📊 QA Standards Used

All bug reports follow standard QA format:
- Clear reproduction steps
- Severity & Priority classification
- Expected vs Actual results
- Business impact awareness

---

## 🎯 Outcome
Demonstrates ability to identify, document, and communicate defects in real ERP and API systems.
