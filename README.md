# Site draft v2 — notes for the team

## v2 changes (22.7.2026, after client shared thehijrahguide.com as reference)

- Warmer look: photo hero, sand/cream backgrounds, rounded cards, Poppins headings, floating WhatsApp button.
- **Photos**: real photography from Wikimedia Commons, CC-licensed — attributions in `img/CREDITS.json`
  (hero: Ali Mansuri CC BY-SA 2.5; Madinah: Mondephile / King Eliot; Jeddah: Joseph Azrak). Keep the credits.
- **New `pricing.html`** — ALL PRICES ARE DRAFT PLACEHOLDERS invented to give the client something to react to
  ($49 consultation / $99 family plan / $199 university application / $1,499 full relocation etc.).
  Isa must set real numbers before launch.
- **New `events.html`** — the events (Hijrah 101, student route webinar, property webinar, monthly Q&A) are
  PROPOSED sessions with placeholder dates. The client must confirm they will actually run them before this
  page goes live, otherwise it's advertising events that don't exist.

Static HTML + one CSS file. No backend, no JS, no build step. Open `index.html` in a browser to view. Mobile-first; check it at phone width first, that's the primary view.

Deploys anywhere (GitHub Pages: push this folder and enable Pages). Before real deploy:

1. Replace `REPLACE-DOMAIN.example` in `sitemap.xml` and `robots.txt` with the real domain.
2. Add the client's logo + favicon when they send it (currently a text wordmark "Hijrah to Saudi" — placeholder name, decide branding with client).
3. Photos: pages are deliberately text-only for now. When adding, use real Haramain/city photography, no stock or AI images.

## Things awaiting client/expert confirmation (marked in copy where relevant)

- All prices/rules say "checked July 2026" — Isa's experts must verify before launch (his own requirement).
- Student-family sponsorship is described as unsettled on study.html because sources genuinely conflict.
- Marriage page describes the process generically — confirm actual process and fee with Isa.
- Community page links the main WhatsApp group from Isa's materials — confirm it's the right invite link and doesn't expire.
- Contact = Isa's WhatsApp/email from his public PDF. Confirm he wants these public on the site.
- The full list of expert questions is in `../research/*.md` (each file ends with an "open questions" section).

## Copy rules used (keep for future edits)

- Follows Wikipedia's "Signs of AI writing" avoid-list: no puffery vocab (vibrant/testament/delve/landscape), no "not just X but Y", no rule-of-three padding, no em dashes, no bold-spam, sentence-case headings, concrete numbers over vague claims.
- Tone: direct older-brother register, religious Arabic terms mixed naturally (deen, iqama, in shaa Allah), honest about costs and legal limits. Legal warnings (free visa, tasattur, overstay) stay in, phrased as sincere advice.
- Palette: deep blue `#16407c` + yellow `#f7c331`. Left-aligned, information-dense, tables for facts. Not a centered single-scroll landing page.
