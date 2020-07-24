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
Necessary for the communication is an USB2serial converter (needed signals: 3.3 V, GND, RxD, TxD and __RTS__). The controller chip needs to be a [CP2102](https://www.silabs.com/documents/public/data-sheets/CP2102-9.pdf) w/ __RTS__ pin. The baud rate needs to be set to [960 baud](https://forum.fhem.de/index.php/topic,80916.msg729625.html#msg729625).

# Modification
The schematic and board files are compatible with EAGLE v6.x.

# Resources
* [WH-MDC05f3e5 documents](http://aquarea.smallsolutions.de/index.php?title=WH-MDC05f3e5#Links_zu_Original_Dokumenten)
* [WiFi module for WH-MDC05f3e5](https://www.haustechnikdialog.de/Forum/t/181931/Intensishome-Wifi-Modul-in-Kombination-mit-der-Panasonic-WH-MDC05F3E5-Geisha) and discussion in Haustechnik Forum
* [PCB hardware discussion](https://forum.fhem.de/index.php/topic,104628.msg985249.html#msg985249) in FHEM forum
* [setup of communcation PCB](https://forum.fhem.de/index.php/topic,80916.msg729625.html#msg729625) in FHEM forum
* [FHEM control](http://aquarea.smallsolutions.de/index.php?title=Steuerung_via_FHEM) in aquarea forum
* [FHEM module](https://github.com/der-lolo/aqaurea)
* for documentation purposes: [online check of MD files](https://dillinger.io/)
