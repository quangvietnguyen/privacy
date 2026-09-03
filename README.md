# Deepy – Privacy Policy Page

This repository contains the official, standalone **Privacy Policy** webpage for **Deepy** (`com.nqv.dwast`).

## Quick Preview
Open `index.html` in any web browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html
```

---

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)
1. Push this folder to a GitHub repository (e.g. `github.com/your-username/deepy-privacy`).
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select **Deploy from a branch**.
4. Set branch to `main` / `root` (`/`) and click **Save**.
5. Your Privacy Policy URL will be: `https://your-username.github.io/deepy-privacy/`

---

### Option 2: Vercel (Instant)
```bash
npx vercel deploy --prod
```

---

### Option 3: Netlify Drop / CLI
```bash
npx netlify deploy --prod --dir=.
```

---

### Option 4: Cloudflare Pages
1. Connect this repo to Cloudflare Pages.
2. Set Build Output directory to `/`.
3. Deploy!

---

## App Store Connect Submission
Use the deployed live URL as your **Privacy Policy URL** in App Store Connect under **App Information** → **Privacy Policy URL**.
