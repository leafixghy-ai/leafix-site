# Leafix GHY — leafix1994.in

Static site, no build step. Rebuilt 2026-09-15 to match the locked master blueprint:
capacity 2 guests (no kitty parties, no hourly stays), 8-page architecture, WHY/HOW/WHAT
funnel structure on every page.

## ⚠️ Photos are honest placeholders — do not replace with anyone else's photos
Every image spot on this site is currently a dashed "Coming soon" placeholder.
**Do not put real estate/lifestyle stock photos of someone else's actual home in here** —
earlier drafts of this site briefly did this (cropped Instagram photos of a real person's
apartment) and it was removed because it misrepresents the actual property to guests and
uses someone else's copyrighted photos without permission. Replace placeholders only with:
- Real photos of the actual Leafix property once renovation is done, or
- Generic, non-identifiable stock photos (e.g. Pexels/Unsplash) if a temporary demo is needed

## Locked facts this site must never contradict
- **Capacity: 2 guests overnight, up to 5 for daytime kitty-party gatherings.** (Reversed 2026-09-15 — the master blueprint's "dropped permanently" no longer applies; kitty parties are back in.) Quiet gatherings only — no loud parties, ever.
- **Nightly stays for overnight guests; kitty parties are daytime-only.** No hourly/day-use bookings for overnight stays.
- **Audience: couples, solo travelers, content creators/workationers, and kitty-party groups.**
- **Brand name: "Leafix GHY"** (not "Leafix Kalapahar" — renamed 2026-09-02).
- **Kalapahar is the factual address, not the SEO hook** — search volume research showed "Kalapahar" itself has low direct search demand. The real hook is quiet-residential + railway-station proximity.

## How to publish this on GitHub Pages (today)

1. Create a new GitHub repo, e.g. `leafix-site`.
2. Upload every file in this folder to the repo root (keep `assets/style.css` inside `assets/`, and `CNAME` at the root).
3. Repo → **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root)**. Save.
4. Point the domain at GitHub Pages — at your domain registrar, set:
   - Four **A records** for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - A **CNAME record** for `www` pointing to `<your-github-username>.github.io`
5. Back in Settings → Pages, confirm the custom domain shows `leafix1994.in`, then enable **Enforce HTTPS** once available.
6. DNS can take minutes to ~24 hours to propagate.

## After it's live
1. Google Search Console → add property → verify → URL Inspection → Request Indexing on the homepage.
2. Google Business Profile → set up if not already done.
3. Set up the real Formspree endpoint (currently `YOUR_FORM_ID` placeholder in two places in `index.html`) at formspree.io — free tier, 50 submissions/month.

## Still to build (per the LOCKED 10-page architecture — confirmed final 2026-09-15)
- `/couples.html` — Phase 1, highest priority (core commercial page)
- `/safety-faq.html` — Phase 1 (solves the Reddit trust-gap directly)
- `/creators-workation.html` — Phase 2
- `/uzan-bazar-vs-kalapahar.html` — Phase 2 (competitive reframe, own page — not merged into a guide)
- `/kalapahar-guide.html` — Phase 3
- `/the-leafix-world.html` — Phase 3 (brand lore/authority)
- `/guwahati-itinerary.html` — Phase 4
- `/romantic-spots-cafes.html` — Phase 4
- `/medical-stay.html` — Phase 4 (hospital-proximity — verify drive times before publishing)

**Before publishing any page with a specific distance/drive-time claim**
(medical-stay, kalapahar-guide, uzan-bazar-vs-kalapahar): verify against real Google Maps
peak-hour data. Getting a distance wrong is worse than not having the claim.
