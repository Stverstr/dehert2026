# 🦌 Grote Sluitingsprijs Café De Hert — MMXXVI

De officiële website van de Grote Sluitingsprijs van Café De Hert, georganiseerd voor
De Baroudeurs & De Baroudellen. Woensdag 30 september 2026. Twee bruggen, een vaart, één café.

> De jury leest alles. Ook deze README.

## Pagina's

| Pagina | Wat |
|---|---|
| `index.html` | De teaser — Communiqué №1, met poll |
| `inschrijven.html` | Communiqué №2 — de datumonthulling en het inschrijfformulier |
| `scorebord.html` | Het voorlopig klassement en het reglement (voor zover onthuld) |
| `app.html` | De koerscentrale voor de wedstrijddag (teams, jury, groot scherm) |
| `uitslag.html` | Het dossier — enkel voor de opperjury |

## Techniek

Statische pagina's (GitHub Pages), data via [Supabase](https://supabase.com)
(PostgREST + RPC's). Er is geen build-stap: wat je hier ziet, is wat er draait.

Alle geheimen — verborgen regels, puntenformules, jury-oordelen, toegangscodes —
leven **server-side** achter row-level security en security-definer-functies.
In deze repo zoeken heeft dus geen zin. De jury heeft daar begrip voor,
maar noteert het wel.

## Voor de renners

- Inschrijven doe je via de inschrijfpagina. Vroeg inschrijven loont (regel №50).
- Klagen kan via het scorebord: klik je eigen naam aan (regel №60).
  Wie klaagt, klaagt in het openbaar.
- Vragen over de puntentelling worden genoteerd. Niet beantwoord.

---
🤖 Gebouwd met [Claude Code](https://claude.com/claude-code)
