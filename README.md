# GitFind — GitHub User Finder

A clean and simple web app to search any GitHub user and display their profile information in real time.

🌐 **Live Demo:** [gitfind-liard.vercel.app](https://gitfind-liard.vercel.app/)

---
## 📸 Preview

![Teks Alternatif](GitFind-Image.png)

---

## Features

- Search any GitHub username instantly
- Display avatar, bio, and profile link
- Show followers, following, and public repositories count
- Display join date and location
- Contribution graph from the last year
- Fast and lightweight — no frameworks, no dependencies

---

##  Built With

| Technology | Purpose |
|---|---|
| HTML | Page structure |
| CSS | Styling and layout |
| JavaScript | Logic and API calls |
| GitHub REST API | Fetching user data |
| Vercel | Deployment |

---

## 📁 Project Structure

```
GitFind/
├── index.html      # Main HTML page
├── styles.css      # Styling
└── script.js       # JavaScript logic (API fetch + DOM manipulation)
```

---

## How to Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/Devjack404/GitFind.git
   ```

2. **Open the project folder**
   ```bash
   cd GitFind
   ```

3. **Open `index.html` in your browser**
   - You can just double-click the file, or
   - Use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code

> No installation or build step needed. It just works.

---

## 📡 API Used

This project uses the **GitHub REST API** to fetch public user data.

```
GET https://api.github.com/users/{username}
```

No API key required for basic usage. Public data only.

---

## 📄 License

This project is open source and free to use.
