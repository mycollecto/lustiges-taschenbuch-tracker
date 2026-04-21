# 🦆 Meine LTB-Sammlung

Lesetracker für alle 610 Bände der Lustigen Taschenbücher. Für Kinder (und Erwachsene) die abhaken wollen, welche Bände sie schon gelesen haben.

**Live:** https://meischer.github.io/ltb-tracker/

## Features
- Alle 610 Bände der Hauptreihe
- Cover-Bilder (nach einmaligem Download via GitHub Action)
- Fortschritt wird lokal im Browser gespeichert
- Funktioniert offline (PWA)
- Filter: Alle / Gelesen / Noch nicht gelesen
- Suche nach Nummer oder Titel
- Konfetti beim Abhaken 🎉

## Setup

1. Repo forken oder klonen
2. GitHub Pages aktivieren (Settings → Pages → Branch: main)
3. GitHub Action ausführen: Actions → "Cover-Bilder herunterladen" → Run workflow

## Cover-Bilder
Die Cover werden von [Duckipedia](https://de.duckipedia.org) geladen und lokal im `covers/` Ordner gespeichert. Einmalig via GitHub Action herunterladen.
