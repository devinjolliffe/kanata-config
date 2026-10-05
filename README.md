# Lofree Flow Lite84 Kanata Layout

Kanata configuration for the Lofree Flow Lite84 US ANSI keyboard.

## Features

- Miryoku-style home-row modifiers
- Left hand: Ctrl / Alt / Win / Shift
- Right hand: Shift / Win / Alt / Ctrl
- Space tap = Space
- Space hold = navigation layer
- Arrow-style navigation on I/J/K/L
- Home / Page Down / Page Up / End on Y/U/O/P
- Delete on ;
- Backtick/grave toggles the modified layer

## Toggle

- Tap ` = switch between normal and modified layers
- Hold ` = send the normal backtick key

The configuration uses `layer-switch` to switch persistently between the `base` and `mods` layers.

## Files

- `kanata.kbd` - main Kanata configuration
- `.gitignore` - ignores local/editor files
- `LICENSE` - MIT license

## Running

```text
kanata --cfg kanata.kbd
```
