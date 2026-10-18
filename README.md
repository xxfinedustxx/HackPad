# F.D. HackPad
F.D Hackpad is a fork of the [HackClubs](https://hackpad.hackclub.com) Hackpad mission. It has an OLED Display it will use [QMK](https://qmk.fm) firmware. It also has SK6812 MINI-E Leds, keys and 2 rotary encoders. *For good measure*

## Features:
- **128x32 OLED Display**
- **Dual Rotonary Knobs**
- **RGB Per-Key Backlighting**
- **16x MX-Style Keys** 

## Cad Model:
<p>
    The case uses 8 M2 Bolts and heatset inserts, 4 are for the case, and the other ones are for the PCB<br>
    It has 4 seperate printed parts (Case Bottom, Case Top, 2x Dial knobs)
</p>
<p align = "center">
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/AssemblyHackPadR.png" width = "400">
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/AssemblyHackPadL.png" width = "400"><br>
</p>
<em>Note: It was made in Fusion360.</em>

## PCB

<p align = "center">
    <span><em>Here's is my PCB! It was made in EasyEDA</em></span>
    <h4>PCB</h4><br>
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/PCB_PCB_Macropad_2026-10-18.png" alt = "No picture">
    <h4>Schematic</h4><br>
    <img src = "https://github.com/xxfinedustxx/HackPad/blob/main/asserts/Schematic_Macropad_2026-10-18.png" alt = "No picture">
    <p>
        <em>Note: I designed my own keyswitch footprints for this project.</em>
    </p>
</p>


## Firmware Overview
This hackpad will use [QMK](https://qmk.fm) firmware for everything.
- first rotary encoder will change volume, press to mute 
- second rotary encoder will change board layout on press or rotation (didn't decide yet) and bu used to display diffrent pngs on the OLED
- OLED will be used to display pngs


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
- [x] 4x M2x8mm Bolts
- [x] 4x M2x3mmx4mm
### 3D Prints
- [ ] 1x Case Top
- [ ] 1x Case Bottom
- [ ] 2x Knob Dials

## Extras 
<p align = "center">
    <img src = "https://tenor.com/hr/view/duck-gif-23067050" width = "200" alt = "New spining duck needed">
</p>