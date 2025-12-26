# mohcine-portfolio

This repository contains the source for my personal portfolio website (GitHub Pages, Jekyll).

## What's included

- Minimal Jekyll site scaffold: `index.md`, `about.md`, `projects.md`, `_layouts` and `assets`.
- A simple workflow to build & deploy with GitHub Pages.
- Instructions below to publish the site to GitHub Pages.

## Quick start

1. Add your resume PDF to the repo root as `resume.pdf`.
2. Add your profile photo to `assets/images/profile.jpg`.
3. Edit `index.md`, `about.md`, and `projects.md` with your content.
4. Initialize a git repo, commit, and push to GitHub (see commands below).

Commands:

```bash
cd mohcine-portfolio
git init
git add .
git commit -m "Initial portfolio scaffold"
git branch -M main
# create repo on GitHub (use gh cli or the website) and then:
git remote add origin git@github.com:<your-username>/mohcine-portfolio.git
git push -u origin main
```

## Enable GitHub Pages

1. In the GitHub repo, go to Settings → Pages. Set Source to `main` branch and `/ (root)` / `gh-pages` depending on your workflow.
2. If using the included workflow, the site will be built and deployed automatically to GitHub Pages.

---

If you want, I can: scaffold actual project pages from your repo(s, create a resume link and add analytics/contact form; tell me which extras you want next.