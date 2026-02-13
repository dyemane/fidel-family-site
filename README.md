# fidel.family

Static website for the Fidel Family app. Hosted on GitHub Pages.

## Pages

- **/** — Landing page
- **/privacy** — Privacy policy (required for App Store / Play Store)
- **/support** — Support & FAQ
- **/press** — Press kit

## Development

Open `index.html` in a browser. No build step required.

## Deploy

Pushes to `main` auto-deploy via GitHub Pages. Custom domain configured via `CNAME`.

## DNS

Point `fidel.family` to GitHub Pages:
- A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- Or CNAME: `fidel.family` → `dyemane.github.io`
