---
title: Introduction
type: docs
rev: r0.2
---

# Introduction

The OrangeCrab is an electronics development board. It is FPGA based featuring an ECP5 from Lattice. The board follows the slim [feather board specification](https://learn.adafruit.com/adafruit-feather/feather-specification) from Adafruit. The FPGA is compatible with all opensource toolchains and is perfect for experimenting with RISC-V cores. There aren't many FPGA boards available that make use of the ECP5, but here are some distinct features that set this broad apart:

* Small Compact size (Take it anywhere!)
* Direct USB connection to the FPGA (Operate as a DFU, MSC, CDC, or composite device!)
* Onborad DDR3 Memory (1Gbit!)
* Preloaded DFU bootloader (No external programmer required!)
* It's Orange!


![Front Photo](orangeCrab-1.jpg "Front Photo")


## Technical details

Here are the main details for the OrangeCrab (25F)
* Lattice ECP5-25F FPGA in csfBGA285 package
    * 24 K - Look Up Tables
    * 1008 Kb - Embedded Block RAM
    * 194 Kb - Distributed RAM
    * 28 - 18x18 Multipliers
    * PLLs: 2
    * Internal oscillator
    * Flexible I/O for DDR3 Memory Support
* DDR3L Memory
    * 128 Mbytes (1Gbit)
    * 64M x16
    * 1.35V low voltage operation
* Micro USB connection
    * Full-speed (12Mbit) USB with direct connection to FPGA
* Non-volatile Storage
    * 128Mbit QSPI FLASH Memory 
        * Bootloader (First 4Mbits)
        * User Bitstream
        * User storage (Firmware/MSC backend/etc)
        * QSPI compatible
    * MicroSD socket
        * 4bit SD interface (CK, CMD, DAT0-3)
* Power supply
    * High effeciency DCDC for main supplies
    * Battery charger (100mA), with charge indicator LED
    * LiPo battery connector (PH type)
* 48MHz onboard oscillator
* Standard 0.05" JTAG connector
* User I/O
    * 1x Button 
    * 1x RGB LED
    * 20x I/O on 0.1" headers
* Analog System
    * Analog Mux
    * SAR ADC, external RC / input comparator of FPGA
    * Digital bypass
    * Internal channels for supply monitor
    * Battery voltage sensing
* Feather Format Board
    * Dimensions: 22.86mm x 50.8mm (0.9" x 2.0")

## Photos
![Front Photo](orangeCrab-5.jpg "Front Photo")
![Back Photo](orangeCrab-4.jpg "Back Photo")
