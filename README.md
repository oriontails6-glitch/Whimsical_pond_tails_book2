# Whimsical Pond Tails — Book Two (Flipbook)

Same format as Book One: a realistic page-curl flipbook, plain HTML/CSS/JS,
ready to host straight from GitHub Pages.

## Folder structure
```
flipbook-story-book2/
├── index.html      ← the whole book: cover, 10 story pages, back cover
├── style.css        ← dreamy storybook styling (same as Book One)
├── script.js         ← initializes the page-curl effect (same as Book One)
└── images/          ← the 10 story illustrations
```

## Editing the story
Everything is in `index.html`. Each page is a `<div class="page">…</div>`
block — find the page by its `<h3>` title and edit the text or swap the
image path inside it.

## Hosting on GitHub Pages
1. Create a new repo (e.g. `Whimsical_pond_tails_book2`) and upload every
   file in this folder, keeping `images/` as a subfolder and `index.html`
   at the repo root.
2. On GitHub: **Settings → Pages** → Source = "Deploy from a branch" →
   branch `main`, folder `/ (root)` → Save.
3. Your live link will look like
   `https://yourusername.github.io/Whimsical_pond_tails_book2/`.

## Notes
- Images were compressed from the original Word doc exports (was ~26MB,
  now ~2.4MB total) so the book loads fast on mobile data.
- `style.css` and `script.js` are the same mobile-tuned versions used for
  Book One, so drag-to-flip, page sizing, and phone layout behave the
  same way here.
- If you ever see a page fail to deploy on GitHub Pages after an edit,
  double check you copy-pasted the *entire* file (first and last lines
  included) and that no smart quotes snuck in from a rich-text editor —
  that's the most common cause of a build breaking after a paste.
