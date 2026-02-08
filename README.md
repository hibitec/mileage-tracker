# Mileage Tracker PWA - Installation Guide

Your iOS mileage tracker has been converted to a Progressive Web App (PWA)! 🎉

## What You Get

Your web app has all the same features as your iOS app:
- ✅ Track available miles balance
- ✅ Quick log trips with description and miles
- ✅ Add personal miles to your balance
- ✅ Edit and delete trips
- ✅ Activity log of all changes
- ✅ Export activity log to CSV
- ✅ Reset balance
- ✅ Works offline after first load
- ✅ Stores data locally on your device
- ✅ No 7-day reinstallation needed!

## Files Included

1. **mileage-tracker.html** - The main app file
2. **manifest.json** - PWA configuration
3. **sw.js** - Service worker for offline support
4. **icon-192.png** - App icon (192x192)
5. **icon-512.png** - App icon (512x512)

## Installation Steps

### Step 1: Host Your App

You need to put these files on a web server. Here are the easiest free options:

#### Option A: GitHub Pages (Recommended - Easiest!)

1. Go to https://github.com and sign in (or create free account)
2. Click "New repository"
3. Name it: `mileage-tracker`
4. Check "Public" and "Add a README file"
5. Click "Create repository"
6. Click "Add file" → "Upload files"
7. Drag and drop ALL 5 files (html, json, js, and both png files)
8. Click "Commit changes"
9. Go to Settings → Pages
10. Under "Source", select "main" branch
11. Click "Save"
12. Wait 1-2 minutes, then your app will be at:
    `https://YOUR-USERNAME.github.io/mileage-tracker/mileage-tracker.html`

#### Option B: Netlify Drop

1. Go to https://app.netlify.com/drop
2. Drag and drop all 5 files into the box
3. Your app is instantly live at the provided URL

#### Option C: Vercel

1. Go to https://vercel.com
2. Sign up/login with GitHub
3. Import your repository or drag files
4. Deploy

### Step 2: Install on Your iPhone

1. **Open Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your app's URL from Step 1
3. Tap the **Share button** (square with arrow pointing up at bottom of screen)
4. Scroll down and tap **"Add to Home Screen"**
5. Give it a name (or keep "Mileage Tracker")
6. Tap **"Add"**

That's it! The app icon will appear on your home screen just like a regular app.

## Important Notes

- **Data Storage**: All your data is stored locally in your browser. It will persist as long as you don't clear Safari's website data.
- **Offline Use**: After loading once, the app works completely offline.
- **Updates**: If you make changes to the code, just re-upload the files to your hosting service. Users may need to refresh the page or clear cache.
- **Backup**: To backup your data, use the "Export Log" feature regularly.

## Troubleshooting

**"Add to Home Screen" option not showing:**
- Make sure you're using Safari (not Chrome or other browsers)
- Make sure the site is using HTTPS (GitHub Pages, Netlify, and Vercel all use HTTPS automatically)

**Data not saving:**
- Make sure you haven't disabled Safari's localStorage
- Check Settings → Safari → Advanced → Website Data

**App not loading offline:**
- Make sure you've opened it at least once while online
- The service worker needs to cache the files on first load

## Need Help?

If you run into any issues:
1. Make sure all 5 files are uploaded to the same directory
2. Make sure the URLs in the HTML file match your setup
3. Try hard refreshing Safari (hold refresh button)
4. Check the browser console for errors (Safari → Develop → Show JavaScript Console)

Enjoy your permanently installed mileage tracker! 🚗📱
