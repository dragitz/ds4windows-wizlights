# ds4windows-wizlights
Using a little bit of assembly and lua we can dected any input (eg. gyro or stick) and use it as a value to modify Wiz lightbulbs.


* Requirements:

pip install pywizlight

Cheat Engine 7.2+

DS4Windows 2.2.2 or 2.2.4 (tested only on theese two)

WizLightbulb

* Guide

1. Open ds4windows and CE
2. Connect a controller (can be joycon, ds4, ds5 or any supported)
3. Attach and load the table
4. Enable "Populate Xinput Map"

5. Edit the script "Joycon Wiz Lights (global)" and edit the ip address to your bulb's ip.
6. Enable Joycon Wiz Lights (global)

If done correctly you can now use the Right Stick to control the luminosity.


If you want to use the gyro data, manually remap gyro data to upward/downward movement of stick from the profile editor (in ds4windows)


* Bugs

I haven't fully adapted the script for all possible ip addresses, so if your ip is bigger than 192.168.9.99, it won't work and you must manually change line 92 "Joycon Wiz Lights (global)" ¯\_(ツ)_/¯ sorry, not sorry
