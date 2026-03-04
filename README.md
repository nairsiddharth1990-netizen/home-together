# 🏠 Home Together — PWA Setup Guide

A household task tracker for couples. Works offline, installs on your phone.

---

## 📦 What's in this folder

```
index.html     ← The entire app (open this in a browser to test locally)
manifest.json  ← Makes it installable as a PWA
sw.js          ← Service worker (offline support)
icon-192.png   ← App icon
icon-512.png   ← App icon (large)
```

---

## 🚀 Deploy to Netlify (free, takes 2 minutes)

1. Go to **[netlify.com](https://netlify.com)** and create a free account
2. Click **"Add new site" → "Deploy manually"**
3. **Drag the entire `home-together` folder** into the upload box
4. Netlify gives you a URL like `https://yourapp.netlify.app`
5. Share that URL with your wife!

---

## 📱 Install on iPhone

1. Open the Netlify URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow at the bottom)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"** — done! 🎉

## 📱 Install on Android

1. Open the Netlify URL in **Chrome**
2. Tap the **three-dot menu** (top right)
3. Tap **"Add to Home Screen"** or **"Install app"**
4. Tap **"Install"** — done! 🎉

---

## 🔔 Push Notifications

After installing, open the app and tap **"Enable reminders"** in the header.
Both you and your wife need to do this on your own phones.

Notifications fire for:
- Tasks due today
- Overdue tasks

---

## 💾 Data

Tasks are saved in your browser's local storage — they persist between sessions
and survive closing the app. Each phone has its own copy of the tasks.

> **Tip:** If you want both phones to share the same task list in real time,
> the next step is adding a small backend (like Firebase or Supabase). 
> Ask Claude to help with that when you're ready!
