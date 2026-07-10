# 🔍 Chrome DevTools Report

This report demonstrates the use of **Chrome DevTools** to inspect and analyze the OrangeHRM web application.

---

# 1. Opening Chrome DevTools

### Steps
- Open the OrangeHRM website.
- Press **F12** to launch Chrome DevTools.

### Result

Chrome DevTools opened successfully.

![Opening Chrome DevTools](screenshots/01-open-devtools.png)

---

# 2. Checking the Login Request Status Code

### Steps

- Open the **Network** tab.
- Log in to the OrangeHRM application.
- Select the **/auth/validate** request.

### Result

**Status Code:** `302 Found`

This status code indicates that the user was successfully authenticated and redirected to another page.

![Status Code](screenshots/02-status-code.png)

---

# 3. Checking Cookies

### Steps

- Open **Application → Cookies**.
- Select the current domain.

### Result

The session cookie created by the application was displayed successfully.

![Cookies](screenshots/03-cookies.png)

---

# 4. Checking Local Storage

### Steps

- Open **Application → Local Storage**.
- Select the OrangeHRM domain.

### Result

Application data was stored successfully in **Local Storage** as **Key–Value** pairs.

![Local Storage](screenshots/04-local-storage.png)

---

# 5. Deleting Cookies

### Steps

- Delete all cookies for the current domain.

### Result

All cookies were removed successfully.

![Delete Cookies](screenshots/05-delete-cookie.png)

---

# 6. Refreshing the Page

### Steps

- Refresh the page (**F5**) after deleting the cookies.

### Result

Since the session became invalid, the application redirected the user back to the **Login** page.

![Refresh Page](screenshots/06-refresh-page.png)

---

# 7. Network Throttling (3G)

### Steps

- Open the **Network** tab.
- Change the throttling option to **Fast 3G** (or 3G).
- Refresh the page.

### Result

The page loaded more slowly, and network request times increased due to the reduced network speed.

![Network Throttling](screenshots/07-network-throttling.png)

---

# 8. Checking the Console

### Steps

- Open the **Console** tab.

### Result

No JavaScript errors were detected during testing.

![Console](screenshots/08-console.png)

---

# 📝 Conclusion

This laboratory demonstrates how Chrome DevTools can be used to inspect HTTP requests, browser storage, cookies, network performance, and console logs while testing a web application. It also shows how browser developer tools help QA engineers identify issues related to authentication, sessions, storage, and client-side behavior.
