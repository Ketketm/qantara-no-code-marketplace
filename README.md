# Qantara — No-Code Marketplace Prototype (Softr + Airtable)

**Qantara** is an interactive marketplace prototype designed to help women in Morocco monetize skills and services (remote or on-site) by making their offers discoverable and easy to contact in one place.

> Status: **Prototype / concept validation phase** (not an operational marketplace).
> Live demo: https://qantara.softr.app/

---

## Why this project
In Morocco, many women have valuable skills (crafts, cooking, tutoring, digital services) but face barriers to formal employment and to reaching paying customers.  
Qantara explores a lightweight model: **listings + discovery + direct connection**, built quickly with a no-code stack.

---

## What’s in the prototype (current functionality)
- Landing page with clear dual CTA: **browse services** or **propose talents**
- **Services catalog** with search + filters (category / type)
- **Talent directory** (profiles by category, location, and availability mode: online / traveling / at-home)
- **Profile drawer** showing a provider’s offers and contact channels (WhatsApp / phone / email)
- “Our project” page for **impact framing** and storytelling
- Register / Connect entry points for authentication and future gated flows

---

## My role
I owned the project end-to-end:
- Problem framing and marketplace concept design
- Information architecture and copywriting
- No-code build (Softr front-end + Airtable data model)
- Early stakeholder discussions in Morocco (including local cooperatives) and exploration of a potential handover model

---

## Tech stack
- **Softr** — pages, UI components, listing views, authentication entry points
- **Airtable** — database schema for talents, offers/services, categories, and profile fields

---

## Architecture (high level)
Qantara follows a simple no-code architecture:
1. **Airtable** stores structured records (talents ↔ offers/services ↔ categories).
2. **Softr** renders searchable lists and detail views from Airtable tables.
3. Users browse services or talent profiles and connect directly (contact-first flow).

More details:  
- `docs/architecture.md`  
- `docs/data-model.md`

---

## Privacy & compliance (public repo)
This repository contains **no personal user data**.
- Screenshots are **redacted** (no real phone numbers/emails).
- Airtable base exports, tokens, admin links, and any sensitive configuration are **not** included.

See `docs/privacy-compliance.md`.

---

## Limitations (honest)
- Prototype only: no verification, moderation, payments, or real operational rollout
- Free-plan constraints (no-code platform limits, scalability, governance)
- Demo dataset for showcasing flows (not real user acquisition)

---

## What I’d build next
- Trust & safety: verification + moderation workflow
- Structured request/booking flow (and optional payment)
- Provider onboarding optimized for mobile + low digital literacy
- Pilot governance with 1–2 cooperatives (roles, SLAs, economics)
- Analytics: funnel tracking (browse → contact → conversion) to iterate based on evidence

---

## Repository contents
- `docs/` — short case study, scope, architecture, data model, privacy notes
- `assets/` — redacted screenshots, diagrams, optional field photos (faces blurred)

---

## Credits
Built during the **Entrepreneurship in Africa** program as a summer project in Morocco.
