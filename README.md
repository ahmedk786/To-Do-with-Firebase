

---

# 📋 Todo App

A simple Todo application built using **HTML**, **CSS**, **JavaScript**, and **Firebase**. This app allows users to **add**, **view**, **edit**, and **delete** their tasks in real time, with data stored in Firebase Firestore.

## 🚀 Features

* ✅ Add new tasks
* 📝 Edit existing tasks
* ❌ Delete tasks
* ☁️ Real-time sync with Firebase Firestore
* 🎨 Responsive UI

## 🔧 Tech Stack

* **Frontend
3. **Add Firebase Config to your App:**
   In your `script.js` (or wherever you initialized Firebase), paste your Firebase config like this:

   ```js
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_STORAGE_BUCKET",
     messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
     appId: "YOUR_APP_ID"
   };

   firebase.initializeApp(firebaseConfig);
   ```

4. **Run the App:**
   Just open `index.html` in your browser.

## 📁 Project Structure

```
todo-app/
│
├── index.html         # Main HTML file
├── style.css          # Stylesheet
├── script.js          # JavaScript logic with Firebase integration
└── README.md          # Project information
```

## 📌 Future Improvements

* User Authentication
* Task due dates & reminders
* Dark mode
* Mobile PWA support

## 📄 License

This project is licensed under the MIT License.

---


# To-Do-with-Firebase
