# reSpace Blog Series Portal · May 2026

Internal handoff portal for the May 2026 reSpace 4-post blog series. Static site hosted on Vercel, mapped to `respace.heyrachael.co`.

## What is in this repo

- `index.html` — the handoff portal (Katrina + dev team entry point)
- `respace-blog-0[1-4]-*.html` — 4 production-ready blog posts
- `respace-email-0[1-4]-*.html` — 4 Gmail-safe email companions
- `respace-mansu-social-prompts-*.html` — 12 Mansu prompts (one click to copy each)
- `respace-blog-strategy-*.pdf` — 17-page branded strategy document
- `respace-content-factory-*.xlsx` — 7-tab production workbook
- `respace-blog-series-*.zip` — full bundle for offline handoff
- `social-posts/` — composition reference for Mansu (SVG layouts)
- `vercel.json` — security headers and caching rules

## Deploy to Vercel

This is a static site. Vercel auto-detects it.

```bash
# From the portal/ directory
vercel
# Follow prompts. Accept defaults. Project name suggestion: respace-content-portal
```

Or connect the GitHub repo to Vercel via the dashboard:
1. Vercel → New Project → Import this GitHub repo
2. Framework Preset: Other
3. Root Directory: `./` (or the portal folder if pushing the whole monorepo)
4. Build Command: leave empty
5. Output Directory: leave empty
6. Click Deploy

## Custom domain · respace.heyrachael.co

After first deploy:
1. Vercel project → Settings → Domains → Add `respace.heyrachael.co`
2. At the registrar for `heyrachael.co`, add a CNAME record:
   - Name: `respace`
   - Value: `cname.vercel-dns.com`
   - TTL: 3600
3. Vercel auto-provisions the SSL cert (a few minutes)

## Local preview

```bash
# Any static server works
npx serve .
# or
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Brand reference

- Brand bible: brand.respace.co
- Public site: respace.co
- Phone: (206) 222-6322
- Contact: office@reSpace.co

## Not for public distribution

This portal is internal review and handoff only. Do not link from public sites.
