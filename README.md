# Nightly ESP8266 Deauther Builds

[**Download latest Deauther V2.5 .bin**](https://github.com/SpacehuhnTech/nightly-deauther/releases/download/nightly/esp8266_deauther_V2.5_1M_Nightly.bin)

[**Download latest Deauther V3 .bin**](https://github.com/SpacehuhnTech/nightly-deauther/releases/download/nightly/esp8266_deauther_V3_1M_Nightly.bin)

**Please note:**   
* They are compiled using the default settings for an ESP8266 with 1MB flash.  
* Compiles only for [ESP8266 Deauther Version 3](https://github.com/SpacehuhnTech/esp8266_deauther/tree/v3).  
* Cuilds are triggered after each push and overwrite existing builds.  

## Installation

1. Download latest compiled .bin file from [nightly-deauther/releases](https://github.com/SpacehuhnTech/nightly-deauther/releases)
2. Install [esptool](https://github.com/espressif/esptool/)
3. Connect your ESP8266
4. Flash it by running `esptool.py -p <PORT> -b 115200 write_flash 0 <BIN_FILE>`.  
   Be sure to replace `<PORT>` with the serial port  
   and `<BIN_FILE>` with the path of the previously download .bin file.
