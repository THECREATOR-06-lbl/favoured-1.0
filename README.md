# Favoured Wings Wholesales — website

A single self-contained page (`index.html`). No build step, no dependencies to install — just the one file.

## Put it live with GitHub Pages

1. **Create a repository**
   - Go to github.com → **New repository**.
   - Name it anything (e.g. `favoured-wings`). Public. Skip adding a README (you already have one).

2. **Upload the file**
   - Open the new repo → **Add file → Upload files**.
   - Upload `index.html` (and this `README.md` if you like) from this folder.
   - Commit directly to the `main` branch.

3. **Turn on Pages**
   - In the repo, go to **Settings → Pages**.
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Branch: `main`, folder: `/ (root)` → **Save**.

4. **Get your link**
   - Wait about a minute, then refresh that same Settings → Pages screen.
   - Your site will be live at:
     `https://<your-github-username>.github.io/<repo-name>/`

That's it — no further setup needed. The file has everything inline (fonts load from Google Fonts, the billboard image is embedded directly in the HTML), so there's nothing else to upload.

## Using a custom domain (optional)
If you own a domain (e.g. `favouredwings.com`):
1. In **Settings → Pages → Custom domain**, enter it and save — GitHub creates a `CNAME` file for you automatically.
2. At your domain registrar, add a `CNAME` record pointing to `<your-github-username>.github.io`.
3. Wait for DNS to propagate (can take a few hours), then check "Enforce HTTPS" back in the Pages settings.

## Making future edits
Any time you want to change text, prices, or the image, just edit `index.html` directly in GitHub (pencil icon → edit → commit), or upload a replacement file. The site updates automatically within a minute or two of the commit.
