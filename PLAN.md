# grandevu.io — Hemsida Plan

## Syfte
Säljande landningssida som konverterar besökare till demo-bokningar.

## Sidor
1. **Startsida** — Hero + value proposition + CTA
2. **Så fungerar det** — 4 steg (se site → testa → onboarda → lev)
3. **Funktioner** — alla 12 moduler med kort beskrivning
4. **Priser** — Starter / Pro / Enterprise + onboarding-modell
5. **Demo** — "Se din restaurang med Grandevu" → formulär
6. **Om oss** — Grandevu-storyn, vision, "Do what you love"
7. **Kontakt** — offert@grandevu.io

## Design
- Färger: mörkt (#1a1a2e), guld (#c4a35a), vit, ljusgrå
- Typografi: Georgia/Garamond (rubriker), Helvetica/Arial (brödtext)
- Logga: data/logo.svg (ljus) + data/logo_dark.svg (mörk)
- Responsiv — mobile first
- Snabb — statisk HTML/CSS/JS, inga tunga ramverk

## Hero-sektion
- Rubrik: "Do what you love."
- Underrubrik: "Vi automatiserar resten — bokningar, personal, löner, fakturor, redovisning, compliance, juridik."
- CTA: "Se hur det ser ut för din restaurang" → demo-formulär
- Bakgrund: mörk med guld-accenter

## Säljbudskap (i ordning)
1. **All data är er** — ingen tredje part äger era kunder
2. **Vi bygger er site först** — gratis, noll risk
3. **Vi kör det själva** — (referens finns men visas inte ännu)
4. **Besparing ~65 000 kr/mån** — konkreta siffror
5. **74 timmar tillbaka** — nästan 2 arbetsveckor/mån

## Demo-flöde
1. Besökare fyller i: restaurangnamn, kontaktperson, e-post
2. Vi bygger deras site i testmiljö (~1 vecka)
3. De får länk till sin egen fungerande prototyp
4. Nöjd → onboarding. Inte nöjd → kostar inget.

## Teknik
- Hosting: OSC (eyevinn-web-runner) eller statisk på grandevu.io via one.com
- SSL: automatiskt via hosting
- Analytics: Umami (self-hosted på OSC)
- AI-skydd: robots.txt noindex på demo-sidor
- Formulär: skickar till offert@grandevu.io

## INTE med ännu
- Vin & Vänner som referens (väntar på godkännande)
- Kundlogotyper / testimonials
- Blogg

## Filstruktur
```
hemsida/
  index.html        — Startsida
  funktioner.html   — Alla moduler
  priser.html       — Prissättning
  demo.html         — Demo-formulär
  om.html           — Om Grandevu
  kontakt.html      — Kontakt
  style.css         — Gemensam CSS
  script.js         — Minimal JS
  bilder/           — Logga, ikoner
```
