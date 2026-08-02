# DwellingMind.app

Complete static launch website and interactive product prototype.

## Run locally

Use any static server:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy

Upload the entire folder to the web root at your host, or deploy to Cloudflare Pages, Netlify, Vercel, GitHub Pages, or Hostinger. No build step is required.

## Porkbun DNS

Point the domain to your host using the DNS values supplied by that host. Enable SSL. The `.app` extension requires HTTPS in modern browsers.

## Forms

The early-access form stores entries in the browser for this demo. Replace `handleLead()` in `assets/site.js` with your Formspree, Basin, ConvertKit, Mailchimp, Supabase, or custom API endpoint before paid traffic.

## Product prototype

The dashboard at `/app/` uses localStorage. Users can add equipment, tasks, documents, and timeline records. Data remains in that browser unless exported.
