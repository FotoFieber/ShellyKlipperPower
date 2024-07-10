# ShellyKlipperPower
secure power off your klipper printer

Design goals:
* don't use external scripting/home automation: all processing on the Shelly

WIth the two scripts you find in this repo, a shell1 1 pm can
* power off the printer, when temperature sensor measures above 65 degree celsius
* remote power on or off the printer
* power off printer, 5 minutes after it is shutdown (no moonraker contact possible)
