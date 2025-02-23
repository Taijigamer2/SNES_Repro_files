# SNES_Repro_files
A collection of SNES reproduction files to help with the creation or conversion of SNES game cartridge PCB 

Here is a collection of PCB files for converting your SNES game carts. The most common use is converting Japanese titles such as Star Ocean and ChronoTrigger to English.
Some of the PCB are useful for creating SA-1 or Super FX games such as Gradius III and Star Fox 2.

Star Ocean - Common methods use the 27C322 42 pin EPROM. This is bulky and cumbersome. The other option is to use the 3V 29L320 which is the incorrect voltage for the SNES.
The best option is to use the pin equivalent 5V EPROM 27C320 SOP. Unfortunately this chip is unavailable but the 48 pin TSOP version is, so I made a 48 pin TSOP to 44 pin SOP adapter. 
You will need a 48 pin TSOP 27C320 IC and a way to program it. From what I could tell it doesn't have a standard pinout so you will need a programmer capable of programming it or use the adapter I made which works with the FlashCat_Xport programmer. You will also need a custom version of the FlashCat_Xport.exe to recognise the chip.

