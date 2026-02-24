# FlowLines — Getting Started

FlowLines improves the readability of Blueprint execution flow by allowing you to customize **Exec pins** and their connecting wires.  
You can adjust colors, wire thickness, and pin size using presets or custom values.

## Installation

1. Extract the `FlowLines` folder into your project:
2. Open Unreal Engine (version 5.1 – 5.6, Win64).
3. Go to **Edit → Plugins**, search for **FlowLines**, and enable it.
4. Restart the Editor if prompted.

## Quick Setup

- Open **Edit → Editor Preferences → Plugins → FlowLines**.
- Choose a **Preset**:
- **Default** — matches Unreal’s standard style
- **High Contrast** — brighter colors and thicker wires
- **Soft** — subtle colors and thinner wires
- **Custom** — manually configure pin and wire style
- If **Custom** is selected, set:
- **Color** (Exec pins & wires)
- **WireThickness** (line thickness, default ~2.5)
- **PinSize** (pin icon scale, default 1.0)

## Quick Demo

1. Open any Blueprint with multiple Exec connections (e.g., Sequence, Branch).
2. Change the preset to **High Contrast** in Editor Preferences.

3. The changes will apply immediately to all Blueprint Exec pins and wires.

