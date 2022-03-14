# Multi-Bootloader
Great way to put the Optiboot bootloader into several handy Atmel chips. The Arduino system provides a way to use existing Arduino devices to make an ISP bootloader burner.

After doing it the 'old fashon way' using just a Nano on a protoboard and a few jumpers, I decided to get a board made that was prewired for several chips with Zif sockets. With the jumper removed, load the ArduinoISP program into the Nano.  Now put the jumper in place to prevent accidental overwriting of the program.

This unit support the following Atmel microcontrollers...

ATmega328: For stand alone versions of Uno/Nano.

ATtiny861: For a chip with 15 usable I/O lines.

ATtiny84:  Just right for so many projects.

ATtiny85:  For small projects using 16/64 Mhz clocking.


