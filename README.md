## Adafruit I2C to 8 Channel Solenoid Driver - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6318"><img src="assets/6318.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit I2C to 8 Channel Solenoid Driver - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6318

### Description

Solenoids are a little like cats: if your project has one solenoid you'll probably stick with just one and in such cases our single MOSFET driver will work well. But if you have more than one solenoid, it's going to be anywhere from 2 to 24. Why? Maybe people just love their purring clicky-clacking. And driving a lot of solenoids is kind of a pain: they all need drive transistors and flyback diodes and then a common power source. That's why we designed the Adafruit I2C to 8 Channel Solenoid Driver featuring an MCP23017 GPIO expander to make eight solenoids at a time easy and solder-free.

This board has an I2C to GPIO expander - so you can use it even if you don't have a lot of pins on your microcontroller. Power the solenoids with a DC power supply in the center terminal blocks, you can use 3V to 24V DC maximum. Then wire up each solenoid to the remaining terminal blocks. The positive side will tie to the power supply you provided, and then the negative side will connect to ground when activated. Each solenoid has its own pass transistor AO3406 N-Channel MOSFET rated for 30Vds, 3.6A peak, and 70mΩ RdsOn. A flyback diode protects your circuit from the inductive kick-back, and a red LED will light up to let you know that the transistor is on.

Since the MCP23017 has 16 total IO pins, we also bring out the B port, which you can use for other general purpose I/O: as LED drivers, or button inputs. There's also three address pins you can jumper closed so up to 8 boards can be daisy-chained together for a total of 64 solenoids.

The Adafruit I2C to 8 Channel Solenoid Driver can be powered/driven with 3V or 5V power and logic so it's usable by everything from an Arduino-compatible Metro 328 to the latest Raspberry Pi. And the SparkFun Qwiic compatible STEMMA QT JST SH connectors ease the process of connecting the Solenoid Driver to your project and allows you to easily share an I2C bus with other STEMMA QT, Qwiic, Grove, or other compatible sensors. QT Cable is not included, but we have a variety in the shop. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
