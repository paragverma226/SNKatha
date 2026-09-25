# Snkatha

An interactive flipbook — **47 pages** — hosted on GitHub Pages.

## View Online

> **[Open Flipbook &rarr;](https://YOUR-USERNAME.github.io/SNKatha/)**
>
> Replace `YOUR-USERNAME` with your GitHub username after publishing.

---

## Publish to GitHub Pages (Free)

### Step 1 — Create a repository
1. Go to [github.com/new](https://github.com/new)
2. Name the repository **`SNKatha`** (or anything you like)
3. Set it to **Public**
4. Click **Create repository** (do NOT initialise with README)

### Step 2 — Upload the files
**Option A — GitHub web UI (easiest):**
1. Open your new repository on GitHub
2. Click **uploading an existing file**
3. Drag and drop **all files and folders** from this `SNKatha/` folder
4. Click **Commit changes**

**Option B — Git command line:**
```bash
cd SNKatha
git init
git add .
git commit -m "Initial flipbook"
git remote add origin https://github.com/YOUR-USERNAME/SNKatha.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Set Branch to **main**, folder to **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes — your flipbook is live at:
   `https://YOUR-USERNAME.github.io/SNKatha/`

---

## Preview Locally

Open `index.html` directly in any modern browser.
No web server or internet connection required.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `←` `→` | Navigate pages |
| `Home` / `End` | First / last page |
| `F` | Toggle fullscreen |
| `A` | Auto-flip (3 s interval) |
| `S` | Toggle page-flip sound |
| `+` / `-` | Zoom in / out |
| `0` | Reset zoom |
| `Ctrl + Scroll` | Zoom with mouse wheel |
| Drag (when zoomed) | Pan the view |

---

*Created with FlipTool — PDF to Flipbook Converter*
