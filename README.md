# ✨ Minimal Browser Homepage

A clean, modern, and fully customizable browser homepage built with **HTML, CSS, and Vanilla JavaScript**.

Designed to replace your browser's default new tab page with a distraction-free dashboard featuring a beautiful clock, customizable shortcuts, and dynamic backgrounds.

---

## 📸 Preview

> Add a screenshot here

<img width="1877" height="954" alt="image" src="https://github.com/user-attachments/assets/21e6be9d-b061-47df-abbd-cc44c28e3940" />


---

## ✨ Features

### 🕒 Beautiful Live Clock
- Large modern digital clock
- Live seconds display
- Current day and date
- Updates every second

---

### 🔍 Instant Search

Search directly from the homepage using Google.

- Press **Enter**
- Opens results instantly

---

### 🚀 Custom Shortcuts

Create your own shortcuts with:

- Website URL
- Custom name
- Automatic favicon fetching
- Optional custom uploaded icon

Features include:

- ➕ Add shortcuts
- ✏️ Edit shortcuts
- ❌ Remove shortcuts
- 🔀 Drag & drop reordering

---

### 🖼️ Dynamic Backgrounds

Supports both:

- Images
- Videos

Backgrounds are stored locally and restored automatically after reopening the browser.

You can also remove the background anytime.

---

### 💾 Local Storage

Everything is saved automatically:

- Shortcuts
- Custom icons
- Backgrounds
- Shortcut order

No account required.

No backend required.

---

### 🎨 Minimal Glassmorphism UI

Features include:

- Frosted glass cards
- Blur effects
- Smooth animations
- Responsive layout
- Modern typography
- Clean dark theme

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/browser-homepage.git
```

Open the folder

```bash
cd browser-homepage
```

Open

```
homepage.html
```

or simply double-click the file.

No build process.

No dependencies.

No frameworks.

---

## 🛠 Customization

You can easily customize:

### Search Engine

Inside the JavaScript:

```javascript
https://www.google.com/search?q=
```

Replace it with:

- DuckDuckGo
- Brave Search
- Bing
- Startpage
- Ecosia

---

### Default Shortcuts

Modify:

```javascript
const defaultShortcuts = [
    ...
]
```

---

### Theme Colors

Inside `:root`

```css
--accent
--glass
--glass-border
--text
--danger
```

---

### Fonts

Currently uses:

- Space Grotesk
- Inter

Can easily be replaced.

---

## 📁 Project Structure

```
.
├── homepage.html
├── icons8-home-32.png
├── README.md
└── preview.png
```

---

## 💡 Future Ideas

- Weather widget
- Notes widget
- Calendar integration
- Multiple search engines
- Keyboard shortcuts
- Todo list
- RSS feeds
- Quotes of the day
- Bookmark import/export
- Theme presets
- Animated wallpapers
- Sync via GitHub Gist
- Light mode

---

## 🌐 Browser Compatibility

Works on all modern browsers:

- ✅ Firefox
- ✅ Chrome
- ✅ Brave
- ✅ Edge
- ✅ Opera

---

## ⚡ Performance

- Zero dependencies
- Single HTML file
- No frameworks
- Fast startup
- Lightweight
- Offline capable (except favicon fetching and web search)

---

## 📜 License

MIT License

Feel free to modify, improve, and use it however you like.

---

## ❤️ Built With

- HTML5
- CSS3
- Vanilla JavaScript

No React.
No Vue.
No Angular.
Just the web.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

Happy browsing! 🚀
