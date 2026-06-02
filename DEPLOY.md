# Deploy PRF Manager to GitHub Pages

Follow these steps to get the app live on your phone in ~5 minutes.

---

## Step 1 — Create a GitHub account (if you don't have one)
Go to https://github.com and sign up for a free account.

---

## Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `prf-manager` (or anything you like)
3. Set to **Public**
4. Click **Create repository**

---

## Step 3 — Upload the files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop ALL THREE files:
   - `index.html`
   - `sw.js`
   - `manifest.json`
3. Click **Commit changes**

---

## Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** → folder: **/ (root)**
5. Click **Save**

GitHub will give you a URL like:
```
https://YOUR-USERNAME.github.io/prf-manager/
```

---

## Step 5 — Get it on your phone
1. Open the URL above in your phone's browser (Safari on iPhone, Chrome on Android)
2. **iPhone:** Tap Share → "Add to Home Screen"
3. **Android:** Tap the 3-dot menu → "Add to Home Screen" / "Install app"

The app will now work fully **offline** — no internet required on the event.

---

## Short URL (optional)
To make the URL easier to share, use https://bitly.com to create a short link pointing to your GitHub Pages URL.

---

## GDPR note
- All patient data is stored **only on the device** that enters it
- Nothing is sent to GitHub or any server — the hosting only serves the app code
- Delete all data from Settings at the end of the event
- Exported PDFs should be treated as clinical records

---

## Updating the app
If you need to update the app later, just re-upload the changed `index.html` to GitHub and the changes will go live automatically.
