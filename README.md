# PushOwl Sales Pulse

Public, aggregate-only dashboard of sales meeting bookings (Calendly), attendance
and outcomes (Read AI). **Contains no lead-level PII** — no emails, names, company
identifiers, meeting summaries, or CRM deal stages. Lead-level detail lives in the
source platforms and a separate access-controlled view.

## Hosting
Single static file: `index.html`. Serve it with GitHub Pages (Settings → Pages →
Deploy from branch → `main` → `/root`).

## Data
Currently a snapshot for Aug 20–27, 2026. Refresh is manual for now (replace
`index.html`); automated daily refresh via GitHub Actions is planned for v2.

## Note on links
The "Meeting report" links point to Read AI and open only for users with a Read AI
login and access to that meeting.
