# My Finance Hub 💰

A simple, mobile-first personal finance application contained entirely within a single HTML file. Built with Vanilla JavaScript and powered by Firebase for authentication and real-time data storage.

* **For English version:** Use `index.html`
* **For Polish version:** Use `index_pl.html`

## ✨ Features

* **Yearly & Monthly Overview:** Navigate easily between different fiscal years and months.
* **Income & Expense Tracking:** Log transactions with categories and descriptions.
* **Real-time Calculations:** Automatically calculates "Free Funds" based on income, expenses, and savings.
* **Savings Goals:** Allocate money to specific buckets (Emergency Fund, Vacation, Unexpected).
* **Vacation Planner:** Set budgets for trips and track specific vacation-related costs against that budget.
* **Annual Reports:** View a summarized breakdown of your finances for the selected year.
* **Mobile Optimized:** Responsive design with swipe gestures for navigation.
* **Cloud Sync:** Data is stored securely in Google Firebase Firestore.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Embedded), Vanilla JavaScript (ES Modules).
* **Backend/Database:** Firebase Firestore.
* **Authentication:** Firebase Auth (Email/Password).
* **Architecture:** Single File Application (No build steps required).

## 🚀 Setup & Installation

Since this is a client-side application using Firebase, you need to set up your own Firebase project to use it.

## Configuration

This project uses Firebase (Firestore & Auth). To make it work:

1. Create a project at [Firebase Console](https://console.firebase.google.com/).
2. Enable **Firestore Database** and **Authentication** (Email/Password provider).
3. Copy your web app configuration.
4. Open `index.html` (or `index_pl.html`) and locate the `firebaseConfig` object (around line 140).
5. Replace the placeholder values with your actual Firebase credentials:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT_ID.firebasestorage.app",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
