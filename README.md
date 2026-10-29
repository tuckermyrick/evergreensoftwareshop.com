# evergreensoftwareshop.com

One static page, served by GitHub Pages from the `main` branch root.

- `index.html` + `assets/` — Vite production build from Dane (Bowbot), merged 2026-10-29 with a contact block.
- `CNAME` — custom domain. Do not delete it or Pages drops the domain.
- Contact email hello@ needs a Cloudflare Email Routing rule.

## DNS (at the registrar)

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | tuckermyrick.github.io |

After DNS propagates, turn on "Enforce HTTPS" in the repo's Pages settings.
