# Let's Get It Together — Podcast Website

A clean, responsive Next.js 14 (App Router) site for showcasing podcast **video + audio** with search and tag filters.

## Quick Start

1. **Install**:
   ```bash
   npm install
   npm run dev
   ```
2. **Edit episodes** in `lib/episodes.ts` (swap `youtubeId` / `audioSrc` with your real links).
3. **Replace platform links** in `app/page.tsx` (Spotify, Apple, RSS, YouTube).
4. **Deploy on Vercel** (free): connect your GitHub repo and ship.

## RSS (optional, later)
You can fetch episodes from your podcast RSS and map to the `Episode` type, then render here.

## Contact form
The `/api/contact` endpoint is stubbed. Connect it to an email provider (e.g., Resend, SendGrid) or a Slack webhook.

## Tech
- Next.js 14 (App Router)
- Tailwind CSS
- Minimal UI components (Button, Card, Input, Badge)
- framer-motion, lucide-react

## License
MIT
