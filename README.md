# Parker Architectural Hardware — website

The website for **Parker Architectural Hardware**: premium kitchen fittings, an interactive
Applications kitchen, the product collection and the Parker Promise.

## What is in this folder

| File / folder | What it is |
|---|---|
| `index.html` | The whole website (layout, text, animations and product data) |
| `assets/` | Logo, kitchen photos, product photos, browser icons and the link-preview image |
| `assets/products/` | Product photos in two sizes (`-520` for cards, `-1000` for the details view) |
| `netlify.toml` | Settings for Netlify (tells it to cache the images so the site loads fast) |

## Publishing on Netlify from this repository

1. Sign in at app.netlify.com.
2. Click **Add new site → Import an existing project → GitHub**, then pick this repository.
3. Leave **Build command** empty and set **Publish directory** to `.` (a single dot).
4. Click **Deploy**. From now on, every change saved to this repository goes live automatically.
