<div align="center">

# 🔑 Password Generator

### *Strong passwords. Instantly. With style.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/No_Dependencies-Zero_Installs-success?style=for-the-badge)

**[🌐 Live Demo →](https://manan-2007.github.io/Password-Generator/)**

</div>

---

## 📖 About

**Password Generator** is a slick, browser-based tool for creating secure random passwords. It's one step up from the Python version — built with a proper UI using HTML, CSS, and Vanilla JavaScript. Users configure their password through a length slider and character-set checkboxes, then generate and copy it with a single click.

It also includes a real-time **password strength indicator** that changes based on length — giving users immediate feedback on how strong their password is.

---

## ✨ Features

- **Length Slider** — Range from 1 to 30 characters (default: 15)
- **Character Set Options:**
  - ✅ Lowercase (a–z) — enabled by default
  - Uppercase (A–Z)
  - Numbers (0–9)
  - Symbols (`!$%&|[](){}:;.,*+-#@<>~`)
  - Exclude Duplicates — no repeated characters
  - Include Spaces
- **Strength Indicator** — Visual colour strip:
  - 🔴 Weak (length ≤ 8)
  - 🟡 Medium (length ≤ 16)
  - 🟢 Strong (length > 16)
- **Copy to Clipboard** — One-click copy icon (Material Symbols Rounded)
- **Auto-Generate on Slider Move** — Password updates live as you drag

---

## 🔍 Core Logic

```javascript
const characters = {
    lowercase: "abcdefghijklmnopqrstuvwxyz",
    uppercase: "ABCDEFGHIJKLMNOPQRSTUVWXYZ",
    numbers:   "0123456789",
    symbols:   "!$%&|[](){}:;.,*+-#@<>~"
}

// Build character pool from checked options
// Randomly sample `length` characters from pool
// Optional: exclude duplicates if checkbox is checked
```

---

## 🛠️ Tech Stack

| Layer | Detail |
|---|---|
| Structure | HTML5 |
| Styling | Vanilla CSS3 |
| Logic | Vanilla JavaScript |
| Icons | Material Symbols Rounded (Google Fonts) |
| Clipboard | `navigator.clipboard.writeText()` |

---

## 📂 Project Structure

```
Password-Generator/
├── index.html      # UI — slider, checkboxes, output, copy button
├── style.css       # All styles — dark card, strength indicator colours
└── script.js       # All logic — generate, copy, strength update, slider sync
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/Manan-2007/Password-Generator.git
cd Password-Generator
# Open index.html in any browser
```

---

<div align="center">

Made by **Manan** · [GitHub](https://github.com/Manan-2007)

</div>
