# Silent Monkey — Monorepo
*Boutique Digital Consulting*

## Struktur

| Ordner | Domain | Status |
|---|---|---|
| /main | silentmonkey.io | ✅ Live |
| /audit | audit.silentmonkey.io | ✅ Live |
| /shared | shared CSS & Design Tokens | ✅ Live |
| /making-of | silentmonkey.io/making-of | 🔧 In Arbeit |
| /blog | blog.silentmonkey.io | 📋 Backlog |

## Stack

Vercel · HTML · CSS · Ghost CMS (blog.silentmonkey.io) · Google PageSpeed Insights API

## Domains

| Domain | Ziel |
|---|---|
| silentmonkey.io | Hauptseite (main/) |
| audit.silentmonkey.io | Audit Tool (audit/) |
| blog.silentmonkey.io | Ghost CMS |
| solution.silentmonkey.io | Squarespace (bis Nov 2026) |
| portal.silentmonkey.io | Proyex Client Portal |

## Design System

- Farben: `#f5f2ec` (light) · `#1a1814` (dark)
- Fonts: Cormorant Garamond · Space Mono
- Shared CSS: `shared/style.css`

## Deployment

Vercel · GitHub Auto-Deploy bei Push auf `main`  
DNS: IONOS → Vercel

## Sprint-Stand

- ✅ Sprint A — Hauptseite, Monorepo, DNS-Migration
- 🔧 Sprint B — Pre-Launch (Cookie Banner, DSGVO, SEO, Sprach-Switch)
- 📋 Sprint C — Shared CSS Monorepo-Sync
