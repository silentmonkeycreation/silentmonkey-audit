# Silent Monkey — Monorepo
*Boutique Digital Consulting · Berlin & Beyond*

## Struktur

| Ordner | Domain | Status |
|---|---|---|
| /main | silentmonkey.io | ✅ Live |
| /audit | audit.silentmonkey.io | ✅ Live |
| /shared | Shared CSS & Design Tokens | ✅ Live |
| /making-of | silentmonkey.io/making-of | 🔧 In Arbeit |
| /imprint | silentmonkey.io/imprint | 🔧 Wartet auf NIF |
| /privacy | silentmonkey.io/privacy | 🔧 Wartet auf DSGVO-Text |
| /gtc | silentmonkey.io/gtc | 🔧 Wartet auf AGB-Text |
| /contact | silentmonkey.io/contact | 📋 Backlog |
| /cases | silentmonkey.io/cases | 📋 Backlog |
| /blog | blog.silentmonkey.io | 📋 Backlog |

## Stack

Vercel · HTML · CSS · Ghost CMS (blog.silentmonkey.io) · Google PageSpeed Insights API · Claude API

## Domains

| Domain | Ziel | Status |
|---|---|---|
| silentmonkey.io | Hauptseite (main/) | ✅ Live |
| audit.silentmonkey.io | Audit Tool (audit/) | ✅ Live |
| blog.silentmonkey.io | Ghost CMS | 📋 Backlog |
| solution.silentmonkey.io | Squarespace (bis Nov 2026) | ⏳ Auslaufend |
| portal.silentmonkey.io | Proyex Client Portal | ✅ Live |
| andreasrossmann.de | — | ⏳ Läuft ab Apr 2027 · kein Renewal |
| silentmonkey.solutions | — | ⏳ Läuft ab Mär 2027 · kein Renewal |

## Design System

- **Farben:** `#17140f` (dark bg) · `#d4a84b` (gold) · `#ede8df` (cream)
- **Fonts:** Bebas Neue · DM Mono · DM Sans
- **Shared CSS:** `shared/style.css`
- **Language Rule:** EN = canonical · DE/ES = optional overlay (ADR-005)

## Deployment

Vercel · GitHub Auto-Deploy bei Push auf `main`
DNS: IONOS → Vercel

## Routing

`vercel.json` — Rewrites + 301 Redirects:
- `/impresssum` → `/imprint` (301)
- `/dsgvo` → `/privacy` (301)
- `/agbde` → `/gtc` (301)
- `/terms` → `/gtc` (301)

## Sprint-Stand

- ✅ Sprint A — Hauptseite, Monorepo, DNS-Migration
- 🔧 Sprint B — Pre-Launch: Footer, Routen, ADRs, Favicon, shared/style.css, 301 Redirects
- 📋 Sprint C — Cookie Banner (Klaro), DSGVO-Text, JSON-LD, OG-Image
- 📋 Sprint D — Shared CSS Monorepo-Sync, Q3 Migration

## ADR-Übersicht

| ADR | Entscheidung | Status |
|---|---|---|
| ADR-001 | One Domain — silentmonkey.io | ✅ Closed |
| ADR-002 | Vercel over Ghost | ✅ Closed |
| ADR-003 | Two Pillars — Consulting + Creation | ✅ Closed |
| ADR-004 | Netlify → Vercel | ✅ Closed |
| ADR-005 | English is canonical | ✅ Closed · 2026-05-07 |

## Letzte Aktualisierung

2026-05-08 · Sprint B
