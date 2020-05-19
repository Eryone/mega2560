How to use the filament runout sensor for your printer

Note:
Please plug your filament runout sensor to z_min port
The pin_rambo.h file use the Z_min(The pin is 10) port for the filament runout sensor

Step:
1. Copy the config then replace the old config of the 'Marlin' folder
2. Upload the firmware via VSC or Arduino
3. Use the 'M502' and 'M500' to reset the EEPROM
4. Test it, you can use the M600 to test it work or not


PS: This config based on Eryone Thinker SE printer stock endstop part.
If you find your sensor didn't work , check your sensor is "pull up" or "pull down".
Also, the logic of it "true" or "false" should be correct.

Refer to this video to get more details of filament runout sensor:

author:
Chris Riley

https://www.youtube.com/watch?v=tl4VZ4zlxFQ&t=3s