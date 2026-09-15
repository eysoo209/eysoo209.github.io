# Yoonsoo Eo — Academic Homepage

Personal academic homepage: <https://eysoo209.github.io/>.

A responsive, static HTML/CSS site hosted on GitHub Pages. No build tools, JavaScript, or third-party tracking are required.

## Update the website

- Edit `index.html` to update the biography, publications, or other CV entries.
- Edit `style.css` to change the layout and appearance.
- Replace `cv.pdf` with the latest CV, keeping the filename unchanged.
- Replace `profile.jpg` to change the profile photograph.
- Commit and push to `main`; GitHub Pages publishes from the root of that branch.

The photo uses CSS `object-fit: cover` in a 240 × 300 frame. The source image is unchanged.

## Sources

Biographical content and scholarly links are based on the September 2026 CV supplied by the owner. Publication status, expected graduation, and anticipated project dates are preserved as listed in that CV. The homepage highlights first-author presentations; the complete presentation list remains in the downloadable CV.

Layout and CSS are adapted from [Seunghyun An’s homepage](https://seunghyun-an.github.io/) at the owner’s request. Only the owner’s CV, photograph, and website files belong in this public repository.

## Local preview

Serve this directory with any static HTTP server, for example:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8000>.
