# CryptoMoneyTicker v1.1

![Demo_CrytptoMoneyTicker](https://github.com/mnett0/CryptoMoneyTicker/blob/master/medias/cryptoticker.gif)

## Update v1.1

Now you can follow 5 crypto-currencies of your choice but without logo, you can always add it. (They are already available for Bitcoin, Ethereum, Ripple, Litecoin and Cardano)

## Description

This a small screen for your desktrop or somewhere else, it allows to follow 5 of your favorites crypto-currencies.

Data are collected via the API of the site [CoinMarketCap](https://coinmarketcap.com) and are updated every 5 minutes.

The display changes of crypto-currencies every minute. You can change this delay but do not exceed 10 updates per minute.

### Materials

* ESP32
* LCD TFT ILI9341 2.2"

![Diagram_CryptoMoneyTicker](https://github.com/mnett0/CryptoMoneyTicker/blob/master/medias/Schema_Cryptho_Ticker.jpg)

### Library required

* [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
* [WiFi](https://github.com/espressif/arduino-esp32/tree/master/libraries/WiFi)
* [WiFiClientSecure](https://github.com/espressif/arduino-esp32/tree/master/libraries/WiFiClientSecure)
* [SPI](https://github.com/espressif/arduino-esp32/tree/master/libraries/SPI)
* [Adafruit-GFX](https://github.com/adafruit/Adafruit-GFX-Library)
* [Adafruit-ILI9341](https://github.com/adafruit/Adafruit_ILI9341)
* [TimeLib](https://github.com/PaulStoffregen/Time)

### To begin

* Enter the IDs of your WiFi :

      47  const char* ssid = "yourSSID";
      48  const char* password = "yourPASSWORD";

* Enter the 5 crypto-currencies of your choice:

![Demo_cryptoname](https://github.com/mnett0/CryptoMoneyTicker/blob/master/medias/cryptoname.gif)

Then take the name from the link as shown above and insert it between " " in the code.

    72  String crypto[] = {"bitcoin", "ethereum", "ripple", "litecoin", "cardano"};

* Choose the screen change interval *(do not exceed 10 changes/minute)*

      141  interval = yourInterval; // in milliseconds

That's it, enjoy! :relaxed:

### License

[MIT](https://github.com/mnett0/CryptoMoneyTicker/blob/master/LICENSE.md)
