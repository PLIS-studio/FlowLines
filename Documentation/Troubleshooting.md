# FlowLines — Troubleshooting Guide

This guide helps you resolve the most common issues you may encounter when using FlowLines.

---

## 1. I enabled the plugin, but nothing changed
- Open **Edit → Editor Preferences → Plugins → FlowLines**.
- Check the **Preset** option:
  - If it is set to **Default**, Unreal will look the same as usual.
  - Switch to **High Contrast** or **Soft** to see immediate changes.
- If you want to fine-tune the look, choose **Custom** and set your own colors and thickness.

---

## 2. Settings are not saving
- Make sure you apply changes in **Editor Preferences**, not **Project Settings**.
- FlowLines is an **Editor plugin**, so its options are stored per-Editor, not per project.
- If you are using multiple Unreal Engine installations, each one may have its own settings.

---

## 3. The plugin shows a warning about engine version
Example message:  
> *The 'FlowLines' plugin was designed for build 5.2.0. Attempt to load it anyway?*

- This is safe to ignore if you are running a supported version (UE 5.1 – 5.6).  
- The plugin is compatible across multiple 5.x versions.  
- If Unreal refuses to load it, download the correct build of the plugin for your engine version.

---

## 4. Hover glow does not appear on exec wires
- Hover effects and glow use Unreal’s default behavior.  
- Make sure you are hovering directly over the wire, not the pin background.  
- Try increasing **WireThickness** in FlowLines settings to make the glow easier to see.

---

## 5. Blueprint lines look too thin or too thick
- Go to **Editor Preferences → FlowLines → WireThickness**.
- Default Unreal thickness is about **2.5**.  
- Try values between **2.0** and **4.0** depending on your screen resolution and zoom level.

---

## 6. Exec pin icons look too small or too large
- Adjust **PinSize** in FlowLines settings.  
- Default scale is **16.0**.  
- Recommended range: **12.0 – 24.0**.

---

## 7. Colors are too bright or too dim
- Use the **Preset** dropdown to quickly test different styles:
  - **High Contrast** — strong bright colors for clarity
  - **Soft** — muted colors for comfort
- If you prefer full control, choose **Custom** and pick any color with the color picker.

---

## 8. I can’t find the plugin settings
- Open Unreal Editor.  
- Go to **Edit → Editor Preferences**.  
- Scroll down to the **Plugins** section.  
- Expand **FlowLines**.  
- All options are listed there.

---

## Still need help?
If you continue to experience problems:
- Check the plugin page on Fab for updates.  
- Make sure you are using the correct version of FlowLines for your Unreal Engine build.  
- Contact support through Fab if the issue persists.

