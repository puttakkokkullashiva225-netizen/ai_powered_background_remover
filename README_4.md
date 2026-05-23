# 🖼️ MasynTech AI Background Remover

A clean, responsive web app that removes image backgrounds instantly using the **Slazzer AI API** — no signups, no installs, just drag, drop, and download.

![MasynTech AI Background Remover](https://img.shields.io/badge/AI-Background%20Remover-4f46e5?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMSAxNlYxNGE0IDQgMCAwIDAtNC00aC00YTQgNCAwIDAgMC00IDRIMTV2LTJhNCA0IDAgMCAxIDQgNHYyaDJ6Ii8+PC9zdmc+)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Features

- 🚀 **Drag & Drop Upload** — Simply drag your image onto the drop zone
- 🤖 **AI-Powered Removal** — Uses Slazzer's ML model for accurate cutouts
- 👁️ **Side-by-Side Preview** — View original and processed images together
- 💾 **One-Click Download** — Save the result as a PNG instantly
- 📱 **Fully Responsive** — Works great on desktop and mobile
- 🔒 **Client-Side Simplicity** — No backend server required

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & markup |
| CSS3 | Styling & responsive layout |
| Vanilla JavaScript | Interactivity & API calls |
| [Slazzer API](https://www.slazzer.com/) | AI background removal |
| Font Awesome 6 | Icons |

---

## 🚀 Getting Started

### Prerequisites
- A modern browser (Chrome, Firefox, Edge, Safari)
- A [Slazzer API key](https://www.slazzer.com/api) (free tier available)

### Installation

```bash
# Clone the repository
git clone https://github.com/puttakkokkullashiva225-netizen/ai_powered_background_remover.git

# Navigate into the project
cd ai_powered_background_remover

# Open in browser
open index.html
# or just double-click index.html
```

### ⚙️ Configuration

Replace the API key in `script.js` with your own Slazzer key:

```js
headers: {
  "API-KEY": "YOUR_SLAZZER_API_KEY_HERE",
},
```

> ⚠️ **Important:** Never commit real API keys to public repositories. Use environment variables or a backend proxy for production.

---

## 📁 Project Structure

```
ai_powered_background_remover/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive layout
├── script.js       # Upload logic, API call, download handler
└── README.md       # You're reading it!
```

---

## 🖥️ Usage

1. Open `index.html` in your browser
2. Drag & drop an image OR click **Select File**
3. Click **Remove Background**
4. Wait a moment while AI processes your image
5. Click **Download Result** to save your transparent PNG

---

## 📸 Demo

| Step | Description |
|------|-------------|
| 1️⃣ | Upload any product, portrait, or object image |
| 2️⃣ | Hit "Remove Background" |
| 3️⃣ | Get a clean PNG with transparent background |

---

## 🔐 Security Note

This project includes a hardcoded API key for demo purposes. For production use:
- Move API calls to a backend server
- Store keys in environment variables (`.env`)
- Add `.env` to `.gitignore`

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Shiva** — [@puttakkokkullashiva225-netizen](https://github.com/puttakkokkullashiva225-netizen)

---

## 🙌 Acknowledgements

- [Slazzer](https://www.slazzer.com/) for the background removal API
- [Font Awesome](https://fontawesome.com/) for the icon set
- [Inter Font](https://fonts.google.com/specimen/Inter) for clean typography
