A sleek, high-performance portfolio and services website for **Lexori Cybersecurity**. Built from scratch using a single-file architecture, this project delivers a fast, responsive, and modern user experience without relying on heavy frontend frameworks.

## ⚡ Overview

This project uses a custom vanilla JavaScript router that mimics Single Page Application (SPA) behavior. It allows users to seamlessly navigate between the home page and specialized service offerings (like Penetration Testing and Threat Intelligence) without reloading the browser, all contained within a single `.html` file.

## ✨ Features

* **Single-File Architecture:** The entire website—HTML structure, CSS styling, and JavaScript logic—is self-contained within one file for ultimate simplicity, portability, and instant loading.
* **Vanilla SPA Routing:** Custom JavaScript functions (`showPage`, `showService`) handle state changes by hiding and revealing distinct DOM sections to create a fluid, multi-page feel.
* **Modern Cybersecurity Aesthetic:** A premium dark-themed UI utilizing custom variables, gradients, and technical typography (Syne, Figtree, JetBrains Mono). Includes terminal-style UI components, animated data feeds, and interactive cards.
* **Scroll-Reveal Animations:** Utilizes the native `IntersectionObserver` API to trigger smooth fade-up animations as elements enter the viewport, keeping the interface engaging.
* **Fully Responsive:** CSS Grid and Flexbox layouts paired with mobile-first media queries ensure the site looks flawless on desktops, tablets, and mobile devices.
* **Zero Dependencies:** No React, Vue, Tailwind, or jQuery. Just pure HTML5, CSS3, and Vanilla JavaScript.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure and layout.
* **CSS3:** Custom properties (variables), Grid/Flexbox layouts, keyframe animations, and responsive media queries.
* **Vanilla JavaScript:** DOM manipulation, custom page routing, and Intersection Observers for scroll animations.

## 🚀 Getting Started

Since this project has no build tools or external dependencies, deployment and testing are completely frictionless:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Beastalex/lexori-website.git](https://github.com/Beastalex/lexori-website.git)
