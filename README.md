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
4. Reife Pflanzen mit der **Sichel** ernten (ein Feld pro Schwung)
5. Ernte am **Verkaufsstand** auslegen – von 8 bis 18 Uhr verkauft Mitarbeiterin Lotte zufällig an Leute aus dem Dorf. Ihren Stundenlohn (4–16 Taler) stellst du selbst ein – je mehr sie verdient, desto schneller verkauft sie. Bezahlt wird nur die Zeit, in der Ware ausliegt
6. Am **Auftragsbrett** warten Bestellungen mit Frist: Ware in die Lieferkiste packen, nachts wird abgeholt und mit Aufschlag bezahlt
7. Mit der **Axt** Bäume fällen (3 Schläge, 5–8 Holz) und Stümpfe entfernen (2 Holz) – höchstens 10 Holz pro Baum. Stümpfe wachsen nicht nach – dafür kann man **Setzlinge** (Laden oder Glück beim Fällen) auf freier Wiese pflanzen, die in 4 Tagen zu Bäumen werden
8. **Beerensträucher** pflanzen: ab dem 3. Tag und danach alle 2 Tage reife Beeren pflücken (einfach mit A).
9. Mit der **Schaufel** Pflanzen und Setzlinge ausgraben und Felder wieder zu Wiese machen
9. Im **Rucksack** (16 Plätze) liegen Ernte und Holz; Gegenstände lassen sich zwischen Rucksack und Werkzeugleiste (8 Plätze) verschieben
10. Der **Dorfladen** liegt in der **Innenstadt**, einem eigenen Ort: Folge dem Weg nach rechts aus der Farm. In der Stadt gibt es Häuser, einen Brunnen, Laternen und Leute aus dem Dorf, mit denen du plaudern kannst. Am linken Rand geht es zurück zur Farm. Dort gibt es Samen, Setzlinge, Beerensträucher, Salat, Ersatzwerkzeug und eine größere Gießkanne. Werkzeuge nutzen sich ab und gehen irgendwann kaputt
11. Vor 2 Uhr nachts durch die Haustür **schlafen gehen** – dabei wird gespeichert

| Ware | Samenpreis | Wachstum | Verkaufspreis (Taler) |
|---|---|---|---|
| Rübe | 20 Taler | 2 Tage | 35 Taler |
| Kohl | 45 Taler | 3 Tage | 90 Taler |
| Kürbis | 90 Taler | 5 Tage | 200 Taler |
| Holz | – | – | 8 Taler |

## Technik

- HTML5 Canvas (384×256 px, pixelgenau skaliert)
- Alle Grafiken prozedural im Code gezeichnet – keine Bilddateien
- Soundeffekte per Web Audio API
- Spielstand im `localStorage` des Browsers
- Schrift: [VT323](https://fonts.google.com/specimen/VT323) über Google Fonts
