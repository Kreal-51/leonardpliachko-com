# leonardpliachko.com

Static personal portfolio of Leonard Pliachko (Senior Product Manager).
No build step. Everything served lives in `public/`.

- Hosting: Cloudflare Workers, assets-only Worker defined in `wrangler.jsonc` (`assets.directory: ./public`).
- Domain: leonardpliachko.com (apex) plus www, www redirects to apex.
- `public/index.html` is the page. `src/index.template.html` is the source it was generated from; edit `public/index.html` directly for small changes.
- CV files: `public/cv/Leonard-Pliachko-CV.pdf` (no photo, default link on the site) and `public/cv/Leonard-Pliachko-CV-photo.pdf`.
- Writing rule: never use the long dash character in any copy. Use a short hyphen or a new sentence.
