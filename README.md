# Schulportal 2026/2027

Zentrales Webportal für Mathematik- und Informatik-Unterrichtsinhalte (Gymnasium / Gesamtschule).

## Struktur

- `index.html` - Zentrales Dashboard mit Klassenübersicht
- `assets/` - Zentrales Styling (CSS), Skripte (JS) & Mediendateien
- `mathe/`
  - `9b/` - Unterrichtsinhalte Mathematik 9b (Lineare Gleichungssysteme etc.)
- `info/`
  - `5/` - Informatik Stufe 5 (5b, 5c, 5d, 5e)
  - `6/` - Informatik Stufe 6 (6a, 6b, 6c, 6d)
  - `diff-9/` - Informatik Differenzierung 9 (WPII)
  - `diff-10/` - Informatik Differenzierung 10 (WPII)
  - `ef/` - Informatik Einführungsphase (Oberstufe)
  - `q1/` - Informatik Qualifikationsphase 1 (Oberstufe)
  - `q2/` - Informatik Qualifikationsphase 2 (Oberstufe)

## Lokale Pflege & Synchronisation

Die Inhalte werden lokal in den jeweiligen Klassenordnern unter `.../web/` gepflegt und über das Skript `sync-web.ps1` automatisch hierhin synchronisiert.