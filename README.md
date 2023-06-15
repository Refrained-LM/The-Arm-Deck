# The-Arm-Deck
A customizable handheld device

First I would Like to name the users that have helped in either their model being used under Creative Commons (Give credit with a link), Stock, or modified to achieve this prototype.


EYEWINK 7" HDMI Display-C Case by ywabiko on Printables: https://www.printables.com/model/85018-eyewink-7-hdmi-display-c-case

Joycon Thumbstick by Keepinitril on Thingiverse: https://www.thingiverse.com/thing:5533819

Potentiometer trigger stackable by lynlim on Thingiverse: https://www.thingiverse.com/thing:1681562

Spring loaded linear converter Potentiometer  by Yoink_0b3 on Thingiverse: https://www.thingiverse.com/thing:2954927

Tactile Push Button(6x6x5mm) Switch Cap   by adimanav on Thingiverse: https://www.thingiverse.com/thing:4918184

Alan Chatham For the Arduino Uno/Mega Joy code that makes the controller possible. https://github.com/AlanChatham/UnoJoy

NicoHood For is Hood loader 2 system. I had to use his files to bring Arduino Uno back to stock as I am able to flash the serial controller directly. https://github.com/NicoHood/HoodLoader2
_________________________________________________________________________________________________________________________________


As of 6/5/23 This project could change drastically as this is the very beginning of publicly releasing this open-source design and community changes will be discussed and implemented.


Current List of things to finish before adding ergonimics.

1. Make a Micro SD card cover to prevent braking.
2. Make trigger mechanism covers to protect the trigger system

____________________________________________________________________________________________________________________

1. Then add ergonomics to the overall design.
2. Make assembly instructions so other people can build without issues.

__________________________________________________________________________________________________________________

Currently In the works

1. Wiring Diagram
2. Parts List
3. Overall Design

_________________________________________________________________________________________________________________________
These Amazon links are regular links I am not an affiliate.

Parts List
1. [Single Board Computer with a Pico-ITX or standard RPI form factor. (I'm using a Radxa Rock 5B)](https://www.okdo.com/us/p/okdo-rock-5-model-b-8gb-single-board-computer-rockchip-rk3588-arm-cortex-a76-cortex-a55/)
2. [7 inch screen with screw holes on top and bottom, similar to the official Raspberry Pi 7" touchscreen display (linked)](https://www.amazon.com/Speakers-1024x600-Capacitive-Touchscreen-Raspberry/dp/B09L7XNBJB/ref=sr_1_1?crid=2OOK0TOKCKS9H&keywords=LESOWN+New%21+Touch+Screen+7+inch+Display+IPS+1024x600&qid=1685989280&s=electronics&sprefix=lesown+new+touch+screen+7+inch+display+ips+1024x600+%2Celectronics%2C114&sr=1-1) 
3. [Momentary push buttons](https://www.amazon.com/Twidec-Colors-Momentary-Pre-soldered-PBS-110-X6C/dp/B07RTZVZ6L/ref=sr_1_3?crid=3I9S1EZ3ELAJO&keywords=Twidec%2F12Pcs+1A+250V+AC+2+Pins+SPST+6+Colors+Normal+Open+Mini+Momentary+Push+Button+Switch+with+Pre-soldered+Wires+PBS-110-X6C&qid=1685989518&s=industrial&sprefix=twidec%2F12pcs+1a+250v+ac+2+pins+spst+6+colors+normal+open+mini+momentary+push+button+switch+with+pre-soldered+wires+pbs-110-x6c+%2Cindustrial%2C119&sr=1-3)
4. [Tactile buttons]( https://www.amazon.com/TWTADE-Yellow-Orange-6x6x5mm-Tactile/dp/B07C7211PJ/ref=sr_1_3?crid=13Y26LATBQ28V&keywords=TWTADE+160PCS+Momentary+Tactile+Touch+Micro+Push+Button+Switch+tact+6x6x5mm+Tactile+Switch+kit%2CEach+Color+20PCS+Red+Blue+Black+Green+White+Yellow+Brown&qid=1685989546&s=industrial&sprefix=twtade+160pcs+momentary+tactile+touch+micro+push+button+switch+tact+6x6x5mm+tactile+switch+kit%2Ceach+color+20pcs+red+blue+black+green+white+yellow+brown+%2Cindustrial%2C108&sr=1-3)
5. [Round Micro Push Button Switch On Off Mini Momentary Self-Locking Switch 2-Pin](https://www.amazon.com/TAODAN-Button-Switch-Momentary-Self-Locking/dp/B0BQ2Y9P2W/ref=dp_prsubs_sccl_1/136-5012402-1154062?pd_rd_w=yjjGj&content-id=amzn1.sym.2c74594d-9264-4cdf-bf3d-e4e41e237275&pf_rd_p=2c74594d-9264-4cdf-bf3d-e4e41e237275&pf_rd_r=KPMGYV85RYNBM8044ABA&pd_rd_wg=hWFrN&pd_rd_r=b469ed30-3f61-4d54-bfe9-0b9495448993&pd_rd_i=B0BQ2Y9P2W&psc=1)
6. [Joycon Thumb sticks](https://www.amazon.com/Joycon-Joystick-Replacement-Controller-Thumbstick/dp/B08BL4LY84/ref=sr_1_1?crid=3IHWPXLVB5V79&keywords=JAOYSTII+Joycon+Joystick+Replacement+4+Pack%2C+Replacement+Joystick+Analog+Thumb+Stick+for+Switch+Joy-Con+Controller+%26+Switch+Lite%2C+Left%2FRight+Analog+Joystick+with+Thumbstick+Grips+%26+Screws&qid=1685989676&s=electronics&sprefix=jaoystii+joycon+joystick+replacement+4+pack%2C+replacement+joystick+analog+thumb+stick+for+switch+joy-con+controller+%26+switch+lite%2C+left%2Fright+analog+joystick+with+thumbstick+grips+%26+screws+%2Celectronics%2C111&sr=1-1)
7. [Heatsink](https://www.amazon.com/uxcell-Cross-Shaped-Notch-Heatsink/dp/B08HHZPYTF/ref=sr_1_2?crid=35YK81MPIGCNQ&keywords=uxcell+Electronic+Radiators+Heatsink+for+MOS+GPU+IC+Chip+Black+19+x+19+x+5+mm+5pcs&qid=1685989723&s=electronics&sprefix=uxcell+electronic+radiators+heatsink+for+mos+gpu+ic+chip+black+19+x+19+x+5+mm+5pcs%2Celectronics%2C109&sr=1-2) & [fans](https://www.amazon.com/dp/B08MKP8P3S/ref=twister_B09MSXKC88?_encoding=UTF8&psc=1)
8. [Rotary Potentiometer]( https://www.amazon.com/WGCD-Knurled-Linear-Rotary-Potentiometer/dp/B07B64MWRF/ref=sr_1_2?crid=X0U57YJYO4VX&keywords=WMYCONGCONG+20+PCS+B10K+10K+Ohm+Knurled+Shaft+Linear+Rotary+Taper+Potentiometer+with+Black+Knob%28WH148%29+Kit&qid=1685989890&s=industrial&sprefix=wmycongcong+20+pcs+b10k+10k+ohm+knurled+shaft+linear+rotary+taper+potentiometer+with+black+knob+wh148+kit+%2Cindustrial%2C122&sr=1-2)
9. [M3 screw set]( https://www.amazon.com/VIGRUE-1110PCS-Stainless-Assortment-Tweezer/dp/B083SGJ7BD/ref=sr_1_2?crid=1KI3337ZB8MZM&keywords=VIGRUE+1110PCS+M3+Hex+Socket+Head+Cap+Screws+Nuts+Kit&qid=1685990089&s=industrial&sprefix=vigrue+1110pcs+m3+hex+socket+head+cap+screws+nuts+kit%2Cindustrial%2C100&sr=1-2)
10. [Right angle USB C to C 60 watt](https://www.amazon.com/3-Pack-Charge-Compatible-Samsung-MacBook/dp/B099N3VKCH/ref=sr_1_1?crid=2O6AQ2SB4G99J&keywords=HOTNOW+USB+C+to+USB+C+Cable+Right+Angle+1.5FT+3Pack%2C+PD+60W+Type+C+USB+2.0+Fast+Charge+Cord+Compatible+with+Samsung+Galaxy+S21%2FS21%2B%2FS20%2B+Ultra+Note+20%2C+Pixel+4%2F3+XL%2C+MacBook+Air+iPad+Pro+2020&qid=1685990133&s=industrial&sprefix=hotnow+usb+c+to+usb+c+cable+right+angle+1.5ft+3pack%2C+pd+60w+type+c+usb+2.0+fast+charge+cord+compatible+with+samsung+galaxy+s21%2Fs21%2B%2Fs20%2B+ultra+note+20%2C+pixel+4%2F3+xl%2C+macbook+air+ipad+pro+2020+%2Cindustrial%2C112&sr=1-1)
11. [Arduino Uno]( https://www.amazon.com/ELEGOO-Board-ATmega328P-ATMEGA16U2-Compliant/dp/B01EWOE0UU/ref=sr_1_3?crid=2CPZJVZVEO32I&keywords=ELEGOO+UNO+R3+Board+ATmega328P+with+USB+Cable%28Arduino-Compatible%29+for+Arduino&qid=1685990179&s=industrial&sprefix=elegoo+uno+r3+board+atmega328p+with+usb+cable+arduino-compatible+for+arduino%2Cindustrial%2C118&sr=1-3)
12. [Wire (I'm currently using Dupont style wire)](https://www.amazon.com/SIM-NAT-Breadboard-Arduino-Raspberry/dp/B06XRV92ZB/ref=sr_1_1_sspa?crid=WOQR8I7GKESX&keywords=SIM%26NAT+12inch+%2F+30cm+120+pcs&qid=1685990365&sprefix=sim%26nat+12inch+%2F+30cm+120+pcs%2Caps%2C110&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFSRDExSDZJQVRRT1omZW5jcnlwdGVkSWQ9QTAxNjc0OTUxSlA2MDY3VkZRSUxLJmVuY3J5cHRlZEFkSWQ9QTA3NDI1NTEyMlMzRUFGU0FHMUZaJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
13. [Battery pack]( https://www.amazon.com/gp/product/B0915T91JN/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
14. [USB A -> Micro B Ribbon cables](https://www.amazon.com/Micro-Ribbon-Degree-Standard-Charging/dp/B077RKFXJT/ref=sr_1_11_sspa?keywords=usb%2Bmicro%2Bb%2Bribbon%2Bcable&qid=1686790856&sprefix=usb%2Ba%2Bto%2Bmicro%2Bb%2Bribbo%2Caps%2C225&sr=8-11-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExNlFSQjhGWE9FNlJSJmVuY3J5cHRlZElkPUExMDM2MTIzM1VLSkxVMUI3NUJQVCZlbmNyeXB0ZWRBZElkPUEwNjA2NzAyMVdZWTFFOFRCNEwyQSZ3aWRnZXROYW1lPXNwX210ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU&th=1)
15. [Wireless (wifi, bluetooth) card, if required for your board](https://www.amazon.com/Wireless-Network-RTL8852BE-Universal-Bluetooth/dp/B0B5LQFGLG/ref=sr_1_3?crid=2CTM8DNNALUPC&keywords=Wireless+Network+Card%2C+RTL8852BE+WiFi6+5G+Laptop+Gigabit+Wireless+LAN+Card+Universal+Bluetooth+5.2+for+Win+10%2C+Plug+and+Play.&qid=1685990797&s=electronics&sprefix=wireless+network+card%2C+rtl8852be+wifi6+5g+laptop+gigabit+wireless+lan+card+universal+bluetooth+5.2+for+win+10%2C+plug+and+play.+%2Celectronics%2C110&sr=1-3)
16. [SSD, if supported by your board](https://www.amazon.com/SAMSUNG-Technology-Intelligent-Turbowrite-Sequential/dp/B08V7GT6F3/ref=sr_1_3?crid=30RUONW6VG46&keywords=SAMSUNG+980+SSD+500GB&qid=1685990864&s=electronics&sprefix=samsung+980+ssd+500gb+%2Celectronics%2C105&sr=1-3)
17. 3d Printer Filament I got PETG but PLA could be used but not advised for strength and heat resistance factor.
18. Springs will be needed for the triggers.....
19. [HDMI Male to Male 180 Degree angle](https://www.amazon.com/gp/product/B08FMKXN3D/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
20. [HDMI Male to Female FPC Flat](https://www.amazon.com/gp/product/B089Q9HMY5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
21. [4layer brand Joy-Con Breakout board](https://4layertech.com/products/joystick-breakout-board-pack-of-2)
22. [USB A to C Cable That supports QC technology]()

These Amazon links are regular links I am not an affiliate.

***Note*** an Arduino Leonardo could be used in place of the Uno as the Arduino Leonardo/Micro has a specific library for game controllers, I do not have code for that currently but I will add it to the code base if someone beats me to it.
    The Arduino Joystick Library (a.k.a. Game Controller library) provides the following:

    X, Y, and Z axis
    32 buttons
    X, Y, and Z axis rotation
    Rudder
    Throttle
    2 Point of View Hat Switches

_____________________________________________________________________________________________________________________________________________________________

Overall design Current Cad workings



![image](https://github.com/Refrained-LM/The-Arm-Deck/assets/64605991/5303e60c-9ed8-4e84-b6f6-cffeb8260d6f)





![image](https://github.com/Refrained-LM/The-Arm-Deck/assets/64605991/a236bfcf-898f-49dc-bfbb-4cfd2a110c4f)




![image](https://github.com/Refrained-LM/The-Arm-Deck/assets/64605991/555bf0e7-f043-442c-82f3-01de7eb0ab9f)

