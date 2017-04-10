CANx
====

CAN Bus interface module for RaceCapture/Pro MK1 only. This adds a single CAN bus interface channel that integrates with the SPI interface available on RJ45 port. 

![ScreenShot](https://github.com/autosportlabs/CANx/blob/master/hardware/CANx.png?raw=true)


See the LICENSE.txt for information on the technology license

Autosport Labs
http://www.autosportlabs.com


Building the CANx board
=======================

Parts are defined in the CANx.csv. 

* All resistors are 0603 5%
* All capacitors are 0603 X7R

Connecting CANx
===============

Connect a short (6" or shorter) RJ45 cable with pins wired straight through between RaceCapture/Pro MK1 and the X2 port of CANx. A simple ethernet 6" extension cable should work fine. 

The CAN bus connection is available on X1 and conforms to the same pinout as RaceCapture/Pro MK2. And, you can use the same CAN->OBDII cable used on the newer versions of RaceCapture/Pro.







