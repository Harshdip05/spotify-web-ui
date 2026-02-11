# 🎵 Spotify UI Clone – High-Fidelity Responsive Web Interface

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](YOUR_GITHUB_PAGES_LINK_HERE)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A **pixel-perfect recreation of the Spotify Web Player UI**, engineered with **HTML5 and CSS3**. This project demonstrates mastery of modern layout architecture, responsive design, and performance-first CSS—patterns utilized in high-traffic production environments.

---

## 🖥️ Project Preview

![Desktop Preview](./assets/screenshots/desktop-main.png)
*Figure 1: High-fidelity desktop interface showcasing the Sidebar, Sticky Navigation, and Persistent Music Player.*

---

## 📌 Project Overview

This project solves the architectural challenges of a modern Single Page Application (SPA) layout:
* **Persistent Global Components:** The music player remains fixed while content updates.
* **Independent Scroll Containers:** Seamless scrolling in the main content area without affecting the sidebar or player.
* **Zero-JS Interactivity:** Leveraging CSS pseudo-classes for state management (hover, active, focus).

---

## 🚀 Technical Highlights

### 🧱 Layout Architecture & UX
* **Hybrid Positioning Strategy:** Implemented a combination of `position: fixed` for the global controls and a Flexbox-based shell for the main application.
* **Scroll Management:** Used `overflow-y: auto` on a flex-grow container (`flex: 1`). This prevents "Double Scrollbars" and mimics native app behavior.
* **Sticky Header:** Implemented `position: sticky` for navigation bars to ensure context-awareness as the user explores the library.

### 🎨 Custom UI Engineering
* **Progress Bar Architecture:** Instead of using heavy libraries, I engineered a custom `<input type="range">` using vendor-specific pseudo-elements (`-webkit-slider-runnable-track` and `-webkit-slider-thumb`) to achieve the exact Spotify branding.
* **Atomic CSS Principles:** Used utility classes (like `.badge` and `.nav-item`) to ensure style reusability and reduce CSS file size.

### 📱 Responsive Design Strategy
* **Fluid Layouts:** Switched from fixed pixel widths to relative units (rem/vh/%) to maintain proportion across different screen densities.
* **Breakpoint Optimization:** Strategically utilized a `.hide` utility class within Media Queries to prioritize "Critical UI" for mobile users, maximizing the 100vh viewport space.

<p align="center">
  <img src="./assets/screenshots/mobile-view.png" width="280" alt="Mobile View" />
  <br>
  <em>Figure 2: Mobile responsive view prioritizing content accessibility.</em>
</p>

---

## 🛠️ Tech Stack & Tools

* **Core:** HTML5 (Semantic Markup), CSS3 (Modern Flexbox)
* **Icons:** FontAwesome 7.0 (Optimized CDN)
* **Typography:** Google Fonts (Montserrat)
* **Version Control:** Git & GitHub (Feature-branch workflow)

---

## 📂 Project Structure

```text
.
├── assets/             # Brand icons and playlist cover art
│   └── screenshots/    # Project preview images
├── index.html          # Semantic HTML5 markup
├── style.css           # Modularized CSS architecture
├── LICENSE             # MIT License
└── README.md           # Professional documentation
```

---

## 📄 License

This project is licensed under the **MIT License**.

```