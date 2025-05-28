
![a](https://github.com/user-attachments/assets/4e11c46b-b2b4-4505-91b3-af24706f13ca)

# Noisy-boy-esp32-Bluetooth-jammer
Bluetooth jammer using esp32 with webserver allow user to test nrf24

## Version Number: initial release 1.0

#  current version: 1.3

Click Webflasher to Flash code
[WEBFLASHER](https://smoochiee.github.io/Noisy-boy-esp32-Bluetooth-jammer/flash)


# READ THIS!!!!!!!READ THIS!!!!!!!

READ THIS!!!!!!!READ THIS!!!!!!!READ THIS!!!!!!!



# Note!!!If your having trouble with webflasher Or stuck on flashing!!!!use this flasher https://esp.huhn.me/  and follow the picture...

![esp huhn](https://github.com/user-attachments/assets/dea93d82-1f3e-4c6b-9fd0-88205792e72a)


[Download bin here](https://drive.google.com/drive/folders/13cM8WRz8HHXuicDLaxfERslyFuzxRw95?usp=drive_link)
READ THIS!!!!!!!
READ THIS!!!!!!!
READ THIS!!!!!!!
READ THIS!!!!!!!
READ THIS!!!!!!!
READ THIS!!!!!!!


---


# DEMO
[DEMO video](https://vt.tiktok.com/ZS2mkctCM/)


# Features

1.Bluetooth jammer Can set channels to attacks
2.Wifi deauther single and deauth all
3.Allow user to setup nrf24l01 module for experiment
4.Scan 2.4ghz spectrum
5.Pre configure attacks
6.You can use single or 2 nrfs



## REQUIRED DEVICE AND MODULE:

* 1 Esp32 wroom 30 pin
* 1 or 2 Nrf24l01 PA LNA
* 14 Jummper wire female to female


## Shoppee link where to buy:

* [NRF24l01](https://ph.shp.ee/995sg2d?smtt=0.0.9)
*  [Esp32 30 pin](https://ph.shp.ee/5biyof5?smtt=0.0.9)
* [Female to female jumper cable](https://ph.shp.ee/pvbwzxh?smtt=0.0.9)



# STEPS TO FOLLOW / INSTRUCTION 
---
 
 ## STEP 1 WIRING VIDEO INSTRUCTION
[Wiring video Tiktok](https://vt.tiktok.com/ZS2mhHxwg/) VIDEO

![316725930-ba7c2991-1542-4296-8b8c-8011c2bc8e77](https://github.com/user-attachments/assets/2eda5c3c-843f-427f-8967-ff948f7b31f0)


![nrf](https://github.com/user-attachments/assets/0925bcad-5da9-4b5b-8263-1537b2578b7c)

---
1. FOR DUAL/TWO NRF24L01
 * HSPI PINS 
 * 3.3V=VCC
 *  GND=GROUND
 * HSPI SCK = 14
 * HSPI MISO = 12
 * HSPI MOSI = 13
 *  HSPI HCS = 15
 *  HSPI CE = 16
 *  ||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
 *    VSPI PINS
 * 3.3V=VCC
 * GND=GROUND
 * VSPI SCK = 18
 *  VSPI MISO =19
 *  VSPI MOSI = 23
 *  VSPI CS =21
 *  VSPI CE = 22
2. FOR SINGLE/ONE NRF24L01 YOU CAN CHOOSE BETWEEN HSPI OR VSPI


## STEP 2 UPLOADING TO WEBFLASHER

PLUG YOUR ESP32 TO COMPUTER AND FOLLOW VIDEO

[Upload using Webflasher](https://www.tiktok.com/@smoochiee89/video/7413955755163847943?is_from_webapp=1&sender_device=pc&web_id=7406626786861385232) VIDEO





## STEP 3 SETUP AFTER WEBFLASHER

* WIFI NAME : BlueJam
* Password: madapaka

[Setup After you Use Webflasher](https://vt.tiktok.com/ZS2q9WAGe) VIDEO


--- 
## LED INDICATOR
[LED](https://www.tiktok.com/@smoochiee89/video/7413986381719948564?is_from_webapp=1&sender_device=pc&web_id=7406626786861385232) VIDEO

---
## BUTTON FUNCTION

BOOT BUTTOM (GPIO 0)

* [BUTTON FUNCTION](https://www.tiktok.com/@smoochiee89/video/7413990152793558279?is_from_webapp=1&sender_device=pc&web_id=7406626786861385232)VIDEO
---
## FEATURES EXPLAIN:
* [WIFI DEAUTHER](https://www.tiktok.com/@smoochiee89/video/7413981169454288148?is_from_webapp=1&sender_device=pc&web_id=7406626786861385232)
* [USER EDIT JAM](https://vt.tiktok.com/ZS2q9bPYd/)
* [SET UP NRF
 RADIO](https://www.tiktok.com/@smoochiee89/video/7414343023418428690?is_from_webapp=1&sender_device=pc&web_id=7406626786861385232)
*THIS SOMETIMES IMPROVE RANGE if powersupply or spi have noise
  * [DATA RATE ](https://nrf24.github.io/RF24/group__Datarate.html)
  * [LOW NOISE AMPLIFIER](https://en.wikipedia.org/wiki/Low-noise_amplifier)
  * [POWER AMPLIFIER LEVEL](https://nrf24.github.io/RF24/group__PALevel.html)


## RC CHANNEL?...
Most rc operates on lower freqeuncy and if it happen to use a 2.4ghz they will not give you channels...so in reality we jam 125 channels..probably they will use 80 t0 125 channels..

## WIFI CHANNEL?...
![ymo5p](https://github.com/user-attachments/assets/7e87ac33-c439-40a4-a5bf-891e97545918)
Frequency of wifi on top and Frequency of nrf on bottom
When you run the jammer it will disconnect you on wifi due to this reason in picture...



# DONATION
* If you like you can donate to MY PAYPAL ACCOUNT :
* The donation will be used to test microcontrollers and various electronic components.  

[PAYPAL](https://paypal.me/smoochieelee?country.x=PH&locale.x=en_US)
or
[GCASH](https://github.com/smoochiee/Ble-jammer/blob/main/GCash-MyQR-16032024181536.PNG.jpg)


<a href="https://www.buymeacoffee.com/smoochiee"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=☕&slug=smoochiee&button_colour=FFDD00&font_colour=000000&font_family=Lato&outline_colour=000000&coffee_colour=ffffff" /></a>



# Although I'm not a great developer, I do give credit to others and appreciate them.Especially to those who help you....

## Donations 
* Sok Ponleu


## Credits 


*   [Tesa klebeband](https://github.com/tesa-klebeband)
* [Bmorcelli](https://github.com/bmorcelli)


