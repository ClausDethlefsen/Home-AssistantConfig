   [![Build Status](https://travis-ci.com/ClausDethlefsen/Home-AssistantConfig.svg?branch=master)](https://travis-ci.com/ClausDethlefsen/Home-AssistantConfig)
<a href="https://github.com/ClausDethlefsen/Home-AssistantConfig/commits/master"><img src="https://img.shields.io/github/last-commit/ClausDethlefsen/Home-AssistantConfig.svg?style=plasticr"/></a>
<a href="https://github.com/ClausDethlefsen/Home-AssistantConfig/stargazers"><img src="https://img.shields.io/github/stars/ClausDethlefsen/Home-AssistantConfig.svg?style=plasticr"/></a>
<!-- ![ha-version-shield] ![maintained] -->


# Home automation

After upgrading to 0.107.1, some picture-entity cards [broke](https://github.com/home-assistant/frontend/issues/4984). Clearing cache in the browser and updating the HACS modules made them work again. 

**Devices I'm using:**
* Homeassistant Version 0.107.1 runs on a Mac Mini (2011'ish) running MacOs High Sierra
  + Installed [Python version 3.8.1](https://www.python.org/downloads/mac-osx/)
  + Followed the instructions to [install HomeAssistant on MacOs](https://www.home-assistant.io/docs/installation/macos/)
  + To upgrade HomeAssistant, I follow [these instructions](https://www.home-assistant.io/docs/installation/virtualenv/#upgrading-home-assistant)
* Installed HACS and integrations
* Created accounts for each family member so they have their personal layout of Lovelace.
* using Duckdns with dehydrated using [these instructions](https://www.splitbrain.org/blog/2017-08/10-homeassistant_duckdns_letsencrypt). I have fixed IP address and have forwarded port 8123, 80 and 443 in my router. I guess it would be wise to study [this description](https://community.home-assistant.io/t/duckdns-its-not-just-me-its-you/131586).
* Philips Hue - several bulps and a smart plug
* Sonos - several Play:1, Play:5, Connect, Connect:amp. A sonos One with Google assistant
* Using [Hue Dimmer for controlling Sonos](https://github.com/ClausDethlefsen/Home-AssistantConfig/blob/master/include/automations/anne.yaml) based on the [Hue remote](https://github.com/robmarkcole/Hue-remotes-HASS) add-on.
* [Sonoff Basic - not flashed](https://www.youtube.com/watch?v=DsTqOlrQQ1k)
* Denon AVR receiver and made and automation that switches the receiver on/off when Sonos plays
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

<a href="https://www.buymeacoffee.com/Bwl9psu" target="_blank">Buy me a coffe, </a>if you like.

