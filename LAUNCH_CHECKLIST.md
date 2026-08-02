# DwellingMind Launch Checklist

## Domain and hosting
- Connect `dwellingmind.app` in Porkbun DNS to the selected web host.
- Force HTTPS and redirect `www` to the preferred canonical domain.
- Confirm `/app/`, legal pages, media kit, sitemap, and robots.txt all load.

## Required integrations
- Replace the local early-access form with a production endpoint.
- Create `hello@`, `press@`, `privacy@`, and `legal@dwellingmind.app` forwarding addresses.
- Add privacy-respecting analytics and conversion events.
- Add an error-monitoring service after a real application backend exists.

## Product backend recommended for the MVP
- Authentication: Supabase Auth or Clerk.
- Database: PostgreSQL through Supabase.
- File storage: Supabase Storage or Cloudflare R2.
- OCR/document extraction: provider abstraction with human confirmation.
- AI: retrieval over user-owned records with citations to record IDs/documents.
- Email: Resend or Postmark.
- Payments: Stripe.

## Do not claim before implemented
- End-to-end encryption.
- Automatic warranty validation.
- Accurate home valuations.
- Professional inspection or safety advice.
- Production-grade privacy from the static demo.
