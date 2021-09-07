# EEPromProgrammer
A project using Arduino and Node.js to read, write, fill, erase, protect, unprotect EEPROM from Node.js.

Necessary components that you need:
* A good quality Breadboard
* Arduino Mega 2560
* Power to Arduino board (USB cable)
* Ardunio dev IDE
* Connectors/wires between Breadboard and Arduino (usually delivered with Arduino board)
* Node js (any version above 1.0 works fine)

# Contents

Using the components above, you can build your own programmatically controlled EEProm-programmer for your projects.
You will be able to perform common operations to the EEPROM: Read, Write, Fill, Erase, Protect, Unprotect.
You will be able to programmatically read a file and write the content to EEProm, or read the content of EEProm and put it in a file.
Also, you will be able to fill the EEProm with a value or erase it using the erase instruction (fills it instantly with 0xff - currently supported by Atmel chips).

Supported (tested) chips are: 
AT28C256 (256K (32K x 8) Paged Parallel EEPROM) 

(more to be added)

# How it works
1. Connect the Arduino and Breadboard according to instructions.
2. Install Node js.
3. Download and unpack the project.
4. Download and install Arduino Ide
5. Upload the eepromprogrammer.ino file to Arduino using the Arduino Ide
6. Configure the Node js with correct COM port.
7. Either make changes to the code to for operations, which suits your needs (read, write etc.)
8. Alternatively, run the example code (e.g. node exampleprogram.js -w eprom.bin COM3 (writes the content of local file eprom.bin to the EEPROM)
