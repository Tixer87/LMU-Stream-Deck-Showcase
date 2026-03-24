# LMU Stream Deck Showcase – Quick Start

## Was das ist

Die Showcase Edition ist eine kompakte Vorschauversion des LMU Stream Deck Dashboards.

Schwerpunkte:
- Wiederholung / Replay
- Kamera-Wechsel
- Fahrzeugwechsel
- Freie Kamerasteuerung

Ziel ist ein sauberer und direkt nutzbarer Einstieg — ohne sofort das volle Profil aufzumachen.

---

## Voraussetzungen

Du brauchst:
- **Le Mans Ultimate**
- **Elgato Stream Deck**
- das importierte **Showcase-Profil**

Wichtig: In LMU immer in der Spalte **Tastatur** belegen — nicht in der Lenkrad- oder Controller-Spalte.

---

## Einrichtungswege

### Weg A — Express

Schnell, aber riskanter.

Das mitgelieferte Preset verwenden:

1. Aktuelle `keyboard.json` sichern (Backup)
2. Die Datei `keyboard_preset_showcase.json` in deinen LMU-Spieler-Ordner kopieren
3. In `keyboard.json` umbenennen

Das ist der schnellste Weg, überschreibt aber bestehende eigene Tastenbelegungen. Das Backup aus Schritt 1 ist deine Absicherung.

### Weg B — Manuell

Sicherer, aber langsamer.

Showcase-Profil in die Stream Deck Software importieren und die benötigten LMU-Funktionen anschließend manuell im Spiel belegen.

Gibt volle Kontrolle und lässt bestehende Einstellungen unberührt.

---

## Benötigte Bindings für die Showcase

Diese Funktionen in LMU belegen, damit die Showcase korrekt funktioniert.

### Hauptseite

| Button | LMU-Funktion zum Belegen |
|---|---|
| Spiegel umschalten | Toggle Mirror |
| Dash Cam | Driving Cameras |
| HUD | Driver Overlay Toggle HUD |
| Replay | Instant Replay |
| TV-Kamera | Tracking Cameras |
| Supporters | Spectator Cameras |
| Chase Cam | Swingman Camera |
| Nächstes Fahrzeug | View Next Vehicle |
| Vorheriges Fahrzeug | View Previous Vehicle |
| Mein Fahrzeug | View Original Vehicle |

### Freie Kamera-Seite

| Button | LMU-Funktion zum Belegen |
|---|---|
| Freie Kamera An/Aus | Toggle Free Move |
| Vorwärts | Camera Move Forward |
| Rückwärts | Camera Move Backward |
| Links | Camera Move Left |
| Rechts | Camera Move Right |
| Hoch | Camera Move Up |
| Runter | Camera Move Down |
| Zentrieren | Zero Free Move |
| Neigen hoch | Camera Tilt Up |
| Neigen runter | Camera Tilt Down |
| Drehen links | Camera Turn Left |
| Drehen rechts | Camera Turn Right |

---

## Wichtiger Hinweis zu LMU-Kameranamen

Die Kameranamen in LMU passen nicht immer zu dem, was die meisten Nutzer erwarten würden.

| LMU-Bezeichnung | Was sie tatsächlich macht | Im Showcase verwendet als |
|---|---|---|
| **Swingman Camera** | Springt hinter das Auto, danach frei bewegbar | Chase Cam |
| **Onboard Cameras** | Kompakte Cockpit-/Action-Cam-Perspektive | GoPro Cockpit Cam |
| **Driving Cameras** | Standard-Cockpit-Fahrsicht | Dash Cam |
| **Tracking Cameras** | TV-/Broadcast-Verfolgerkameras | TV-Kamera |
| **Spectator Cameras** | Feste Streckenkameras | Supporters |

Dieses Profil beschriftet die Buttons nach ihrem tatsächlichen Verhalten — nicht nach den LMU-Spielbezeichnungen.

---

## Aufbau der Showcase

### Hauptseite

Die Hauptseite enthält die nützlichsten Kamera- und Replay-Funktionen direkt:
- Replay
- TV-Kamera-Wechsel
- Feste Zuschauerkameras (Supporters)
- Chase Cam
- Cockpit- und Fahrkamera-Ansichten
- Nächstes / vorheriges Fahrzeug
- Zurück zum eigenen Fahrzeug
- Einstieg in die freie Kamera

### Freie Kamera-Ordner

Der Freie-Kamera-Ordner enthält die erweiterten Kamerabewegungssteuerungen:
- Freie Kamera ein-/ausschalten
- Bewegen in alle Richtungen (vorwärts, rückwärts, links, rechts, hoch, runter)
- Drehen und Neigen
- Kamera zentrieren / zurücksetzen

Damit bleibt die Hauptseite übersichtlich, während volle Kamerakontrolle trotzdem erreichbar ist.

> **Tipp: Free Cam lässt sich mit jeder Kameraperspektive kombinieren.**
> Zuerst eine Kamera wählen — zum Beispiel Chase Cam — dann den Free-Cam-Ordner öffnen und die Free Cam aktivieren. Die freie Kamera baut auf der aktuell gewählten Perspektive auf und lässt sich von dort frei weiter bewegen. Du startest nicht bei null.

---

## Der Showcase-Button

Der Button oben links auf der Hauptseite ist das Branding der Showcase Edition.

Er kann so konfiguriert werden, dass er diese Quick-Start-Datei öffnet — damit ist der Branding-Button nicht nur Dekoration, sondern gleichzeitig ein Hilfe-Einstieg.

---

## Hinweis zum Pro-Upgrade

Das Einrichten der Showcase ist keine verlorene Arbeit.

Wo Showcase und Pro dieselben Funktionen teilen, nutzen sie dieselben LMU-Tastenbelegungen. Wenn du später auf die Pro-Version wechselst, ist ein Großteil deines Binding-Setups bereits erledigt.

Du fängst nicht von vorne an.

---

## Was in der Showcase bewusst nicht enthalten ist

Folgende Funktionen sind absichtlich ausgelassen — sie sind Teil der Pro Edition:

- Zündung und Starter
- Blick links / rechts / zurück
- Motor-Map-Steuerung
- Regeneration / Energieverwaltung
- Sitzverstellung, FOV
- HUD-Details (Fahrernamen, Standings, Telemetrie)
- Replay-Geschwindigkeit, Einzelbild, Rückspulen
- MFD-Navigation
- Box-Anfrage und Box-Menü

---

## Feedback

Was als Feedback am meisten hilft:
- Was sofort funktioniert hat
- Was sich unklar angefühlt hat
- Welche Buttons du am häufigsten genutzt hast
- Ob die Kameralogik klarer war als LMUs Standard-Bezeichnungen

---

## Abschließender Hinweis

Die Showcase ist ein vollständiges, nutzbares Produkt für sich.
Kein Demo, das ausläuft. Keine ausgehöhlte Platzhalterversion.
Ein fokussiertes Werkzeug — und ein sauberer Einstieg in die Pro-Version, wenn du bereit bist.
