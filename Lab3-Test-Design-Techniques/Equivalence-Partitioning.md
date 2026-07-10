# 🧪 Equivalence Partitioning (EP)

## 🎯 Objective

The purpose of this test is to verify the validation of the **Mobile Number** field, which should accept **exactly 10 digits**.

---

## 📋 Test Information

**Field:** Mobile Number

**Validation Rule:** The field accepts exactly **10 digits**.

---

## 📊 Test Cases

| Test Class | Test Data | Expected Result |
|------------|-----------|-----------------|
| Invalid (Below Range) | `123456788` | An error message should be displayed, and the form should not be submitted. |
| Valid | `2355955671` | The form should be submitted successfully. |
| Invalid (Above Range) | `23334674801` | The user should not be able to enter the 11th digit. The field should accept a maximum of 10 digits. |

---

## 📝 Conclusion

Equivalence Partitioning divides the input data into **valid** and **invalid** partitions. Testing one representative value from each partition helps reduce the number of test cases while maintaining effective validation coverage.
