# 📓 Contact Management System

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tech](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-orange)

A modern, responsive, web-based Contact Manager application designed with a sleek "Laptop Window" user interface. This application allows users to store, manage, and dial contacts, utilizing **Local Storage** for data persistence so your contacts remain
 saved even after refreshing the browser.

---

## 📸 Screenshots

![App Interface](./screenshots/dialer-view.png)
*The Dialer Interface*

![Contact List](./screenshots/contact-list.png)
*The Contact Management List*

---

## 🚀 Features

* **Dual View Interface:**
    * **📱 Keypad/Dialer:** A realistic phone keypad implementation to type numbers manually.
    * **👥 Contact List:** A grid view of all saved contacts with management options.
* **CRUD Operations:** Create, Read, Update, and Delete contacts seamlessly.
* **Data Persistence:** Uses the browser's `localStorage` API to save data (works like a client-side database).
* **Smart Interactions:**
    * "Create Contact" shortcut appears automatically when typing a number in the dialer.
    * Visual feedback and Toast notifications for actions (Success/Error).
    * Confirmation modals before deletion to prevent accidents.
* **Modern UI/UX:**
    * Glassmorphism-inspired design.
    * Smooth CSS animations and transitions.
    * Responsive layout styled as a desktop application window.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:** Flexbox, Grid, CSS Variables (Custom Properties), and Keyframe animations.
* **JavaScript (ES6+):** DOM manipulation, Event handling, and LocalStorage logic.

---

## 📂 Project Structure

```text
contact-management-system/
├── index.html        # Main HTML file containing structure and logic
├── assets/           # (Optional) Folder for icons/images
├── screenshots/      # Folder for README images
└── README.md         # Project documentation
