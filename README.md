- <p align="center"> <img src="https://img.shields.io/badge/React-18.0.0-61DAFB?style=flat&logo=react" /> <img src="https://img.shields.io/badge/TailwindCSS-v3-38B2AC?style=flat&logo=tailwindcss" /> <img src="https://img.shields.io/badge/License-MIT-green.svg" /> <img src="https://img.shields.io/badge/Status-Active-brightgreen" /> </p>

- A modern and secure Password Manager built with React, designed to store and manage passwords locally in your browser using localStorage.
- The app supports add, edit, delete, show/hide, copy to clipboard, and includes toast alerts for a smooth user experience.

  **🚀 Features**

- 🔑 Save Passwords with website, username, and password

- 👁️ Show/Hide Passwords

- 📋 Copy to Clipboard

- ✏️ Edit & Delete Entries

- 💾 LocalStorage Persistence

- ☑️ Unique IDs using UUID

- 🔔 Toast Notifications

- 🎨 Responsive UI with Tailwind CSS

**🛠️ Tech Stack**
**Technology**	               **Description**
- React.js	                  Frontend framework
- Tailwind CSS	              Styling
- UUID	Unique ID             generation
- React-Toastify	            Notifications
- LocalStorage	              Data persistence

- **react-password-manager/**
- ├── src/
- │   ├── components/
- │   │   └── Manager.jsx
- │   ├── App.jsx
- │   ├── main.jsx
- │   ├── index.css
- ├── package.json
- └── README.md

**🧩 How It Works**

- User inputs:

- Website

- Username

- Password

- A unique ID is generated using UUID.

- Data is saved into localStorage.

- User can view, copy, edit, or delete passwords.

- UI updates instantly without page reload.
