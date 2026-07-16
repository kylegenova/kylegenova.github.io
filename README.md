# kylegenova.github.io

Personal academic website of Kyle Genova, served at [www.kylegenova.com](https://www.kylegenova.com).

## Structure

- `index.html` — the site (single page, no build step, no dependencies)
- `CV.pdf` — compiled CV, linked from the site
- `cv/cv.tex` — CV source

## Updating the CV

```sh
cd cv
xelatex cv.tex && xelatex cv.tex
cp cv.pdf ../CV.pdf
```

Requires XeLaTeX (MacTeX) and the Charter font (included with macOS).
