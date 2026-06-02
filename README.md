# Botany

Materials for Botany course

## Course website

<https://your-username.github.io/botany/>

## Structure

This is a Quarto website with revealjs presentation slides for each lecture:

- `day1/` through `day7/` - Weekly lecture slides
- `on-demand/` - Self-paced lecture content
- `index.qmd` - Main course homepage
- `styles.css` - Custom CSS styling
- `_quarto.yml` - Quarto configuration

## Building the site

To preview the site locally:

```bash
quarto preview
```

To render the site:

```bash
quarto render
```

## Deployment

Deploy to `gh-pages` branch with:

```bash
quarto publish gh-pages
```

Or manually push the `docs/` folder to GitHub and enable GitHub Pages in
repository settings.
