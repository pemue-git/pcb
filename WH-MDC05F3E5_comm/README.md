# Communication PCB for a Panasonic heat pump
Communication PCB for a Panasonic [WH-MDC05f3e5](http://aquarea.smallsolutions.de/index.php?title=WH-MDC05f3e5) heat pump also called "Geisha". This PCB is based on a schematic posted [here](https://forum.fhem.de/index.php/topic,80916.msg879068.html#msg879068).

# Changelog

* v2.0 (throughole version)
  * based on this [schematic](https://forum.fhem.de/index.php/topic,80916.msg879068.html#msg879068)
  * added static signal on unused gates
  * schematic
    ![picture](pic/WH-MDC05F3E5_comm_v2.0_sch.jpg)

* v3.0 (SMD version)
  * all parts changed to SMD
  * layout top
  
    ![picture](pic/WH-MDC05F3E5_comm_v3.0_top.png)
  * layout bottom
  
    ![picture](pic/WH-MDC05F3E5_comm_v3.0_bot.png)
  * assembled PCB and USB2serial converter
    ![picture](pic/WH-MDC05F3E5_comm_v3.0-pic01.jpg)
  * [schematic](WH-MDC05F3E5_comm_v3.0_sch.pdf)
  * [gerber files](gerber/WH-MDC05F3E5_comm_v3.0_gerber.zip)
    

# Assembly
Necessary for the communication is an USB2serial converter (needed signals: 3.3 V, GND, RxD, TxD and __RTS__). The baud rate needs to be set to [960 baud](https://forum.fhem.de/index.php/topic,104628.msg989942.html#msg989942).

# Modification
The schematic and board files are compatible with EAGLE v6.x.

# Resources
* [WH-MDC05f3e5 documents](http://aquarea.smallsolutions.de/index.php?title=WH-MDC05f3e5#Links_zu_Original_Dokumenten)
* [discussion in FHEM forum](https://forum.fhem.de/index.php/topic,104628.msg985249.html#msg985249)
* for documentation purposes: [online check of MD files](https://dillinger.io/)