## Emirhan Çoban

Software engineer who likes building mobile and full-stack products from design to something people can actually use.
Currently looking for an **internship** · Türkçe / English

[emirhancoban.com](https://www.emirhancoban.com)

<br>

### Open source projects

- **[atls.](https://github.com/emirhan-coban/atls)**: a passport-themed travel app, mark the countries you've visited on a 3D globe. *React Native, Expo, Skia, Supabase*
- **[NEXUS](https://github.com/emirhan-coban/trading-terminal)**: a paper-trading terminal for crypto and stocks, no real orders. *Python, FastAPI, TypeScript*
- **[Pet Adoption](https://github.com/emirhan-coban/pet-adoption)**: adoption platform with web and mobile apps. *Next.js, React Native, Supabase*
- **[Fonova](https://github.com/emirhan-coban/fonova)**: a startup hub web platform ([demo](https://startup-hub-ten.vercel.app)). *Next.js, Prisma, PostgreSQL*
- **[Hand-controlled puzzle](https://github.com/emirhan-coban/hand-controlled-puzzle-game)**: a camera game you play with hand gestures. *Python, MediaPipe*
- **[Zihindar](https://github.com/emirhan-coban/wavelength-turkce)**: a Turkish offline party game ([play](https://zihindar.vercel.app)). *Flutter*

<br>

### Private projects

The code for these is not public, happy to walk through any of them.

**Multi-tenant barbershop booking SaaS** *(Java, Spring Boot, PostgreSQL, Redis, React/TypeScript, Three.js, Docker)*
A multi-tenant reservation platform for barbershops, built in phases with written technical notes and an OpenAPI contract for each. Customers pick a chair in a 3D shop view, new customers go through owner approval, and trusted customers get auto-confirmed appointments after a verified first visit. Includes idempotent approve/reject flows, Redis rate limiting, audit/outbox events, cancel and reschedule with version checks, in-app notifications and `.ics` export, plus versioned 3D shop scenes with draft, publish and rollback. Separate dev, CI, staging and production Docker Compose setups.

**Wandered** *(React Native, Expo, SQLite, Zustand)*
Scans the photo gallery for GPS-tagged photos, works out the country offline with point-in-polygon lookup on Natural Earth data (no reverse-geocoding API), and builds a personal travel map, stats and shareable "Wrapped"-style cards. Photos are scanned in batches of 500 with `expo-media-library`.

**Mühür** *(React Native, Expo, TypeScript, Reanimated)*
A Turkish swipe-based life-decision game in the style of Reigns. Yes/No choices move health, pride and money, with day-by-day ledgers, seasonal and random events, job offers, card chains, difficulty scaling and mini-games. Shipped through EAS builds with ads and tracking-transparency support.

**New-business lead pipeline** *(Python, Celery, Alembic, Playwright, Docker, Expo)*
A pipeline for a POS software company that finds newly opened food and retail businesses from free, public sources, enriches contact details and delivers scored leads. Each source is a watermark-based collector behind a shared interface, with rate limiting and retries, raw data kept immutable and reprocessed on fixes, and Turkish-aware text normalization. Includes a small mobile client. Built to respect robots.txt and never bypass logins or CAPTCHAs.

**Portfolio and app showcase sites** *(Next.js, React/Vite, plain HTML/CSS/JS)*
Personal portfolio and app showcase sites with a bilingual Next.js version, light and dark themes, SEO metadata (Open Graph, JSON-LD, sitemap) and no-framework performance-focused pages.

**Smaller work**
Flutter mini-games and a Firebase-backed Flutter app, a photo-sharing web page, and data structures and algorithms practice in C#.

<br>

### Stack

TypeScript · React Native · Expo · Next.js · Flutter · Python · Java · Supabase · PostgreSQL · Docker · Figma
