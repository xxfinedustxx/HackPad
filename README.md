# HackPad
(template)
description

## Features:
- **128x32 OLED Display**
- **Dual Rotonary Knobs**
- **RGB Per-Key Backlighting**
- **16x MX-Style Keys** 

## Cad Model:
<p align = "center">
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/AssemblyHackPadR.png" width = "400">
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/AssemblyHackPadL.png" width = "400">
</p>
description

## PCB
<p align = "center">
    <p>Here's is my PCB! It was made in EasyEDA</p>
    <h3>PCB</h>
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/PCB_PCB_Macropad_2026-10-18.png">
    <h3>Schematic</h3>
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/Schematic_Macropad_2026-10-18.png">
</p>


## Firmware Overview
This hackpad will use [QMK][https://qmk.fm] firmware for everything.
-first rotary encoder will change volume, press to mute 
-second rotary encoder will change board layout on press or rotation (didn't decide yet) and bu used to display diffrent pngs on the OLED
-OLED will be used to display pngs


## BOM
### Electronics
- [ ] 16x MX-Style switches
- [ ] 16x white blank DSA keycaps
- [ ] 20x 1N4148 Diodes
- [ ] 16x SK6812 MINI-E LEDs
- [ ] 1x unsoldered Seeed XIAO RP2040
- [ ] 1x 0.91 inch OLED display
- [ ] 1x PCB
- [x] 1x MCP23017-E/ML (I2C Port Expander)
- [x] 1x 10kΩ UNI-ROYAL 0805W8F1002T5E
- [x] 2x 4.7kΩ UNI-ROYAL 0805W8F4701T5E
### Hardware & Fasteners
- [ ] 6x M3x16mm SHCS Bolts
- [ ] 6x M3x5mx4mm heatset inserts
### 3D Prints
- [ ] 1x Case Top
- [ ] 1x Case Bottom
- [ ] 2x Knob Dials
