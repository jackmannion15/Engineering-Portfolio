# Jack Mannion — Engineering Portfolio

A static site version of the portfolio, built to be hosted free on GitHub Pages.

## What's in here
- `index.html` — all page content
- `styles.css` — all styling
- `images/` — project photos and CAD renders

No build step, no dependencies — just plain HTML/CSS.

## Deploy it on GitHub Pages (free)

1. **Create a new GitHub repo.**
   Go to github.com → New repository. Name it whatever you want (e.g. `portfolio`).
   Keep it public.

2. **Upload these files.**
   On the repo's main page, click "Add file" → "Upload files," then drag in
   `index.html`, `styles.css`, `README.md`, and the whole `images` folder.
   Commit the changes.

3. **Turn on Pages.**
   In the repo, go to Settings → Pages (left sidebar).
   Under "Build and deployment," set Source to **Deploy from a branch**,
   Branch to **main** and folder to **/ (root)**. Save.

4. **Wait ~1 minute, then find your link.**
   Refresh that same Settings → Pages screen — it'll show your live URL:
   `https://<your-username>.github.io/<repo-name>/`

5. **Put that link on your resume and LinkedIn.**

## Making changes later
Edit `index.html` for text/content, `styles.css` for colors/spacing/layout.
Any edit you commit to the `main` branch redeploys automatically within a
minute or two — no separate publish step.

## Adding more projects
Copy one `<section class="sheet">...</section>` block in `index.html`,
update the text and image filenames, and update the "Sheet 0X / 0Y" numbers
across all sections to match the new total.
