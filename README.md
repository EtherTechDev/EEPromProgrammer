# EEPromProgrammer
A project using Arduino and Node.js to read, write, fill, erase, protect, unprotect EEPROM from Node.js.

Necessary components that you need:
* A good quality Breadboard
* Connectors/wires to Arduino
* Arduino Mega 2560
* Node js (any version above 1.0)

# Contents

Using the components above, you can build your own EEProm-programmer for your projects.
You will get programmatic control over the common operations (Read, Write, Fill, Erase, Protect, Unprotect).
You will be able to programmatically read a file and write the content to EEProm, or read the content of EEProm and put it in a file.
Also, you will be able to fill the EEProm with a value or erase it using the erase instruction (fills it instantly with 0xff - currently supported by Atmel chips).

Supported (tested) chips are: 
AT28C256 (256K (32K x 8) Paged Parallel EEPROM) 

(more to be added)

