# Thomas Liang — personal website

Static researcher homepage. No build step: `index.html` + `style.css`, with the CV in `cv/`.

- `cv/resume.tex` — LaTeX source (XeLaTeX, uses the `resume` class from ThmsLiang/resume)
- `cv/Thomas_Liang_Resume.pdf` — last built PDF, linked from the site

Preview locally:

```bash
python3 -m http.server 8000
```

To host on GitHub Pages, push to GitHub and enable Pages on the `main` branch (root).
