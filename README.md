# ADX-POCKET
ADX POCKET - ARDUINO DIGITAL MODES TRANSCEIVER with CAT Control

ADX POCKET is based on ADX Arduino Digital Modes Transceiver Design:

ADX POCKET consists of two boards:

1- ADX POCKET Main Board which incorporates a USB Hub, a USB to Serial conveter, An Atmega328P/AU microcontroller and a CM108 USB Soundcard in one board.

2- ADX POCKET RF Transceiver board includes all circuitry needed for a ADX Digital transceiver RF section.

RF board plugs on top of ADX POCKET controller board to create a full fledged digital modes optimized CAT controlled HF Transceiver.

This allows one USB connection to operate sound card and CAT control in a compact and versatile HF Digital Modes Transceiver that can fit in a shirt pocket!

ADX POCKET has two DC powering modes:

1- USB powered QRPp Transceiver mode with sub 1 watt RF output arounf 700 mW.

2- DC 12V external power mode where a DC 10 to 12V power is applied to have up to 5 Watts QRP transceiver.

Power management is selected via a slide switch.

IMPORTANT NOTE ON NT7S SI5351 LIBRARY VERSIONS   

Please install SI5351 Library that is in ADX Github under ADX Firmware! 
Or use Etherkit SI5351 Library Version 2.1.3. 
ADX firmware is compatible with only Etherkit SI5351 Library version 2.1.3.
____________________________________________________________________________

ADX is an Arduino based Digital Modes Transceiver.

- ADX - is abbreviation for Arduino Digital Xceiver.

- ADX is a mono band (actually quad band) digital modes optimized HF transceiver that can cover four pre-programmed bands one band at a time by swapping Band LPF Modules. 
It can work on 80m, 40m, 30m,20m, 17m, 15m and 10m bands and can operate on four of the most popular digital modes, FT8, FT4, JS8call and WSPR.

- ADX now supports CAT via emulating KENWOOD TS2000 HF Transceiver with 115200 bps,8,1 Serial comm. CAT controls Band and Mode changes.

My goal with this project is to design a simple HF Transceiver optimized for operating on Digital modes:
-	Simple to procure – meaning not effected by chip shortage
-	Simple to build – 2 modules, 2 IC’s and 4 Mosfets!
-	Simple to setup and tune – One simple calibration procedure is all needed.
-	Simple to operate – Plug in ADX MIC to soundcard MIC input and ADX SPK to PC soundcard speaker input and we are good to go with any digital modes Software.
-	Dirt Cheap – Costs less than 25$ to get all parts and PCB if we exclude ridiculous shipping costs!

- Plug in a USB cable between ADX Arduino and your PC, Select Kenwood TS2000 with 115200bps,8,1 setup as your CAT rig and you will have CAT control on ADX!
