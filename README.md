# xbmcnut's Home Assistant configuration
### For now, until I can figure out how to get my entire config into Github safely and securely, some of my config files can be accessed through my [Wiki](https://github.com/xbmcnut/Hass.ioConfig/wiki "Pete's Wiki") along with some Home Assistant tips and tricks. 
### Want to get more info?
<a href="https://twitter.com/xbmcnut?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @xbmcnut</a> on Twitter or check out [xbmcnut on YouTube](https://www.youtube.com/petestothers).
### Hardware
My Home Assistant installation now resides on an Intel NUC i5 with 16GB RAM and a 256GB nVME SSD (overkill!). This is more reliable than using any device that leverages a SD Card (in my opinion). If you are using a SD card, I highly encourage as your very first integration to add the excellent [Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup "Hass.io Google Drive Backup Add-on") for your installation files and set this to backup every day.

My [MQTT Broker](https://hub.docker.com/_/eclipse-mosquitto) is running on my Synology NAS in a docker container along with a few other IoT components.
#### Gadgets
* 9 x Shelly1
* 5 x Shelly PM1
* 1 x Shelly 2.5
* 2 x Shelly Dimmer
* 2 x ShellyEM
* 1 x Shelly Door/Window sensor
* 4 x Sonoff
* 5 x Sonoff POW
* 1 x Sonoff Dual
* 1 x Sonoff TH10 with temp probe
* 1 x Sonoff RF Bridge (all running Tasmota)
* 4 x Xiaomi Temperature and Humidity Sensors
* 5 x Xiaomi Motion Detectors
* 6 x Xiaomi Door and Window Sensors (integrated into IP65 boxes)
* 6 x Xiaomi Zigbee Smart Plugs with power monitoring (Soldering iron, Espresso machine, TV Cabinet, Office power...)
* 1 x Xiaomi Gateway
* 3 x Xiaomi buttons (Gen1 and Gen2)
* 1 x Xiaomi wireless light switch
* 1 x [Dresden Conbee II Zigbee Gateway](https://amzn.to/3jAXMUV) (currently running with deCONZ add-on)
* 1 x [Aeon Labs Z-Wave stick](https://amzn.to/3bipmDp)
* 2 x [Aeon Labs MultiSensor 6](https://amzn.to/3hWqjEg)
* 5 x Z-Wave in-wall switch modules
* 1 x [Yale Security Assure Lock with Z-Wave](https://amzn.to/2YVRDe1)
* 1 x Harmony Hub
* 1 x Samsung Galaxy Tab A 10.1 running Fully Kiosk Browser. Video on that [**here**](https://www.youtube.com/watch?v=sv67ovOhjzQ).

#### Streaming
* 3 x Echo Dot  
* 3 x Google Home  
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
* [Alexa Media Player](https://github.com/custom-components/alexa_media_player)
* [Attributes](https://github.com/pilotak/homeassistant-attributes)
* [browser_mod](https://github.com/thomasloven/hass-browser_mod)
* [HACS](https://github.com/hacs/integration)
* [SmartIR](https://github.com/smartHomeHub/SmartIR)
#### Integrations
* [Bar Card](https://github.com/custom-cards/bar-card)
* [button-card](https://github.com/custom-cards/button-card)
* [Canvas Gauge Card](https://github.com/custom-cards/canvas-gauge-card)
* [card-mod](https://github.com/thomasloven/lovelace-card-mod)
* [card-tools](https://github.com/thomasloven/lovelace-card-tools)
* [Custom Header](https://github.com/maykar/custom-header) **Must have!**
* [Flexible Horseshoe Card for Lovelace](https://github.com/AmoebeLabs/flex-horseshoe-card)
* [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
* [Search Card](https://github.com/postlund/search-card)
