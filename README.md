# Applications Privacy Policies

Official privacy policies directory for our mobile and web applications.

## Directory Structure

```
privacy/
├── index.html          # Hub directory page listing all applications
├── deepy/
│   └── index.html      # Deepy Privacy Policy (/deepy)
└── README.md
```

---

## App Store & Google Play URLs

* **Deepy Privacy Policy URL:** `https://<your-domain>/deepy` (or `https://<your-username>.github.io/privacy/deepy/`)

---

## Adding Future Apps
To add another app in the future:
1. Create a new folder (e.g., `app-name/`).
2. Add its `index.html`.
3. Add a link card into the root `index.html`.

---

## Deployment Options

### GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings** → **Pages** → Source: **Deploy from a branch** (`main` / root).
3. Deepy URL: `https://<your-username>.github.io/<repo-name>/deepy/`

### Vercel / Cloudflare Pages / Netlify
Deploy the root folder. Both `/` and `/deepy` will automatically be routed.
