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

![MIT](https://github.com/mnett0/CryptoMoneyTicker/blob/master/LICENSE.md)
