# SVRM Nexus — Charming Design Studio

<div align="center">

![SVRM Nexus Banner](https://img.shields.io/badge/SVRM%20Nexus-Charming%20Design%20Studio-C96B3A?style=for-the-badge&logoColor=white)

[![GitHub Pages](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-181717?style=flat-square&logo=github)](https://suvaniwaghmare085-droid.github.io/SVRM-Nexus)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)

**A creative design studio website built for bold brands.**  
Crafted by [Suvani Waghmare](https://www.linkedin.com/in/suvani-waghmare)

[🌐 View Live Site](https://suvaniwaghmare085-droid.github.io/SVRM-Nexus) · [📧 Get In Touch](mailto:suvaniwaghmare085@gmail.com) · [🔗 LinkedIn](https://www.linkedin.com/in/suvani-waghmare)

</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Pages & Sections](#-pages--sections)
- [Tech Stack](#-tech-stack)
- [Design System](#-design-system)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deploy on GitHub Pages](#-deploy-on-github-pages)
- [Contact Form Setup](#-contact-form-setup)
- [Customization Guide](#-customization-guide)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Contact](#-contact)

---

## 🎨 About The Project

**SVRM Nexus** is the official website for *Charming Design Studio* — a creative agency founded by **Suvani Waghmare** that specializes in branding, UI/UX design, web design, content strategy, social media design, and analytics & growth.

The website is designed to reflect the studio's core philosophy: *Design is not decoration. It's communication.* Every section is intentional, every interaction purposeful.

Built as a **pure HTML/CSS/JS** project — no frameworks, no build tools, no dependencies. Just clean, fast, and portable web code that works everywhere and deploys instantly.

> *"We craft compelling visual identities, digital experiences, and strategic content that make your brand impossible to ignore."*

---

## 🌐 Live Demo

🔗 **[https://suvaniwaghmare085-droid.github.io/SVRM-Nexus](https://suvaniwaghmare085-droid.github.io/SVRM-Nexus)**

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🌙 **Dark / Light Mode** | Full theme toggle with preference saved in `localStorage` |
| 📱 **Fully Responsive** | Optimized for mobile, tablet, and desktop screens |
| 🎞️ **Scroll Reveal Animations** | Staggered entrance animations triggered on scroll using `IntersectionObserver` |
| 🧭 **Sticky Navbar** | Transparent navbar that gains background and shadow on scroll |
| ☰ **Mobile Hamburger Menu** | Accessible slide-in menu for small screens |
| 🎴 **Service Cards** | 6 animated service cards with hover effects and decorative numbering |
| 🖼️ **Project Portfolio** | 6 featured project cards with custom gradient accents |
| 👤 **Founder Section** | Dedicated section with bio, LinkedIn, and email CTA |
| 📬 **Contact Form** | Functional form ready to wire to Formspree or Netlify Forms |
| ⚡ **Zero Dependencies** | No npm, no build step — open `index.html` and it works |
| 🔤 **Custom Typography** | Cormorant Garamond (display) + DM Sans (body) via Google Fonts |
| 🎯 **Active Nav Highlighting** | Nav links highlight to match the current section on scroll |

---

## 📄 Pages & Sections

The website is a single-page application with smooth scrolling between the following sections:

### 1. 🏠 Hero
- Full-viewport opening with a headline, tagline, and two CTAs
- Animated floating service preview cards
- Decorative background gradient orbs

### 2. 🛠️ Services
Six core services offered by SVRM Nexus:

| # | Service | Description |
|---|---------|-------------|
| 01 | **Branding & Identity** | Logo design, brand guidelines, visual identity systems |
| 02 | **UI / UX Design** | User-centered design, wireframes, prototyping, usability testing |
| 03 | **Web Design** | Responsive websites, landing pages, e-commerce design |
| 04 | **Content Strategy** | Content planning, copywriting, SEO, social media strategy |
| 05 | **Social Media Design** | Post templates, story designs, campaign assets |
| 06 | **Analytics & Growth** | Performance tracking, conversion optimisation, market research |

### 3. 💡 About / Philosophy
- Studio values and philosophy
- Key stats: 50+ projects, 30+ clients, 3+ years experience
- CTA to start a project

### 4. 🖼️ Featured Projects
Six portfolio showcases:
- The Roast House — Brand Identity
- Flux Finance App — UI/UX Design
- Aura Wellness Studio — Web Design
- GreenLeaf Organic — Content Strategy
- Ember Fashion — Social Media Design
- Nova EdTech — Analytics & Growth

### 5. 👩‍💼 Meet The Founder
- Bio of **Suvani Waghmare** — Designer · Strategist · Storyteller
- Work With Me button (email link)
- LinkedIn profile link

### 6. 📬 Contact
- Contact details (email + LinkedIn)
- Full inquiry form with name, email, service selection, and message
- Simulated send confirmation (ready for real integration)

### 7. 🔻 Footer
- Studio branding
- Services quick links
- Social / contact links
- Copyright

---

## 🛠️ Tech Stack

This project is intentionally built with **zero external dependencies** for maximum portability and performance.

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, animations, CSS variables, Grid & Flexbox layout |
| **Vanilla JavaScript** | Theme toggle, scroll effects, mobile menu, form handling |
| **Google Fonts** | Cormorant Garamond + DM Sans (loaded via CDN) |
| **IntersectionObserver API** | Performant scroll-triggered reveal animations |
| **localStorage** | Persisting user's theme preference across sessions |

---

## 🎨 Design System

### Color Palette

| Token | Light Mode | Dark Mode | Usage |
|-------|-----------|-----------|-------|
| `--bg` | `#FAF8F3` | `#141210` | Page background |
| `--bg-soft` | `#F2EEE4` | `#1E1C18` | Section backgrounds |
| `--bg-card` | `#FFFFFF` | `#252320` | Cards and panels |
| `--ink` | `#1C1A16` | `#F5F0E8` | Primary text |
| `--ink-soft` | `#4A4538` | `#C8BEA8` | Secondary text |
| `--ink-muted` | `#8C8272` | `#7A7060` | Muted/tertiary text |
| `--accent` | `#C96B3A` | `#C96B3A` | Burnt orange — primary accent |
| `--accent-2` | `#E8A96A` | `#E8A96A` | Warm gold — secondary accent |
| `--border` | `#E0D9CC` | `#2E2A24` | Borders and dividers |

### Typography

| Role | Font | Weight |
|------|------|--------|
| Display / Headlines | Cormorant Garamond | 300, 400, 500, 600, 700 |
| Body / UI | DM Sans | 300, 400, 500, 600 |

### Spacing & Radius

- Section padding: `96px 0`
- Card border radius: `20px` (lg), `12px` (md)
- Button radius: `8px`
- Container max-width: `1160px`

---

## 📁 Project Structure

```
SVRM-Nexus/
│
├── index.html          # Main HTML — all sections of the website
├── style.css           # Full design system + layout + animations
├── script.js           # Interactivity: theme, nav, menu, scroll, form
└── README.md           # You're reading it!
```

---

## 🚀 Getting Started

### Prerequisites

None. Seriously — you just need a web browser.

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/suvaniwaghmare085-droid/SVRM-Nexus.git

# 2. Navigate into the project
cd SVRM-Nexus

# 3. Open in your browser
open index.html
# or just double-click index.html in your file manager
```

That's it. No `npm install`. No build step. No config files.

> **Tip:** For the best local development experience, use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code for hot-reloading.

---

## 🌐 Deploy on GitHub Pages

Your site can be live in under 2 minutes:

### Step 1 — Push to GitHub

```bash
# If you cloned this repo, just push your changes
git add .
git commit -m "Initial commit"
git push origin main
```

If starting fresh:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/suvaniwaghmare085-droid/SVRM-Nexus.git
git push -u origin main
```

### Step 2 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. In the left sidebar, click **Pages**
4. Under **Source**, select **Deploy from a branch**
5. Set branch to `main` and folder to `/ (root)`
6. Click **Save**

### Step 3 — Visit Your Live Site

After 1–2 minutes, your site will be live at:

```
https://suvaniwaghmare085-droid.github.io/SVRM-Nexus
```

> GitHub Pages automatically rebuilds your site every time you push to `main`.

---

## 📬 Contact Form Setup

The contact form currently simulates sending (for demo purposes). To make it fully functional, choose one of the following integrations:

### Option A — Formspree (Recommended, Free)

1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form and copy your form ID
3. In `index.html`, replace the `<form>` opening tag:

```html
<!-- Replace this -->
<form class="contact-form" id="contact-form" onsubmit="handleSubmit(event)">

<!-- With this -->
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

4. Remove the `onsubmit` JavaScript handler — Formspree handles the rest.

### Option B — Netlify Forms (If deploying on Netlify)

```html
<form class="contact-form" name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
  <!-- rest of your fields -->
</form>
```

### Option C — EmailJS (No backend needed)

```javascript
// In script.js, replace the setTimeout block with:
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form)
  .then(() => { /* show success */ })
  .catch(() => { /* show error */ });
```

---

## 🔧 Customization Guide

### Change the Brand Color

Open `style.css` and update the accent color in `:root`:

```css
:root {
  --accent:   #C96B3A;   /* Change to your brand color */
  --accent-2: #E8A96A;   /* Change to your secondary color */
}
```

### Update Contact Information

In `index.html`, search for and replace:
- `suvaniwaghmare085@gmail.com` → your email
- `suvani-waghmare` → your LinkedIn handle

### Add a Real Founder Photo

In `index.html`, find the `.founder-photo` div and replace the SVG placeholder with an `<img>` tag:

```html
<div class="founder-photo">
  <img
    src="assets/founder.jpg"
    alt="Suvani Waghmare"
    style="width:100%; height:100%; object-fit:cover;"
  />
</div>
```

Create an `assets/` folder and add your photo there.

### Update Project Cards

Each project card uses a CSS variable for its accent color. Change it per card:

```html
<div class="project-card" style="--card-accent: #YOUR_HEX_COLOR;">
```

### Add New Sections

Since this is a single HTML file, copy an existing `<section>` block, give it a new `id`, and add a matching anchor link in the navbar `<ul>`.

---

## 🗺️ Roadmap

- [ ] Add real founder photo
- [ ] Connect contact form to Formspree
- [ ] Add case study detail pages for each project
- [ ] Add client testimonials section
- [ ] Add blog / insights section
- [ ] Add custom animated cursor
- [ ] Add project filtering (All / Branding / Web / etc.)
- [ ] Add Open Graph meta image for social sharing
- [ ] Improve SEO with structured data

---

## 📄 License

Distributed under the MIT License.

```
MIT License

Copyright (c) 2025 Suvani Waghmare — SVRM Nexus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📬 Contact

**Suvani Waghmare** — Founder, SVRM Nexus

| Platform | Link |
|----------|------|
| 📧 Email | [suvaniwaghmare085@gmail.com](mailto:suvaniwaghmare02@gmail.com) |
| 🔗 LinkedIn | [linkedin.com/in/suvani-waghmare](https://www.linkedin.com/in/suvani-waghmare) |
| 🐙 GitHub | [github.com/suvaniwaghmare085-droid](https://github.com/suvaniwaghmare085-droid) |
| 🌐 Website | [suvaniwaghmare085-droid.github.io/SVRM-Nexus](https://suvaniwaghmare02-droid.github.io/SVRM-Nexus) |

---

<div align="center">

Made with ❤️ by **Suvani Waghmare**
© 2025 SVRM Nexus · Charming Design Studio

*Design is not decoration. It's communication.*

</div>
