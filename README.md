# Gold Store - Responsive Skincare Website

A modern, highly responsive landing page interface for a boutique skincare store named **Gold Store** (marketing the premium **GlowSkin** line). Styled with **Bootstrap 5** and custom CSS rules, focusing on soft typography, overlay cards, and clean visual structures.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat-square&logo=bootstrap&logoColor=white)](#)

---

## 📸 Interface Preview

*Note: Capturing and adding high-resolution screenshots here is highly recommended. Suggested views include:*
- **Desktop Home Page - Welcome Banner and Header**
- **Mobile Responsive View - Best Sellers Stacked Card Grid**
- **Get in Touch Form validation layout**

---

## 🌟 Key Features

- **Mobile-First Responsive Layout**: Adapts gracefully to all viewports (mobile, tablet, desktop) using Bootstrap 5's responsive containers and flex grid.
- **Overlay Cards**: Modern CSS hover overlays containing item descriptions and ratings.
- **Multi-page Structure**:
  - 🏠 **Home Page (`index.html`)**: Features sliding best sellers and customer benefits grid.
  - 🌿 **About Us (`aboutus.html`)**: Details the company's story, mission, and values.
  - 📞 **Contact Us (`contactus.html`)**: Standard user message feedback form.
- **Zero-Error Console Execution**: All outstanding script 404 links (such as missing `pllugin.js` references) and redundant duplicate layouts have been removed.
- **Offline & Local Compatibility**: Restructured navigation paths from absolute paths (which broke when opening files locally) to relative file paths.

---

## 🛠️ Tech Stack

### Core Technologies
- **HTML5** (Semantic structure, cards)
- **CSS3** (Typography, overlay hover animations, custom grid variables)

### Frameworks & Libraries
- **Bootstrap 5.3.5** (Layout configurations)
- **FontAwesome 6.4.0** (Social and contact navigation icons)

---

## 📂 Project Structure

```text
gold-store/
├── css/
│   └── style.css            # Custom CSS rules, overlay hover animations, responsive breakpoints
├── img/
│   ├── p1.jpeg, p2.jpeg...  # Skincare product images
│   └── w1.jpeg, w2.jpeg...  # Grid benefit showcase illustrations
├── .gitignore               # Standard git ignore definitions
├── index.html               # Main Home Page entry
├── aboutus.html             # About Us info view page
├── contactus.html           # Contact Us and feedback form page
├── LICENSE                  # MIT License
├── CONTRIBUTING.md          # Contributions guidelines and coding standards
├── CODE_OF_CONDUCT.md      # Contributor Covenant Code of Conduct
├── SECURITY.md              # Security policy and vulnerability reports
├── SUPPORT.md               # Help and support channels
└── CHANGELOG.md             # Releases and update logs
```

---

## ⚙️ Installation & Usage

This website runs entirely inside the browser and does not require complex local dependencies.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HazemTaha/gold-store.git
   cd gold-store
   ```

2. **Open locally**:
   - Double-click `index.html` to open it in your browser directly.
   - *Or* run a local server for the best development experience:
     ```bash
     python -m http.server 4000
     ```
   - Open your browser to `http://localhost:4000`.

---

## 🧑‍💻 Recruiter-Friendly Insight

### The Problem It Solves
Boilerplate landing pages are often filled with absolute pathing (e.g. `/index.html`) which fails on local files deployment, triggers 404 errors for missing assets, and holds redundant duplicate HTML pages. This repository has been fully audited to ensure **perfect path resolution**, **zero dev console errors**, and **clean file structures** – showcasing attention to detail in asset loading.

### Code Highlights
- **Relative Path Bindings**: Standardizes navbar links (`./aboutus.html`) so the project renders perfectly whether viewed on local disk, behind sub-routes, or on serverless CDNs.
- **Resource Cleanliness**: Removed a missing script reference (`pllugin.js`) that triggered 404 console errors on every page load.
- **CSS Overlay Transitions**: Employs clean CSS transitions (`transition: ease .5s; opacity: 0;`) inside `style.css` to build responsive product slide matrices, avoiding JavaScript performance overhead.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
