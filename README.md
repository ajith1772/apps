# 📱 App Showcase Portal

A modern, minimalist, icon-only App Launcher and Web Portal built with HTML5 and CSS3. Designed with an iOS/macOS Launchpad aesthetic featuring vibrant gradients, glassmorphism cards, ambient hover glow effects, and responsive layout for all device screen sizes.

---

## ✨ Features

- 🎨 **Modern Aesthetics**: Glassmorphism translucent containers with ambient radial backdrop glows.
- 🚫 **Icon-Only Interface**: Clean, clutter-free UI with **no text labels**—pure reliance on distinct, high-res vector icons.
- 📱 **Fully Responsive**: Dynamic CSS Grid that seamlessly adapts across Mobile, Tablet, and Desktop displays.
- ⚡ **Lightweight & Fast**: Zero JavaScript dependencies—pure HTML5 and CSS3 powered by FontAwesome 6 CDN.
- 🏷️ **Categorized Layout**: Elegant visual separation between **Official** and **Personal** application hubs.

---

## 🔗 Included Applications

### 🏛️ Official Links
| App Icon Purpose | Target URL |
| :--- | :--- |
| **School Bus** | `https://tdtti.github.io/schoolbus/` |
| **School Parliament (Election)** | `https://tdtti.github.io/School-Parliament/` |
| **USS Portal (TRAILS)** | `https://tdtti.github.io/TRAILS/` |
| **School Fest (Uthsav)** | `https://tdtti.github.io/Uthsav/` |
| **School News 2025** | `https://tdtti.github.io/school-news-2025/` |
| **Time Table** | `https://tdtti.github.io/tdtti/` |
| **Student Database** | `https://tdtti.github.io/tdtti2/` |
| **Social Science 7** | `https://tdtti.github.io/ss/` |

### 👤 Personal Links
| App Icon Purpose | Target URL |
| :--- | :--- |
| **EV Owned** | `https://ajith1772.github.io/mpa/` |
| **EV Sister** | `https://ajith1772.github.io/chellu/` |
| **Census Map** | `https://ajith1772.github.io/ajith/` |

---

## 🚀 Quick Start

1. **Clone or Download**:
   Download the project code or save it into an `index.html` file.

2. **Launch**:
   Double-click `index.html` to open it in any modern browser (Chrome, Safari, Edge, Firefox).

3. **Deploy (Optional)**:
   Publish it directly to platforms like **GitHub Pages**, **Vercel**, or **Netlify** for free hosting.

---

## 🛠️ Customization Guide

### ➕ Adding a New App Icon
To add a new link, paste the following snippet inside either `.app-grid` container:

```html
<a href="YOUR_URL_HERE" target="_blank" class="app-tile icon-custom" title="Your App Name">
    <i class="fa-solid fa-star"></i>
</a>
