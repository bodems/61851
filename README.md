# iec61851

## About this project
This software allows it to turn a single-board computer with some GPIOs, AD converters and other interfaces into an EVSE for charging electric vehicles.. Currently it is at a very early stage 

## Hardware requirements
*  some GPIOs
*  some AD converters or a suitable bus like I2C or SPI for connecting AD converters
*  PWM output
*  serial connection for reading metering values via Modbus RTU

## Recommended hardware
*  NanoPi NEO
*  MCP3008 as AD converter
*  Bender RCMB104

## safety note
If you don't use a Bender RCMB104 for DC protection, you have to install a RCD type B or another suitable DC protection system!
