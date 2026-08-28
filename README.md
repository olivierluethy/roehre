# 📺 RÖHRE · VT-88

Eine Webseite, die sich wie ein **echter Röhrenfernseher** anfühlt — kein klassisches Website-Layout, sondern ein CRT-TV in einem dunklen Zimmer.

Öffne einfach `index.html` im Browser und **drücke eine beliebige Taste**, um einzuschalten.

## Features

- **CRT-Feeling:** Einschalt-Animation, Scanlines, Schattenmaske, rollender Helligkeitsbalken, Flimmern, Glasspiegelung, Röhren-Wölbung und Vignette.
- **Echter Sound (Web Audio API):** Bildrauschen beim Umschalten, 1-kHz-Testton, generierte Musik, Knack- und Blip-Geräusche, Netzbrummen.
- **Umgebungslicht:** Der Fernseher wirft farbiges Licht an die Wand, passend zum aktuellen Sender.
- **Klickbare Fernbedienung** und drehbare Gehäuse-Knöpfe.
- **Programmführer (EPG)** und On-Screen-Display wie bei einem echten TV.

## Steuerung

| Taste | Funktion |
|-------|----------|
| beliebige Taste | Einschalten |
| `↑` / `↓` | Sender wechseln |
| `←` / `→` | Lautstärke |
| `0`–`9` | Sendernummer eintippen |
| `M` | Stumm |
| `G` | Programmführer |
| `P` | Aus |
| `F` | Vollbild |

Eine unbekannte Sendernummer (z. B. `42`) zeigt **„KEIN SIGNAL"** mit Schneegestöber.

## Sender

1. **NEUS 24** — Nachrichten mit Globus, Sprecher, Lower-Third & Laufband
2. **WETTER+** — Landkarte, Städte-Icons, 5-Tage-Vorhersage
3. **TESTBILD** — SMPTE-Farbbalken + Testton
4. **ARCADE** — Pong (KI gegen KI)
5. **MTV · MUSIK** — Regenbogen-Equalizer zur Musik
6. **TERRA** — Naturdoku mit Bergen, See und Vögeln
7. **TOON!** — Zeichentrick mit hüpfendem Charakter
8. **KOSMOS** — Sternenwarp mit Fakten

## Technik

Eine einzige, eigenständige `index.html` — reines HTML, CSS und Canvas/Web-Audio, ohne Build-Schritt und ohne externe Abhängigkeiten (außer Google Fonts).
