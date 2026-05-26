# InterPet4D Project Page

Static project page for **InterPet4D: A Multimodal 4D Human–Pet Interaction Dataset for Pet Motion Generation** (ECCV 2026).

## Local preview

Just open `index.html` in a browser, or run a tiny static server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Repo **Settings → Pages → Build and deployment → Source**: `Deploy from a branch`.
3. Branch: `main` / folder: `/ (root)`. Save.
4. Page will be live at `https://<user>.github.io/<repo>/` in a minute.

## What to fill in

Search the HTML for these placeholders and replace them:

- `href="#"` on each author name → personal homepage
- `href="#"` on the **Paper / arXiv / Code / Dataset / Video** buttons → real URLs
- `static/images/teaser.png` → teaser image (Fig. 1 from the paper works well)
- `static/images/capture_setup.png` → capture-setup figure (Fig. 2)
- `static/images/architecture.png` → IPMG architecture (Fig. 3)
- `static/videos/teaser.mp4`, `petting.mp4`, `commanding.mp4`, `calling.mp4`, `freeform.mp4`, `result1.mp4`, `result2.mp4` → demo clips
- Results table → fill in baseline numbers from the paper

## Structure

```
.
├── index.html
├── static/
│   ├── css/index.css
│   ├── images/   (drop figures here)
│   └── videos/   (drop demo clips here)
└── README.md
```

Template adapted from the [Nerfies](https://nerfies.github.io/) project page (CC BY-SA 4.0).
