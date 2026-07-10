# 🐞 Bug Report #002

## 📌 Bug Information

| Field | Value |
|--------|-------|
| **Bug ID** | BUG_2 |
| **Title** | Student Name Field Accepts Special Characters |
| **Priority** | Medium |
| **Severity** | Medium |
| **Status** | Open |
| **Reported By** | Ləman Qurbanova |
| **Date Reported** | 20 June 2026 |

---

## 📝 Description

On the **qa-practice.com** website, the **First Name** field accepts special characters such as `#`, `$`, `%`, `^`, `&`, and `*`. The form is submitted successfully even though the input is invalid.

---

## 🔄 Steps to Reproduce

1. Open the **qa-practice.com** website.
2. Navigate to **Forms → Practice Forms**.
3. Enter `#$%^&*(` into the **First Name** field.
4. Fill in the remaining required fields with valid data.
5. Click the **Submit** button.

---

## ✅ Expected Result

The system should display a validation error message and prevent the form from being submitted when special characters are entered into the **First Name** field.

---

## ❌ Actual Result

The form is submitted successfully even though the **First Name** field contains only special characters.

---

## 📊 Additional Information

- **Priority:** Medium
- **Severity:** Medium
- **Status:** Open
