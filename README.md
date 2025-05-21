# 🔍 aDreamDe GitHub User & Post Finder

This project allows you to search any GitHub user by **username**, view their profile details, and retrieve their **public repositories** using GitHub's REST API.

---

## 🚀 Features

- ✅ Search GitHub users by **username**
- 📄 Show user info: **Name**, **ID**, **Email** (if public)
- 📦 List all **public repositories (posts)** of the user
- 📘 Each post shows its **repository ID** and **name**
- ❌ Displays "User not found" if username is invalid

---

## 🔗 GitHub API Endpoints Used

- 🔹 **User Info API:**  
  `https://api.github.com/users/USERNAME`

- 🔹 **User Repositories (Posts) API:**  
  `https://api.github.com/users/USERNAME/repos`

---

## 📁 Project Flow

1. User inputs GitHub username (e.g., `octocat`)
2. App fetches and displays:
   - 👤 **Name**
   - 🆔 **User ID**
   - 📧 **Email** (if public)
3. A button lets user load public repositories
4. Each repo is shown with:
   - 📘 **Repo ID**
   - 📝 **Repo Name**

---

## 🧪 Example

**Input**: `torvalds`  
**Output**:
- ID: `1024025`
- Name: `Linus Torvalds`
- Repos:
  - `linux` (ID: `2325298`)
  - `subsurface` (ID: `22456173`)

---

## ✅ Technologies Used

- JavaScript (Vanilla)
- GitHub REST API (v3)
- HTML / CSS (for UI if needed)

---

## 🧠 How to Use

> This project is written in plain JavaScript and runs in the browser.

1. Clone or download this repository
2. Open `index.html` in your browser
3. Enter GitHub username and search
4. Click "Get Posts" to fetch public repos

---

## 📂 Folder Structure

```bash
.
├── index.html       # (User interface)
├── script.js        # (All JS logic)
└── README.md        # (This file)

👨‍💻 Author
Made with ❤️ by [Malak Sana Ullah] — aDreamDe project
Feel free to contribute or suggest improvements!
