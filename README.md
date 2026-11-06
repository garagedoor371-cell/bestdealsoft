# BestDealSoft — static website starter

A responsive, server-rendered static HTML site for **BestDealSoft**, an independent editorial guide to software offers on AppSumo. No framework, build step, external font, stock imagery, or JavaScript dependency is required. Pages are readable and crawlable as plain HTML.

## Preview locally

From the repository root:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080` in a browser.

## Publish on Cloudflare Pages

1. Create a new GitHub repository and upload the contents of this project. (This chat cannot push to GitHub directly; do not put an access token in chat.)
2. In Cloudflare, create a **Pages** project and connect the repository.
3. Use no framework / static HTML. Leave the build command empty and set the build output directory to `/` (repository root).
4. Deploy, then add your purchased domain in the Pages project's custom-domain settings and follow Cloudflare's DNS instructions.
5. After the domain is live, verify `/robots.txt`, `/sitemap.xml`, and each page. Add the sitemap in Google Search Console.

The site is plain static HTML served from the repository root — there is no `public/` folder and no build step.

## Before launch — important owner tasks

- Confirm that `bestdealsoft.com` is available and that you can use the name. This project assumes the canonical hostname `https://bestdealsoft.com/`; update canonical tags, Open Graph URLs, JSON-LD, `robots.txt`, `sitemap.xml`, and any redirect rules if your final domain differs.
- Set up `hello@bestdealsoft.com` or replace it everywhere with a working email address you control.
- Review and adapt the privacy notice to the actual hosting, analytics, newsletter, cookies, and affiliate tools you use. The current page is a starter notice, not legal advice.
- Check the affiliate program's current disclosure and trademark requirements before adding affiliate links. Add `rel="sponsored"` to paid/affiliate links and disclose the relationship clearly near the link.
- Publish genuine, original reviews before adding product ratings, claims, product schema, or review cards. The empty `/reviews/` archive is intentionally `noindex` and is not in the sitemap until it has substantive content.
- The site currently has no product reviews, newsletter form, analytics script, or working contact backend. The contact page uses email.

## Included pages

- `/` — home
- `/about/` — about BestDealSoft
- `/reviews/` — empty review-library notice (`noindex,follow`; intentionally absent from the sitemap until real reviews exist)
- `/editorial-policy/` — how reviews are evaluated, plus FAQ (with FAQPage schema)
- `/affiliate-disclosure/` — affiliate transparency
- `/privacy/` — starter privacy notice (must be checked before launch)
- `/contact/` — email contact
- `/404.html`, `/robots.txt`, `/sitemap.xml`, `/llms.txt`, and Cloudflare Pages `_headers`

The logo is embedded as SVG in the page header and is also supplied as `logo.svg` and `favicon.svg`.
