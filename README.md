# smartthings-code

Based upon the work by Anders Sveen (https://github.com/anderssv/smartthings-code) with increased functionality.

# Known Issues
Together with webcore, temperature and humidity data does not behave as expected. 25,6 turns in to 256 for example not sure how to fix yet. Otherwise it works.

# SmartApps

## Verisure integration

- [SmartApp](smartapps/orecus/verisure.src/verisure.groovy)
- [Verisure Alarm](devicetypes/orecus/verisure-alarm.src/verisure-alarm.groovy)
- [Verisure Sensor](devicetypes/orecus/verisure-sensor.src/verisure-sensor.groovy)

This SmartApp polls the Verisure alarm at given intervals to update it's state, together with climate data.

You'll also need to install both custom device handlers to use this smartapp.

NOTE: If the app fails on installation the error is probably in your username/password. Make sure they are correct
and try again.

# Device Handlers

## Verisure Alarm
- Displays Alarm State
- Displays State Change Timestamp
- Displays State Change By

## Verisure Sensor
- Displays Temperature
- Displays Humidity
- Displays Type
- Displays Timestamp