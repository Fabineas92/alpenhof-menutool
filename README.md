# Alpenhof – Menükarten-Tool

Internes Tool zur Erstellung der täglichen Menükarten im Restaurant Alpenhof (Tradition Julen).

**Live:** https://fabineas92.github.io/

## Zugang

Passcode: `3920`

## Funktionen

- Deutsche Eingabe, automatische Übersetzung nach **Französisch** (kursiv) und **Englisch** (fett)
- Strikte Reihenfolge DE → FR → EN, technisch gegen Vertauschen abgesichert
- Format fix: **297 × 297 mm**
- Schriftart wählbar: **Avenir** oder **Semplicita Pro Bold** (mit Fallback-Hinweis)
- Rechtschreibprüfung DE (LanguageTool API)
- Übersetzung (MyMemory API, kostenlos)
- Overflow-Warnung, Layout-Validierung
- Export als **PDF** oder **Excel**

## Lokal starten

Einfach `index.html` im Browser öffnen – keine Installation nötig.
Für Export-Funktionen wird eine Internetverbindung benötigt (CDN).

## Struktur

- `index.html` – komplette App (HTML/CSS/JS)
- `assets/logo.svg` – Tradition-Julen-Logo
- Layout-Konstanten zentral im CSS (`:root` Variablen)

## Hinweis

Der Passcode ist ein client-seitiges Zugangsgate, kein kryptografischer Schutz.
Ausreichend für interne Restaurantnutzung.
