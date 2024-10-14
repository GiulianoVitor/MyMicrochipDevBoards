# Microchip PIC-IoT Wx (WG, WA, WM)

## Overview

The Microchip PIC-IoT Wx board is a small platform for development IoT Solutions based on 3 main blocks: Microcontroller, Secure  element and a Connection with cloud using a Wi-Fi module.
The variants WA, WG and WM refers to a pre-programmed solutions using **AWS - Amazon Web Services** (WA), **Google Cloud** IoT Core (WG) and **Microsoft Azure** (WM).

> **Note:** 
> Google Cloud IoT Core has been shut down and can no longer be used.


![Board](Images/board.png)

## Hardware

The board features the following elements:

+ Microcontroller PIC24FJ128GA705
+ On-board debugger
+ Secure Element (ATECC608A)
+ Temperature Sensor (MCP9808)
+ Light Sensor (TEMT6000)
+ LiPo Charger (MCP73871) + LiPo Connector
+ MiKroBUS socket (MIKROE Click boards)
+ 2 User Switches
+ 4 Status Led 
+ Wi-Fi Module (ATWINC1510)



![Board Main Components](Images/BoardMainComponents.png)

![Board Pinout](Images/BoardPinout.png)


## Software requirements
+ IDE: MPLABX Version 5.15 or later (using V6.0)
+ Compiler: XC16 Version 1.35 or later (using 2.70)
+ Code Generation: MCC Plug-in V3.75+, MCC Foundation Services V0.1.32+, MCC Pic-IoT Wx Sensor Node V1.1.1



## References
+ https://iot.microchip.com/pic-iot
+ https://www.microchip.com/en-us/development-tool/AC164164
+ https://github.com/microchip-pic-avr-solutions/pic-iot-aws-sensor-node
+ https://github.com/microchip-pic-avr-solutions/microchip-iot-developer-guides-for-aws
+ https://github.com/Azure-Samples/Microchip-PIC-IoT-Wx
+ https://www.microchip.com/en-us/product/PIC24FJ128GA705
+ https://www.microchip.com/en-us/product/ATECC608A
+ https://www.microchip.com/en-us/product/ATWINC1500
+ https://github.com/microchip-pic-avr-tools/iotprovision-bin/releases/
