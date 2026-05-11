# 🍑 Glute Tracker - GitHub Pages Deployment Guide

## What You'll Get
- **Permanent URL** that works from any WiFi network, cellular data, or device
- **Works offline** after first visit (Progressive Web App)
- **Installable as an app** on your iPhone home screen
- **Free forever** - no server costs

---

## Quick Setup (5 minutes)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Create a free account (use any email)

### Step 2: Create a New Repository
1. After logging in, click the **+** icon (top right) → **New repository**
2. Fill in:
   - **Repository name:** `g-tracker`
   - **Description:** "My glute training tracker app"
   - **Public** (must be public for free GitHub Pages)
   - ✓ Check "Add a README file"
3. Click **Create repository**

### Step 3: Upload Your Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these 3 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Scroll down and click **Commit changes**

### Step 4: Enable GitHub Pages
1. In your repository, click **Settings** (top menu)
2. Scroll down and click **Pages** (left sidebar)
3. Under "Source", select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 5: Get Your URL
1. Refresh the Settings → Pages page
2. You'll see: **"Your site is live at https://adriannabardowska.github.io/g-tracker/"**
3. Click the URL to test it
4. **Save this URL** - it's your permanent link!

---

## Using Your App

### On Any Device (First Time)
1. Open your GitHub Pages URL: `https://adriannabardowska.github.io/g-tracker/`
2. The app loads (uses `index.html`)

### Install as App on iPhone
1. Open your GitHub Pages URL in Safari
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**
5. You'll see a "Glute Tracker" icon on your home screen with the 💪 emoji

### Works Everywhere
- ✓ From home WiFi
- ✓ From gym WiFi
- ✓ On cellular data
- ✓ Offline (after first visit)
- ✓ On any device (phone, tablet, computer)

---

## Updating Your App

When you want to change the workout program:

1. Edit the file on your Mac
2. Go to your GitHub repository
3. Click on the file you want to update (e.g., `index.html`)
4. Click the **pencil icon** (Edit this file)
5. Delete all content and paste your new content
6. Click **Commit changes**
7. Wait 1-2 minutes, then refresh your app (changes will appear)

**Or use GitHub Desktop app (easier):**
1. Install [GitHub Desktop](https://desktop.github.com/)
2. Clone your repository
3. Edit files locally
4. Commit & push changes
5. Changes go live automatically

---

## Files You Need to Upload

### 1. index.html
Your main app file (the tracker with all the workouts)

### 2. manifest.json
Makes your app installable on iPhone home screen

### 3. sw.js
Service worker that makes your app work offline

---

## Troubleshooting

**"My URL doesn't work"**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure repository is **Public** not Private
- Check that you selected **main** branch and **/ (root)** folder

**"Changes don't show up"**
- Wait 1-2 minutes after uploading
- Hard refresh: Hold Shift and click refresh button
- Clear browser cache

**"App doesn't work offline"**
- Visit the URL once while online
- Service worker needs to install first
- Check browser console for errors

**"Can't install on iPhone"**
- Make sure you're using Safari (not Chrome)
- Make sure manifest.json and sw.js are uploaded
- Try refreshing the page first

---

## Your Files Are Located At:
- Main folder: `/Users/adriannabardowska/Documents/Glute-Training-Plan/`
- iCloud backup: `/Users/adriannabardowska/Library/Mobile Documents/com~apple~CloudDocs/`

---

## Example URLs

Your current GitHub Pages URL is:
- `https://adriannabardowska.github.io/g-tracker/`

The exact URL depends on the GitHub username and repository name.

---

## Next Steps

1. Follow the Quick Setup above
2. Get your permanent URL
3. Install the app on your iPhone home screen
4. Start tracking workouts from anywhere!

**Questions?** Check [GitHub Pages documentation](https://docs.github.com/en/pages)
