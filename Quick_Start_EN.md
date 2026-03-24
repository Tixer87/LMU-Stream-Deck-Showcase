# LMU Stream Deck Showcase – Quick Start

## What this is

This Showcase Edition is a compact preview version of the LMU Stream Deck Dashboard.

It focuses on:
- replay control
- camera switching
- car switching
- free camera access

The goal is to give you a clean and useful entry point without throwing the full profile at you right away.

---

## Before you start

You need:
- **Le Mans Ultimate**
- **Elgato Stream Deck**
- the imported **Showcase profile**

Important: In LMU, always bind keys in the **Keyboard** column, not in the wheel or controller column.

---

## Setup options

### Path A — Express

Fast, but riskier.

Use the provided keyboard preset:

1. Back up your current `keyboard.json`
2. Copy the provided `keyboard_preset_showcase.json` into your LMU player folder
3. Rename it to `keyboard.json`

This is the quickest way, but it will overwrite your existing custom keyboard bindings. The backup in step 1 is your safety net.

### Path B — Manual

Safer, but slower.

Import the Showcase profile into the Stream Deck software, then bind the required LMU functions manually inside the game.

This gives you full control and leaves your existing setup untouched.

---

## Required bindings for the Showcase

Bind these functions in LMU so the Showcase works correctly.

### Main page

| Button | LMU function to bind |
|---|---|
| Toggle Mirror | Toggle Mirror |
| Dash Cam | Driving Cameras |
| HUD | Driver Overlay Toggle HUD |
| Replay | Instant Replay |
| TV Camera | Tracking Cameras |
| Supporters | Spectator Cameras |
| Chase Cam | Swingman Camera |
| Next Car | View Next Vehicle |
| Previous Car | View Previous Vehicle |
| My Car | View Original Vehicle |

### Free Camera page

| Button | LMU function to bind |
|---|---|
| Free Camera On/Off | Toggle Free Move |
| Forward | Camera Move Forward |
| Back | Camera Move Backward |
| Left | Camera Move Left |
| Right | Camera Move Right |
| Up | Camera Move Up |
| Down | Camera Move Down |
| Center | Zero Free Move |
| Tilt Up | Camera Tilt Up |
| Tilt Down | Camera Tilt Down |
| Turn Left | Camera Turn Left |
| Turn Right | Camera Turn Right |

---

## Important camera note

LMU's camera labels do not always match what most users would expect.

| LMU label | What it actually does | Used in Showcase as |
|---|---|---|
| **Swingman Camera** | Jumps behind the car, freely movable | Chase Cam |
| **Onboard Cameras** | Compact cockpit / action cam perspective | GoPro Cockpit Cam |
| **Driving Cameras** | Standard cockpit driving view | Dash Cam |
| **Tracking Cameras** | TV-style broadcast follow cameras | TV Camera |
| **Spectator Cameras** | Fixed trackside cameras | Supporters |

This Showcase labels buttons by what they actually do — not by LMU's in-game names.

---

## How the Showcase is structured

### Main Page

The main page gives you the most useful camera and replay functions immediately:
- Replay
- TV camera switching
- Fixed spectator cameras (Supporters)
- Chase Cam
- Cockpit and driving camera views
- Next / previous car
- Jump back to your own car
- Entry to Free Camera

### Free Camera Folder

The Free Camera folder contains extended camera movement controls:
- Toggle free camera on/off
- Move in all directions (forward, back, left, right, up, down)
- Rotate and tilt
- Center/reset position

This keeps the main page clean while still giving you full camera control when needed.
> **Tip: Free Cam works with any camera perspective.**
> Switch to a camera first — for example Chase Cam — then open the Free Camera folder and activate Free Cam. The free camera builds on the current view and lets you adjust it from there. You are not starting from a blank position.
---

## The Showcase button

The top-left button on the main page is the Showcase Edition branding button.

It can be configured to open this Quick Start file, so the branding button is not just decorative — it acts as a help entry point.

---

## Pro upgrade note

Setting up the Showcase is not wasted work.

Where Showcase and Pro share the same functions, they use the same underlying LMU key bindings. If you later move to the Pro version, a large part of your binding setup is already done.

You are not starting from scratch.

---

## What is intentionally not in the Showcase

The following functions are deliberately excluded — they are part of the Pro Edition:

- Ignition and Starter
- Look left / right / back
- Engine map controls
- Regeneration / energy management
- Seat adjustment, FOV
- HUD detail controls (driver names, standings, telemetry)
- Replay speed, frame step, reverse
- MFD navigation
- Pit request and pit menu

---

## Feedback

If something feels unclear, the most helpful feedback is:
- what worked immediately
- what felt confusing
- which buttons you used most
- whether the camera logic felt clearer than LMU's default naming

---

## Final note

The Showcase is a complete, usable product on its own.
It is not a demo that expires or a stripped-down placeholder.
It is a focused tool — and a clean starting point for the Pro version when you are ready.
