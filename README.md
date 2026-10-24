bdeewang.com
========

Personal website of Deewang Bhamidipati, built with [Quarto](https://quarto.org) and hosted on GitHub Pages at <https://bdeewang.com>.

## Editing

- Each page is a `.qmd` file in this folder (`research.qmd`, `teaching.qmd`, …), written in Markdown.
- Site-wide settings (title, menu, footer, theme) are in `_quarto.yml`.
- Fonts, colours and layout are in `theme.scss`; dark-mode colours are in `theme-dark.scss`.
- `_header-title.html` puts each page's title in the header; `_about-photo.html` rotates the homepage photo.
- Images, fonts and other files live in `static/`.

## Preview and publish

```bash
quarto preview              # live preview while editing
quarto publish gh-pages     # build the site and publish it to the gh-pages branch
```

The original design was based on the Jekyll template **Seredyna** by Derek Kedziora (https://derekkedziora.com).

All content on this site is under a [Creative Commons Zero License](https://creativecommons.org/publicdomain/zero/1.0/). You’re free to copy, reuse, modify or do whatever you want with it.
