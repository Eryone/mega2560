# Eryone Thinker V2 Firmware
###  (Based on Marlin2.0.x)

![GitHub Stars](https://img.shields.io/github/stars/Eryone/mega2560.svg)
![GitHub contributors](https://img.shields.io/github/contributors/Eryone/mega2560.svg)
![GitHub followers](https://img.shields.io/github/followers/Eryone.svg)

- Author: 
  - **Tom Yuan**
  - **Eryone** 


## Support 3D printer

| 3D Printer Model    | Motherboard                | Stepper Driver    
| ------------------- | -------------------------- | --------------
| Eryone Thinker SV2  | Thinker V2 Motherboard     | TMC2208
| Eryone Thinker SV2  | Thinker V2 Motherboard     | TMC2209
| Eryone Thinker SE   | Thinker V2 Motherboard     | TMC2208
| Eryone Thinker SE   | Thinker V2 Motherboard     | TMC2209

### Thinker V2 Motherboard

![](http://www.eryone.com/forum/download/file.php?id=433)

## Source               

- *[Stable Firmware](https://github.com/Eryone/mega2560)* This is the offical firmware, not have much feature but stable.
- *[Marlin officail](https://github.com/MarlinFirmware/Marlin)* Marlin offical firmware release main page
- *[Marlin Gcode](https://marlinfw.org/meta/gcode/)* Marlin offical gcode introduction

## Feature
- Thinker SV2/SE with TMC2208
  - **Filament change**
  - **Z babystep** 
  - **Mesh bed leveling or auto bed level**
  - **SD card print percent**
  - **LCD shows filament used**

- Thinker SV2/SE with TMC2209
  - **TMC UART**
  - **Sensorless homing**
  - **Filament change**
  - **Z babystep** 
  - **Mesh bed leveling or auto bed level**
  - **SD card print percent**
  - **LCD shows filament used**


## Build and Install
- **Please ues the "M502" and "M500" to reset the EEPROM when you uploaded the firwmare**
We prepared the hex file, you can choose the correct one then upload it to your printer.
Recommand to use the **Ultimaker Cura** upload it.
Refer to this link:
- *[Upload firmware via Cura](https://www.youtube.com/watch?v=SpdjvYkUQY4)*

To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [VS Code](https://docs.platformio.org/en/latest/integration/ide/vscode.html). Detailed build and install instructions at:

- *[Youtube Guide Video](https://www.youtube.com/watch?v=b2D4I9Yxejw)*
- **Please ues the "M502" and "M500" to reset the EEPROM when you uploaded the firwmare**

### Change the language: Open the "configuration.h" then find this line:
- "#define LCD_LANGUAGE" then set the language you want to set. Built it and upload it to your printer.

## How to use the config&Guide
- Notes: Before this section, if you are not familiar with the marlin then you should back to the previous section.
- Go to "Thinker V2"→"docs" to refer the guide of TMC2209 with Thinker V2 motherboard
- Open the ”config“→“Eryone”→Then choose the correct model folder then enter
- Copye the ** "configuration.h" and "configuration_adv.h" **
- Then paste them to ** "Marlin" ** folder
- **Please ues the "M502" and "M500" to reset the EEPROM when you uploaded the firwmare**


## Join our group& Contact us
- *[Facebook](https://www.facebook.com/groups/247271792709370/)*
- *[Instagram](https://www.instagram.com/eryone3d/)*
- *[Eryone Forum](https://www.instagram.com/eryone3d/)*
- *[Youtube](https://www.youtube.com/eryone3d)*














