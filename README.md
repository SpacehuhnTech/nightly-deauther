# Nightly ESP8266 Deauther Builds

![Build V3](https://github.com/SpacehuhnTech/nightly-deauther/workflows/Build%20V3/badge.svg)

[**Click here to download the latest .bin file**](https://github.com/SpacehuhnTech/nightly-deauther/releases/download/Nightly-V3/esp8266_deauther_V3_1M_Nightly.bin)

**Please note:**   
* They are compiled using the default settings for an ESP8266 with 1MB flash.  
* Only compiles only for [ESP8266 Deauther Version 3](https://github.com/SpacehuhnTech/esp8266_deauther/tree/v3).  
* These builds are run after each commit, but overwrite existing builds from the same day.  

## Installation

1. Download latest compiled .bin file from [nightly-deauther/releases](https://github.com/SpacehuhnTech/nightly-deauther/releases)
2. Install [esptool](https://github.com/espressif/esptool/)
3. Connect your ESP8266
4. Flash it by running `esptool.py -p <PORT> -b 115200 write_flash 0 <BIN_FILE>`.  
   Be sure to replace `<PORT>` with the serial port  
   and `<BIN_FILE>` with the path of the previously download .bin file.
