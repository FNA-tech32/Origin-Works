# Origin Works — Creative Agency & Portfolio Website

[![Website Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)]()
[![Responsive](https://img.shields.io/badge/design-responsive-blue.svg)]()

Welcome to the official repository for **Origin Works**, a modern, fully-responsive creative agency and digital portfolio website. Designed with a clean aesthetic and smooth user experience, Origin Works showcases creative capabilities, client work, multidisciplinary design solutions, and clear communication channels.

---

## 📌 Table of Contents

- [About Origin Works](#about-origin-works)
- [Website Features](#website-features)
- [Live Navigation & Sections](#live-navigation--sections)
- [Contact Details & Location](#contact-details--location)
- [Project Structure](#project-structure)
- [Technologies & Libraries](#technologies--libraries)
- [Getting Started](#getting-started)
- [Customization Guide](#customization-guide)
- [Browser Compatibility](#browser-compatibility)
- [License & Credits](#license--credits)

---

## 🎨 About Origin Works

**Origin Works** is a digital design and creative studio dedicated to crafting engaging digital art, intuitive interfaces, modern web solutions, and standout brand identities. The website serves as both a comprehensive portfolio and an interactive touchpoint for prospective clients and partners.

---

## ✨ Website Features

- **Modern Hero Landing:** High-impact background visual with dark overlay, branding tagline, and carousel navigation controls.
- **Service Offerings:** Grid of specialized digital capabilities (Intuitive Web Design, System Development, Graphic Art, Photography).
- **Design Highlights Showcase:** Visual presentation of design principles emphasizing responsive layouts, clean code, and cross-browser compatibility.
- **Filterable Portfolio Gallery:** Interactive showcase for apps, photography, web development, and print projects.
- **Embedded Media Video:** Integrated video section for brand storytelling and agency showreels.
- **Company About & Analytics:** Agency overview accompanied by statistical metric counters (completed projects, awards, coffee consumed, letters sent).
- **Testimonials & Skills Metrics:** Authentic client feedback paired with visual skill proficiency bars (Adobe Suite, HTML/CSS, JavaScript, PHP).
- **Inspirational Quote:** Clean typographic divider for brand ethos and inspiration.
- **Tiered Pricing Tables:** Clear, comparative subscription/service plans (Basic, Premium, Pro, Platinum) with call-to-action buttons.
- **Newsletter Subscription:** Integrated subscription form for staying connected with the studio.
- **Direct & Alternative Contact Section:** Interactive contact form paired with primary phone, alternative support line, email address, and studio physical location.
- **Social & Branded Footer:** Consistent brand closing with social connectivity icons (Facebook, Twitter, LinkedIn).

---

## 🧭 Live Navigation & Sections

The single-page website includes smooth in-page anchor navigation:

| Section Anchor | Purpose |
| :--- | :--- |
| `#home` | Hero banner introducing Origin Works |
| `#services` | Core agency services and capabilities |
| `#portfolio` | Gallery of creative projects and filter tags |
| `#about` | Agency story, statistics, testimonials, and skill bars |
| `#pricing` | Service packages, feature tiers, and pricing options |
| `#contact` | Inquiry form, primary and alternative contact lines, studio address |

---

## 📞 Contact Details & Location

Get in touch with **Origin Works** through any of our official channels:

- **Brand:** Origin Works
- **Primary Telephone:** `+1 (212) 555-0148`
- **Alternative Contact:** `+1 (212) 555-0192`
- **Email Inquiries:** [contact@originworks.com](mailto:contact@originworks.com)
- **Studio Address:**
  ```text
  Origin Works Studio
  17 Creative Parkway, Suite 400
  New York, NY 10001
  USA
  ```

---

## 📂 Project Structure

```text
Origin-Works/
├── index.html                # Main semantic HTML5 markup
├── README.md                 # Project documentation and guide
├── CSS/
│   ├── all.css               # Font Awesome core styles
│   ├── all.min.css           # Minified Font Awesome stylesheet
│   ├── normalize.css         # Modern HTML5 element normalization
│   └── template-two.css      # Custom styling, layout & responsive queries
├── imgs/                     # Visual assets, photos, icons, and video
│   ├── about.png
│   ├── awesome-video.mp4
│   ├── design-features.jpg
│   ├── landing.jpg
│   ├── logo.png
│   ├── mobile.png
│   ├── quote.jpg
│   ├── shuffle-01.jpg .. 08.jpg
│   ├── skills-01.jpg
│   ├── skills-02.png
│   ├── stats.png
│   └── subscribe.jpg
└── webfonts/                 # Font Awesome vector font binaries
    ├── fa-brands-400.*
    ├── fa-regular-400.*
    ├── fa-solid-900.*
    └── fa-v4compatibility.*
```

---

## 🛠️ Technologies & Libraries

- **HTML5:** Semantic markup, accessibility labels, and HTML5 video playback.
- **CSS3:** Custom properties (CSS variables), CSS Flexbox, CSS Grid layouts, smooth scrolling (`scroll-behavior: smooth`), and media queries for responsive breakpoints.
- **Normalize.css:** Cross-browser rendering consistency.
- **Font Awesome:** Scalable vector icons for services, social links, metrics, and navigation.
- **Google Fonts:** Clean typography utilizing the *Open Sans* font family.

---

## 🚀 Getting Started

No build tools, bundlers, or server runtimes are required. This is a lightweight, zero-dependency static project.

### Option 1: Direct File Launch
Simply double-click `index.html` or open it in any web browser.

### Option 2: Local Development Server

#### Using Python
```bash
# Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

#### Using Node.js (npx)
```bash
npx serve .
```

#### Using VS Code Live Server
Right-click `index.html` in Visual Studio Code and select **"Open with Live Server"**.

---

## 🎨 Customization Guide

### 1. Brand Name & Colors
Colors are managed through CSS variables in `CSS/template-two.css`:
```css
:root {
    --main-color: #19c8fa;              /* Primary accent color */
    --transparent-color: rgb(14 116 143 / 70%); /* Hero overlay color */
    --secondary-color: #777;           /* Text secondary color */
    --section-padding: 100px;          /* Vertical spacing between sections */
}
```

### 2. Updating Contact Information
Edit the contact details inside the `<div class="info">` block in `index.html`:
```html
<div class="info">
    <h4>Get In Touch</h4>
    <span class="phone">+1 (212) 555-0148</span>
    <span class="phone">+1 (212) 555-0192 (Alternative)</span>
    <span class="phone">contact@originworks.com</span>
    <h4>Where We Are</h4>
    <address>Origin Works Studio<br />17 Creative Parkway, Suite 400<br />New York, NY 10001<br />USA</address>
</div>
```

### 3. Replacing Portfolio & Hero Media
Swap or replace files inside the `imgs/` folder with your preferred assets, keeping the corresponding filenames or updating the paths in `index.html`.

---

## 🌐 Browser Compatibility

Tested and compatible across all modern evergreen browsers:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Apple Safari (latest)
- Microsoft Edge (latest)
- Opera (latest)

---

## 📄 License & Credits

- **Brand:** © 2024 **Origin Works**. All Rights Reserved.
- **Icons:** [Font Awesome](https://fontawesome.com/)
- **Fonts:** [Google Fonts — Open Sans](https://fonts.google.com/specimen/Open+Sans)
