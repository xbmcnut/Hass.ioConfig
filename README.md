# xbmcnut's Home Assistant configuration
### For now, until I can figure out how to get my entire config into Github safely and securely, some of my config files can be accessed through my [Wiki](https://github.com/xbmcnut/Hass.ioConfig/wiki "Pete's Wiki") along with some tips and tricks. 
### Want to get more info?
### Hardware
My Home Assistant installation now resides on an Intel NUC i5 with 16GB RAM and a 256GB nVME SSD (overkill!). This is more reliable than using any device that leverages a SD Card (in my opinion). If you are using an SD card, I highly encourage as your very first integration to add the excellent [Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup "Hass.io Google Drive Backup Add-on") for your installation files and set this to backup every day.

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
* Dresden Conbee II Zigbee Gateway (currently running with deCONZ add-on)

#### Streaming
* 3 x Echo Dot  
* 2 x Google Home  
* 4 x Google Home Mini  
* 3 x Chromecast  
* 4 x Chromecast Audio
* 1 x Android TV with [PiPup](https://play.google.com/store/apps/details?id=nl.rogro82.pipup&hl=en) installed which allows HA to send it messages and other content

#### Network
* 1 x UniFi 24-port Gen2 PoE switch  
* 1 x UniFi 24-port switch  
* 1 x UniFi 8-port PoE switch  
* 1 x UniFi 8-port switch  
* 2 x UniFi AC-Lite AP  
* 1 x UniFi AC-Pro AP
* 1 x UniFi USG 
* 1 x Synology RS814+ NAS (Docker: MQTT, TasmoAdmin, UniFi Controller and AdGuard)
* 1 x rPi3 running a 2nd AdGuard server as a [Ubuntu Appliance](https://ubuntu.com/appliance/adguard). Also running a backup MQTT broker
### Integrations
* Alexa Media Player
* deCONZ
* Google Cast
* HACS
* HomeKit Bridge
* Logitech Harmony Hub
* Mobile App
* MQTT
* Samsung Smart TV
* Sony Bravia TV
* Sony Songpal
* Synology DSM
* Xiaomi Gateway (Aqara)
* Z-Wave
### Add-ons
* deCONZ
* Hass.io Google Drive Backup
* MariaDB
* phpMyAdmin
* Samba share
* TasmoBackup
* Terminal & SSH
### HACS
#### Frontend
* HACS
#### Integrations
* [Bar Card](https://github.com/custom-cards/bar-card)
* button-card
* Canvas Gauge Card
* card-mod
* card-tools
* Custom Header
* Flexible Horseshoe Card for Lovelace
* Mini Graph Card
* Search Card
