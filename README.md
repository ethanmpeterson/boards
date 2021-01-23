# Ethan's Printed Circuit Board Designs
Boards is a monolithic repository containing all of my personal PCB projects in Altium Designer. Each project is
listed below with a breif description and link to a post about the project on my blog.

## Peterson Development Platform (PDP)
The PDP is a first attempt at an STM32 development board using ST-Link for debugging and an STM32F7 series MCU. The full blog post on the PDP can be found [here](http://portfolio.petetech.net/peterson-dev-platform/)

## A CAN Transceiver Breakout Board
This board breaks out a CAN Transceiver IC to assist with the usage of the CAN bus controller built into STM32 chips. The full blog post can be found [here](http://portfolio.petetech.net/can-transceiver/).

## Custom Black Magic Probe / ST-LINK Debugger
The Debugger project aims to create a standard reference design for STM32 debuggers. This reference design can be used in future designs to add both debug and serial communication with the host computer seamlessly. The full blog post can be found [here](http://portfolio.petetech.net/debugger/)

## Buck Converter Breakout Board
An example buck converter circuit which regulates 12V supply to a 5V 2A output. Altium designer files are located in the buck folder.

## CAN Bus Shield for STM32 Development
The CAN bus shield is a standard size Arduino shield designed to be fitted to an STM32 Nucleo F446RE development board. The shield implements two CAN transceiver circuits, which are connected to the corresponding CAN controller pins on the nucleo board. The only difference between the CAN transceiver breakout board circuit and the transceiver circuitry on the shield is the addition of a switch to enable and disable bus termination. This design is located in the DevKit folder.

## STM32 Based CAN Bus Development Board (Mock ECU)
The Mock ECU is a CAN enabled STM32F4 development board aimed at helping my formula teammates with emulating the car's CAN bus in a remote development environment. The full post on the Mock ECU can be found [here](http://portfolio.petetech.net/mock-ecu/)
