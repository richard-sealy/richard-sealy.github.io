# richard-sealy.github.io

Personal website for Richard Sealy, leadership coach. Plain static HTML and CSS with no build step. GitHub Pages serves the site directly from the main branch.

## Structure

- `index.html` is the home page
- `about/`, `coaching/`, `contact/` each hold a page as `index.html`
- `writing/` is the blog. The index lists posts and each post lives in its own folder, for example `writing/what-the-mountains-teach/index.html`
- `assets/css/style.css` holds all styling
- `.nojekyll` tells GitHub Pages to serve the files as they are

## Adding a blog post

1. Copy an existing post folder inside `writing/` and rename it to a short slug for the new post
2. Edit the copied `index.html` with the new title, date, description and body
3. Add a matching entry to the list in `writing/index.html` and, if you want it featured, to the recent writing list in the root `index.html`
4. Commit and push to main. The site updates within a couple of minutes
