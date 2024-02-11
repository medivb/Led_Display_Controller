# Led_Display_Controller
A 16x16 LED matrix controller using an ESP8266 in ESPHome

A little while ago I stumbled across a 16x16 LED (16cm x 16cm) panel on Temu. It has a WS2812B controller embedded (which turned out to be supported by ESPHome) and was cheap, so I could not ignore it. This repo is for all you out there who want to either have a laugh or maybe get some useful out of it. I had a great time setting this up.

Shopping list:

Display: https://share.temu.com/Dk74zsn6iAA
Controller: ESP8266 (esp01_1m)
Frame: Ikea picture frame
Power supply: https://share.temo.com/1DY5w7jjBWA (24/12V to 5V-5A)
Power source: Old laptop PSU (18V)

The display can consume quite some power, which is why I went a little overboard on that. This setup works great and as it turns out, I am only using 25% brightness, so that reduces the max power consumption a lot.

I added my yaml which contains a lot of comments and is therefore pretty self explanatory.
