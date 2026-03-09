# Time-Tracker PWA — Deployment Guide

## Files in this folder
- `index.html` — The full time tracker app
- `manifest.json` — Makes it installable as an app
- `sw.js` — Service worker for offline support
- `icons/` — App icons

## Step-by-step: Deploy to GitHub Pages

### 1. Create a GitHub account
Go to https://github.com and sign up (free).

### 2. Create a new repository
- Click the "+" icon → "New repository"
- Name it: `time-tracker`
- Set to **Public**
- Click "Create repository"

### 3. Upload your files
- Click "uploading an existing file"
- Drag and drop ALL files from this folder:
  - index.html
  - manifest.json
  - sw.js
  - icons/ folder (upload icon-192.svg and icon-512.svg)
- Click "Commit changes"

### 4. Enable GitHub Pages
- Go to repository → Settings → Pages
- Under "Source" select: **Deploy from a branch**
- Branch: **main** | Folder: **/ (root)**
- Click Save

### 5. Your app is live!
After ~1 minute your URL will be:
`https://YOUR-USERNAME.github.io/time-tracker/`

---

## Install on Android

1. Open Chrome on your Android phone
2. Visit your GitHub Pages URL
3. Tap the **3-dot menu** (top right)
4. Tap **"Add to Home screen"**
5. Tap **"Add"**

Time-Tracker now appears on your home screen like a real app! ✓
Works fully offline ✓
Data saves on your phone ✓
