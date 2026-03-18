# PS Strategic Advisors — Website Relaunch

## Projektinfo
- **Kunde:** PS Strategic Advisors UG
- **Agentur:** 7marketplace
- **Gründer:** Alexander Schuh (Geschäftsführer) + Sven Petzold (Gesellschafter)
- **Domain (Preview):** strategicadvisors.7marketplace.de
- **Domain (Final):** ps-strategicadvisors.com
- **Sprache:** Deutsch
- **Kontakt:** info@ps-strategicadvisors.com
- **Telefon:** 0123 - 456 789 / 0800 - 123 456 78 (gebührenfrei)

## Stack
- Static HTML/CSS/JS (kein Framework nötig)
- Cloudflare Pages Deployment
- Mobile-first, responsive
- SEO-optimiert (Meta-Title, Meta-Description, Open Graph, Schema.org)

## Design
- **Primärfarbe:** Türkis aus Logo (ca. #0097A7 oder ähnlich — extrahieren aus Screenshot)
- **Sekundärfarbe:** Dunkel (Navy/Anthrazit #1A2332)
- **Akzent:** Gold/Amber für CTAs (#D4A843)
- **Font:** Montserrat (wie aktuell) oder Inter
- **Stil:** Premium Unternehmensberatung, clean, viel Weißraum, professionelle Bildsprache
- **Keine Stock-Fotos-Optik** — eher abstrakte Grafiken, geometrische Elemente
- **Dark Header/Footer, helle Content-Bereiche**

## Seitenstruktur

### 1. Startseite (index.html)
- Hero: Headline "Purchase to Performance" + Subline + CTA
- USPs: max. Prozesseffizienz, max. Transparenz, 100% digital
- Über uns Teaser (20+ Jahre Erfahrung)
- Leistungspakete (Advisory & Strategy, Design & Implementation, All-in-1 Premium)
- Werte (Integrität, Ehrlichkeit, Partnerschaft)
- Team Teaser (Alexander + Sven)
- Kontakt Section
- SEO: Meta-Title, Description, OG Tags, Schema.org Organization

### 2. Leistungen Übersicht (leistungen/index.html)
- Grid/Cards aller 14 Leistungen mit kurzer Beschreibung + Link zur Unterseite

### 3. 14 Leistungs-Unterseiten (leistungen/{slug}.html)
Jede Seite: ~500-700 Wörter, SEO-optimiert, eigener Meta-Title/Description

1. **Analyse & Strategie** — analyse-strategie.html
2. **Budgeting** — budgeting.html
3. **Controlling** — controlling.html
4. **Data Analytics** — data-analytics.html
5. **Design & Implementierung** — design-implementierung.html
6. **Digitalisierung** — digitalisierung.html
7. **Forecasting** — forecasting.html
8. **Interimsmanagement** — interimsmanagement.html
9. **Kostenoptimierung** — kostenoptimierung.html
10. **Prozessmanagement** — prozessmanagement.html
11. **Reporting** — reporting.html
12. **Training** — training.html
13. **Unternehmensberatung** — unternehmensberatung.html
14. **Working Capital Management** — working-capital-management.html

### 4. Über uns (ueber-uns.html)
- Geschichte (seit 2002/2006, BWL-Studium, gemeinsames Forschungsprojekt)
- Alexander Schuh — Unternehmerkarriere, mehrere Unternehmen
- Sven Petzold — 20+ Jahre Finanzprofi, leitende Funktionen
- Werte-Section

### 5. Kontakt (kontakt.html)
- Kontaktformular (Name, Email, Telefon, Nachricht, Datenschutz-Checkbox)
- Telefonnummern
- Email
- Calendly-Integration (30 Min kostenlos, 60 Min kostenpflichtig)

### 6. Impressum (impressum.html)
### 7. Datenschutz (datenschutz.html)
### 8. AGB (agb.html)

## SEO Requirements
Jede Seite braucht:
- `<title>` — max 60 Zeichen, Keyword + Brand
- `<meta name="description">` — max 155 Zeichen, Call-to-Action
- `<meta name="keywords">` — relevant
- Open Graph: og:title, og:description, og:image, og:url
- Twitter Card: summary_large_image
- Schema.org: Organization (Startseite), Service (Leistungsseiten)
- Canonical URL
- Hreflang (de)
- Sitemap.xml
- robots.txt

## Content-Vorgaben
- **Zielgruppe:** CFOs, Finance-Teams, Geschäftsführer von Konzernen, KMUs, Start-ups
- **Tonalität:** Professionell, kompetent, vertrauenswürdig, klar (kein "Beraternebel")
- **USP:** Purchase-to-Pay Digitalisierung, 20+ Jahre Erfahrung, DSGVO-konform, branchenunabhängig
- **CTAs:** "Erstgespräch buchen", "Jetzt beraten lassen", "Mehr erfahren"
- **Keine Typos!** (Original hatte: "Desgin", "Impementierung", "Leisutngspakte")

## Leistungspakete (von der aktuellen Seite)

### 1. Digital Start (Advisory & Strategy)
- Analyse bestehender P2P- und Kreditorenprozesse
- Individuelle Strategien für digitale Transformation
- Automatisierungs- und Einsparpotenziale identifizieren
- Zielbild + Digitalisierungs-Roadmap
- DSGVO-konform, revisionssicher, ergebnisorientiert

### 2. Automated Flow (Design & Implementation)
- Implementierung Tool "PS Solutions"
- Integration in bestehende ERP-Landschaft
- Aufbau der Accounts Payable Abteilung
- Schulungen
- SLA-Optionen

### 3. All-in-1 Premium
- Beratung + Umsetzung + Betrieb aus einer Hand
- Gesamte Purchase-to-Pay-Kette
- 100% digitale Prozesse
- Tool-Management + laufende Optimierung

## Performance
- Lighthouse Score: 90+ in allen Kategorien
- Lazy Loading für Bilder
- Minified CSS/JS
- Keine externen Dependencies außer Fonts
