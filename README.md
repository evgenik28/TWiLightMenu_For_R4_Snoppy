# TWiLightMenu for R4 Snoppy Plus

![Status](https://img.shields.io/badge/status-custom%20firmware-blue)
![Platform](https://img.shields.io/badge/platform-Nintendo%20DS-lightgrey)
![PICO](https://img.shields.io/badge/hardware-Raspberry%20Pi%20Pico-green)
![TWiLightMenu](https://img.shields.io/badge/TWiLightMenu-supported-purple)

## Overview

This project provides a custom firmware solution for the **R4 Snoppy
Plus** cartridge, which is normally unsupported by standard flashing
utilities.\
The original flash method is non-functional, so this firmware leverages
a **Raspberry Pi Pico** combined with **TWiLight Menu++** to deliver
full compatibility.

## Key Features

-   Fully operational custom firmware for an otherwise unsupported
    cartridge.
-   Bootloader reconstruction using Raspberry Pi Pico.
-   Direct support for TWiLightMenu.
-   Designed for reliability and ease of flashing.

## Requirements

-   R4 Snoppy Plus cartridge\
-   Raspberry Pi Pico (any model supporting USB flashing)\
-   Precompiled firmware files\
-   TWiLightMenu files

## Installation

1.  Flash the provided UF2 file to your Raspberry Pi Pico by dragging it
    into the PICO USB storage device.
2.  Connect the Pico to your R4 Snoppy Plus following the pinout
    instructions.
3.  Run the flashing script (included in this repository).
4.  Copy TWiLightMenu files to your microSD card.
5.  Boot and enjoy full functionality on an unsupported card.

## Notes

This firmware is specifically created **because the original flashing
mechanism does not work** on the R4 Snoppy Plus.\
It provides a reliable alternative path to run TWiLightMenu.

## Disclaimer

This project is provided without warranty. Use at your own risk.

------------------------------------------------------------------------

## Buttons & Visual Elements

[![Download
Firmware](https://img.shields.io/badge/Download-Firmware-orange)](#)\
[![Open Documentation](https://img.shields.io/badge/Docs-Open-blue)](#)\
[![Support Project](https://img.shields.io/badge/Support-Donate-red)](#)
