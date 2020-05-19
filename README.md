# Eryone Thinker V2 Firmware-Beta 
###  (Based on Marlin2.0.x)

![GitHub Stars](https://img.shields.io/github/stars/Eryone/mega2560.svg)
![GitHub contributors](https://img.shields.io/github/contributors/Eryone/mega2560.svg)
![GitHub followers](https://img.shields.io/github/followers/Eryone.svg)

- Author: 
  - **Tom Yuan**
  - **Eryone** 

## Please ues the "M502" and "M500" to reset the EEPROM when you uploaded the firwmare

## Support 3D printer

| 3D Printer Model    | Motherboard                | Stepper Driver    
| ------------------- | -------------------------- | --------------
| Eryone Thinker S    | Thinker V2 Motherboard     | TMC2208
| Eryone Thinker S    | Thinker V2 Motherboard     | TMC2209
| Eryone Thinker SE   | Thinker V2 Motherboard     | TMC2208
| Eryone Thinker SE   | Thinker V2 Motherboard     | TMC2209

### Thinker V2 Motherboard

![](https://www.eryone.com/forum/download/file.php?id=162)

## Source               

- *[Stable Firmware](https://github.com/Eryone/mega2560)* This is the offical firmware, not have much feature but stable.
- *[Marlin officail](https://github.com/MarlinFirmware/Marlin)* Marlin offical firmware release main page
- *[Marlin Gcode](https://marlinfw.org/meta/gcode/)* Marlin offical gcode introduction

## Feature
- Thinker V2 with TMC2208
  - **Filament change**
  - **Z babystep** 
  - **Mesh bed leveling or auto bed level**
  - **Remaining time display**
  - **LCD shows filament used**

- Thinker V2 with TMC2209
  - **TMC UART**
  - **Sensorless homing**
  - **Filament change**
  - **Z babystep** 
  - **Mesh bed leveling or auto bed level**
  - **Remaining time display**
  - **LCD shows filament used**

## How to use the config
- Open the config folder
- Choose the "Thinker V2"， "Thinker V2(TMC2209+Sensorless)" or "Thinker V2(Filament runout)" folder
- Choose the stock config or auto level config.
  The auto level config inculded the Inductive sensor and bltouch sensor
  -  **The thinker SE user can't use the inductive sensor. Please don't use this type config**
- Replace the old config at "Marlin" folder

## Build and Install
To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [VS Code](https://docs.platformio.org/en/latest/integration/ide/vscode.html). Detailed build and install instructions at:

- *[Youtube Guide Video](https://www.youtube.com/watch?v=b2D4I9Yxejw)*



## Join our group& Contact us
- *[Facebook](https://www.facebook.com/groups/247271792709370/)*
- *[Instagram](https://www.instagram.com/eryone3d/)*
- *[Eryone Forum](https://www.instagram.com/eryone3d/)*
- *[Youtube](https://www.youtube.com/eryone3d)*














