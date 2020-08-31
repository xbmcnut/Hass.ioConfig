# xbmcnut's Home Assistant configuration
For now, until I can figure out how to get my entire config into Github safely and securely, my config files can be accessed through my [Wiki](https://github.com/xbmcnut/Hass.ioConfig/wiki "Pete's Wiki") along with some tips and tricks. 
### Want to get more info?
### Hardware
My Home Assistant installation now resides on an Intel NUC i5 with 16GB RAM and a 256GB nVME SSD (overkill!). This is more reliable than using any device that leverages an SD Card. If you are using an SD card, I highly encourage as your very first integration to add the excellent [Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup "Hass.io Google Drive Backup Add-on") for your installation files and set this to backup every day.

My [MQTT Broker](https://hub.docker.com/_/eclipse-mosquitto) is running on my Synology NAS in a docker container along with a few other IoT components.
#### Gadgets
* Shelly1, Shelly PM1, Shelly 2.5, Shelly Dimmer, ShellyEM, Shelly Door/Window sensor (x1)
* Sonoff, Sonoff POW, Sonoff Dual, Sonoff Bridge, Sonoff SV all running Tasmota
* Xiaomi Temperature and Humidity Sensors
* Xiaomi Motion Detectors
* Xiaomi Door and Window Sensors (integrated into IP65 boxes)
* Xiaomi Gateway
* Xiaomi buttons (Gen1 and Gen2)
* Xiaomi wireless light switches
* Desden Conbee II Zigbee Gateway (currently running with deCONZ add-on)
### Integrations
### Docker Containers
### Add-ons
### HACS
