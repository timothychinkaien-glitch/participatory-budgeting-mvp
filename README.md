# Common Ground — Participatory Budgeting MVP

A self-contained front-end event demo built from the authoritative **MVP Event Flow & System Design v0.2** in the supplied archive.

## Run it

Open `index.html` in a modern browser, or serve this folder locally:

```powershell
cd "C:\Users\timot\Documents\Codex\2026-10-11\ple\outputs\participatory-budgeting-mvp"
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Demo flows

- Audience card: `104826` (four votes, active)
- Spare card to activate at check-in: `881072`
- Donor: `DM-4829` (twelve votes)
- Use **Operations** to open voting, gift audience votes, close voting, add any required safety votes, finalise, and publish.

The demo persists browser state in local storage; **Reset demo data** restores the original scenario.

## Scope

This is a working client-side prototype, appropriate for validating the event workflow and visual design. A production deployment still needs the supplied TypeScript/PostgreSQL backend to provide authentication, private donor links, audited server-side ledger entries, atomic vote closing, real email delivery, imports, exports, and secure sessions.

