# Ismaila Abioye Adeniran — Portfolio Website

A lightweight static portfolio website designed for GitHub version control and Cloudflare Pages deployment.

## Positioning

The site positions Ismaila across public health, population research, quantitative analysis, research support, and graduate-study readiness rather than narrowing him to a single health-data job title.

## Files

- `index.html` — full website structure and content
- `styles.css` — responsive visual system and animations
- `script.js` — navigation, scroll state, and reveal interactions
- `assets/Ismaila_Adeniran_CV.docx` — downloadable CV

## Add the portrait later

Replace the `.portrait-placeholder` block in `index.html` with an image element, for example:

```html
<img class="portrait-image" src="assets/ismaila-portrait.jpg" alt="Portrait of Ismaila Abioye Adeniran">
```

Then add to `styles.css`:

```css
.portrait-image {
  width: 100%;
  min-height: 490px;
  object-fit: cover;
  border-radius: 24px;
}
```

## Deploy with GitHub + Cloudflare Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In Cloudflare Pages, choose **Connect to Git** and select the repository.
4. Framework preset: **None**.
5. Build command: leave blank.
6. Build output directory: `/`.
7. Deploy.

Any later push to the connected branch will trigger a new Cloudflare Pages deployment.
