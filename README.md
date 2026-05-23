# 🚀 Gokul Avhad — Portfolio

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Status-Live-00f5d4?style=for-the-badge&labelColor=0d0d14)
![HTML](https://img.shields.io/badge/HTML5-Static-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=0d0d14)
![CSS](https://img.shields.io/badge/CSS3-Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=0d0d14)
![JS](https://img.shields.io/badge/JavaScript-Canvas-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=0d0d14)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Hosted-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d14)

**Full Stack AI Developer · Python · Machine Learning · Flask · MySQL**

[🌐 Live Site](https://gokulavhad.github.io) · [📧 Email](mailto:gokulavhad2002@gmail.com) · [💬 WhatsApp](https://wa.me/918530003623) · [LinkedIn](https://www.linkedin.com/in/gokul-avhad-052aa7210/) · [GitHub](https://github.com/Gokulavhad)

</div>

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎨 **Ultra-Modern Dark UI** | Cinematic dark theme with cyan + purple accent system |
| 🕸️ **Canvas Particle Animation** | Interactive neural-network particle system in the hero section — mouse-reactive |
| ⌨️ **Typed Text Effect** | Cycling role titles with smooth typewriter animation |
| 🖱️ **Custom Cursor** | Smooth trailing cursor with hover state interactions |
| 📜 **Scroll Reveal Animations** | IntersectionObserver-based staggered fade-in for all sections |
| 📊 **Animated Skill Bars** | Skill progress bars that fill on scroll into view |
| 🔢 **Counter Animations** | Stat numbers count up when visible |
| 🗂️ **Project Filter** | Filter projects by category (AI/ML, Web Apps, Data Science) |
| 💬 **WhatsApp Direct Message** | Floating WhatsApp button + contact form sends pre-filled message |
| 📧 **Email Contact Form** | Opens mailto with pre-filled subject and body |
| 📱 **Fully Responsive** | Mobile-first, works on all screen sizes |
| 🍔 **Mobile Navigation** | Slide-in hamburger menu on small screens |
| ⚡ **Zero Dependencies** | Pure HTML/CSS/JS — no frameworks, no build step |
| 🚀 **GitHub Pages Ready** | Single `index.html` — deploy in one click |

---

## 🗂️ Project Structure

```
gokul-portfolio/
├── index.html        ← Entire site (HTML + CSS + JS inline)
└── README.md         ← This file
```

> Everything is self-contained in `index.html`. No npm, no build tools, no server required.

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create a new GitHub repository

Go to [github.com/new](https://github.com/new) and create a repo named:

```
gokulavhad.github.io
```

> ⚠️ The repo name **must match** `yourusername.github.io` for GitHub Pages to work as your root domain.

---

### Step 2 — Upload files

**Option A — via GitHub website (easiest):**
1. Open your new repo on GitHub
2. Click **Add file → Upload files**
3. Drag and drop `index.html` and `README.md`
4. Click **Commit changes**

**Option B — via Git CLI:**
```bash
git clone https://github.com/Gokulavhad/gokulavhad.github.io.git
cd gokulavhad.github.io

# Copy index.html and README.md into this folder, then:
git add .
git commit -m "feat: launch portfolio site"
git push origin main
```

---

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select `main` branch, folder `/root`
3. Click **Save**
4. Wait 1–2 minutes, then visit: `https://gokulavhad.github.io`

---

## ✏️ Customization Guide

### Add your real photo

Replace the `GA` initials in the hero avatar block with an `<img>` tag:

```html
<!-- Find this in index.html: -->
<div class="hero-avatar">
  <div class="avatar-glow"></div>
  GA   ← replace with:
  <img src="your-photo.jpg" alt="Gokul Avhad"
       style="width:100%;height:100%;object-fit:cover;border-radius:28px;">
</div>
```

Upload your photo to the repo and reference it as `./photo.jpg`.

---

### Add real project links

Find each project card and update the GitHub link:

```html
<a href="https://github.com/Gokulavhad/YOUR-REPO-NAME" target="_blank" class="project-link">
  GitHub
</a>
```

Add a live demo link alongside it:
```html
<a href="https://your-demo-link.com" target="_blank" class="project-link">
  Live Demo ↗
</a>
```

---

### Add a project thumbnail

Replace the emoji in `.project-thumb` with an image:

```html
<div class="project-thumb">
  <img src="./screenshots/project1.png"
       style="width:100%;height:100%;object-fit:cover;opacity:.7;">
  <span class="project-category">AI / ML</span>
</div>
```

---

### Update WhatsApp number

Search for `918530003623` in `index.html` and replace with your number (country code + number, no `+`):

```
918530003623  →  91XXXXXXXXXX
```

---

### Change accent colors

At the top of `<style>`, update CSS variables:

```css
:root {
  --c1: #00f5d4;   /* Primary accent — cyan */
  --c2: #7c3aed;   /* Secondary accent — purple */
  --c3: #f72585;   /* Tertiary — pink */
}
```

---

### Add a new section

Copy the pattern from any existing section:

```html
<section id="your-section" style="background:var(--bg)">
  <div class="reveal">
    <div class="section-label">07 — Label</div>
    <h2 class="section-title">Section Title</h2>
    <p class="section-sub">Description text here.</p>
  </div>
  <!-- your content here -->
</section>
```

Add its nav link:
```html
<li><a href="#your-section">Label</a></li>
```

---

## 📱 WhatsApp Integration

Two touch points are built in:

| Location | Behavior |
|---|---|
| **Floating button** (bottom-right) | Always visible, opens WhatsApp with a default greeting |
| **Contact form "WhatsApp" button** | Sends the form's name + message as the pre-filled WhatsApp text |
| **Contact list item** | Direct link to WhatsApp chat |

The WhatsApp URL format used:
```
https://wa.me/918530003623?text=Hi%20Gokul!...
```

---

## 🔧 Sections Overview

| # | Section | Content |
|---|---|---|
| 01 | **Hero** | Name, typed roles, particle canvas, socials, CTA buttons |
| 02 | **About** | Bio, stats counter, what-I-do service cards |
| 03 | **Skills** | Animated progress bars, tech stack pills |
| 04 | **Experience & Education** | Dual timeline layout |
| 05 | **Projects** | Filterable project cards with tags and links |
| 06 | **Certificates** | Credential cards with direct PDF links |
| 07 | **Contact** | Email form + WhatsApp button + contact list |

---

## 🌐 Live Site

After deploying: **https://gokulavhad.github.io**

---

## 📬 Contact

| Channel | Link |
|---|---|
| 📧 Email | [gokulavhad2002@gmail.com](mailto:gokulavhad2002@gmail.com) |
| 💬 WhatsApp | [+91 85300 03623](https://wa.me/918530003623) |
| 💼 LinkedIn | [gokul-avhad-052aa7210](https://www.linkedin.com/in/gokul-avhad-052aa7210/) |
| 🐙 GitHub | [@Gokulavhad](https://github.com/Gokulavhad) |
| 📸 Instagram | [@gokul.avhad.144](https://www.instagram.com/gokul.avhad.144/) |
| 🎥 YouTube | [@gokulavhad6022](https://www.youtube.com/@gokulavhad6022) |
| 🐦 X / Twitter | [@Gokulav75088317](https://x.com/Gokulav75088317) |

---

<div align="center">

Built with ❤️ by **Gokul Avhad** — Pune, India

</div>
