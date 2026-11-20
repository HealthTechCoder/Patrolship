# Patrol — 3D Aerial Combat

Patrol is a fast-paced, browser-based 3D aerial combat game. Pilot a fighter through a procedurally generated world, engage enemy aircraft and ground defences, survive increasingly difficult waves, earn credits, and upgrade your aircraft.

The game runs directly in a modern browser and uses WebGL 2 for its 3D rendering. No installation or build step is required.

## Play

Open the game through [GitHub Pages](https://healthtechcoder.github.io/Patrolship/) once Pages is enabled for this repository, or serve `index.html` from a local web server.

**Requirements:** a modern browser with WebGL 2 support. On mobile, landscape orientation is recommended. A “Play anyway” option is available in portrait mode.

## Controls

The game selects its control layout from the input device reported by the browser.

### Desktop — mouse and keyboard

| Input | Action |
|---|---|
| Mouse movement | Steer |
| Left-click | Perform a loop |
| Hold left mouse button | Afterburner / boost |
| Right-click or **F** | Fire missile |
| Hold **G** | Fire guns |
| Hold **Left Shift** | Boost |
| **R** | Loop |
| **T** | Toggle tank mode |
| **X** | 180-degree turn |
| **C** | Deploy flare |
| **Space** | Change camera view |
| **1–4** | Select an upgrade while the upgrade shop is open |

### Mobile and touchscreen

Touch-capable devices with a coarse pointer get an on-screen joystick and touch buttons. Drag the joystick to steer; use the labelled buttons for boost, missiles, guns, loop, flare, view, tank mode and the 180-degree turn. Rotate to landscape for the recommended layout. Safe-area spacing is included for devices with notches and home indicators.

### Gamepad

A connected browser gamepad is detected automatically. The left stick steers; face, shoulder and menu buttons provide the game actions. The on-screen touch controls are visually de-emphasised while a gamepad is active.

## Features

- WebGL 2 real-time 3D rendering
- Procedurally generated terrain and sky
- Enemy fighters, specialist aircraft and ground defences
- Escalating waves, boss encounters and missile threats
- Gun and missile combat, flares and aircraft manoeuvres
- Credits and an upgrade shop
- Desktop mouse/keyboard, touchscreen and gamepad input

## Run locally

Serve the repository with a local HTTP server rather than opening the file directly. For example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Compatibility notes

- WebGL 2 is required.
- Audio is off by default and can be enabled in-game.
- Full-screen mode is available where supported by the browser.
- Performance and available screen space vary by device.
