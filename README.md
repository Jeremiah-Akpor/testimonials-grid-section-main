# Testimonials Grid Section

A responsive implementation of the [Frontend Mentor Testimonials Grid Section challenge](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7), built with semantic HTML and CSS.

![Challenge design preview](./preview.jpg)

## Links

- **Live site (after GitHub Pages is enabled):** https://jeremiah-akpor.github.io/testimonials-grid-section-main/
- **Source code (after pushing):** https://github.com/Jeremiah-Akpor/testimonials-grid-section-main

> These are the planned GitHub Pages and repository URLs. The live site requires publishing from the repository's `main` branch (root directory), and the repository name must match the URL above.

## Overview

Five graduate testimonials arranged in a single column on mobile and a four-column, two-row CSS Grid layout on wider screens. Selected cards span multiple tracks to match the challenge's desktop composition.

## Built with

- Semantic HTML5 (`main`, `article`, and testimonial headings)
- CSS custom properties in `tokens.css`
- CSS Grid for the desktop layout
- Flexbox for profile details and page alignment
- Mobile-first responsive styling and media queries
- CSS logical properties for spacing
- Barlow Semi Condensed via Google Fonts

## What I learned

- How fractional grid tracks (`fr`) divide available space after accounting for `gap`.
- How `grid-column` and `grid-row` position cards and span multiple tracks.
- Why `grid-row: span 2` controls size, while `grid-row: 1 / span 2` also fixes the starting row.
- How explicit item placement differs from Grid's automatic placement.
- How to separate page-level centering from the inner testimonial grid.
- How to share a color palette through CSS custom properties while giving individual cards distinct styles.


## Author

- GitHub: [Jeremiah-Akpor](https://github.com/Jeremiah-Akpor)

## Credits

Design and challenge by [Frontend Mentor](https://www.frontendmentor.io/).
