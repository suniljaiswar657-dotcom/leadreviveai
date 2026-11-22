# LeadRevive AI

A mobile-first lead follow-up and revenue recovery dashboard for Indian small businesses.

## MVP features
- Lead capture and editing with customer, requirement, budget, location, source, notes and follow-up date
- Lead status pipeline: New Lead, Contacted, Qualified, Site Visit, Negotiation, Converted, Follow-up and Lost
- Follow-up queue for due, overdue and upcoming conversations
- Transparent heuristic priority score (status, follow-up timing and budget)
- Hindi + English message drafts with friendly, professional and short tones
- WhatsApp click-to-open links with prefilled messages; messages are never sent automatically
- CSV import and export
- Dashboard metrics and pipeline insights
- Responsive dark UI for Android phones and desktop

## Run locally
Open `index.html` in a modern browser, or deploy this repository to Vercel as a static site. No build command is required.

## Demo mode and limitations
This version stores leads in the current browser's `localStorage`. Data is not synced across devices, is not backed up automatically, and is not protected by user accounts. Export CSV regularly. Do not enter sensitive customer information until authenticated cloud storage and access controls are implemented.

Message drafting currently uses rule-based templates as an offline fallback. No external AI model, WhatsApp Business API, automatic messaging, or cloud database is connected in this MVP.

## Deploy on Vercel
Import `suniljaiswar657-dotcom/leadreviveai` in Vercel. Framework preset: Other. Build command: leave empty. Output directory: `.`. Deploy.
