# false_website

Personal CV site for Nick "False" Wiseman. Plain static HTML and CSS in
`public/`, hosted on Cloudflare Pages.

## Deploy

```sh
npx wrangler pages deploy public --project-name false-wiseman
```

Needs `CLOUDFLARE_API_TOKEN` (Pages Edit) and `CLOUDFLARE_ACCOUNT_ID` in the
environment, or a `wrangler login` session.
