# Setup Guide – Showcase Edition

## Two setup paths

There are **2 ways** to set up the Showcase Edition:

### Path 1 – Quick start
You use the ready-made Showcase preset.

Best if you:
- want the fastest setup
- do not have important custom LMU bindings yet

Downside:
- your current `keyboard.json` will be replaced

### Path 2 – Manual setup
You keep your current LMU bindings and assign only the Showcase functions yourself.

Best if you:
- do not want to overwrite anything
- want full control over your setup

Downside:
- takes longer

---

## Preparation

LMU key binding file path:

```text
[LMU installation]\UserData\player\keyboard.json
````

Before changing anything:

* back up your current `keyboard.json`
* open the Stream Deck software
* have the Showcase `.streamDeckProfile` ready

---

# Path 1 – Quick start

1. Copy `keyboard_preset_showcase.json` into `UserData\player\`
2. Rename the file to `keyboard.json`
3. Replace the existing `keyboard.json`
4. Import the Showcase `.streamDeckProfile` into Stream Deck

After that, do a quick check in LMU to make sure the Showcase functions respond.

---

# Path 2 – Manual setup

1. Import the Showcase `.streamDeckProfile` into Stream Deck
2. In LMU open: **Settings → Controls → Keyboard**
3. Assign only the functions that are actually used in the Showcase profile

### Main page

| Showcase button  | LMU function                         |
| ---------------- | ------------------------------------ |
| Toggle Mirror    | Toggle mirrors                       |
| HUD Management   | HUD function used by the profile     |
| TV Camera Switch | matching TV / camera switch function |
| Cockpit Cam      | cockpit / onboard camera             |
| Dash Cam         | dash / dashboard camera              |
| Chase Cam        | chase cam / follow camera            |
| Next Car         | view next vehicle                    |
| Jump to My Car   | view original vehicle / my car       |
| Previous Car     | view previous vehicle                |

### Free Camera page

| Showcase button     | LMU function                 |
| ------------------- | ---------------------------- |
| Camera On/Off       | enable / disable free camera |
| Free Camera Forward | move free camera forward     |
| Free Cam Up         | move free camera up          |
| Free Camera Left    | move free camera left        |
| Camera Center       | reset free camera            |
| Free Camera Right   | move free camera right       |
| Rotate Camera Up    | tilt free camera up          |
| Rotate Camera Down  | tilt free camera down        |
| Free Cam Down       | move free camera down        |
| Rotate Camera Left  | rotate free camera left      |
| Free Camera Back    | move free camera back        |
| Rotate Camera Right | rotate free camera right     |

Empty slots in the layout stay empty.

---

## Test

After Path 1 or Path 2:

### Check the main page

* Toggle Mirror
* HUD Management
* TV Camera Switch
* Cockpit Cam
* Dash Cam
* Chase Cam
* Next Car
* Jump to My Car
* Previous Car
* Free Camera folder

### Check the Free Camera page

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
* Back button

---

## Important

This Showcase version is focused on:

* camera switching
* car views
* vehicle switching
* free camera
* mirrors
* HUD

It is not a driving control profile.

---

## Troubleshooting

### A button does not respond

* check whether the function is assigned in LMU
* check whether the Stream Deck button sends the correct key
* check whether LMU is the active window

### Something is wrong after Path 1

* check whether you really used `keyboard_preset_showcase.json`
* check whether the file was correctly renamed to `keyboard.json`
* restart LMU

### My custom bindings were overwritten

* restore your backup of the old `keyboard.json`
* restart LMU
