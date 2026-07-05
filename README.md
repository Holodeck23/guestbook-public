# GuestBook — Interactive Demo

**Revenue intelligence for short-term rentals.** One dashboard. Every guest. Fully compliant.

GuestBook pulls the bookings from your PMS, turns them into real revenue numbers, and files
the guest paperwork through a modular compliance engine — Austria and Italy live today.

## Live demo

The demo in this repository is the actual product interface running on sample data —
three apartments, every screen clickable, no account needed.

**→ [guestbook-public.vercel.app](https://guestbook-public.vercel.app)**

Or run it locally: open `index.html` in any browser. No build step, no dependencies.

## What's in the demo

| Screen | What it shows |
|--------|---------------|
| **Analytics** | Revenue, occupancy, ADR, RevPAR — net of commission, cross-month attributed; channel mix; 26-week occupancy calendar |
| **Ops Cockpit** | Everything that needs a decision today: check-ins, checkouts, compliance deadlines |
| **Inbox** | All guest conversations, every channel, one place |
| **Messages** | AI-drafted guest replies — approve, edit, or let confidence-based auto-send handle them |
| **Compliance** | The modular engine: guest registration, local tax, statistics — 🇦🇹 + 🇮🇹 live, more markets plug in |
| **Reservations** | PMS-synced bookings, each carrying its own compliance status |
| **Best Clients** | Most valuable repeat guests, with one-click "find similar clients" |
| **Marketing Hub** | Lead list, email campaigns with open/click tracking, and the lead scraper |
| **Pricing** | Price calendar with pace-based suggestions |
| **Integrations** | PMS, pricing, email, AI providers, messaging channels — each testable |
| **Settings** | Properties, auto-send thresholds, guest languages, digital check-in |

An **EN / DE** toggle sits in the top bar. The ✦ button opens the AI Command Centre.

## The compliance engine

Compliance is modular by design. Each market plugs its own rules into the same workflow:

- 🇦🇹 **Austria** — live: Meldezettel, Ortstaxe, Statistik Austria, digital check-in
- 🇮🇹 **Italy** — live: Alloggiati Web, tassa di soggiorno, ISTAT
- 🇩🇪 **Germany** — coming: Meldeschein, Kurtaxe, statistics
- 🇨🇭 **Switzerland** — coming: registration, Kurtaxe / taxe de séjour

## Enquire

GuestBook is in private preview with a small number of hosts.
**Contact: [holodeck23@gmail.com](mailto:holodeck23@gmail.com?subject=GuestBook%20enquiry)**

## Notes

- Everything in the demo is **sample data** — nothing is connected to live systems.
- The demo is a single self-contained HTML file. Fonts load from Google Fonts and fall back
  to system fonts offline.
- See [docs/DEMO-GUIDE.md](docs/DEMO-GUIDE.md) for a guided tour.

## License

© 2026 GuestBook. All rights reserved. This repository is published for demonstration
purposes only — no license is granted to copy, modify, or redistribute the code or design.
