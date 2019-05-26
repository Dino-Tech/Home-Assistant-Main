# Home-Assistant-Main
### Home Assistant Config Files (YAMLs). These are my Home Assistant configuration files.

Message me via [Discord #Lovelace channel](https://discord.gg/aYTW2Z9) or the [HomeAssistant forums](https://community.home-assistant.io/t/dinotechs-may-24-new-mobile-popups-lovelace-screens/84271) if you have any questions or recommendations in regards to my repository! 

If I've helped you, and you really want to, you can <link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/9lTxIVgZ3"><img src="https://www.buymeacoffee.com/assets/img/BMC-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px">Buy me a coffee</span></a>, but don't feel obliged - I'm not doing this for free coffee, but I do get tired :stuck_out_tongue_winking_eye: 

<html>
<head>
  <title>Home Assistant Loading Animation</title>
  <style type="text/css">
    /*  lazy placement and background for demo */
    body {
      background-color: #038fc7;
      height: 100vh;
      width: 100vw;
      overflow: hidden;
      background-image: radial-gradient(circle, #038fc7, #026b95);
      background-size: cover;
      background-position: 50% 50%;
    }

    svg {
      width: 66vw;
      height: 66vh;
      margin-left: 16.666vw;
      margin-top: 16.666vh;
    }

    /*main-logo*/
    .ha-logo path,
    .ha-logo circle {
      fill: none;
      stroke: #99e1fd;
      stroke-width: 0.125px;
      stroke-linejoin: round;
    }
    .ha-logo path.house,
    .ha-logo circle.house {
      stroke-linecap: round;
      stroke-width: .3px;
    }

    .loading.ha-logo circle {
      animation: nodes 6s linear infinite;
    }

    .loading.ha-logo .house {
      animation: house 6s ease infinite;
    }

    .loading.ha-logo .circut {
      animation: circut 6s cubic-bezier(0.7, 0.1, 0.1, 0.9) infinite;
    }

    @keyframes house {
      0% {
        stroke-dashoffset: -50;
        stroke-dasharray: 50 50;
      }
      45% {
        stroke-dashoffset: -100;
      }
      50% {
        stroke: #99e1fd;
      }
      60% {
        stroke: white;
      }
      75% {
        stroke: #99e1fd;
      }
      80% {
        stroke-dashoffset: -100;
      }
      100% {
        stroke-dashoffset: -130;
        stroke-dasharray: 50 50;
      }
    }
    @keyframes circut {
      0% {
        stroke-dasharray: 20 20;
        stroke-dashoffset: -20;
      }
      13% {
        stroke-dashoffset: -20;
      }
      50% {
        stroke-dashoffset: -40;
        stroke: #99e1fd;
      }
      60% {
        stroke: white;
      }
      70% {
        stroke: #99e1fd;
      }
      85% {
        stroke-dashoffset: -40;
      }
      100% {
        stroke-dashoffset: -60;
        stroke-dasharray: 20 20;
      }
    }
    @keyframes nodes {
      0% {
        stroke-dasharray: 0 4;
      }
      25% {
        stroke-dasharray: 0 4;
      }
      35% {
        stroke-dasharray: 4 0;
        stroke: #99e1fd;
      }
      41% {
        fill: none;
      }
      42% {
        fill: #99e1fd;
      }
      55% {
        fill: none;
        stroke: #99e1fd;
      }
      65% {
        fill: white;
        stroke: white;
      }
      75% {
        stroke: #99e1fd;
        fill: none;
        stroke-dasharray: 4 0;
      }
      85% {
        fill: #99e1fd;
        stroke: #99e1fd;
      }
      93% {
        fill: none;
        stroke-dasharray: 4 0;
        stroke-dashoffset: 0;
      }
      100% {
        stroke-dashoffset: -4;
        stroke-dasharray: 0 4;
      }
    }
    .ha-logo circle:nth-child(1n) {
      animation-delay: -0.054s;
    }

    .ha-logo circle:nth-child(2n) {
      animation-delay: -0.108s;
    }

    .ha-logo circle:nth-child(3n) {
      animation-delay: -0.162s;
    }

    .ha-logo circle:nth-child(4n) {
      animation-delay: -0.216s;
    }

    .ha-logo circle:nth-child(5n) {
      animation-delay: -0.27s;
    }

    .ha-logo circle:nth-child(6n) {
      animation-delay: -0.324s;
    }

    .ha-logo circle:nth-child(7n) {
      animation-delay: -0.378s;
    }

    .ha-logo circle:nth-child(8n) {
      animation-delay: -0.432s;
    }

    .ha-logo circle:nth-child(9n) {
      animation-delay: -0.486s;
    }

    .ha-logo circle:nth-child(10n) {
      animation-delay: -0.54s;
    }

    .ha-logo circle:nth-child(11n) {
      animation-delay: -0.594s;
    }

    .ha-logo circle:nth-child(12n) {
      animation-delay: -0.648s;
    }

    .ha-logo circle:nth-child(13n) {
      animation-delay: -0.702s;
    }

    .ha-logo circle:nth-child(14n) {
      animation-delay: -0.756s;
    }
  </style>
</head>
<body>
  <svg
    class="ha-logo loading"
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 10 10">
    <path
      class="house"
      d="M1.9 8.5V5.3h-1l4-4.3 2.2
         2.1v-.6h1v1.7l1 1.1H7.9v3.2z"   />
    <path
      class="circut"
      d="M5 8.5V4m0 3.5l1.6-1.6V4.3M5
         6.3L3.5 4.9v-.6m2.7.7l.4.4L7
         5M5.9 6.1v.5h.5M4.2 5v.5h-.8m1
         1.5v.6h-.6m1.2.8L3.6 6.7M5
         8.4l1-.9h.7M4.6 3.6L5 4l.4-.4" />
    <g>
      <circle cx="5.5" cy="3.4" r="0.21" />
      <circle cx="4.5" cy="3.4" r="0.21" />
      <circle cx="6.6" cy="4.1" r="0.21" />
      <circle cx="3.5" cy="4.1" r="0.21" />
      <circle cx="4.2" cy="4.8" r="0.21" />
      <circle cx="6.1" cy="4.8" r="0.21" />
      <circle cx="7.1" cy="4.8" r="0.21" />
      <circle cx="6.6" cy="6.6" r="0.21" />
      <circle cx="5.9" cy="5.9" r="0.21" />
      <circle cx="3.2" cy="5.5" r="0.21" />
      <circle cx="3.5" cy="6.5" r="0.21" />
      <circle cx="4.4" cy="6.8" r="0.21" />
      <circle cx="3.6" cy="7.6" r="0.21" />
      <circle cx="6.9" cy="7.5" r="0.21" />
    </g>
  </svg>
</body>
</html>

<p align="center">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif">
</p>

### I'm currently running [Home Assistant](https://home-assistant.io) version __0.93.2__ on a RPi3B.

# A Few Stats On my Setup:
| Tracked Devices | Lights | Binary Sensors | Switches | Automations | Scripts | Sensors | Alerts  |
|:---------------:|:------:|:--------------:|:--------:|:-----------:|:-------:|:-------:|:-------:|
|12               |37      |56              |70        |82           |109      |281      |12       | 

### Cameras(8):
* [Wyze Cam v2(7)](http://amzn.to/2QqoYsf)
* [Wyze Pan Cam(1)](http://amzn.to/2QqoYsf)

### Thermostat:
* [Google Nest Thermostat E](http://amzn.to/2Qpyqfe)

### Power Supply(4):
* [3 Prong UPS](http://amzn.to/2W0GKbD)

* [2 Prong UPS](http://amzn.to/2W6W5Yf)

### Device Trackers:
* nmap
* bluetooth
* ping
* Google Maps (for GPS and battery statuses & HA iOS App)

### Google Homes & Assistant Powered Devices(14) 
* Google Hub(1), Google Home(2), Google Home Mini(5), Google Assisted speakers - Zolo mini(1), Insignia(2), Insignia portable(1), Chromecast powered TV's(2)
*(used for voice controlled Lovelace commands/device control)*

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
### Main Kiosk Screen
Main panel has auto-changing background images, sleep and wake functions that are controlled via motion, time of day/night,  voice activated and presence detection. The drop downs selection keeps the screen less cluttered until needed to select popups to view so backgrounds are more visible when not in use....

The end result is like having 30 different views that can accessed via one main screen... with one path, `/lovelace/0` without having to navigate to another view and that was my goal! *(see aditional picture 'Pop-up' gallery link below)*

<img src="https://github.com/Dino-Tech/Home-Assistant-Main/blob/master/screenshots_tablet/1.png" />

### Mobile Screens

### Desktop Screens

### Pop-up Images Gallery
* [Tablet Pop-ups](https://imgur.com/a/tbY9HW2)
* Mobile Pop-ups
