# 🚀 devMilap — Tailwind CSS Component Library

**devMilap** is a clean, modular, and production-ready UI library built entirely with **Tailwind CSS v3**. All components are prefixed with `.devmilap-*` to avoid class name conflicts and are optimized for real-world frontend applications.

---

## 📌 Why devMilap?

- ✅ **Built with Tailwind v3**
- 🎯 **Minimalist & utility-first** — pure CSS, no JS
- 🧱 **Component-first architecture** — buttons, cards, badges, and more
- 🛡️ **Scoped with `.devmilap-` prefix** — no global class pollution
- 🌍 **CDN + NPM** support — use it your way

---

## 📦 Installation via NPM

### ✅ Step 1: Create a Vite + React Project

```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
```

---

### ✅ Step 2: Install Tailwind CSS v3

```bash
npm install -D tailwindcss@^3 postcss autoprefixer
npx tailwindcss init -p
```

This creates two files:
- `tailwind.config.js`
- `postcss.config.js`

---

### ✅ Step 3: Configure Tailwind

Edit `tailwind.config.js`:

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  darkMode: 'class',
  content: [
    './index.html',
    './src/**/*.{js,ts,jsx,tsx}',
    './node_modules/devmilap/dist/**/*.css'
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

---

### ✅ Step 4: Install devMilap

```bash
npm install devmilap
```

---

### ✅ Step 5: Import Styles

In your main CSS file (e.g. `src/index.css`):

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

/* Import devMilap styles */
@import 'devmilap/dist/devmilap.css';
```

---

### ✅ Step 6: Use devMilap Components

---

## 🌐 CDN Usage (Optional)

If you’re not using Tailwind in your build process, include via CDN:

```html
<link href="https://cdn.jsdelivr.net/npm/devmilap/dist/devmilap.min.css" rel="stylesheet" />
```

---

Docs coming soon at [https://devmilap.dev](https://devmilap.dev)

---

## 🧾 License & Usage Terms

MIT License © 2025 Soumay Sikchi

### ✅ You May:
- Use in personal and commercial projects
- Modify and extend with attribution
- Share components in open-source work

### ❌ You May Not:
- Reupload or rename this library
- Redistribute under a different identity
- Sell this package without consent

---

## 📬 Feedback & Contributions

- 🐞 [Submit Issues](https://github.com/SOUMAYSIKCHI/devMilapUI/issues)
- 📦 [NPM Package](https://www.npmjs.com/package/devmilap)
- 🧠 Author: [Soumay Sikchi](https://github.com/SOUMAYSIKCHI)
