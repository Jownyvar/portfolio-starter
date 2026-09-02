# Portfolio starter

A one-page portfolio: one HTML file, one stylesheet, no build step. Fork it, make it
yours, and put it online with GitHub Pages in about 15 minutes.

## Make it yours

1. **Fork** this repository into your GitHub account.
2. On your fork: **Settings** → **General** → **Rename** the repository to `portfolio`.
3. **Clone** it: `git clone git@github.com:<your-username>/portfolio.git`
4. Open `index.html` and edit the three marked spots: your name, one line about you, your links.
5. Commit and push:

   ```
   git add .
   git commit -m "Make the portfolio mine"
   git push
   ```

## Put it online

1. On GitHub: **Settings** → **Pages**.
2. Source: **Deploy from a branch**. Branch: `main`, folder `/ (root)`. **Save**.
3. Wait about a minute, then open `https://<your-username>.github.io/portfolio`.

Every future update is the same loop: edit, `git add .`, `git commit -m "..."`, `git push`.

## Notes

- Keep paths relative (`href="style.css"`, never `/style.css`). The site is served under
  `/portfolio/`, so absolute paths break.
- Do not create folders that start with `_`; GitHub Pages skips them unless you add a
  `.nojekyll` file.
