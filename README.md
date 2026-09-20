# ICLR Submission 11751

Anonymous project page for ICLR submission 11751.

Live site: https://iclr11751.github.io/

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Layout

Static HTML (Bulma CSS), no build step.

- `index.html` — the page
- `static/` — CSS/JS/favicon
- `new_assets/intact/` — intact-object thumbnails shown in the pickers
- `results/` — result videos, named `{object}__{vertical,horizontal}__vel{n}__mat{n}__frac{n}.mp4` under one folder per channel (`force`, `stress`, `strain`, `flow`, `damage`, `fracture`)
