# jaguarcartreader

Modification of GrumpyGopher's modification of @sakman55's Standalone Atari Jaguar Cart Reader <br/>
Adds support for dumping ROMs 6MB in size.<br/>

Text from GrumpyGopher's fork retained below for reference.<br/>

Modification of @sakman55 Standalone Atari Jaguar Cart Reader<br/>
Adds support for renaming game automatically when reading rom.<br/>

If match is found screen will display game name otherwise no match found will be displayed.<br/>

Programmed with Arduino IDE 1.8.19 and the following libraries:<br/>
SdFat 1.1.4<br/>
SPI 1.0<br/>
Adafruit_GFX_Library 1.2.7<br/>
Adafruit_SSD1306 2.5.10 
* **Note:** by default the Adafruit_SSD1306 sets the lcd height to 32 instead of 64. You will need to edit Adafruit_SSD1306.h and comment out this line:<br/>
* #define SSD1306_128_32<br/>
* and then uncomment out this line:<br/>
* //#define SSD1306_128_64<br/>

Testing was only done with Read Rom functionality<br/>

File Jag.txt needs to be copied to the root of the SD card<br/>

