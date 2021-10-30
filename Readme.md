Piggyback is a small circuit board that carries an Atmega-32u4-MU microprocessor and all of the supporting components needed for it to run. The only thing you need to provide is 5V power and ground.

![Piggyback 1.0 Image](https://github.com/NCKiser/Piggyback/blob/1c746d0e03b7dc0ca6e609dd61bb62d86d96331c/Piggyback_1.0.png)

Piggyback has 4 legs, each with 8 castellated holes spaced 0.1in (2.54mm) apart. These legs break out all of the GPIO, power, and USB Data pins. Each leg roughly corresponds to a port of the 32u4's IO.

Piggyback was designed with custom mechanical keyboard PCBs in mind. The board fits snuggly under a row of MX or Alps style switches spaced 0.75in (19.05mm) apart. The legs fit within the space between the switch footprints.

Piggyback features ESD protection on the USB data lines, as well as a 500mA resettable polyfuse on the 5V line.

To use the Piggyback in your PCB designs, (load and place the symbol and footprint in your schematic and PCB), and wire it up to your USB port and key matrix. If you are using a USB-C connector, you will need to take care of the CC pins on your own (usually with 5.1k resistors to ground).

PiggybackBT is based on the Kikoto bluetooth pro-micro board, source for that can be found here: https://github.com/zhiayang/mikoto

This is open-source, as long as you give credit, and is free for commercial use. You can make, modify, and sell this board as you please, as long as you do not claim to own the copyright.
