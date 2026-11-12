# SNES Player

**Version: 0.1.0**

A dedicated browser-based Super Nintendo emulator using the JavaScript SNES core bundled locally from [lrusso/Emulatrix](https://github.com/lrusso/Emulatrix).

## Current build

- Local ROM picker; the file input is not restricted to a particular extension.
- ROM data is read on-device and passed directly to the emulator.
- No CDN, iframe, external script, runtime download, or external asset is used.
- Start-page control selector: Hide controls (default), 1P controls, or 2P controls.
- Control selection is saved locally and remains in effect when entering or leaving fullscreen.
- Keyboard mappings are listed below.

## Keyboard controls

| Action | Player 1 | Player 2 |
|---|---|---|
| D-pad | W A S D | Arrow keys |
| A | Z | P |
| B | X | [ |
| X | Q | O |
| Y | E | I |
| L | C | ] |
| R | V | \\ |
| Select | 1 | - |
| Start | 2 | = |

## Run locally

Open `index.html` in a modern browser. Some browsers restrict local JavaScript or audio features when opened directly from a file URL; hosting these bundled files on the same origin may be required. The emulator itself does not fetch runtime assets.

## License and attribution

The bundled `snes-core.js` is taken from the MIT-licensed [Emulatrix](https://github.com/lrusso/Emulatrix) project by Leonardo Javier Russo. See [LICENSE](LICENSE). The upstream SNES core is also listed at [lrusso/SuperNintendo](https://github.com/lrusso/SuperNintendo).
