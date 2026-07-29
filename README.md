# Portfolio

Personal portfolio site showcasing projects, contact details, and a downloadable resume.

Overview

This folder contains the portfolio landing page and supporting assets used to present projects and contact information.

Primary files

- `Portfolio.html` — main portfolio page (projects, about, contact)
- `mallard.jpg`, `Mandarin Duck.jpg`, `Bufflehead.jpg`, `harlequin.jpg` — local image assets used in the project previews
- `style.css` — styles used by the portfolio pages (if present)

Local preview

Open `Portfolio.html` in your browser to view locally. To serve the folder via a simple HTTP server, run one of the following from this folder:

```bash
# PHP built-in server
php -S localhost:8000

# Python 3 simple server
python -m http.server 8000
```

Then open `http://localhost:8000/Portfolio.html` in your browser.

Notes

- Images are stored locally; if you move or rename them, update the image `src` paths in `Portfolio.html`.
- Replace any images you don't have rights to before publishing publicly.
