# Sovol-SV08-max</br>
These are the config files from my Sovol SV08max.</br>
The original from Sovol (dated 15.08.2025) can be found in the second branch (original)</br>
I mainly rearange and divide the .cfg files to my standard.</br>
I de-installed Obico with kiauh even though kiauh is fuc*** on SOVOL machines</br>
I updated the system via kiauh</br>
I installed reshelper to easier handling input shaper with automatic generation the png pictures</br>
Take care for the folders. reshelper use the "update" folder from Sovol. I deletet it and then installation is okay. PNG will be in home/sovol/klipper/config/RES_DATA </br>
Print start and end gcode is newly written. Moved the procedure from Orcaslicer to Klipper.</br>
Changed the speed and accel for the buffer, because my one was eating filament a little and made a strange sound. Printed up to 30mm³/s without any problem</br>
Added a heat soak time (one for PLA another one other mateiral)</br>
Printer is standard and uses a 0.6mm nozzle (if you use 0.4mm change it in printer.cfg)</br>
ORCA MACHINE START G-CODE:</br>
M104 S0</br>
M140 S0</br>
START_PRINT EXTRUDER=[nozzle_temperature_initial_layer] BED=[bed_temperature_initial_layer_single] MATERIAL=[filament_type] VENDOR=[filament_vendor] CHAMBER_TEMP=[chamber_temperature] TOOL={initial_tool}</br>
</br>
ORCA MACHINE END G-CODE:</br>
END_PRINT</br>
</br>
Have fun :-)</br>
</br>
## 15.08.2025</br>
multiple_fan part cooler added</br>
tacometer pin for fan2 and 3 added (yet not tested)</br>
cooling fan for ssr changed to controller fan</br>
max_accel reduced to 5500</br>
    (make sure to change it in your slicer settings for printer and print profile)</br>
max_cruise_ratio upped to 0.35</br>
</br>
## 16.08.2025</br>
reduced homing speed from 100 to 75 for X and Y</br>
max_accel up to 25000, because it doesn't matter if you're not printing.</br>
</br>
</br>
</br>
## LOT OF UPDATES:</br>
https://github.com/3DPrintDemon/Demon_Klipper_Essentials_Unified/blob/a77fac0396def972f6b2f291deeeff3f3a48ec80/Documentation/INSTALL_INSTRUCTIONS/SOVOL_SV08_MAX_SETUP/SV08_MAX_EXTRA_INSTRUCTIONS.md</br>

