SparkFun Pro RF - LoRa, 915MHz (SAMD21) Arduino Example Code
======================================

[![SAMD21 Pro RF LoRa 915MHz](https://cdn.sparkfun.com/assets/parts/1/3/2/0/2/14916-Sparkfun_Pro_RF_-_LoRa_915MHz__SAMD21_-01a.jpg)](https://cdn.sparkfun.com/assets/parts/1/3/2/0/2/14916-Sparkfun_Pro_RF_-_LoRa_915MHz__SAMD21_-01a.jpg)

[*SparkFun SAMD21 Pro RF LoRa 915MHz (WRL-14916)*](www.sparkfun.com/products/14916)

The [SparkFun SAMD21 Pro RF](www.sparkfun.com/products/14916) is the fated meeting of a SAMD21 and a long-range [RFM95W LoRa®-enabled radio](http://www.hoperf.com/upload/rf/RFM95_96_97_98W.pdf). The outcome is a compact, blazing fast MCU with excellent point to point data transmission in the 915MHz ISM band with LoRa Capabilities. The SAMD21 Pro RF comes with a LiPo connector, an on-board LiPo charger, and a slide switch to power the board on and off. The board programs over a reinforced Micro-B connector with a slim reset button that fits nicely on the side of the board. We’ve even added our popular [Qwiic](https://www.sparkfun.com/qwiic) connector to the edge of the board making it incredibly easy to add sensors and actuators without the need for solder or a soldering iron!

Repository Contents
-------------------

* **/SAMD21 PRF Client** - Code to set up the SAMD21 Pro RF as a client.
* **/SAMD21 PRF Server** - Code to set up the SAMD21 Pro RF as a server.
* **/ttn abp node hello world** - Code to set up LoRaWAN, using [The Things Network](https://www.thethingsnetwork.org/) for the network server.

Documentation
--------------
* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfun/SAMD21_Pro_RF)** - Main repository for the SAMD21 Pro RF.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-samd21-pro-rf-hookup-guide)** - Basic hookup guide the SAMD21 Pro RF going over the point to point radio capabilities of the radio module and how to set up and use LoRaWAN. 

Libraries Used by the Example Code
-------------------

* **[Paul Stoffregen's Radio Head Library](https://github.com/PaulStoffregen/RadioHead)** - Library for the RFM95W radio module. 
* **[Matthijs Kooijman LoRaMAC-library-in-C modified to run in Arduino](https://github.com/matthijskooijman/arduino-lmic)** - The original library was IBM's LMIC (LoRaMAC-in-C), that has been modified to run in the Arduino IDE. 

License Information
-------------------

This code is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
