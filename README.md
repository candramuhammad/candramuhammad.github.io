# Candra Muhammad — Classic Dark Academic Website

A plain-HTML GitHub Pages website with an early-2000s academic style and dark background. No build tools or paid hosting required.

## Publish

1. Make a backup of the current GitHub repository files before replacing them.
2. Upload the CONTENTS of this folder to the root of `candramuhammad.github.io` (not a nested `candra-classic-dark` folder).
3. Replace the old `index.html` and `assets/style.css`. Upload `assets/script.js`, `assets/favicon.svg`, `.nojekyll` (optional for this plain HTML setup), and the entire `articles/` folder.
4. **Remove old files only if you are sure they are no longer needed.** The old `assets/script.js` or separate unused files can remain safely.
5. Commit and revisit https://candramuhammad.github.io/ after deployment.

## Writing articles / Menulis artikel

- Articles index: `articles/index.html`
- English template: `articles/en/sample.html`
- Indonesian template: `articles/id/contoh.html`
- Copy a template and rename it, e.g. `articles/id/mengenal-energi-gelap.html`.
- Change its `<title>`, `<h1>`, description, and main body. Use `lang="id"` for Indonesian articles.
- Add a link to the new file under the matching language in `articles/index.html`.
- Both sample links are clearly labeled TEMPLATE and should be removed or replaced before public launch of the blog.
- For many articles, consider moving to Jekyll later to write Markdown and generate index pages automatically.

## GIF / ASCII

Place your animation at `assets/phantom_crossing.gif`; replace the demo `<pre>...</pre>` in `index.html` with:

```html
<img src="assets/phantom_crossing.gif" alt="ASCII animation of the phantom-divide crossing" width="640">
```

Use the native export resolution to avoid blurring. Add a link to the Python source separately; GitHub Pages does not run Python on the server.

## Navigation

Teaching is omitted from the navigation and homepage for now. The site uses an Articles section instead. The website is static and can be edited directly on GitHub.
