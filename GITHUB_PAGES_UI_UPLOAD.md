# GitHub Pages UI Upload Checklist (Username-only)

This folder is ready for GitHub UI upload **without buying/setting a custom domain**.

## 1) Create repository
- Create a **public** GitHub repository named exactly:
  - `shaikhmisrail.github.io`

> This must match your GitHub username (`shaikhmisrail`).

## 2) Upload files using GitHub UI
- Open the repo in browser
- Click **Add file → Upload files**
- Drag and drop **all files from this folder**
- Commit changes

Required files in this folder:
- `index.html`
- `Shaikh_Israil_Resume.pdf`

## 3) Enable Pages in UI
- Repo **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: `main` and `/ (root)`

## 4) Do NOT configure custom domain
- In **Settings → Pages**, leave **Custom domain** empty
- If there is an old custom domain value, remove it

## 5) Final checks
- Open your site at:
  - `https://shaikhmisrail.github.io`
- Click **View resume** and confirm PDF opens

---

If you later want `shaikhisrail.me`, you can add a `CNAME` file and configure DNS.
