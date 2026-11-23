# Research visualization layout update

This package updates your current dark academic homepage, preserving the other sections and bilingual articles.

## Publish

1. Upload/replace `index.html` and `assets/style.css` in your existing GitHub Pages repository.
2. Upload your own `PHANTOM_EXE_v3.gif` **into `assets/`** (it is not included in this package).
3. Keep the existing `assets/script.js`, `assets/favicon.svg`, and `articles/` files.
4. Commit your changes; GitHub Pages will redeploy automatically.

## Adding the next animation

In `index.html`, find the desired `<figure class="research-visual research-placeholder">`.
Replace it with a figure like:

```html
<figure class="research-visual">
  <div class="ascii-title">DYNAMICAL SYSTEMS / ASCII ANIMATION</div>
  <img src="assets/phase_portrait.gif" alt="Animated phase portrait" width="640" loading="lazy">
  <figcaption>Animated phase portrait</figcaption>
</figure>
```

Upload the new GIF to `assets/` with exactly the same spelling/capitalization. The CSS automatically shows text and GIF side-by-side on larger screens and stacked on phones.

Avoid enlarging GIFs above their exported width to keep ASCII text crisp. Animated GIFs run automatically; users who prefer reduced motion may still see them animate, so a static alternative is a worthwhile future enhancement.
