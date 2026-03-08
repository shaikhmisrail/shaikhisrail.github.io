# GitHub Pages UI Upload Checklist

This folder is ready for GitHub UI upload.

## 1) Create repository
- Create a **public** GitHub repository named: `<your-github-username>.github.io`
  - Example: `shaikhisrail.github.io`

## 2) Upload files using GitHub UI
- Open the repo in browser
- Click **Add file → Upload files**
- Drag and drop **all files from this folder**
- Commit changes

Required files in this folder:
- `index.html`
- `Shaikh_Israil_Resume.pdf`
- `CNAME`

## 3) Enable Pages in UI
- Repo **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: `main` and `/ (root)`

## 4) DNS records at registrar
For apex domain (`shaikhisrail.me`) add A records:
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

For `www` add CNAME:
- `www` -> `<your-github-username>.github.io`

## 5) Final checks
- In GitHub Pages settings, verify custom domain shows `shaikhisrail.me`
- Enable **Enforce HTTPS** once certificate is ready
- Open:
  - `https://shaikhisrail.me`
  - `https://www.shaikhisrail.me`
- Click **View resume** and confirm PDF opens

> If your final domain is different, edit the `CNAME` file before upload.
