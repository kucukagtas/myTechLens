# 🔍 My Tech Lens — Technology Blog & Digital Culture Platform

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-kucukagtas.github.io%2FmyTechLens-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://kucukagtas.github.io/myTechLens/)
[![Language: Turkish](https://img.shields.io/badge/Language-Turkish_%28T%C3%BCrk%C3%A7e%29-E30A17?style=for-the-badge&logo=googletranslate&logoColor=white)](https://kucukagtas.github.io/myTechLens/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome_7-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)

<p align="center">
  <strong>A modern, responsive technology blog and digital culture magazine — published in Turkish.</strong>
</p>

[🌐 Visit Live Website](https://kucukagtas.github.io/myTechLens/) • [✨ Key Features](#-key-features) • [🛠️ Tech Stack](#️-tech-stack) • [📁 Project Structure](#-project-structure) • [🚀 Getting Started](#-getting-started) • [🌐 Deployment](#-deployment) • [📄 License](#-license)

---

</div>

## 📖 Overview

**My Tech Lens** is an engaging, modern digital technology blog and editorial publication. Technology is far more than complex source code or dry technical specifications; it shapes our everyday routines from the moment we wake up. *My Tech Lens* brings the rapid evolution of the digital world to the screen through an accessible, genuine, and unfiltered personal perspective.

🇹🇷 **Language Note:** The entire website interface, navigation, editorial articles, category taxonomy, and contact forms are published in **Turkish (Türkçe)** (*"Teknoloji sadece karmaşık kodlar ve teknik özelliklerden ibaret değil; uyandığımız andan itibaren hayatımızın ta kendisi. My Tech Lens, dijital dünyanın hızla değişen akışını anlaşılır, samimi ve filtresiz bir bakış açısıyla ekrana taşıyor."*).

Built with semantic **HTML5**, **Bootstrap 5**, and custom **CSS3**, the website delivers seamless responsiveness, crisp typography, and balanced visual harmony across all modern desktop, tablet, and mobile devices.

🔗 **Live Deployment:** [https://kucukagtas.github.io/myTechLens/](https://kucukagtas.github.io/myTechLens/)

---

## ✨ Key Features

- **📱 Fully Responsive Layout:** Fluid design system adapting smoothly to mobile screens, tablets, laptops, and wide desktop monitors using Bootstrap's flexbox grid and custom CSS media queries.
- **🇹🇷 Native Turkish Content & Editorial Voice:** Authentic technology insights written in Turkish, bridging high-level digital trends with practical, everyday consumer tech realities.
- **📰 Engaging Hero Section:**
  - High-impact header showcase featuring responsive hero illustration artwork.
  - Interactive Call-to-Action buttons: *"Yazıları Keşfet"* with smooth scrolling to the featured articles and *"İletişime Geç"* navigating to the contact page.
  - *"Benim Gözümden"* thematic overview section setting the tone for the publication.
- **🗂 Balanced Article Card Grid:**
  - Six curated technology articles spanning AI workplace impacts, foldable smartphone durability, cloud gaming, modern web aesthetics, electronic cable hoarding habits, and smart home quirks.
  - Symmetrically aligned cards with fixed aspect-ratio imagery, uniform title line clamps, and balanced teaser descriptions.
  - Dynamic hover elevation effects with softened drop shadows.
- **📑 Comprehensive Multi-Page Architecture:**
  - **Homepage:** Landing page featuring hero banner, publication intro, and featured technology highlights.
  - **Articles Archive:** Dedicated articles archive with categorized sidebar navigation (*Geniş Açı*, *Yakın Çekim*, *Filtresiz*, *Odak Ayarı*), brand-colored breadcrumbs, horizontal card layouts with responsive image scaling, and pagination controls.
  - **Contact:** Interactive contact gateway featuring a styled alert box (*"Lütfen Bu Formu Doldurun!"*), clean multi-field input form, accent submit button, and a live embedded interactive Google Map (Anıtkabir, Ankara).
- **🎨 Curated Color Palette & Visual Identity:**
  - Warm terracotta primary branding (`#e1855f`) paired with modern cyan accents (`#5fbbe1` / `#4baed6`).
  - Navbar links enhanced with high-contrast styling for optimal readability.
  - Subtle micro-animations, consistent button transitions, and custom brand favicon branding.
- **🔍 Built-in Search Bar:** Integrated search input with styled submit button present across all page navigation bars.
- **⚡ Fast Performance & Zero Heavy Runtimes:** Lightweight static structure delivering instant page loads and excellent Core Web Vitals metrics.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic markup across all pages (`header`, `nav`, `main`, `footer`, forms, meta tags) |
| **CSS3** | Custom design system (`style.css`), typography, color tokens, line-clamping, and responsive media queries |
| **Bootstrap 5.3.8** | Responsive layout grid, navigation bar collapse behavior, and base utility components |
| **Font Awesome 7** | Vector icons for search, navigation arrows, buttons, and alert notices |
| **Google Maps Embed API** | Interactive location map integration on the contact page |
| **GitHub Pages** | Continuous deployment, automated Git integration, and global CDN hosting |

---

## 📁 Project Structure

```text
myTechLens/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow for automatic GitHub Pages deployment
├── img/
│   ├── 1.jpeg              # Article thumbnail: AI in the Workplace
│   ├── 2.jpeg              # Article thumbnail: Foldable Smartphones
│   ├── 3.jpeg              # Article thumbnail: Cloud Gaming & Consoles
│   ├── 4.jpeg              # Article thumbnail: Soul of Modern Web Design
│   ├── 5.jpeg              # Article thumbnail: The Mystery Cable Drawer
│   ├── 6.jpeg              # Article thumbnail: Smart Home Quirks
│   ├── bg2.jpeg            # Hero banner illustration
│   └── favicon.png         # Brand identity icon and favicon
├── blogs.html              # Articles archive, category sidebar & horizontal cards
├── bootstrap.css           # Bootstrap 5 framework stylesheet
├── contact.html            # Contact form & embedded interactive Google Map
├── index.html              # Homepage with hero showcase & featured article grid
├── LICENSE                 # MIT License
├── README.md               # Project documentation
└── style.css               # Custom styles, color tokens & responsive rules
```

---

## 🚀 Getting Started

To explore or run this project locally on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/kucukagtas/myTechLens.git
```

### 2. Navigate to the Project Directory

```bash
cd myTechLens
```

### 3. Run Locally

Since this is a pure static web project, you can run it without any build tools:

* **Directly in Browser:** Double-click `index.html` or drag it into any modern web browser.
* **VS Code Live Server:** Right-click `index.html` and select **"Open with Live Server"**.
* **Via Node.js `serve`:**
  ```bash
  npx serve .
  ```

---

## 🌐 Deployment

The live version of **My Tech Lens** is deployed on **GitHub Pages**:

👉 **[https://kucukagtas.github.io/myTechLens/](https://kucukagtas.github.io/myTechLens/)**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE) — see the [LICENSE](LICENSE) file for details.
