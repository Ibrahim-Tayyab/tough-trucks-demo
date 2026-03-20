# 🛻 Tough Trucks — UI Replica

![Tough Trucks Preview](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

A pixel-perfect, fully responsive frontend replica of the **Tough Trucks** website. This landing page was crafted with attention to detail, matching the typography, colors, layout, and visual interactions of the original design for American truck sales, accessories, and custom builds.

---

## 🚀 Features

- **Pixel-Perfect UI:** Meticulous recreation of the header, navigation, hero section, feature badges, and category cards.
- **Custom Inline SVG Logo:** The "Tough Trucks" logo (with the navy starry top-bar and red body) was precisely recreated using native inline SVG—no external image assets required.
- **Fully Responsive:** Adapts seamlessly across mobile, tablet, and desktop devices.
- **Interactive Mobile Menu:** Implements a sleek slide-in hamburger menu for smaller viewports via minimal Vanilla JavaScript.
- **Automated Deployments:** Fully integrated with GitHub Actions for immediate, zero-touch deployment to GitHub Pages on every push.

## 🛠️ Built With

- **HTML5:** Semantic and accessible document structure.
- **Tailwind CSS:** Utility-first styling utilized via CDN, configured with exact brand colors (e.g., `#B91C1C` for primary red, `#1E3A5F` for navy blue).
- **Google Fonts:** Integrates **Oswald** for bold, impactful headings and **Inter** for clean, readable body text.
- **Vanilla JS:** Lightweight script handling the mobile navigation overlay.
- **Unsplash API:** Curated high-quality automotive placeholder imagery.

## 📂 Project Structure

```text
📁 shopyfy/
├── 📄 2_demo copy.html      # Main landing page (Consider renaming to index.html for production)
├── 📄 README.md             # Project documentation and details
└── 📁 .github/              # CI/CD Configuration folder
    └── 📁 workflows/
        └── 📄 deploy.yml    # Automated GitHub Pages deployment script
```

## 💻 Running Locally

Since this project consists of standard HTML and CSS via CDN, you don't need any complex build tools.

1. **Option 1 (Direct Open):** Simply double-click on `2_demo copy.html` or drag it into any modern web browser.
2. **Option 2 (Local Server):** If you wish to run it on a local HTTP server:
   - Using Python: `python -m http.server 8000`
   - Using Node: `npx http-server -p 8000`
   - Then navigate to `http://localhost:8000/2_demo%20copy.html`

## 🌍 CI/CD & Deployment

This project includes a **GitHub Actions** workflow designed for immediate production scaling. 

When you push code to the `main` or `master` branch on GitHub, the `deploy.yml` workflow will automatically bundle the directory and publish it to **GitHub Pages**. 

**To use this:**
1. Rename `2_demo copy.html` to `index.html` (Recommended).
2. Push this folder to a GitHub repository.
3. Enable GitHub Actions in the repository settings (`Settings > Pages > Source > GitHub Actions`).
4. Your website is instantly live!

## 🎨 Design System

**Tailwind Extensions (`tailwind.config` injection):**
*   `brand-red`: `#B91C1C`
*   `brand-darkred`: `#991B1B`
*   `brand-navy`: `#1E3A5F`
*   `brand-dark`: `#111827`

---
*Developed as a high-fidelity frontend portfolio implementation.*
