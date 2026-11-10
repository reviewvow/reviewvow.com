# reviewvow.com

Source for the ReviewVow website, a static page deployed to Cloudflare.

## Layout

- `site/`: the published files (`index.html`, `.well-known/security.txt`)
- `wrangler.jsonc`: Cloudflare deploy config (kept outside `site/` so it is never published)

## Deploy

```
npx wrangler deploy
```

Run from the repo root. Requires `npx wrangler login` once.

## Security

See the organization's [security policy](https://github.com/reviewvow/.github/blob/main/SECURITY.md).
