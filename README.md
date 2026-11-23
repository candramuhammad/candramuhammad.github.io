# Minimal academic website for GitHub Pages

A lightweight, responsive, free-to-host academic and educational website. No account, build tools, dependencies, framework, or hosting payment required beyond your GitHub account.

## Preview locally

Open `index.html` in a browser. You can also use `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Customize before publishing

1. In `index.html`, replace `Your Name`, `YOUR NAME`, `Your Institution`, `Your City, Country`, and the example bio.
2. Update the example publications. **These are placeholders, not real papers.** Update the URLs or delete the entries entirely.
3. Update links in the contact section, or remove ones you don't want to share.
4. Link your teaching projects or notebooks when you are ready. Currently the teaching cards are descriptive placeholders.
5. Change the page title and metadata in the HTML `<head>`.
6. Optionally customize colors in `assets/style.css` at `:root`.

## Publish on GitHub Pages (no command line)

1. Sign in at https://github.com.
2. Click **+** (top right) → **New repository**.
3. Name the repository **YOUR-EXACT-USERNAME.github.io** (replace with your own GitHub username).
4. Choose **Public** and create the repository.
5. On the repository page, choose **Add file** → **Upload files**. Upload `index.html`, the `assets` folder and its contents, and optionally `README.md`. Ensure `index.html` is at the repository root and the stylesheet at `assets/style.css`.
6. Click **Commit changes**.
7. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
8. Open **https://YOUR-EXACT-USERNAME.github.io/** after deployment. GitHub says publication can take up to about 10 minutes.

If the repository has a different default branch, choose that branch instead of `main`. With GitHub Free the repository must be public to publish it with GitHub Pages.

## Updating later

Edit `index.html` directly on GitHub using the pencil button and commit your changes. GitHub Pages will republish the site automatically.

## Privacy

Everything in this public repository and on the site is public. Do not upload private contact details, unpublished research data, passwords or API keys.

Official guide: https://docs.github.com/en/pages/quickstart
