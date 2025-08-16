# Grand Polo Club & Resort — Selvara 3 (Full-Stack Next.js)

Production-ready starter for a Dubai real estate launch page. Built with **Next.js App Router + Tailwind** and **serverless API routes**.

## Features
- Landing page with hero, highlights, payment plan
- Listings grid (mock data in `lib/listings.ts` + `/api/listings`)
- Lead form posting to `/api/contact` (logs to Vercel Functions; replace with CRM/webhook)
- Tailwind & dark UI, mobile-friendly
- Deploys 1-click on **Vercel** (no config needed)

## Quick Start
```bash
# install
npm i

# dev
npm run dev

# build
npm run build && npm start
```

## Deploy to Vercel
- Connect this repo to Vercel → it auto-detects Next.js.
- Ensure `images.unsplash.com` is allowed in `next.config.mjs` (already done).
- Submit the form and check **Functions → Logs** for leads.

## Customize
- Replace mock listings in `lib/listings.ts` or hook to DB/CRM.
- Add dynamic pages under `app/[slug]/page.tsx`.
- Wire `/api/contact` to a webhook or email provider.
