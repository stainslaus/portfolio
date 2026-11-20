# Stainslaus Phillimon – Portfolio

A static portfolio site (HTML, CSS and a little JavaScript, no build step) ready for GitHub Pages.

## Contact details
Email and LinkedIn are set in the Contact section of `index.html`. The portrait used on the landing page is `images/stainslaus.webp`; replace that file (same name) to change the photo.

## Publish on GitHub Pages
1. Create a new public repository on GitHub. Name it `<your-username>.github.io` to get the address `https://<your-username>.github.io`, or use any name (e.g. `portfolio`) to get `https://<your-username>.github.io/portfolio`.
2. Click **Add file > Upload files** and drag in everything from this folder (`index.html`, `.nojekyll`, `README.md` and the `images` folder, including `stainslaus.webp`). Commit.
3. Go to **Settings > Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. Wait a minute or two, then open the address shown on that page.

## Adding a new project
1. Export the design as WebP or JPG: a full-size copy (about 2000 px on the long side) into `images/full/` and a smaller copy (about 900 px) into `images/thumbs/`, both with the same file name.
2. In `index.html`, copy one `<figure class="work">…</figure>` block, change the image path, title, category (`flyers`, `brochures`, `social`, `signage` or `identity`) and give `data-index` the next number.
3. Add a matching entry at the end of the `projects` list near the bottom of the file (`src`, `title`, `desc`, `w`, `h`), and update the count on the filter button.
