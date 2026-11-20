# Cabral's Log

Personal blog of Paulo Cabral, built with [Marmite](https://marmite.blog).

## Write

```bash
marmite . --new "My Post Title" -t "postgresql,performance"
```

Posts live in `content/posts/` (they have a date), pages in `content/pages/` (no date).

## Preview

```bash
marmite . site --watch --serve
```

Then open http://localhost:8000.

## Deploy

Push to `main` on GitHub with Pages set to "GitHub Actions" (Settings → Pages).
Set `url:` in `marmite.yaml` to the final address.
