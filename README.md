# Xiao Tan — Academic Homepage

A minimal, static academic homepage for Xiao Tan based on the original template's layout and visual style. It shows only basic contact information. Publications, projects, affiliations, and awards are intentionally omitted until their details are supplied.

## Preview locally

```bash
python3 -m http.server 8080 --bind 127.0.0.1
```

Open <http://127.0.0.1:8080/>.

## Update the page

- Edit `index.html` for the name, introduction, email, and GitHub link.
- Add research interests, publications, or projects inside `<main>` when ready. A comment marks the insertion point.
- Edit `stylesheet.css` to adjust the visual design.
- Replace the monogram artwork with a real portrait if desired.

## Publish with GitHub Pages

In the repository settings, choose **Pages → Build and deployment → Deploy from a branch**, then select **main** and **/(root)**. The resulting URL will normally be `https://xiaotankeer.github.io/academic-homepage/`.
