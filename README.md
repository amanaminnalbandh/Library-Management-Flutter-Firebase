# 📚 Library Management System (Flutter & Firebase)

A professional, full-stack library management solution built as part of the Mobile Application Development II (MAD-II) curriculum. This project demonstrates advanced Flutter state management, secure authentication, and real-time cloud synchronization using Google Firebase.

---

## 🎓 Academic Credentials
* **Developer:** Amanul Amin Nalbandh (Aman)
* **Degree:** Bachelor of Computer Applications (BCA)
* **University:** Bhagwan Mahavir University
* **Enrollment No:** 2302020101243
* **Course:** Mobile Application Development II (MAD-II)

---

## 🎯 Project Objectives
The system was designed to meet a rigorous set of academic and technical requirements:
* **Authentication Module:** Secure user access with form validation and password encryption.
* **Book Module (CRUD):** Complete management of library inventory including Title, Author, ISBN, and Quantity.
* **Data Persistence:** Hybrid storage approach using both browser local storage and Cloud Firestore.
* **UI/UX Standards:** Global themed design utilizing a professional orange color scheme.

## 🛠️ Technical Stack
* **Frontend:** Flutter (Web/Mobile)
* **Backend:** Firebase Authentication & Cloud Firestore
* **Security:** SHA-256 Password Hashing
* **State Management:** Provider Pattern
* **Version Control:** Git & GitHub

## ✨ Key Features

### 1. Secure Authentication
* **Regex Validation:** Strict email format checking and minimum 6-character password enforcement.
* **Encryption:** Passwords are hashed using the SHA-256 algorithm before reaching the database, ensuring they are never stored in plain text.
* **Named Routing:** Implemented URL-based navigation (`/`, `/register`, `/dashboard`) for a seamless web experience.

### 2. Intelligent Book Module
* **Dynamic Dashboard:** Real-time display of the library catalog.
* **Hybrid CRUD Storage:**
  * *Local:* Data is cached in the browser using JSON format via `SharedPreferences`.
  * *Cloud:* Direct synchronization with a Firebase NoSQL database for global accessibility.
* **Data Testing:** Specifically tested with specialized technical titles like *Generative AI* & *LLM Engineering*.

## 🚀 Installation & Setup

**1. Clone the Repository:**
```bash
git clone [https://github.com/amanbuilds1/Library-Management-Flutter-Firebase.git](https://github.com/amanbuilds1/Library-Management-Flutter-Firebase.git)
cd Library-Management-Flutter-Firebase
