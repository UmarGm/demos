# Website concepts: Cafe · Barbershop · SaaS

Static sites, no build step. Open `index.html` or deploy to GitHub Pages (Settings → Pages → Branch: main / root).

- `cafe/` — menu filter, table reservation
- `barbershop/` — online booking with slots and .ics calendar export
- `saas/` — interactive kanban demo, pricing toggle, FAQ, waitlist

Forms save to the browser's localStorage as a demo. To receive real submissions, connect the form handlers to Formspree, Google Forms or your own backend.
