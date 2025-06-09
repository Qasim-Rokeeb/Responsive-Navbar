
# 📱 Responsive Navbar – Day 24 of 30 Days of JavaScript

A sleek and responsive **navigation bar** built using **HTML**, **CSS**, and **JavaScript**. This navbar adapts perfectly to all screen sizes and includes a mobile-friendly hamburger menu.

---

## ✨ Features

- ✅ Fully responsive navigation layout
- 🍔 Hamburger menu for mobile devices
- 🎯 Active link styling
- 💻 Smooth transitions using pure CSS and JavaScript
- 🧩 No external frameworks used

---

## 📸 Preview

Here’s a look at the responsive navigation bar in action:

![App Preview](https://raw.githubusercontent.com/Qasim-Rokeeb/Responsive-Navbar/main/screenshot.png)

---

## 🌐 Live Demo

🔗 [View Live Project](https://qasim-rokeeb.github.io/Responsive-Navbar)

---

## 🧱 Built With

- **HTML5** – Semantic layout
- **CSS3** – Flexbox and media queries for responsiveness
- **JavaScript** – Toggle menu visibility for smaller screens

---

## 📁 Project Structure

```bash
Responsive-Navbar/
├── index.html         # Contains the header, logo, links, and script
├── style.css          # Inline styles in this project
├── screenshot.png     # Preview image
└── README.md
```

---

## ⚙️ How It Works

1. On large screens, navigation links are visible in a horizontal layout.
2. On small screens (≤ 900px), the menu collapses into a hamburger icon.
3. Clicking the hamburger icon toggles the `.active` class on `.nav-bar`.

```js
hamburger = document.querySelector(".hamburger");
hamburger.onclick = function(){
    navBar = document.querySelector(".nav-bar");
    navBar.classList.toggle("active");
}
```

---

## 🧠 What I Learned

- How to use **media queries** for responsive layouts
- How to create a **hamburger menu** from scratch
- How to toggle visibility and transitions with JavaScript and class manipulation

---

## 📅 Challenge

This is **Day 24** of my **30 Days of JavaScript** challenge.  
Follow my journey and check out the other days:

📲 [@qasimrokeeb](https://x.com/qasimrokeeb)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
````

