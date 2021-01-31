# Archived

*This repo is qrchived since Home Assistant is moving to more UI setups and therefore I do not have the need to have a backup on github anymore.*

# This is my personal Home Assistant configuration with HASS.IO

[![Build Status](https://travis-ci.org/ajfriesen/home_assistant_configuration.svg?branch=master)](https://travis-ci.org/ajfriesen/home_assistant_configuration)

[![GitHub Activity][commits-shield]][commits]

[![GitHub Last Commit][last-commit-shield]][commits]

I am using Home Assistant with [HASS.IO](https://home-assistant.io/) on a HP ProLiant G7 MicroServer N54L.

## Screenshots

![alt text](screenshots/home_screen.png "Home Screen")

![alt text](screenshots/kitchen_timer.png "Kitchen Timer")

![alt text](screenshots/alarm_clock.png "Alarm Clock")

## Hardware

List of my current used hardware:

- Sonoff devices with [Tasmota Firmware](https://github.com/arendst/Sonoff-Tasmota)
  - 2 x [Sonoff S20](http://sonoff.itead.cc/en/products/residential/s20-socket)
  - 3 x [Sonoff POW](http://sonoff.itead.cc/en/products/sonoff/sonoff-pow)
    - Washing machine
    - TV
  - 6 x [Sonfoff Basics](http://sonoff.itead.cc/en/products/sonoff/sonoff-basic)
    - All 6 are used for lights
- Phillips Hue
  - 1 x Bridge
  - 2 x normal E27 bulps
- Fritz!Box 6490 cable
- Xiaomi vacuum (first generation)
- 3 x Google Chromecast Audio
- 3 x Google Home

## Features I use with Home Assistant

- Automaticly vacuum once a day and send a notification
- Alarm clock for turning on the lights in the morning
- Kitchen socket with timer function for the rice cooker
- Turn off all lights, when nobody is home
- Track location for me and my significant other via Owntracks
- Washing machine socket with voltage, current and wattage sensor
- Check regulary mails against [Have I been pwnd?](https://haveibeenpwned.com/)
- Check my internet provider with speedtest.net
- Google Assistant to control some switches, lights, etc.
- Use the the [HASS Configurator](https://home-assistant.io/addons/configurator/) Add-On for [HASS.IO](https://home-assistant.io/)
