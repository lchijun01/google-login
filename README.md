# Google Login Demo

This project is a simple demo showing how to integrate **Google Sign-In** using the [Google Identity Services](https://developers.google.com/identity) with a Node.js backend.

## 🔧 Features

- Google One Tap & Sign-In Button
- Backend token verification
- Display user profile after login
- LocalStorage to keep session
- Responsive UI
- Logout support

---

## 📦 Technologies

- HTML/CSS (Frontend)
- Node.js + Express (Backend)
- Google Identity Services
- `google-auth-library` for token verification

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/lchijun01/google-login.git
cd google-login
```

### 2. Install backend dependencies
```
npm install
```
### 3. Create .env file
```
GOOGLE_CLIENT_ID=your-google-client-id
PORT=3000
```
Get your Client ID from Google Cloud Console.

### 4. Run the app
```
node server.js
```
Visit: http://localhost:3000