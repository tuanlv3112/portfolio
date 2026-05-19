# Vũ Thị Thanh Bình — Portfolio

Personal portfolio website for Vũ Thị Thanh Bình, Social Content Creator.

## Structure

```
portfolio/
├── index.html
├── css/styles.css
├── js/main.js
└── assets/images/    ← put your photos here
```

## Adding Photos

Replace placeholder divs with `<img>` tags:

| Placeholder | Suggested image | Location in HTML |
|---|---|---|
| Hero photo | `assets/images/profile.jpg` | `.hero-image-placeholder` |
| About photo | `assets/images/about.jpg` | `.about-img-placeholder` |
| Job 1 campaign | `assets/images/hunter-work.jpg` | first `.job-img-placeholder` |
| Job 2 livestream | `assets/images/hoangha-live.jpg` | second `.job-img-placeholder` |
| Job 3 content | `assets/images/sadesign-content.jpg` | third `.job-img-placeholder` |
| Job 4 viral | `assets/images/pigme-content.jpg` | fourth `.job-img-placeholder` |

## Deploy on GitHub Pages

1. Push to GitHub:
```bash
git init
git add .
git commit -m "init portfolio"
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

2. Go to repo **Settings → Pages → Source → Deploy from branch → main**

Site will be live at: `https://YOUR_USERNAME.github.io/portfolio/`
