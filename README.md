# Anil Sonagara — Developer Portfolio

A fully animated, production-grade mobile developer portfolio.

## 🚀 Deploy on GitHub Pages (Free & Auto-Update)

### Step 1 — Create GitHub Repo
1. Go to [github.com/new](https://github.com/new)
2. Name it: `portfolio` (or `anil-sonagara.github.io` for a custom URL)
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Upload Files
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/ (root)`
3. Click **Save**
4. Your site will be live at: `https://YOUR_USERNAME.github.io/portfolio`

---

## ✏️ How to Update Portfolio

### Add a new project:
Edit `index.html` → find `<!-- PROJECTS GRID -->` → copy a `.project-card` block and fill in your new project details.

### Change your info:
- **Hero text**: Search for `hero-name` and `hero-title`
- **About section**: Search for `<!-- ABOUT -->`
- **Skills**: Search for `<!-- SKILLS -->`
- **Experience**: Search for `<!-- EXPERIENCE -->`

### Add project images:
Drop new `.png` or `.jpg` files into `/images/` folder, then reference them in `index.html` as `images/your-file.png`.

### Push updates:
```bash
git add .
git commit -m "Updated projects"
git push
```
GitHub Pages auto-rebuilds within ~1 minute. ✅

---

## 📁 File Structure
```
portfolio/
├── index.html          ← Main portfolio file (edit this)
├── images/
│   ├── admire-care.png
│   ├── bimakart.png
│   └── prux.png
└── README.md
```
