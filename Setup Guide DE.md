# Setup-Guide – Showcase Edition

## Zwei Wege zur Einrichtung

Für die Showcase Edition gibt es **2 Wege**:

### Weg 1 – Schnellstart
Du übernimmst das fertige Showcase-Preset.

Gut, wenn du:
- schnell starten willst
- keine wichtigen eigenen LMU-Bindings hast

Nachteil:
- deine bisherige `keyboard.json` wird ersetzt

### Weg 2 – Manuell
Du behältst deine aktuellen LMU-Bindings und belegst nur die Showcase-Funktionen selbst.

Gut, wenn du:
- nichts überschreiben willst
- volle Kontrolle behalten möchtest

Nachteil:
- dauert länger

---

## Vorbereitung

Pfad der LMU-Tastenbelegung:

```text
[LMU-Installation]\UserData\player\keyboard.json
````

Bevor du etwas änderst:

* vorhandene `keyboard.json` sichern
* Stream Deck Software öffnen
* Showcase-`.streamDeckProfile` bereithalten

---

# Weg 1 – Schnellstart

1. `keyboard_preset_showcase.json` in `UserData\player\` kopieren
2. Datei in `keyboard.json` umbenennen
3. vorhandene `keyboard.json` ersetzen
4. Showcase-`.streamDeckProfile` in Stream Deck importieren

Danach in LMU kurz prüfen, ob die Showcase-Funktionen reagieren.

---

# Weg 2 – Manuell

1. Showcase-`.streamDeckProfile` in Stream Deck importieren
2. In LMU öffnen: **Einstellungen → Steuerung → Tastatur**
3. Nur die Funktionen belegen, die im Showcase-Profil wirklich verwendet werden

### Hauptseite

| Showcase-Button  | LMU-Funktion                                 |
| ---------------- | -------------------------------------------- |
| Toggle Mirror    | Spiegel ein-/ausschalten                     |
| HUD Management   | HUD-Funktion gemäß Profilbelegung            |
| TV Camera Switch | passende TV-/Kamera-Umschaltung              |
| Cockpit Cam      | Cockpit-/Onboard-Kamera                      |
| Dash Cam         | Dash-/Armaturenbrett-Kamera                  |
| Chase Cam        | Chase Cam / Verfolgerkamera                  |
| Next Car         | Nächstes Fahrzeug betrachten                 |
| Jump to My Car   | Ursprungsfahrzeug betrachten / Mein Fahrzeug |
| Previous Car     | Vorheriges Fahrzeug betrachten               |

### Free Camera Seite

| Showcase-Button     | LMU-Funktion                           |
| ------------------- | -------------------------------------- |
| Camera On/Off       | Freie Kamera aktivieren / deaktivieren |
| Free Camera Forward | Freie Kamera nach vorn bewegen         |
| Free Cam Up         | Freie Kamera nach oben bewegen         |
| Free Camera Left    | Freie Kamera nach links bewegen        |
| Camera Center       | Freie Kamera zurücksetzen              |
| Free Camera Right   | Freie Kamera nach rechts bewegen       |
| Rotate Camera Up    | Freie Kamera nach oben neigen          |
| Rotate Camera Down  | Freie Kamera nach unten neigen         |
| Free Cam Down       | Freie Kamera nach unten bewegen        |
| Rotate Camera Left  | Freie Kamera nach links drehen         |
| Free Camera Back    | Freie Kamera nach hinten bewegen       |
| Rotate Camera Right | Freie Kamera nach rechts drehen        |

Leere Felder im Layout bleiben leer.

---

## Test

Nach Weg 1 oder Weg 2:

### Hauptseite prüfen

* Toggle Mirror
* HUD Management
* TV Camera Switch
* Cockpit Cam
* Dash Cam
* Chase Cam
* Next Car
* Jump to My Car
* Previous Car
* Free Camera Ordner

### Free Camera Seite prüfen

* Camera On/Off
* Free Camera Forward
* Free Cam Up
* Free Camera Left
* Camera Center
* Free Camera Right
* Rotate Camera Up
* Rotate Camera Down
* Free Cam Down
* Rotate Camera Left
* Free Camera Back
* Rotate Camera Right
* Zurück-Button

---

## Wichtig

Diese Showcase-Version ist auf folgende Bereiche fokussiert:

* Kamera-Umschaltung
* Fahrzeugansichten
* Fahrzeugwechsel
* freie Kamera
* Spiegel
* HUD

Sie ist kein Fahrsteuerungs-Profil.

---

## Fehlerbehebung

### Ein Button reagiert nicht

* prüfen, ob die Funktion in LMU belegt ist
* prüfen, ob der Stream-Deck-Button die richtige Taste sendet
* prüfen, ob LMU im Vordergrund läuft

### Nach Weg 1 stimmt etwas nicht

* prüfen, ob wirklich `keyboard_preset_showcase.json` verwendet wurde
* prüfen, ob die Datei korrekt in `keyboard.json` umbenannt wurde
* LMU neu starten

### Eigene Bindings wurden überschrieben

* Backup der alten `keyboard.json` zurückkopieren
* LMU neu starten