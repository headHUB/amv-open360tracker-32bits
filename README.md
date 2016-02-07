# amv-open360tracker-32bits 

This is the 32 bits versión of the "continuous 360 degree rotating antenna tracker system" for FPV. This proyect has been developed and maintained by users of the [FPV spanish community](http://www.aeromodelismovirtual.com/showthread.php?t=34530).

Please, we encourage you to read all the documentation before using this firmware in your devices, otherwhise they could be dammaged. In the wiki you'll find detailled information about how to install and configure it with success.

## Plataforma Hardware

This firmware has been developed for controllers based on STM32F series microprocessors, which fit the technical specifications of the popular NAZE32 flight controller. By now, it has been tested on the **Flip32** flight controller which incorporates the magnetometer, but it could work on other NAZE32 based boards like with external magnetometer.

# Features

This firmware provides an **all in one anntena tracker controller system**, this means that it is able to work with several telemetry protocols without the the need of compile and upload the firmware to the board each time you want to change from one to another.

And not only that, it...

En estos momentos los protocolos de telemetría implementados son:

- **MFD** 
- **GPS TELEMETRY (direct NMEA from GPS)**
- **MAVLINK**
- **RVOSD**
- **FRSKY D**
- **LTM**

El resto de protocolos soportados en la versión 8 bits están en fase de integración en esta nueva versión de 32bits.

# Protocolos de telemetría de salida soportados

En estos momentos los protocolos de telemetría implementados son:

- **MAVLINK** 
- **MFD**
- **FRSKY D**
- **FRSKY X (Smartport)**
- **HOTT**
- **LTM**



