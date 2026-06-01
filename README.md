# AI Roast Me — Privacy & Terms

GitHub Pages site for AI Roast Me legal docs.

**Live URL:** `https://<your-username>.github.io/roastme-privacy/`

## Files

- `index.html` — landing page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `support.html` — Support / FAQ
- `_style.css` — shared dark theme styles

## Deploy to GitHub Pages (5 minutes)

```bash
cd /Users/akbaralikhasanov/Public/AppStore/privacy-site

# 1. init repo
git init
git add .
git commit -m "Initial site"
git branch -M main

# 2. create the repo on GitHub
#    Open https://github.com/new
#    Name: roastme-privacy
#    Visibility: Public
#    Don't initialize with README

# 3. push (replace USERNAME)
git remote add origin https://github.com/USERNAME/roastme-privacy.git
git push -u origin main

# 4. enable GitHub Pages
#    GitHub → your repo → Settings → Pages
#    Source: Deploy from a branch
#    Branch: main / (root)
#    Save
```

Wait ~1 minute. Your site will be at:

- `https://USERNAME.github.io/roastme-privacy/`
- `https://USERNAME.github.io/roastme-privacy/privacy.html`
- `https://USERNAME.github.io/roastme-privacy/terms.html`
- `https://USERNAME.github.io/roastme-privacy/support.html`

## Use in App Store Connect

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://USERNAME.github.io/roastme-privacy/privacy.html` |
| **Support URL** | `https://USERNAME.github.io/roastme-privacy/support.html` |
| **Marketing URL** (optional) | `https://USERNAME.github.io/roastme-privacy/` |

## Before publishing — replace placeholders

- [ ] `support@roastme.app` → your actual support email (search/replace across all 4 HTML files)
- [ ] Effective date if you change it later

## Updating

Edit any file, then:
```bash
git add . && git commit -m "Update" && git push
```
Changes go live in ~1 minute.
