# MarlinConfig

Some Marlin firmware configurations



# ChironMods contains configurations for Anycubic 3D printer

For now based on 2.0.7.2


## ChironMods/stock

Official Anycubic Chiron configurations file for reference


## ChironMods/BLTouch

Modification for supporting BLTouch.

Tested with the antclabs bltouch v3

BLtouch is connected on servo 0 and on the extruder head pin-out (the ones used with original sensor).

It needs some adjustement such as activating HighSpeed option and reduce the probing delay.

## ChironMods/BLTouch_TMC2209

Modification for supporting BLTouch plus TMC2209.

Tested with the BIGTREETECH TMC2209 V1.2.

I will put the VRef here once the printer is re-assembled :)


## ChironMods/BLTouch_TMC2209_Laser

Modification for supporting BLTouch plus TMC2209 plus a Laser cutter/engraver.

In progress fully untested, it just compiles and I have soldered the pin out on servos 1,2 and 3.

