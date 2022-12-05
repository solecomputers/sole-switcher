# Sole Switcher

This repository contains the schematics and code for Sole Switcher, a pocket
device for tracking between two states without manufacturer-ascribed meaning.

Sole Switcher consists of a slide switch and an RGC LED.
One state of the switch corresponds to the blue color on the LED and the other
to the red color.
Every switch flip records an entry onto the internal memory with the date and
time of the flip as well as the state of the switch after the flip.

The RTC used to track the current date and time needs to be initialized prior
to the first use.

There will be an iOS companion app used to initialize the RTC as well as to
download the records off of the device into your phone.

This device is a WIP.

## Schematics & Code

The project is in an idea stage as of current.
I am prototyping the schematics and code on Wokwi.

https://wokwi.com/projects/350240282854294099

## To-Do

There are also to-do comments in the code on Wokwi.

### Look into radio-based RTC initialization

AFAIK it is possible to fetch the current date and time off the ambient radio
broadcast waves.
This would be a more user-friendly way to initialize the RTC than using the
companion app.
