# OctoPrint-Striplight

This plugin interfaces LEDs controlled by either GPIO or SPI using the FastLED library.
The LEDs are intended to be connected to the Raspi or machine running octoprint.

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/plasmarobo/OctoPrint-Striplight/archive/master.zip

**TODO:** Describe how to install your plugin, if more needs to be done than just installing it via pip or through
the plugin manager.

## Configuration

Be sure to define your LED type (APA102, WS2812, LPD8806, AnalogRGB, etc) as well as the hardware interfaces or pins in use
