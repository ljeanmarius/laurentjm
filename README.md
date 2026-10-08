# laurentjm.com

Personal site. Plain HTML and CSS in `public/`, no build step and no dependencies.

## Edit

Everything is in `public/index.html`. Search for `TODO` to find the parts that still need your content.

## Preview

```bash
python3 -m http.server 8000 --directory public
```

## Deploy

Netlify publishes `public/` on every push to `master` (see `netlify.toml`).
