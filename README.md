# Clean Hugo Blog (GitHub Pages Ready)

This is a **ready-to-go Hugo blog** you can push to GitHub and host on **GitHub Pages** using **GitHub Actions**.

## What you get
- Markdown posts (`content/posts/...`)
- Tags + Categories + Series (built-in Hugo taxonomies)
- Clean, fast, minimal theme included in this repo (`themes/cleanlite`) — no external theme dependency
- GitHub Actions workflow that builds + deploys to GitHub Pages on every push to `main`

---

## 1) Run locally

### Install Hugo (Extended)
- macOS (Homebrew): `brew install hugo`
- Windows (winget): `winget install Hugo.Hugo.Extended`

Then:

```bash
hugo server
```

Open the URL Hugo prints (usually http://localhost:1313).

Important: write and edit posts only in `content/posts/*.md` (or `content/posts/<name>/index.md`).
The `public/` folder is generated HTML output and should not be edited manually.

---

## 2) Create a new post

```bash
hugo new posts/my-new-post.md
```

Edit the front matter to add tags/categories:

```yaml
---
title: "My New Post"
date: 2026-02-13
draft: false
tags: ["one", "two"]
categories: ["notes"]
series: ["start-here"]
---
```

---

## 3) Deploy to GitHub Pages

1. Create a new GitHub repo (example: `myblog`)
2. Copy these files into the repo (or just upload them), then commit + push to `main`.

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin main
```

3. In GitHub: **Settings → Pages**
   - Under **Build and deployment**, set **Source** to **GitHub Actions**
   - Keep branch/source settings empty (the workflow handles deployment artifacts)

4. Go to the **Actions** tab, you should see a workflow run named **Deploy Hugo site to GitHub Pages**.
   - When it finishes, your site will be live at:
     - `https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/` (project site)

> Tip: If you want the site at `https://<YOUR_USERNAME>.github.io/` (no /repo), create a repo named `<YOUR_USERNAME>.github.io`.

---

## Customize
- Site config: `hugo.toml`
- Theme templates: `themes/cleanlite/layouts/`
- Theme CSS: `themes/cleanlite/assets/css/main.css`
