# ReSystem prototypes

This is a static site with no build step. Vercel serves the repository root.

| Path | Product | Source |
|---|---|---|
| `/` | Landing page | — |
| `/reai/` | REAI | Claude artifact `5GnRCQgosiSzjic1wS3XkK` (v23, File 17 UI) |
| `/reconcierge/iphone/` | reConcierge iPhone Prototype 003 r3 | Claude artifact `6zDk27E9W1CvTJuQmib7rB` (v2) |
| `/reconcierge/desktop/` | reConcierge Desktop Prototype 001 r3 | Claude artifact `P3KXYN39d8Yh8WdXoHXycy` (v2) |
| `/4edu/` | 4EDU Academy (ForEDU) | Claude artifact `GyCXC6QreVtMERLm2aphWM` (version 1791410491-7b96) |

## Rules

- **This repository is public.** It must never contain API keys, session secrets, passwords or personal data. Any server key goes only into Vercel Environment Variables.
- These pages are **prototypes with sample data**. They are not production releases, and no independent gate has certified them.
- REAI's helper answers call `/api/ai`. That backend is not deployed here.
- The three products stay separate. Each product has its own folder and its own evidence trail.

## History

This repository replaces `desert-gabby/demo`, which is retired. On 2026-10-09 G decided to use the new accounts: GitHub `gabbyworkspace` and Vercel `reworkspace-3866`. The old demo apps (Aurora, Pulse Counter, AI Concierge chat, Haven, SkyHop/ReFlight) were not carried over.
