# 🔍 aDreamDe – GitHub User & Post Finder

A clean and interactive frontend project that allows users to search for any GitHub user by **username**, display their **profile information**, and fetch their **public repositories** — all using **HTML**, **CSS**, and **JavaScript**, with data dynamically fetched from the GitHub REST API.

🚀 **Live Demo**: [Click here to view](https://sanaullah-7.github.io/UserFind/)  
📦 **API Source**: [GitHub Users API](https://api.github.com)

---

## 📖 Project Description

This is a single-page web app where users can:

- Enter a GitHub **username** in the input field.
- View that user’s **ID**, **Name**, and **Email** (if available).
- Click on a **“Get Posts”** button to view that user’s public **repositories** as “posts”.

The app fetches real-time data from the GitHub REST API using the `fetch()` method. It demonstrates how to work with asynchronous JavaScript, conditional rendering, and DOM manipulation.

This project is 100% frontend and doesn’t require a backend or database. It is a great exercise in working with APIs and building real-world UIs with plain JavaScript.

---

## 📌 Features

- 🔍 Search GitHub users by their username
- 📋 Display user info: `Name`, `User ID`, `Email`
- 📘 Fetch and show public repositories with:
  - Repo `ID`
  - Repo `Name`
- ⚠️ Show “User not found” message if input is invalid
- ⚡ Responsive and interactive design

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- GitHub REST API (`https://api.github.com/users/`)  
- GitHub Pages (for deployment)

---

## 📂 Project Structure

```bash
.
├── index.html        # Main HTML file with input/search UI
├── script.js         # Contains fetch logic and DOM manipulation
├── style.css         # Styling for cards, layout, and buttons
└── README.md         # Project documentation
