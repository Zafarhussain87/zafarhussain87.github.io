# My personal website

A one-page personal site (About, News, Projects, Publications, CV) hosted free on GitHub Pages.
No build tools needed: it's a single `index.html` file.

## Put it online (about 5 minutes)

1. Create a free account at https://github.com.
2. Click **+ → New repository** and name it exactly `yourusername.github.io`
   (replace `yourusername` with your GitHub username). Make it **Public**.
3. Click **uploading an existing file** and drag in `index.html`, `README.md`,
   and (optionally) `cv.pdf` and `profile.jpg`. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`, and click **Save**.
5. After 1–2 minutes your site is live at `https://yourusername.github.io`.

## Edit it

Open `index.html` on GitHub, click the pencil icon, edit, and commit. The site updates in about a minute.

- **Name, role, links**: the `HERO` block near the top
- **Photo**: upload `profile.jpg`, then swap the `<div class="avatar">YN</div>` line for
  `<img class="avatar" src="profile.jpg" alt="Zafar Malik">`
- **Projects / Publications**: copy an existing block and change the text
- **CV**: upload your PDF as `cv.pdf` so the "Download CV" buttons work
- **Colours**: change `--accent` in the `:root` section at the top of the file

## Optional: custom domain

Buy a domain (e.g. yourname.com), add it under **Settings → Pages → Custom domain**,
and follow GitHub's DNS instructions.
