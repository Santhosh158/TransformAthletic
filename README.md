# Transform30 — 30-Day Athletic Transformation PWA

## Quick Deploy (3 options)

### Option 1: GitHub Pages (Free, Recommended)
1. Create a new GitHub repo (e.g., `transform30`)
2. Upload ALL files from this folder to the repo root
3. Go to Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Folder: `/ (root)`
4. Wait 1-2 minutes. Your app will be live at `https://yourusername.github.io/transform30`
5. Open that URL on your iPhone in Safari → Share → Add to Home Screen

### Option 2: Netlify (Free, Drag & Drop)
1. Go to https://app.netlify.com/drop
2. Drag this entire folder into the browser
3. Done! You get a URL like `random-name.netlify.app`
4. Open on iPhone Safari → Share → Add to Home Screen

### Option 3: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder
3. Follow prompts. Get a URL.
4. Open on iPhone Safari → Share → Add to Home Screen

## Adding to iPhone Home Screen
1. Open the deployed URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (square with arrow at bottom)
3. Scroll down, tap **"Add to Home Screen"**
4. Tap **"Add"**
5. The app will appear on your home screen with its own icon
6. It launches full-screen — no browser bar!

## What's Saved
- Your current day selection
- All checklist completions for every day
- Data persists across sessions via localStorage

## Files
```
index.html          — The entire app (React + all data)
manifest.json       — PWA configuration
sw.js               — Service worker (offline support)
apple-touch-icon.png — iPhone home screen icon
icons/
  icon-192.png      — Android/web icon
  icon-512.png      — Large icon
  icon-maskable-512.png — Maskable icon
```
