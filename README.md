# Rowenna Draw

Portfolio site for Rowenna Draw. Static files, no build step.

- Site files live in `public/`.
- Every push to `main` deploys automatically through Cloudflare.
- Cloudflare Workers reads `wrangler.jsonc`; on Cloudflare Pages use build output directory `public` and leave the build command empty.
