# Spotify UI Clone – High-Fidelity Responsive Web Interface

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](YOUR_GITHUB_PAGES_LINK_HERE)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A pixel-perfect recreation of the Spotify Web Player interface. This project focuses on modern CSS layouts, including **Flexbox architecture**, **Sticky positioning**, and **Responsive Design** principles used in large-scale production applications.

---

## 🚀 Technical Highlights

* **Layout Architecture:** Utilized a hybrid of `position: fixed` for global navigation (Music Player) and `flex: 1` with `overflow: auto` for the scrollable main content area.
* **Custom UI Components:** Engineered custom CSS for the HTML5 range input (`.progress-bar`) using `::-webkit-slider-runnable-track` and `::-webkit-slider-thumb` to match Spotify's branding.
* **Performance Optimization:** Implemented system font stacks and prioritized critical CSS for the "Above the Fold" content (Sidebar & Sticky Nav).
* **Responsive UX:** Used CSS Media Queries to handle layout shifting for tablet and mobile views, ensuring the `hide` class toggles elements to maximize screen real estate.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for accessibility.
* **CSS3:** Flexbox, Custom Scrollbars, Sticky Positioning, and Media Queries.
* **Icons:** FontAwesome 7.0 (Integrated via CDN).
* **Typography:** Google Fonts (Montserrat).

## 📂 Project Structure

```text
.
├── assets/             # Images, icons, and logo assets
├── homeworkk-assets/   # Images, icons, and logo assets
├── index.html          # Core structure and semantic markup
├── style.css           # Modular CSS styles
└── README.md           # Documentation