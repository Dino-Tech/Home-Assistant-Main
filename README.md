<p align="center">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif">
</p>
<h1 align="center">
  My Home Assistant Configuration
</h1>
<h4 align="center">Be sure to :star: my repo so you can keep up to date on the daily progress!.</h4>
<div align="center">
  <h4 align="center">
    <a href="https://github.com/Dino-Tech/Home-Assistant-Main/stargazers"><img src="https://img.shields.io/github/stars/Dino-Tech/Home-Assistant-Main?style=plasticr"/></a>
    <a href="https://github.com/Dino-Tech/Home-Assistant-Main/commits/master"><img src="https://img.shields.io/github/last-commit/Dino-Tech/Home-Assistant-Main?style=plasticr"/></a>
  </h4>
</div>
<p><font size="3">
This Repo is designed for Smart Home inspiration.  The configuration, devices and layout should help inspire your journey into the IOT world.  This is a working configuration of <strong>my Smart Home</strong>.  All of the code is free to use and contribute to. This readme is inspired from the great documentation of <a href="https://github.com/CCOSTAN/Home-AssistantConfig/blob/master/README.md">CCOSTAN</a>

![Screenshot of Home Assistant Header](https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/HAbrewed2.jpg)
<hr>
<div align="center">
  <h4 align="center">
    <a href="https://www.buymeacoffee.com/9lTxIVgZ3" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/black_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a><br>
  </h4>
</div>

You can message me via [Discord #Lovelace channel](https://discord.gg/aYTW2Z9) or the [HomeAssistant forums](https://community.home-assistant.io/t/dinotechs-latest-mobile-designs-and-themes-updated-oct-18/143180) if you have any questions or recommendations in regards to my repository! 

If you would like to show your support, you can <link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/9lTxIVgZ3"><img src="https://www.buymeacoffee.com/assets/img/BMC-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px">Buy me a coffee</span></a> - I'm not doing this for free coffee, but I do get tired :stuck_out_tongue_winking_eye: 

### I'm currently running [Home Assistant](https://home-assistant.io) version __0.102.0__ on a RPi4B.

# A Few Stats On my Setup:
| Tracked Devices | Lights | Binary Sensors | Switches | Automations | Scripts | Sensors | Alerts  |
|:---------------:|:------:|:--------------:|:--------:|:-----------:|:-------:|:-------:|:-------:|
|8                |56      |89              |76        |104          |174      |391      |36       | 

### Cameras(8):
* [Wyze Cam v2(7)](http://amzn.to/2QqoYsf)
* [Wyze Pan Cam(1)](http://amzn.to/2QqoYsf)

### Thermostat:
* [Google Nest Thermostat E](http://amzn.to/2Qpyqfe)

### Power Supply(4):
* [3 Prong UPS](http://amzn.to/2W0GKbD)
* [2 Prong UPS](http://amzn.to/2W6W5Yf)

### Device Trackers:
* [NMAP](https://www.home-assistant.io/components/nmap_tracker/)
* [Bluetooth Tracker](https://www.home-assistant.io/components/bluetooth_tracker/)
* [Ping (ICMP)](https://www.home-assistant.io/components/ping/)
* [Person](https://www.home-assistant.io/components/person/)
* [Life360](https://www.home-assistant.io/components/life360/) *(for GPS and battery statuses & HA iOS App)*

### Google Homes & Assistant Powered Devices(15) 
* Google Hub (1)
* Google Home (2)
* Google Home Mini (6) 
* Zolo mini (1) 
* Insignia (2) 
* Insignia portable (1) 
* Google Chromecast (3rd Generation) (1)
* Google Chromecast Ultra (1)

*(used for voice controlled Lovelace screen commands/device control)*

### Tablets:
* Insignia 10.1"(2) - (currently 1 wall mounted & 1 in office for screen designing)
* Android 7"(1) - wall mounted alarm panel keypad

### Security:
* [Konnected alarm](http://amzn.to/2YIlunM) - 18 zone system
* [Sonoff RF Bridge](http://amzn.to/2QlTfIL) - running tasmota
* [Sonoff PIR Motion Sensors](http://amzn.to/2ExNXVA)
* [IR Pyroelectric Infrared PIR Motion Sensors](http://amzn.to/2YUfGI9)
*(14 total - used for alarm, automations & tablet 'ON' & 'OFF' screens)*

# Screenshots

### Mobile Screens

#### My Mobile Login *(Pixel 2 XL running Fully Kiosk Browser)* 
#### **Themes inspired** from Android 10's new accent colors
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/main1.2.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu1.1.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu8.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu2.1.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu3.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu4.1.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu5.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu6.2.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu7.jpg" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/menu9.1.jpg" />

### Main Kiosk Screen *(restricted access)*
Main panel has auto-changing background images, sleep and wake functions that are controlled via motion, time of day/night,  voice activated and presence detection. The drop down selection keeps the screen less cluttered until needed for selecting popups to view so backgrounds are more visible when kiosk is idle....

The result is like having 30 different views that can be accessed via *_one_* main screen... with one path, `/lovelace/0` without having to navigate to another view and that was my goal! *(see aditional picture 'Pop-up' gallery link below)*

<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/30.png" />
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/32.png" />

#### iPhone 6 Mobile Login *(restricted views access)*
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/iPhone.jpg" />

#### Guest Access Mobile Login *(restricted access)*
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/mobile_screens1.jpg" />

### Desktop Login *(desk menu with all areas access)*
<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/Desk%20Menu.jpg" />

### Pop-up Images Gallery
* [Tablet Pop-ups](https://imgur.com/a/tbY9HW2)
