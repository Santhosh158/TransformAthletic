# Transform30 — 30-Day Athletic Transformation PWA

## 🚀 Deploy to iPhone in 2 Minutes

### Option 1: Netlify (Easiest — Drag & Drop)
1. Unzip this file on your computer
2. Go to **https://app.netlify.com/drop**
3. Drag the **entire unzipped folder** into the browser
4. You'll get a URL like `random-name.netlify.app`
5. Open that URL on your **iPhone in Safari**
6. Tap the **Share button** (⬆️ square with arrow)
7. Tap **"Add to Home Screen"** → **Add**
8. Done! Launches full-screen like a real app.

### Option 2: GitHub Pages (Free)
1. Create a new GitHub repo (e.g., `transform30`)
2. Upload ALL files maintaining the folder structure
3. Settings → Pages → Source: `main` branch, `/ (root)`
4. Wait 2 min → live at `https://yourusername.github.io/transform30`
5. Open on iPhone Safari → Share → Add to Home Screen

### Option 3: Vercel (Free)
1. Install: `npm i -g vercel`
2. Run `vercel` in this folder
3. Open the URL on iPhone Safari → Share → Add to Home Screen

## 📱 What You Get
- **Full-screen app** — no browser bar, looks native
- **9 tabs**: Today, Train, Meals, Posture, Science, Life, Roadmap, Grocery, Supps
- **Progress saves automatically** — checklist ticks and current day persist via localStorage
- **Works offline** after first load (service worker caches everything)
- **30 days** of unique workouts with Week 1-2 break-in → Week 3-4 barbell progression → Test Week
- **7 unique meal plans** with full recipes, macros, and ingredients
- **26 research citations** across 7 science categories

## 📁 Files
```
index.html              ← The entire app (67KB)
manifest.json           ← PWA config (standalone mode)
sw.js                   ← Service worker (offline)
apple-touch-icon.png    ← iPhone home screen icon (180×180)
icons/
  icon-192.png          ← Standard web icon
  icon-512.png          ← Large icon
  icon-maskable-512.png ← Android adaptive icon
```

## ⚠️ Important
- Must use **Safari** on iPhone (other browsers have limited PWA support)
- Data is stored in localStorage — clearing Safari data will reset progress
- The app loads React from CDN on first visit, so you need internet for the first load
