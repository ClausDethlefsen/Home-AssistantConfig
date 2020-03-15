[![Build Status](https://travis-ci.com/ClausDethlefsen/Home-AssistantConfig.svg?branch=master)](https://travis-ci.com/ClausDethlefsen/Home-AssistantConfig)
<a href="https://github.com/ClausDethlefsen/Home-AssistantConfig/commits/master"><img src="https://img.shields.io/github/last-commit/ClausDethlefsen/Home-AssistantConfig.svg?style=plasticr"/></a>
<style>.bmc-button img{height: 34px !important;width: 35px !important;margin-bottom: 1px !important;box-shadow: none !important;border: none !important;vertical-align: middle !important;}.bmc-button{padding: 7px 10px 7px 10px !important;line-height: 35px !important;height:51px !important;min-width:217px !important;text-decoration: none !important;display:inline-flex !important;color:#FFFFFF !important;background-color:#FF813F !important;border-radius: 5px !important;border: 1px solid transparent !important;padding: 7px 10px 7px 10px !important;font-size: 22px !important;letter-spacing: 0.6px !important;box-shadow: 0px 1px 2px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;margin: 0 auto !important;font-family:'Cookie', cursive !important;-webkit-box-sizing: border-box !important;box-sizing: border-box !important;-o-transition: 0.3s all linear !important;-webkit-transition: 0.3s all linear !important;-moz-transition: 0.3s all linear !important;-ms-transition: 0.3s all linear !important;transition: 0.3s all linear !important;}.bmc-button:hover, .bmc-button:active, .bmc-button:focus {-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;text-decoration: none !important;box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;opacity: 0.85 !important;color:#FFFFFF !important;}</style><link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/Bwl9psu"><img src="https://cdn.buymeacoffee.com/buttons/bmc-new-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:15px;font-size:28px !important;">Buy me a coffee</span></a>


# Home automation

**Devices I'm using:**
* Homeassistant Version 0.106.6 runs on a Mac Mini (2011'ish) running MacOs High Sierra
  + Installed [Python version 3.8.1](https://www.python.org/downloads/mac-osx/)
  + Followed the instructions to [install HomeAssistant on MacOs](https://www.home-assistant.io/docs/installation/macos/)
  + To upgrade HomeAssistant, I follow [these instructions](https://www.home-assistant.io/docs/installation/virtualenv/#upgrading-home-assistant)
* using Duckdns with dehydrated using [these instructions](https://www.splitbrain.org/blog/2017-08/10-homeassistant_duckdns_letsencrypt). I have fixed IP address and have forwarded port 8123, 80 and 443 in my router. I guess it would be wise to study [this description](https://community.home-assistant.io/t/duckdns-its-not-just-me-its-you/131586).
* Philips Hue - several bulps and a smart plug
* Sonos - several Play:1, Play:5, Connect, Connect:amp. A sonos One with Google assistant
* Using [Hue Dimmer for controlling Sonos](https://github.com/ClausDethlefsen/Home-AssistantConfig/blob/master/include/automations/anne.yaml)
* [Sonoff Basic - not flashed](https://www.youtube.com/watch?v=DsTqOlrQQ1k)
* Denon AVR receiver
* Some Samsung TVs
* Netatmo weather station with some extra indoor modules and the rain module
* Gogogate2 for the garage cover
* A number of iphones
* Tile
* synology NAS
* Apple TV4
* Hunter-Douglas curtains (currently [not working](https://github.com/home-assistant/core/issues/32324))
* Foscam camera
* Plex
* A nice [mini-media-player](mini-media-player) for controlling Sonos

## screenshots
![Main window](screenshots/main.jpg)
![Player](screenshots/player.jpg)



