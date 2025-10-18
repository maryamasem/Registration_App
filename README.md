# 🧾 Registration App

A modern **Registration and Authentication App** built with **Kotlin** and **Firebase Authentication**, providing a smooth and secure user experience.

---

## 🚀 Features

✅ **User Registration (Sign Up)**
- Create a new account using an email and password
- Validates input fields before submission

✅ **User Login**
- Secure login using Firebase Authentication
- Supports “One-Time Login” (remembers session until the user logs out manually)

✅ **Email Verification**
- Sends a verification link to the user’s email after registration
- Prevents unverified users from accessing the main content

✅ **Forgot Password**
- Users can easily reset their password via email

✅ **One-Time Login**
- Keeps the user logged in after the first successful login
- Redirects directly to the main screen on app launch if already authenticated

---

## 🧠 Tech Stack

- **Language:** Kotlin
- **UI:** XML 
- **Backend:** Firebase Authentication
- **IDE:** Android Studio

---

## ⚙️ How It Works

1. **Sign Up:**
   - Enter email and password
   - A verification email is sent to confirm the account

2. **Login:**
   - Enter credentials
   - If email is verified → navigate to Home screen
   - If not verified → prompt user to verify email

3. **Forgot Password:**
   - Enter registered email to receive password reset link

4. **One-Time Login:**
   - Firebase remembers the current session
   - Users stay logged in until they log out manually
