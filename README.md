# ADX-POCKET
ADX POCKET - ARDUINO DIGITAL MODES TRANSCEIVER with CAT Control

- A short youtube video demonstrating ADX POCKET with CAT CONTROL: https://youtu.be/bQiwh-gOaUY

ADX POCKET is based on ADX Arduino Digital Modes Transceiver Design:
https://github.com/WB2CBA/ADX

- ADX is an Arduino based Digital Modes Transceiver.

- ADX - is abbreviation for Arduino Digital Xceiver.

- ADX is a mono band (actually quad band) digital modes optimized HF transceiver that can cover four pre-programmed bands one band at a time by swapping Band LPF Modules. 

It can work on 80m, 40m, 30m,20m, 17m, 15m and 10m bands and can operate on four of the most popular digital modes, FT8, FT4, JS8call and WSPR.

ADX POCKET consists of two boards:

1- ADX POCKET Main Board which incorporates a USB Hub, a USB to Serial conveter, An Atmega328P/AU microcontroller and a CM108 USB Soundcard in one board.

2- ADX POCKET RF Transceiver board includes all circuitry needed for a ADX Digital transceiver RF section.

RF board plugs on top of ADX POCKET controller board to create a full fledged digital modes optimized CAT controlled HF Transceiver.

This allows one USB connection to operate sound card and CAT control in a compact and versatile HF Digital Modes Transceiver that can fit in a shirt pocket!

ADX POCKET has two DC powering modes:

1- USB powered QRPp Transceiver mode with sub 1 watt RF output around 700 mW whole rig powered from USB 5 volts of PC. ADX POCKET draws 320 mA average from USB port on TX.

2- DC 12V external power mode where a DC 10 to 12V power is applied to get up to 5 Watts QRP RF Power.

Power management is selected via a slide switch.

IMPORTANT NOTE ON NT7S SI5351 LIBRARY VERSIONS   

Please install SI5351 Library that is in ADX POCKET Github under ADX POCKET Firmware! 
Or use Etherkit SI5351 Library Version 2.1.3. 
ADX firmware is compatible with only Etherkit SI5351 Library version 2.1.3.

ADX POCKET can be opreated via classic buttons and Leds interface or CAT Control interface depending on user's choice.

ADX POCKET CAT Control Settings:
- Rig Emulation: KENWOOD TS2000

- Comm Port Settings: 115200 bps, 8 bit, 1 stop bit.

- PTT Control: CAT
