# Pomodojo PWA — Setup Guide

## How to Deploy on GitHub Pages (Free)

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com) and sign up (free)

### Step 2: Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `pomodojo`
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3: Upload the Files
1. On your new repo page, click **"Add file"** → **"Upload files"**
2. Drag and drop all 3 files from the Pomodojo-PWA folder:
   - `index.html`
   - `sw.js`
   - `manifest.json`
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **"Deploy from a branch"**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/pomodojo/`

---

## How to Install on Your iPhone

### Add to Home Screen
1. Open Safari on your iPhone
2. Go to `https://YOUR-USERNAME.github.io/pomodojo/`
3. Tap the **Share** button (square with arrow at bottom)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it **Pomodojo** and tap **Add**

### Enable Notifications
1. Open Pomodojo from your home screen
2. When prompted, tap **"Allow"** for notifications
3. If you missed the prompt: go to **Settings → Notifications → Pomodojo** and enable

---

## That's It! 🎉

Your Pomodojo app is now:
- ✅ On your home screen like a real app
- ✅ Full screen (no browser bar)
- ✅ Works offline
- ✅ Saves your data locally
- ✅ Free forever — no expiration, no signing
- ✅ Sends notifications when focus sessions end

---

## Updating the App

If you want to make changes later:
1. Edit the files on GitHub (or upload new versions)
2. On your iPhone, open Pomodojo and pull down to refresh
3. The service worker will update the cached version

---

## Troubleshooting

**App doesn't appear full screen:**
→ Make sure you opened it from the Home Screen icon, not from Safari

**Notifications not working:**
→ Must be added to home screen first (Safari doesn't support PWA notifications)
→ Check Settings → Notifications → Pomodojo

**Data disappeared:**
→ This can happen if you clear Safari's website data. It's rare in normal use.

**Changes not showing after update:**
→ Open the app, wait 5 seconds, close it, reopen — the service worker will update
