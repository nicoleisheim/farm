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
| Zahlentasten / Mausrad | Gegenstand wählen |
| I / Tab | Rucksack öffnen |
| Klick auf Nachbarfeld | Dort handeln |
| Esc | Dialog schließen |

### Auf dem Handy

- **Joystick** (links unten) – laufen, stufenlos
- **A-Knopf** (rechts unten) – Werkzeug benutzen, interagieren
- Gegenstand in der Leiste antippen – auswählen
- Feld direkt neben der Figur antippen – dort handeln
- **Rucksack** (neben der Werkzeugleiste) – Inventar öffnen

Im Hochformat liegen Steuerung und Werkzeugleiste unter dem Spielfeld, und die Kamera folgt der Figur. Im Querformat sitzen Joystick und A-Knopf links und rechts neben dem Spielfeld.

## Spielablauf

1. Gras mit der **Hacke** auflockern
2. **Samen** säen (Rübe, Kohl, Kürbis)
3. Täglich mit der **Gießkanne** gießen – am Teich auffüllen
4. Reife Pflanzen mit der **Sichel** ernten (erntet auch die beiden Nachbarfelder) und in die **Versandkiste** legen – bezahlt wird über Nacht
5. Im **Dorfladen** neue Samen, Salat (Energie) und eine größere Gießkanne kaufen
6. Im **Rucksack** alle Gegenstände ansehen, Werkzeuge in die Hand nehmen oder Ernte essen
7. Vor 2 Uhr nachts durch die Haustür **schlafen gehen** – dabei wird gespeichert

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
- Schrift: [Fredoka](https://fonts.google.com/specimen/Fredoka) über Google Fonts
