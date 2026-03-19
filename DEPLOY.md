# Deploy to GitHub Pages

## Step 1 — Create a GitHub repo

1. Go to https://github.com/new
2. Name it `superhumn-site`
3. Set to **Public** (required for free GitHub Pages)
4. Leave "Initialize with README" unchecked
5. Click "Create repository"

---

## Step 2 — Upload your files

On the empty repo page, click **"uploading an existing file"**

1. Drag in everything from this folder: `index.html`, the `images/` folder
2. Commit message: `Initial site upload`
3. Click **Commit changes**

---

## Step 3 — Enable GitHub Pages

1. Repo → **Settings** → **Pages** (left sidebar)
2. Source → **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Click **Save**

Live in ~60 seconds at:
`https://[your-github-username].github.io/superhumn-site/`

---

## Step 4 — Connect superhumn.com (optional)

1. Settings → Pages → Custom domain → enter `superhumn.com` → Save
2. At your domain registrar, add these DNS records:

```
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   [your-username].github.io
```

3. Check "Enforce HTTPS" once DNS propagates (~24 hrs)

---

## Updating the site later

- Edit text: click `index.html` in the repo → pencil icon → edit in browser → commit
- Swap images: drag new files into the `images/` folder (keep same filenames)
- Every commit auto-republishes within ~30 seconds

---

## Folder structure

```
superhumn-site/
├── index.html
├── images/
│   ├── logo.png                  ← already included
│   ├── hero-bg.jpg               ← your photo here
│   ├── product-feature.jpg
│   ├── channel-healthcare.jpg
│   ├── channel-education.jpg
│   ├── channel-corporate.jpg
│   └── channel-k12.jpg
├── IMAGES.md                     ← photo size guide
└── DEPLOY.md                     ← this file
```
