# max32660_lm75a

## MAX32660 LM75A Library (Experimental)

This repository has an experimental codesets running on MAX32660-EVKIT accessing for LM75A Temperature Sensor board (CJMCJ-75) through I2C protocol(bus). I developed the code using Maxim Integrated EV Kit Software, Low Power ARM Micro Toolchain(windows) which you can download from following link:

https://www.maximintegrated.com/en/design/software-description.html/swpart=SFW0001500A

Basically, it is Eclipse Neon with GNU ARM Toolchain (on Windows) and board specific libary source codes.

Note: This code set is not completed yet. However, you can use this code as a starting place on how to use maxim i2c library.


# Development Platform Information: 

## MAX32660-EVKIT (Evaluation Kit for the MAX32660)

https://www.maximintegrated.com/en/products/microcontrollers/MAX32660-EVKIT.html

* MAX32660-EVKIT Board
* MAX3265PICO Debug Adapter
* SWD ribbon cable
* USB A to Micro B cable


# FTDI D2XX Programming

http://www.ftdichip.com/Support/Documents/DataSheets/Modules/DS_UMFT201_220_230XB.pdf

##  FTDI UMFT201XB, I2C Slave USB Dongle or  FTDI’s FT201XQ Breakout Board

There is I2C sample code comes with i2c library in the maxim toolchains. However, I wasn't able start immeidately. So, I decided to use FTDI FT201XQ breakout board with D2xx library. With this breakout board, I was able to power the max32660 board and get immediately result as I programming. I will add more on my experience later.
