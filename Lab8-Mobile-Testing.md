# 📱 Lab 8 – Mobile Testing Report

## 🎯 Objective

The purpose of this laboratory is to verify the mobile application's stability, responsiveness, and functionality under different devices, orientations, lifecycle states, and network conditions.

---

# ✅ Test Cases

## 1. UI/UX Testing

**Checking**
- The application's UI was tested on different devices (iPhone 13 Pro and Pixel 8).

**Expected Result**
- The UI should be displayed correctly on all devices, and the responsive design should work properly.

**Actual Result**
- The UI was displayed correctly on both devices.
- Responsive design worked as expected.

**Status:** ✅ PASS

---

## 2. Background / Lifecycle Testing

**Checking**
- The application was sent to the background for 5 minutes and then reopened.

**Expected Result**
- The application should continue working normally after reopening.
- User data should be preserved.
- No crashes or errors should occur.

**Actual Result**
- The application resumed successfully after 5 minutes.
- Data remained unchanged.
- No crashes or unexpected behavior were observed.

**Status:** ✅ PASS

---

## 3. Orientation Testing

**Checking**
- Portrait and Landscape modes were tested.

**Expected Result**
- The UI should adapt correctly without delays.

**Actual Result**
- The UI adjusted correctly.
- A slight delay was observed while refreshing the screen.

**Status:** ✅ PASS

---

## 4. Network Testing

**Checking**
- The application was tested under **4G** and **Offline Mode**.

**Expected Result**
- The application should remain stable when the network connection is lost and restored.
- No freezing or error messages should appear.

**Actual Result**
- Internet connection was disabled and enabled again.
- The application remained stable in both conditions.

**Status:** ✅ PASS

---

## 5. Functionality Testing

**Checking**
- The main application features were tested.

**Expected Result**
- All core features should work correctly.

**Actual Result**
- Core functionality worked successfully.
- Minor delays were observed during some screen transitions.

**Status:** ✅ PASS

---

# 📊 Test Summary

| Result | Count |
|---------|------:|
| ✅ PASS | **5** |
| ❌ FAIL | **0** |

---

# 🧪 Tested Areas

- UI/UX Testing
- Background / Lifecycle Testing
- Orientation Testing
- Performance Testing
- Network Testing
- Functionality Testing

---

# 📱 Tested Devices

- Google Pixel 8
- Apple iPhone 13 Pro

---

# 💻 Tested Operating Systems

- Android 15.0
- iOS 18.2

---

# 🌐 Tested Network Conditions

- 4G
- Offline Mode

---

# 📝 Conclusion

The mobile application performed successfully across different devices, operating systems, and network conditions. No critical defects or crashes were observed during testing. Minor UI transition delays were noticed but did not affect the overall functionality of the application.
