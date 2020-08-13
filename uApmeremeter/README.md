# µAmperemeter
This project summarizes the work from [here](https://www.openhardware.io/view/380/Micro-nano-ampere-meter-double) and [here](https://www.thingiverse.com/thing:3641379).
The discussion about this project os done in [FHEM forum](https://forum.fhem.de/index.php/topic,104466.0.html).

# Changelog

* v1.0 (initial version)
  * implementation of the µAmperemeter with the red HX711 board
  * solder jumper for OLED display (because they have different pinouts)
  * __CAUTION:__ OLED display should have a level shifter for SCL and SDA lines!
  * connections: __OUT+__: channel 1 (+), __A-__: channel 2 (+), __C1__, __C2__: GND; __T1__, __T2__: button

  * [gerber files](uAMP_v1.0_gerber/uAMP_v1.0_gerber.zip)
  * [schematic](uAMP_v1.0_sch.pdf)
  * [bill of materials](uAMP_v1.0.xls)
 

* v1.1 (SMD version)
  * green HX711 board added (either red or green HX711 board can be used)
  * change resistors to SMD only (remove through hole resistors)
  * level shifter for OLED display added
  * connections: __OUT+__: channel 1 (+), __A-__: channel 2 (+), __C1__, __C2__: GND; __T1__, __T2__: button; __T3__, __T4__: reset,

  * [gerber files](uAMP_v1.1_gerber/uAMP_v1.1_gerber.zip)
  * [schematic](uAMP_v1.1_sch.pdf)
  * [bill of materials](uAMP_v1.1.xls)

# Modification
The schematic and board files are compatible with EAGLE v4.x.

# Resources
* First project idea on [openhardware](https://www.openhardware.io/view/380/Micro-nano-ampere-meter-double)
* Refinement and case on [thingiverse](https://www.thingiverse.com/thing:3641379)
* Discussion in [FHEM forum](https://forum.fhem.de/index.php/topic,104628.msg985249.html#msg985249)
* for documentation purposes: [online check of MD files](https://dillinger.io/)
