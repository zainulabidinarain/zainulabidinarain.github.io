# Zain Ul Abidin — Portfolio Website

A clean, dark-academic personal portfolio for GitHub Pages.

---

## 📁 Folder Structure

```
your-github-username.github.io/          ← root of GitHub Pages repo
├── index.html                           ← main page (all sections)
├── style.css                            ← all styles + theming
├── README.md                            ← this file
└── assets/
    ├── profile.jpg    ← YOUR PHOTO (400×400px recommended, square crop)
    └── cv.pdf         ← your downloadable CV/resume
```

---

## 🚀 GitHub Pages Deployment

1. **Create a repo** named `<your-github-username>.github.io`  
   (e.g., `zainulabdin995.github.io`)

2. **Upload all files** maintaining the folder structure above.

3. **Add your photo** at `assets/profile.jpg`  
   - Recommended: 400×400px, centered face, square crop
   - If not present, a stylish monogram placeholder shows instead

4. **Add your CV** at `assets/cv.pdf` (optional — removes the download button if missing)

5. Go to repo **Settings → Pages → Source → main branch → / (root)**

6. Your site goes live at `https://zainulabidinarain.github.io` within a few minutes!

---

## 🎨 Customization Guide

### Colors (in `style.css` `:root`)
```css
--accent:       #d4a853;   /* warm amber gold — change to your preference */
--bg-primary:   #0d0f14;   /* main background */
--text-primary: #e8e4d9;   /* main text color */
```

### Light theme
Edit `[data-theme="light"]` block in `style.css`.

### Fonts
Replace the Google Fonts link in `<head>` and update `--font-display` and `--font-body` variables.

### Adding a new section
1. Add a `<section class="section" id="my-section">` in `index.html`
2. Add a nav link: `<li><a href="#my-section" class="nav-link">My Section</a></li>`
3. Add `.reveal` class to elements you want to animate in on scroll

---

## ✅ Features

- **Dark / Light theme** — toggleable, preference saved in localStorage
- **Smooth scroll reveal** animations (IntersectionObserver, no JS library)
- **Active nav link** highlighting on scroll
- **Fully responsive** — mobile hamburger menu, tablet/desktop grid layouts
- **Accessible** — ARIA labels, keyboard navigable, reduced-motion support
- **No dependencies** — pure HTML5, CSS3, vanilla JS
- **GitHub Pages ready** — no build step required

---

## 📧 Contact

- Email: zainulabdin995@gmail.com  
- LinkedIn: https://www.linkedin.com/in/zainulabidinarain/  
- GitHub: https://github.com/zainulabidinarain
