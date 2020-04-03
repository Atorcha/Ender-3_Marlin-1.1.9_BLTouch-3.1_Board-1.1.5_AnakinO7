Ender-3-marlin-abl-firmware-1.1.9-AnakinO7
=========================

necesidades:
BLTOUCH
SD Support
placa 1.1.5
Sin menu bed level
Sin bootscreen

Feature Changes
=========================

enabled AUTO_BED_LEVELING_BILINEAR</br>
enabled FIX_MOUNTED_PROBE</br>
enabled Z_SAFE_HOMING</br>
change drivers to TMC2208_STANDALONE</br>
change to X_PROBE_OFFSET_FROM_EXTRUDER -42</br>
change to Y_PROBE_OFFSET_FROM_EXTRUDER -5</br>
change HOMING_FEEDRATE_XY (60*70)

<h3>Memory Saving Options</h3></br>
disable BOOTSCREEN</br>
enabled DISABLE_M503</br>
disabled SPEAKER</br>
disabled ARC_SUPPORT</br>
disabled EEPROM_CHITCHAT</br></br>
enable AUTO_BED_LEVELING_LINEAR</br>
enable PRINTCOUNTER SUBE AL 99%</br>
enable #define SLIM_LCD_MENUS</br>
enable "BABYSTEPPING" in Configuration_adv.h</br>
enable "BABYSTEP_ZPROBE_OFFSET" in Configuration_adv.h</br>
enable "BABYSTEP_ZPROBE_GFX_OVERLAY" in Configuration_adv.h</br>
disable PID_AUTOTUNE_MENU</br>

<h3>Pruebo</h3>

<b>Flash Memory Usage:</b> 98% (128438 bytes)</br>
<b>Variable Memory Usage:</b> 29% (4.79 Kb)</br>

ABL Probe Configurations
=========================

X_PROBE_OFFSET_FROM_EXTRUDER -40</br>
Y_PROBE_OFFSET_FROM_EXTRUDER -10</br>
Z_PROBE_OFFSET_FROM_EXTRUDER 2</br>

LEFT_PROBE_BED_POSITION 10</br>
RIGHT_PROBE_BED_POSITION 170</br>
FRONT_PROBE_BED_POSITION 30</br>
BACK_PROBE_BED_POSITION 190</br>

Z_MIN_ENDSTOP_INVERTING true</br>
Z_MIN_PROBE_ENDSTOP_INVERTING true</br>
