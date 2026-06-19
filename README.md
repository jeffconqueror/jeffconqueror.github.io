# jingchl6.github.io

My personal academic website. Plain HTML + CSS — no build step.

Live at: https://jingchl6.github.io (once deployed, see below).

## Files
- `index.html` — all the content (edit the text here).
- `style.css` — the styling (colors, spacing).
- `images/avatar.svg` — placeholder photo. Replace with your own (see below).

## Customize (search for `[...]` placeholders in index.html)
- [x] Photo (`images/profile.jpg`, cropped from `pic.jpg` — you can delete `pic.jpg`).
- [x] Advisor: Ziad Al-Halah. Master: Zhiting Hu (UCSD). Undergrad: Sitao Huang (UCI).
- [x] Google Scholar + email (jingcheng.li@utah.edu) linked.
- [ ] Confirm your school/department link (defaults to Kahlert School of Computing).
- [ ] Update the start date in **News** (currently 2026.08).
- [ ] Add publications using the template comment in `index.html`.

## Preview locally
```bash
cd jingchl6.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (free, via GitHub Pages)
A GitHub **user site** must live in a repo named exactly `jingchl6.github.io`.

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin https://github.com/jingchl6/jingchl6.github.io.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a
branch → Branch: `main` / `root` → Save.** Your site goes live at
https://jingchl6.github.io within a minute or two.
