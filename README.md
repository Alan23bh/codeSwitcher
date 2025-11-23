
# CodeSwitcher

CodeSwitcher is a clean, lightweight front-end project that allows users to switch between multiple programming-language snippets inside a single UI component.  

It mimics the behavior of popular documentation sites (like Stripe, Supabase, Clerk, etc.) by letting users toggle between languages and instantly see the corresponding code version. This is a purely front-end implementation using **HTML, CSS, and vanilla JavaScript** — perfect for demonstrating DOM manipulation, UI state handling, and component-based thinking without a framework.

---

## 🚀 Live Demo

🔗 **https://alan23bh.github.io/codeSwitcher/**

---

## 🎯 Features

- 🔄 **Language Switcher UI** — Toggle instantly between JavaScript, Python, Rust, Go, Java, and others.  
- 🌙 **Dark-Themed, Modern Styling** — Inspired by real-world developer documentation.  
- 📦 **Reusable Component Pattern** — Each code snippet is stored and rendered dynamically.  
- ⚡ **Zero Dependencies** — Built using **HTML + CSS + Vanilla JavaScript** only.  
- 📱 **Fully Responsive** — Optimized for desktop, tablet, and mobile.  
- 🧩 **Clean File Structure** — Easy to extend with more languages or more snippet groups.  

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- Custom dark theme
- No frameworks / no libraries

---


---

## 🧠 How It Works

### Each code block is wrapped with a `data-language` attribute
Example:
```html
<pre data-language="javascript"> ... </pre>
<pre data-language="python"> ... </pre>
