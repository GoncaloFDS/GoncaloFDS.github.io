# goncalofds.github.io

My CV, served by GitHub Pages at <https://goncalofds.github.io>.

One page of plain HTML and one hand-written stylesheet. No build step,
no framework, no dependencies beyond two webfonts.

```
index.html                   the whole site
assets/css/site.css          the whole stylesheet
assets/img/                  headshot and screenshots
assets/img/games/            thumbnails for each title
assets/goncalo-soares-cv.pdf
```

Editing: open `index.html`, change the text. `site.css` holds the palette
and spacing as custom properties at the top.

## The PDF

`assets/goncalo-soares-cv.pdf` is the one-page CV linked from the header.

It is a static file, not generated from this page, so editing
`index.html` does not update it. When the text changes, replace the PDF
by hand.
