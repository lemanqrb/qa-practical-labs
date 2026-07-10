# 🧪 Boundary Value Analysis (BVA)

## 🎯 Objective

The purpose of this test is to verify the validation of the **Mobile Number** field using the **Boundary Value Analysis (BVA)** technique.

---

## 📋 Test Information

**Field:** Mobile Number

**Validation Rule:** The field must contain **exactly 10 digits**.

---

## 📊 Boundary Test Cases

| Boundary Value | Expected Result |
|----------------|-----------------|
| 9 digits | ❌ Validation error should be displayed. |
| 10 digits | ✅ Input should be accepted successfully. |
| 11 digits | ❌ Validation error should be displayed. |

---

## 📝 Conclusion

Boundary Value Analysis focuses on testing values at the edges of valid input ranges. Since the Mobile Number field accepts exactly **10 digits**, the boundary values are:

- **9 digits** → Invalid
- **10 digits** → Valid
- **11 digits** → Invalid

Testing these boundary values helps identify validation issues that commonly occur at input limits.
