---
layout: post
title: Lumen LED Keychain
description:  Keychain with a LED matrix.
skills: 
  - PCB Design
  - EasyEDA
  - I2C
  - Small Package Soldering (0603, 0402...)
  - Drones
  - Charlieplexing


main-image: /LumenBanner.png
---

---
{% include image-gallery.html images="LumenGIF.gif" height="800" %} 

This project was submited as the final project for the Electronic Circuit Design And Manufacturing Bootcamp. I tried to challenge myself by designing with having production in mind, So I foucsed on three main criteria: to be Cost Effective, Have a Small Package and Power Efficiency. I have utilized the ATTiny1616 for it's power efficiency and cost with more than enough memory (Could have even went with the ATTiny85 but wanted to play it safe). I also took advantage of Charlieplexing which cut the number traces and pins to insure smaller package. With usilizing the ATTiny sleep mode with using the interrupt signal from the accelerometer to wake-up the MCU to insure power efficiency.

# Status
(Complete)\
The first version is done, with the second version in-progress.
# Specs
  • ATTINY1616 Microcontroller\
  • IS31FL3731 Charlieplex LED Driver\
  • MCP73832T Battery Charger\
  • LIS2DW12TR Accelerometer

## Schematics
{% include image-gallery.html images="Schematic.png" height="800" %} 
<br />
<br />
## Layout
{% include image-gallery.html images="Layout.png" height="800" %} 
<br />
<br />
# Files
Files will be included later after some light modifcations.



