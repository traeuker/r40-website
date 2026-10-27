# r40.org

Static single-page site for R40. No build step: `index.html` is the whole site.

- `index.html` – the page
- `favicon.svg` – browser tab icon
- `.well-known/security.txt` – responsible-disclosure contact (renew `Expires` yearly)

Deploy: Cloudflare Pages, connected to this repo, build command empty, output directory `/`.
