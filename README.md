# GitHub Pages — Earnly Driver legal/support site

This folder contains the static site that hosts Earnly Driver's Privacy Policy and Support page. Apple requires both URLs to submit the app, so this is a hard blocker for the App Store submission.

The site is built with Jekyll (which GitHub Pages renders for free, no build setup needed on your side).

## Files

| File | Final URL |
|---|---|
| `index.md` | `/` |
| `privacy-en.md` | `/privacy/` |
| `privacy-es.md` | `/privacidad/` |
| `support-en.md` | `/support/` |
| `support-es.md` | `/soporte/` |
| `_config.yml` | (Jekyll config — not a public page) |

The permalink for each page is set inside the file's frontmatter, so the final URL doesn't depend on the filename.

---

## How to publish (one-time, ~10 minutes)

You need a **public** GitHub repo. The app source code can stay private; the legal pages have to be public because Apple's review server fetches them anonymously.

### Step 1 — Create a new public repo on GitHub

1. Go to <https://github.com/new>
2. **Repository name:** `earnly-driver` (recommended) or anything you prefer — this becomes part of the URL
3. **Description:** *Earnly Driver — privacy policy and support*
4. **Visibility:** Public *(required for GitHub Pages on free accounts)*
5. Leave everything else empty. Click **Create repository**.

### Step 2 — Push these files to the new repo

From this folder (`AppStore/legal/`), run:

```bash
cd /Users/user/Proyectos/EarnlyDriver/AppStore/legal

git init
git add .
git commit -m "feat: initial Jekyll site for privacy + support"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/earnly-driver.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 3 — Enable GitHub Pages

1. On the new repo's GitHub page, click **Settings** (top right of the repo, not your account settings)
2. Left sidebar: **Pages**
3. **Source:** Deploy from a branch
4. **Branch:** `main` / `(root)` — click **Save**
5. Wait ~30–60 seconds. The page will refresh with a green box: *"Your site is live at https://YOUR-USERNAME.github.io/earnly-driver/"*

### Step 4 — Verify the URLs work

Open these in your browser and confirm they load:

- `https://YOUR-USERNAME.github.io/earnly-driver/privacy/`
- `https://YOUR-USERNAME.github.io/earnly-driver/privacidad/`
- `https://YOUR-USERNAME.github.io/earnly-driver/support/`
- `https://YOUR-USERNAME.github.io/earnly-driver/soporte/`

If you see formatted pages with the Cayman theme, you're done. If you see the raw markdown, GitHub Pages hasn't finished building — wait another minute and refresh.

### Step 5 — Paste URLs into App Store Connect

In ASC → **App Information** → **General Information**:

- **Privacy Policy URL (English):** `https://YOUR-USERNAME.github.io/earnly-driver/privacy/`
- **Privacy Policy URL (Spanish):** `https://YOUR-USERNAME.github.io/earnly-driver/privacidad/`

In ASC → **App Information** → **Localized Information** → **Support URL**:

- **Support URL (English):** `https://YOUR-USERNAME.github.io/earnly-driver/support/`
- **Support URL (Spanish):** `https://YOUR-USERNAME.github.io/earnly-driver/soporte/`

---

## Updating the site later

When you need to update Privacy Policy or Support content (e.g. before a major version that changes data handling), edit the markdown file, then:

```bash
git add .
git commit -m "docs: update privacy policy for X"
git push
```

GitHub Pages rebuilds automatically in ~30 seconds.

---

## Optional: custom domain

If you ever buy `earnly-driver.com` or similar, you can point GitHub Pages at it:
1. Add a `CNAME` file with the domain inside this folder
2. In GitHub Pages settings, enter the custom domain
3. Configure DNS at your registrar (`A` records to GitHub's IPs)

Not needed for App Store submission — `github.io` URLs are accepted by Apple.
