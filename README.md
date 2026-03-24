# LMU Stream Deck Showcase

A compact showcase profile for **Le Mans Ultimate** designed to give a fast and clean entry into replay and camera control on Stream Deck.

## What this is

The Showcase Edition is a focused introduction to the wider LMU Stream Deck project.

It is built to:
- look polished immediately
- be useful right away
- avoid feeling like a broken lite version
- make the upgrade path to Pro easy and logical

## Important

The Showcase Edition is **not wasted setup work**.

For overlapping functions, it uses the same LMU bindings as the Pro profile.  
That means if you start with Showcase, a large part of the binding work is already done when moving to Pro.

## Current Showcase Structure

The Showcase uses:
- **one main page**
- plus a **Free Cam folder** as a second level

This structure was chosen on purpose because it feels cleaner and stronger than splitting the showcase into multiple equally important main pages.

## Main Page

The main page includes:

- Toggle Mirror
- HUD
- Replay
- TV Camera
- Supporters
- GoPro Cockpit Cam
- Dash Cam
- Chase Cam
- Next Car
- My Car
- Previous Car
- Free Cam Folder

## Free Cam Folder

The Free Cam folder includes:

- Free Camera On/Off
- Forward
- Back
- Left
- Right
- Up
- Down
- Camera Center
- Rotate Up
- Rotate Down
- Rotate Left
- Rotate Right
- Get Pro

## Camera Logic

Le Mans Ultimate uses several camera names that can be confusing.

### Chase Cam
The most practical chase-cam-like function is:

**Swingman / Schwenkkopf Camera**

This is the camera that behaves most like the chase cam users normally expect.

### Tracking Cameras
Tracking Cameras are **not** the intended chase cam.  
They behave more like broadcast or TV-style cameras.

### Supporters
Supporters represents the more fixed spectator / trackside style of view.

## Free Cam Tip

Free Cam is not just an isolated special mode.

You can combine it with other camera views.  
For example:

1. choose Chase Cam first
2. open the Free Cam folder
3. activate Free Cam
4. adjust the view more freely from there

This makes Free Cam much more powerful than it first appears.

## Replay Note

Two replay-related functions are intentionally active in the Showcase:

- **Instant Replay** = opens replay view
- **Replay Play** = play/pause while in replay

This is intentional and correct.

## Setup Options

There are two setup paths.

### Way A – Express
Fast, simple, but more risky.

- back up your current LMU keyboard file first
- copy the provided preset into the LMU folder
- rename it as needed for LMU

### Way B – Manual
Slower, but safer.

- bind the required functions manually
- better if you already use a custom setup

## Preset Logic

There are two presets in the project:

1. `keyboard_preset_pro.json`
2. `keyboard_preset_showcase.json`

### Pro Preset
The complete full preset.  
It stays unchanged.

### Showcase Preset
Derived from the Pro preset.

It keeps the same structure and key layout, but all non-required bindings are set to `0` instead of being removed.

## Branding Button

The branding button remains branding.

However, it can still open something useful in the background, such as:
- Quick Start
- Read Me
- setup information

So it stays visually branded while also being useful for the user.

## Project Direction

This showcase is part of a larger project direction:

- Showcase Edition
- Pro Edition
- Smart Wheel
- Pit State Logic
- RaTiX integration

## Status

The Showcase is currently intended for internal testing and controlled sharing first, before broader release.

---

More documentation will follow.
