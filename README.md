# Xiaolin Liu Academic Homepage

Static academic homepage for Xiaolin Liu, a Ph.D. student in Intelligence Science and Technology at the University of Science and Technology of China.

## Preview

Run a local static server:

```bash
python -m http.server 8000 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8000/
```

## Content

Main files:

- `index.html`: profile, biography, research interests, publications, education, awards
- `styles.css`: layout and responsive styling
- `personal.jpg`: profile photo
- `qdu.jpg`, `sdu.png`, `ustc.png`: school logos
- `zgca.webp`: Beijing Zhongguancun Academy logo
- `haier.jpg`, `SII.webp`: internship organization logos

Publication metadata was filled from the public ORCID record:

```text
https://orcid.org/0009-0004-5440-5908
```

## Deploy To GitHub Pages

Create a GitHub repository named:

```text
czkqh.github.io
```

Then push this repository:

```bash
git remote add origin https://github.com/czkqh/czkqh.github.io.git
git push -u origin main
```

The site will be available at:

```text
https://czkqh.github.io
```
