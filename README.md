# SENSA Smart Stepper Driver 
<p align="center"> 
<img width="600" height="400" src="https://raw.githubusercontent.com/SensaOrg/StepperDriver/master/Docs/board.png">
</p>

### Main features
- on-board ATMEGA328/P
- A4988 module 
- CAN Bus - MCP25625
- Encoder and switch support

## What is the SENSA Smart Stepper Driver?
The SENSA Smart Stepper Driver is an add-on module for a stepper motor and houses all features needed to gain full control of your stepper motor.
Next to the on-board CAN Bus, the driver can also be controlled through USART or I2C.


### ATMEGA328/P
The ATMEGA328/P controls the whole board which is equipped with the Arduino platform.
It runs our [open-source code](), which can be easily modified for any project.

### A4988 module
We have chosen the easily accessible A4988 stepper driver module. It has all features that are needed and it is easy to control.

### MCP25625
The CAN Bus is a very robust communication protocol, which supports up to 1Mb/s speeds and it only requires 3 wires for it to work (CANH, CANL, GND).
The [MCP25625](http://ww1.microchip.com/downloads/en/DeviceDoc/20005282B.pdf) is a CAN controller with an integrated transceiver, meaning it doesn't take up much space.

### Encoder and switches
We have added a connector for an encoder, whose pins are connected to interrupt pins of the ATMEGA328/P. 
Two switches can be also added to the board via a connector, which can help you add control to your project. 

## Images
![Top view](https://raw.githubusercontent.com/SensaOrg/StepperDriver/master/Docs/Output/top_view.jpg)
![Bottom view](https://raw.githubusercontent.com/SensaOrg/StepperDriver/master/Docs/Output/bottom_view.jpg)

## Sponsored by AISLER
### Develop and manufacture your own premium boards at [aisler.net](https://aisler.net/)



