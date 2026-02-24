# FlowLines — Usage Guide

## Location
All settings are available under:
**Edit → Editor Preferences → Plugins → FlowLines**

## Options
- **Preset**
  - **Default** — Unreal’s original look
  - **High Contrast** — orange/bright exec wires, thicker lines, larger pins
  - **Soft** — light desaturated exec wires, thinner lines, smaller pins
  - **Custom** — full manual control
- **Color**
  - Custom color for Exec pins and wires  
  - Supports color picker or `FLinearColor(R,G,B,A)`
- **WireThickness**
  - Controls exec wire thickness  
  - Default = 2.5
  - Recommended range = 2.0 – 4.0
- **PinSize**
  - Controls exec pin icon scale  
  - Default = 16.0
  - Recommended range = 12 – 24

## Preset Examples
- **High Contrast**
  - Color: `FLinearColor(1.0, 0.267, 0.0, 1.0)`
  - WireThickness: `3.5`
  - PinSize: `20.0`
- **Soft**
  - Color: `FLinearColor(0.35, 0.459, 0.586, 1.0)`
  - WireThickness: `2.0`
  - PinSize: `14.4`

## Notes
- Settings are stored in Editor Preferences, not per-project, unless overridden by config.
- For Example Projects: you can pre-save settings in `Config/DefaultEditorPerProjectUserSettings.ini` to showcase the plugin immediately.
