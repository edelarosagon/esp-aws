### How to get started on AWS IoT with NodeMCU for less than 5 euros

* Download [NodeMCU Driver](https://www.dropbox.com/sh/nqh9yqm9pd9hgg6/AAD0_wmnLMD3OxDO3TCsj4PLa?dl=0) CH341SER_*yourOS* and install it

* If you want to play around with LUA, download [ESPlorer](http://esp8266.ru/esplorer/)

* Download [Arduino IDE](https://www.arduino.cc/en/Main/Software)

* Configure your Arduino IDE to support ESP8266

>
File>Preference and copy the URL below to Additional Board Manager URLs
 http://arduino.esp8266.com/stable/package_esp8266com_index.json

> Go to Tools > Boards > Board Manager. Look for esp8266 and hit install.
> Select NodeMCU 1.0 (ESP-12E Module)

* Install [AWS SDK](https://www.dropbox.com/sh/nqh9yqm9pd9hgg6/AAD0_wmnLMD3OxDO3TCsj4PLa?dl=0) as a Arduino Library

* Install your sensor library if any (in our case DHT22)

* Download aws-esp-ino.zip and unzip it to your Arduino folder

* Log in to your AWS Account and add a Thing. Call your thing ESPNODE

* Edit keys.cpp and fill in your AWS Account and WIFI settings
