# Venue Audience Intelligence

Confidential market analysis, audience personas, and hospitality bidder strategy for Caesars Superdome and US Bank Stadium.

## Access

Live URL: *(set after GitHub Pages is enabled — see below)*

Password: `venue2026`

---

## Deploy to GitHub Pages (one-time setup)

### Step 1 — Create the repository

1. Go to [github.com/new](https://github.com/new)
2. Name it something like `venue-intelligence` (can be private or public)
3. Leave everything else as default
4. Click **Create repository**

### Step 2 — Upload the file

1. On the new repo page, click **Add file → Upload files**
2. Drag both `index.html` and `README.md` into the upload area
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages

1. Go to **Settings** (top tab of the repo)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save**

### Step 4 — Get your URL

GitHub will show a banner: *"Your site is live at https://yourusername.github.io/venue-intelligence"*

It takes about 60 seconds to go live after saving. That's your permanent shareable URL.

---

## Changing the password

The password is protected by SHA-256 hashing inside `index.html`.

To change it:

1. Pick a new password
2. Get its SHA-256 hash — paste your password into [sha256.online](https://sha256.online) or run: `echo -n "yourpassword" | sha256sum`
3. Open `index.html` and find the line: `const HASH = '94d0b8cea53...'`
4. Replace the hash value with your new one
5. Re-upload to GitHub — the change goes live within ~60 seconds

---

## File details

| File | Purpose |
|------|---------|
| `index.html` | Complete self-contained web app (436 KB) |
| `README.md` | This file |

The HTML file has zero external dependencies — all fonts are embedded as base64, all JS is inline. It works offline and will never break due to a CDN going down.

---

*Caesars Superdome · US Bank Stadium · March 2026*
