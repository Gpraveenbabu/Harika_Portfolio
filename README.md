# Academic & Professional Portfolio Website

A clean, modern, and lightweight single-page portfolio website designed for researchers, academics, and agricultural economists. Built with pure HTML, CSS, and Vanilla JavaScript with zero external dependencies or frameworks.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build](https://img.shields.io/badge/dependencies-none-brightgreen)

---

## 🌟 Key Features

- **⚡ Zero Dependencies:** Built with native HTML5, CSS3, and JavaScript — no Node.js, build steps, or external bundlers required.
- **📱 Fully Responsive:** Seamless mobile-first design with a custom touch-friendly navigation drawer.
- **🌙 Automatic & Manual Dark Mode:** Adapts automatically to system preferences (`prefers-color-scheme`) with smooth color transitions.
- **🗺️ Interactive Map:** SVG-based interactive map displaying international research experience across multiple countries.
- **📊 Animated Counters:** Number counters that animate smoothly as you scroll into view.
- **📜 Expandable Timeline:** Interactive experience timeline with collapsible details.
- **🍃 Custom Motion & Parallax:** Lightweight scroll-driven animations and subtle parallax effects.
- **♿ Accessible & Performant:** Built with semantic HTML, ARIA attributes, keyboard support, and `prefers-reduced-motion` handling.

---

## 📁 Repository Structure

```text
.
├── index.html        # Main HTML layout & styling
├── portfolio.js      # Structured JavaScript logic (navigation, map, animations)
├── photo.jpg         # Profile image (add your photo here)
└── README.md         # Repository documentation
```

---

## 🛠️ Quick Start & Local Setup

Since this project uses vanilla web technologies, you don't need `npm` or any installation step.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. **Open in browser:**
   Double-click `index.html` or open it using a local development server like Live Server in VS Code.

---

## 🚀 How to Deploy on GitHub Pages

1. Push your code to your GitHub repository:
   ```bash
   git add .
   git commit -m "Initial portfolio release"
   git branch -M main
   git push -u origin main
   ```
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select `Deploy from a branch`.
4. Set the branch to `main` and folder to `/ (root)`.
5. Click **Save**. Your site will be live at `https://<username>.github.io/<repo-name>/` within a few minutes!

---

## ⚙️ Customization Guide

### 1. Adding Your Profile Photo
Place your photo in the root directory named `photo.jpg`, then update line 13 in `portfolio.js`:

```javascript
// Change from empty string to your image filename or external URL:
const PORTRAIT_SRC = 'photo.jpg';
```

### 2. Updating Contact Info & Links
Open `index.html` and locate the `#contact` section to update your email, LinkedIn, ORCID, and location:

```html
<a href="mailto:your-email@example.com">...</a>
<a href="https://www.linkedin.com/in/your-profile">...</a>
```

### 3. Modifying Content & Sections
All portfolio data (Research Areas, Experience, Education, Publications, Map Coordinates) is structured clearly at the top of `portfolio.js`.

---

## 📄 License

This project is licensed under the MIT License — feel free to customize and use it for your own portfolio!
