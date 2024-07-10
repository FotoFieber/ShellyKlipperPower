# ShellyKlipperPower
secure power off your klipper printer

Design goals:
* don't use external scripting/home automation: all processing on the Shelly

Hardware:
* Shelly 1 pm
* Shelly Addon
* Temperature sensor(s)
* Wires/Wago to install the Shelly 1 (see picture)

![Installation on my Sovol SV 08](https://github.com/FotoFieber/ShellyKlipperPower/blob/main/shelly_sv08.jpg?raw=true)

WIth the two scripts you find in this repo installed on the Shelly
* power off the printer, when temperature sensor measures above 65 degree celsius
* remote power on or off the printer
* power off printer, 5 minutes after it is shutdown (no moonraker contact possible)
* measure power consumption
