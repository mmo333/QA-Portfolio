# Bug Reports

## 📌 Overview
Sample QA bug reports written in real defect format.

---

## 🐞 BUG-001

**Title:** Purchase Order can be created without supplier

**Severity:** High

**Steps:**
1. Open Purchase Orders
2. Click Create
3. Leave Supplier empty
4. Save

**Expected:**
System should block saving

**Actual:**
System allows creation

---

## 🐞 BUG-002

**Title:** Invalid OTP accepted

**Severity:** Medium

**Steps:**
1. Send random OTP format
2. Submit request

**Expected:**
Validation error

**Actual:**
Request accepted

---

## 📊 QA Standards

All bugs follow industry-standard structure:
- Clear reproduction steps
- Severity classification
- Expected vs Actual results
- Business impact awareness
