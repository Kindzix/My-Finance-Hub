# My Finance Hub 💰

A simple, mobile-first personal finance application contained entirely within a single HTML file. Built with Vanilla JavaScript and powered by Firebase for authentication and real-time data storage.

## ✨ Features

* **Yearly & Monthly Overview:** Navigate easily between different fiscal years and months.
* **Income & Expense Tracking:** Log transactions with categories and descriptions.
* **Real-time Calculations:** Automatically calculates "Free Funds" based on income, expenses, and savings.
* **Savings Goals:** allocate money to specific buckets (Emergency Fund, Vacation, Unexpected).
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
4. Open `index.html` and locate the `firebaseConfig` object (around line 140).
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


PL
# My Finance Hub 💰

Prosta aplikacja typu "Mobile-First" do zarządzania finansami osobistymi, zawarta w całości w jednym pliku HTML. Zbudowana przy użyciu czystego JavaScript (Vanilla JS) i zasilana przez Google Firebase do uwierzytelniania i przechowywania danych w czasie rzeczywistym.

## ✨ Główne Funkcje

* **Przegląd Roczny i Miesięczny:** Łatwa nawigacja między latami podatkowymi i poszczególnymi miesiącami.
* **Śledzenie Wpływów i Wydatków:** Rejestrowanie transakcji z podziałem na kategorie, źródła i opisy.
* **Obliczenia w Czasie Rzeczywistym:** Automatyczne wyliczanie "Wolnych środków" na podstawie dochodów, wydatków i oszczędności.
* **Cele Oszczędnościowe (Skarbonki):** Alokacja pieniędzy na konkretne cele (Poduszka Finansowa, Wakacje, Nagłe Wydatki).
* **Planer Wakacji:** Ustalanie budżetów na wyjazdy i śledzenie konkretnych kosztów wakacyjnych względem założonego budżetu.
* **Raporty Roczne:** Podsumowanie finansów dla wybranego roku w formie czytelnego zestawienia.
* **Zoptymalizowany pod Mobile:** Responsywny design i obsługa gestów przesunięcia (swipe) do nawigacji "Wstecz".
* **Synchronizacja w Chmurze:** Bezpieczne przechowywanie danych w bazie Firebase Firestore.

## 🛠️ Technologie

* **Frontend:** HTML5, CSS3 (osadzony), Vanilla JavaScript (ES Modules).
* **Backend/Baza danych:** Firebase Firestore.
* **Uwierzytelnianie:** Firebase Auth (Email/Hasło).
* **Architektura:** Single File Application (Brak skomplikowanego procesu budowania/kompilacji).

## 🚀 Instalacja i Konfiguracja

Ponieważ jest to aplikacja działająca po stronie klienta (client-side) korzystająca z Firebase, musisz skonfigurować własny projekt Firebase, aby z niej korzystać.

### 1. Sklonuj repozytorium
```bash
git clone [https://github.com/TWOJ_NICK/my-finance-hub.git](https://github.com/TWOJ_NICK/my-finance-hub.git)
cd my-finance-hub
