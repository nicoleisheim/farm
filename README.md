# 🌻 Sonnenhof

Ein kleines, gemütliches Farm-Spiel im Pixel-Look – inspiriert von Stardew Valley. Läuft komplett im Browser, ohne Abhängigkeiten oder Build-Schritt: eine einzige `index.html`.

## Spielen

- Lokal: `index.html` im Browser öffnen.
- Online über **GitHub Pages**: Repository → *Settings* → *Pages* → *Branch: main / (root)* → speichern. Nach kurzer Zeit ist das Spiel unter `https://<dein-name>.github.io/<repo-name>/` erreichbar.

## Steuerung

| Taste | Aktion |
|---|---|
| WASD / Pfeiltasten | Laufen |
| Leertaste / E | Werkzeug benutzen, interagieren |
| 1–6 / Mausrad | Gegenstand wählen |
| Klick auf Nachbarfeld | Dort handeln |
| Esc | Dialog schließen |

Auf Touch-Geräten erscheinen Steuerkreuz und A-Knopf.

## Spielablauf

1. Gras mit der **Hacke** auflockern
2. **Samen** säen (Rübe, Kohl, Kürbis)
3. Täglich mit der **Gießkanne** gießen – am Teich auffüllen
4. Reife Pflanzen ernten und in die **Versandkiste** legen – bezahlt wird über Nacht
5. Im **Dorfladen** neue Samen, Salat (Energie) und eine größere Gießkanne kaufen
6. Vor 2 Uhr nachts durch die Haustür **schlafen gehen** – dabei wird gespeichert

| Pflanze | Samenpreis | Wachstum | Verkaufspreis |
|---|---|---|---|
| Rübe | 20g | 4 Tage | 35g |
| Kohl | 50g | 7 Tage | 120g |
| Kürbis | 100g | 10 Tage | 260g |

## Technik

- HTML5 Canvas (384×256 px, pixelgenau skaliert)
- Alle Grafiken prozedural im Code gezeichnet – keine Bilddateien
- Soundeffekte per Web Audio API
- Spielstand im `localStorage` des Browsers
- Schrift: [Pixelify Sans](https://fonts.google.com/specimen/Pixelify+Sans) über Google Fonts
