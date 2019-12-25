## Overview

This project is a fork from the original [spacehuhn/esp8266_deauther](https://github.com/spacehuhn/esp8266_deauther). The goal of this fork is being lighter and simpler. 

## What is different

The following modules were removed from the original project:

- Web interface with all the code
- Wifi module (pwned)

Compared compiled sizes

- Original  Sketch uses 703380 bytes (67%) of program storage space. Maximum is 1044464 bytes
- Lite:     Sketch uses 568804 bytes (54%) of program storage space. Maximum is 1044464 bytes

## How does it work?

The basic method of interaction is the serial interface.

## Future development

- Keep the core funcionality up to date with upstream
- Simplify and extend the serial interface.
