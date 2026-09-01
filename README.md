# Paulos Lab Website

Starter lab website built with [Quarto](https://quarto.org/) and designed for free hosting on GitHub Pages.

## 1. Install Quarto

Download Quarto from:

https://quarto.org/docs/get-started/

You do not need R or Python just to build this site.

## 2. Preview the site locally

Open a terminal in this folder and run:

```bash
quarto preview
```

Quarto will open the site in your web browser and automatically refresh as you edit files.

## 3. Replace the placeholders

Search the project for:

- `YOURUSERNAME`
- `YOUR EMAIL`
- `YOUR OFFICE`
- `YOUR LAB LOCATION`
- `#` links
- placeholder photos

Replace:

- `images/hero-placeholder.jpg`
- `images/project-placeholder.jpg`
- `images/abby-placeholder.jpg`

with your own images using the same filenames, or change the filenames in the code.

## 4. Create the GitHub repository

A simple option is:

`YOURUSERNAME.github.io`

Then upload/push all project files to that repository.

## 5. Publish with GitHub Pages

From the project folder:

```bash
quarto publish gh-pages
```

The first time, Quarto may ask you to authorize GitHub.

After publishing, your site will be available at:

`https://YOURUSERNAME.github.io`

## 6. Editing later

Most routine edits happen in the `.qmd` files.

For example, adding a person or changing a research description is just editing Markdown text and republishing.

## Color palette

- Warm cream: `#F7F4EE`
- Paper white: `#FFFDF8`
- Deep green: `#214E46`
- Muted sage: `#A8B7A5`
- Rust accent: `#A65A3A`
- Gold accent: `#C79B58`
- Charcoal: `#24302D`

You can change these near the top of `styles.css`.
