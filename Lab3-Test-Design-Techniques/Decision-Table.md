# 🧪 Decision Table Testing

## 🎯 Objective

The purpose of this test is to verify form validation by checking different combinations of user inputs using the **Decision Table** test design technique.

---

## 📋 Test Information

**Form Fields**

- Name
- Email
- Mobile Number

---

## 📊 Decision Table

| Rule | Name Entered | Valid Email | 10-Digit Mobile Number | Expected Result |
|------|:------------:|:-----------:|:-----------------------:|-----------------|
| 1 | ✅ Yes | ✅ Yes | ✅ Yes | Form is submitted successfully. |
| 2 | ❌ No | ❌ No | ❌ No | Error messages are displayed for all required fields, and the form is not submitted. |
| 3 | ✅ Yes | ❌ No | ✅ Yes | An error message is displayed for the **Email** field. |
| 4 | ✅ Yes | ✅ Yes | ❌ No | An error message is displayed for the **Mobile Number** field. |
| 5 | ❌ No | ✅ Yes | ✅ Yes | An error message is displayed for the **Name** field. |
| 6 | ❌ No | ❌ No | ✅ Yes | Error messages are displayed for the **Name** and **Email** fields. |

---

## 📝 Conclusion

Decision Table Testing is used to validate different combinations of input conditions and their expected outcomes. This technique ensures that business rules are tested efficiently by covering both valid and invalid scenarios with a minimal number of test cases.
