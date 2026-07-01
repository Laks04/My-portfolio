<div align="center">

# ✦ Lakshitha Loganathan — Portfolio

### *Build. Learn. Repeat.*

**AI/ML Engineer · Bengaluru, India**

[![Live Site](https://img.shields.io/badge/Live%20Site-Open%20Portfolio-cccccc?style=for-the-badge&logo=googlechrome&logoColor=000)](https://laks04.github.io/My-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshitha-loganathan/)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-333333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshithaloganathan4@gmail.com)

</div>

---

## 📌 Overview

Personal portfolio website for **Lakshitha Loganathan**, a final-year Computer Engineering student (AI/ML specialisation) at East Point College of Engineering and Technology, Bengaluru — GPA 8.8 / 10.

This is a single-file, zero-dependency portfolio built to the architecture and design standards of a modern Next.js + Tailwind CSS + Framer Motion stack, delivered as a self-contained HTML file that runs anywhere with no build step required.

---

## 🖥️ Preview

| Section | Description |
|---|---|
| **Hero** | Animated particle network · Playball name · typewriter role · Build. Learn. Repeat. tagline |
| **About** | Bio · trait cards · live terminal metrics block |
| **Projects** | Phishing URL Detection Engine — 95K+ URLs, 0.96 F1 |
| **Experience** | Tabbed: Work → Hackathons → Education → Certifications |
| **Skills** | Animated skill bars · 4 categories · spoken languages |
| **Contact** | Email CTA · LinkedIn · phone |

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Architecture | Next.js 14 App Router (component structure pattern) |
| Styling | Tailwind CSS utility system (CSS custom properties) |
| Language | TypeScript (JSDoc-annotated throughout) |
| Animations | Framer Motion (`whileInView`, `staggerChildren`, `AnimatePresence`) |
| Fonts | Playball · Crimson Text 400 Italic · JetBrains Mono |
| Colour palette | `#000000` · `#333333` · `#666666` · `#999999` · `#CCCCCC` |
| Delivery | Single HTML file · zero dependencies · no build step |

---

## ✨ Features

- **Sticky navbar** — transparent on hero, frosted-glass blur on scroll, active-section highlighting, animated underline indicator, scroll-progress bar
- **Mobile drawer** — hamburger menu with numbered links, slide-down animation, closes on outside tap
- **Framer Motion animations** — `initial → animate` fade-up on every section, `staggerChildren` delays, `whileHover` spring lifts on all cards
- **Typewriter** — cycles through roles: AI/ML Engineer · Model Builder · Pipeline Architect · NLP Enthusiast
- **Neural canvas** — live WebGL-style particle network in the hero background
- **Tabbed experience** — Work → Hackathons → Education → Certifications with animated panel transitions
- **Skill bars** — animate on first scroll into view (IntersectionObserver)
- **Shimmer gradient text** — animated greyscale shimmer on section titles
- **One-click copy** — email address copies to clipboard from contact section
- **Fully responsive** — tested at 375px (mobile), 768px (tablet), 1280px+ (desktop)
- **Dark mode native** — pure `#000000` background throughout

---

## 🚀 Getting Started

### View instantly (no install needed)

```bash
# Clone the repo
git clone https://github.com/lakshithaloganathan/portfolio.git
cd portfolio

# Open directly in your browser
open index.html
# or on Windows:
start index.html
```

That's it. No `npm install`. No build step. No environment variables.

### Rename for GitHub Pages

```bash
cp lakshitha-portfolio-v2.html index.html
```

Push to your repo and enable **GitHub Pages → Deploy from branch → `main` → `/root`** in repository Settings.

---

## 🗂️ Project Structure

```
portfolio/
├── index.html          # Complete portfolio — single self-contained file
└── README.md           # This file
```

### Internal component structure (mirrors Next.js App Router)

```
[/components/Navbar.tsx]     — Sticky nav, hamburger, progress bar, active link tracker
[/components/Hero.tsx]       — Canvas animation, typewriter, stats
[/components/About.tsx]      — Bio, trait cards, terminal block
[/components/Projects.tsx]   — Phishing URL Detection Engine card with metrics
[/components/Experience.tsx] — Tabbed: Work / Hackathons / Education / Certifications
[/components/Skills.tsx]     — Animated skill bars, language pills
[/components/Contact.tsx]    — Email CTA, LinkedIn, phone links
```

---

## 🎨 Design Tokens

```css
--black:  #000000   /* background */
--dark:   #111111   /* canvas, terminal */
--card:   #1a1a1a   /* card backgrounds */
--border: #2a2a2a   /* all borders */
--dark2:  #333333   /* dim text, timeline lines */
--mid:    #666666   /* secondary text */
--light:  #999999   /* body text */
--pale:   #cccccc   /* accent, headings */
--white:  #f0f0f0   /* primary headings on hover */
```

```
Playball          — name only (hero + nav logo + footer)
Crimson Text 400 Italic — all body text, descriptions, section headings
JetBrains Mono    — labels, badges, code blocks, nav links, stats
```

## 📬 Contact

| Channel | Detail |
|---|---|
| Email | lakshithaloganathan4@gmail.com |
| LinkedIn | [linkedin.com/in/lakshithaloganathan](https://www.linkedin.com/in/lakshithaloganathan) |
| Phone | +91 7795187927 |
| Location | Bengaluru, Karnataka, India |

---

## 🛠️ Customisation

All content lives directly in `index.html` — no CMS, no config files, no API calls.

| What to change | Where in the file |
|---|---|
| Name / tagline / bio | `#hero` and `#about` sections |
| Projects | `#projects` section — update metrics, description, stack tags |
| Work experience | `#tab-work` inside `#experience` |
| Hackathons | `#tab-hack` inside `#experience` |
| Education | `#tab-edu` inside `#experience` |
| Certifications | `#tab-certs` inside `#experience` |
| Skill levels | `data-w` attributes on `.s-fill` elements in `#skills` |
| Contact info | `#contact` section and `copyEmail()` function in `<script>` |
| Colour palette | `:root` CSS custom properties at top of `<style>` block |
| Fonts | Google Fonts `<link>` tag in `<head>` + `--font-*` variables |

---

<div align="center">

Made with intention · Bengaluru, India · 2025

</div>
