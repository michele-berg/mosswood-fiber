# Mosswood Fiber Studio

Static website for Mosswood Fiber Studio, designed to run on GitHub Pages.

## Pages

- `index.html` — landing page
- `gallery.html` — gallery placeholders for knitted creations
- `teaching.html` — upcoming teaching engagements
- `recommended-patterns.html` — recommended patterns and next-project ideas
- `books.html` — book recommendations with space for affiliate links
- `contact.html` — bot-resistant contact email, instructor bio, and Ravelry ID

## Assets

The source file `Logo images.png` was split into three image panels:

- `assets/images/mosswood-tree-logo.jpg`
- `assets/images/mosswood-round-logo.jpg`
- `assets/images/mosswood-knot-logo.jpg`

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

Commit these files to the repository and enable GitHub Pages for the repository's default branch. The site uses plain HTML and CSS, so no build step is required.
