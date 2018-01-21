# CryptoMoneyTicker v1

![Demo_CrytptoMoneyTicker](https://media.giphy.com/media/3ohc15P4FztPVI5GM0/giphy.gif)

## Description

This a small screen for your desktrop or somewhere else, it allows to follow 5 of your favorites crypto-currencies.

Actually, the crypto-currencies "supported" by the program are : Bitcoin, Ethereum, Ripple, Litecoin and Cardano (more coming soon).

Data are collected via the API of the site [CoinMarketCap](https://coinmarketcap.com) and are updated every 5 minutes.

The display changes of crypto-currencies every minute. You can change this delay but do not exceed 10 updates per minute.

      122   interval = yourInterval; // in milliseconds

Updates coming soon

### Materials

* ESP32
* LCD TFT ILI9341 2.2"

![Diagram_CryptoMoneyTicker](https://i.imgur.com/Vytu6ym.jpg)

### Library required

* [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
* [WiFi](https://github.com/espressif/arduino-esp32/tree/master/libraries/WiFi)
* [WiFiClientSecure](https://github.com/espressif/arduino-esp32/tree/master/libraries/WiFiClientSecure)
* [SPI](https://github.com/espressif/arduino-esp32/tree/master/libraries/SPI)
* [Adafruit-GFX](https://github.com/adafruit/Adafruit-GFX-Library)
* [Adafruit-ILI9341](https://github.com/adafruit/Adafruit_ILI9341)
* [TimeLib](https://github.com/PaulStoffregen/Time)

### To begin

Enter the IDs of your WiFi :

    35   const char* ssid = "yourSSID";
    36   const char* password = "yourPASSWORD";

That's it, enjoy! :relaxed:

### License

The MIT License (MIT)

Copyright © 2018 Médéric NETTO

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
