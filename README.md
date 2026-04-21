# NUH ClinPath Guidelines — PWA

Clinical guidelines quick-reference app for Nottingham University Hospitals.

## Files in this package

| File | Purpose |
|------|---------|
| `index.html` | The full app — all guidelines, search, navigation |
| `manifest.json` | Makes it installable as an app |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen, small) |
| `icon-512.png` | App icon (splash screen, large) |

---

## How to deploy (5 minutes, one-time)

### Step 1 — GitHub account
Go to **github.com** → Sign up (free). Skip if you already have one.

### Step 2 — Create a repository
- Click **+** (top right) → **New repository**
- Name: `nuh-guidelines` (or anything you like)
- Set to **Public**
- Tick **Add a README file**
- Click **Create repository**

### Step 3 — Upload all 5 files
- Inside the repo, click **Add file → Upload files**
- Drag all 5 files from this folder: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
- Click **Commit changes**

### Step 4 — Enable GitHub Pages
- Click **Settings** tab
- Left sidebar → **Pages**
- Under Source: select **Deploy from a branch**
- Branch: **main** → folder: **/ (root)**
- Click **Save**
- Wait 2 minutes → your URL appears at the top of the Pages section

Your URL will be: `https://YOUR-USERNAME.github.io/nuh-guidelines`

---

## Install on phone

### iPhone (Safari only — must use Safari, not Chrome)
1. Open your GitHub Pages URL in **Safari**
2. Tap the **Share button** (box with arrow pointing up)
3. Scroll down → tap **Add to Home Screen**
4. Name it **NUH Guidelines** → tap **Add**

### Android (Chrome)
1. Open your URL in **Chrome**
2. Tap the **three dots** menu (top right)
3. Tap **Add to Home Screen** or **Install app**
4. Tap **Install**

The app will appear on your home screen and open full-screen like a native app.
It also works **offline** after the first load.

---

## Share with colleagues
Once live, just send them the URL. They can install it themselves in 30 seconds.

## Update the guidelines
To add or update a guideline:
1. Go to your GitHub repo
2. Click on `index.html` → pencil icon (Edit)
3. Make changes
4. Commit — the live app updates automatically within ~1 minute

---

## Guidelines currently included
- Febrile Neutropenia in Adult Oncology (REF:1538 v7.0)
- Antiemetics / CINV (REF:1490 v7)
- Diarrhoea Post Chemo/RT (REF:1837)
- Chemical Pleurodesis — Nursing & Clinical Procedure Guide

*Built with ClinPath · NUH · Vish Naicker ST6 Clinical Oncology*
