# Corne Keyboard ZMK Config

ZMK firmware configuration for Corne keyboard with Nice Nano v2 controllers.

## Flashing Instructions

1. **Download firmware** from [GitHub Actions](../../actions) - get the latest successful build artifacts
2. **Enter bootloader mode** - Double-tap the reset button on the Nice Nano
3. **Mount as drive** - A drive named "NICENANO" should appear
4. **Flash firmware** - Drag the corresponding `.uf2` file onto the drive:
   - `corne_left-nice_nano_v2.uf2` → Left side
   - `corne_right-nice_nano_v2.uf2` → Right side
5. **Repeat** for the other half

The microcontroller will automatically reboot after flashing.

## Editing Keymap

Use the [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) for visual keymap editing.

## Layers

- **Layer 0**: Default QWERTY layout
- **Layer 1**: Media controls, brightness, arrows, Bluetooth
- **Layer 2**: Numbers and symbols
- **Layer 3**: Aerospace workspace management (cmd+ctrl keybinds)
  - Hold shift for window moving (cmd+ctrl+shift)

## Configuration Features

- Deep sleep after 15 minutes (battery saving)
- Enhanced Bluetooth connectivity (+8dBm transmission power)
- Aerospace window manager integration
