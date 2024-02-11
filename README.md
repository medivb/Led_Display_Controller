# Led_Display_Controller
<i>A 16x16 LED matrix controller using an ESP8266 in ESPHome</i>

A little while ago I stumbled across a 16x16 LED (16cm x 16cm) panel on Temu. It had a WS2812B controller embedded (which turned out to be supported by ESPHome) and was cheap, so I simply could not ignore it. This repo is for all you out there who want to either have a laugh or maybe get some useful out of it. I had a great time setting this up.

<b>Shopping list:</b><br>
<ul>
<li>Display: https://share.temu.com/Dk74zsn6iAA</li>
<li>Controller: ESP8266 (esp01_1m, but any other type would have worked as well)</li>
<li>Frame: Ikea picture frame</li>
<li>Power supply: https://share.temo.com/1DY5w7jjBWA (24/12V to 5V-5A)</li>
<li>Power source: Old laptop PSU (18V)</li>
</ul>
The display can consume quite some power, which is why I went a little overboard on that. This setup works great and as it turns out, I am only using 25% brightness, so that reduces the max power consumption a lot.<br>
<br>
I added my yaml which contains a lot of comments and is therefore pretty self explanatory.<br>
<br>
Some pictures of the final result:<br>
![Endresult_2](https://github.com/medivb/Led_Display_Controller/assets/69627753/5292b63d-db01-4580-b2f6-5d81bdd75a1e)<br>
![Endresult_1](https://github.com/medivb/Led_Display_Controller/assets/69627753/e019a00e-dc2d-4148-b4fb-d1151258523a)

