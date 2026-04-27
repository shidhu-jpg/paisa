# Paisa PWA — Deploy Instructions

## Files in this folder
```
index.html      ← The full app
manifest.json   ← PWA configuration
sw.js           ← Service worker (offline support)
icon-192.png    ← App icon (Android home screen)
icon-512.png    ← App icon (splash screen / Play Store)
```

---

## Option 1 — Netlify (Easiest, 60 seconds)

1. Go to https://netlify.com
2. Sign up free (use Google login)
3. Drag this entire folder onto the Netlify dashboard
4. You get a live link like: https://paisa-abc123.netlify.app
5. Share that link on WhatsApp — anyone can open it and tap "Add to Home Screen"

Optional: Go to Site Settings → Change site name → https://paisa.netlify.app

---

## Option 2 — GitHub Pages (Free, permanent)

1. Go to https://github.com and create a free account
2. Click "New repository" → name it "paisa" → Public
3. Upload all files from this folder
4. Go to Settings → Pages → Source: main branch → Save
5. Live at: https://yourusername.github.io/paisa

---

## Option 3 — WebIntoApp (Get an APK)

1. First deploy to Netlify or GitHub Pages (above)
2. Go to https://webintoapp.com
3. Paste your URL
4. Download the .apk file
5. Share via WhatsApp, Google Drive, or direct link
6. Recipients enable "Install from unknown sources" once, then install

---

## How users install it on Android

1. Open the link in Chrome
2. Chrome shows a banner: "Add Paisa to Home Screen"  
   OR tap Chrome menu (⋮) → "Add to Home Screen"
3. Tap Install
4. Paisa appears on their home screen like a real app ✓

## How users install it on iPhone (iOS Safari)

1. Open the link in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap Add ✓

---

## What "works offline" means

Once installed, Paisa loads instantly even with no internet.  
All data is stored on the device (localStorage).  
No server, no database, no monthly cost.

---

Built with ♥ by Paisa
