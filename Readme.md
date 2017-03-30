A simple arduino library for the Itead Nextion HMI.
===================================================

**Nextion LCD Touchscreen Tutorial for Arduino**

http://openhardware.gridshield.net/home/nextion-lcd-getting-started-for-arduino

**Nextion LCD Touchscreen Library Functions**

http://openhardware.gridshield.net/home/nextion-example-code-functions


Note that you can replace "Serial1" with Serial or Serial2 or whatever Serial ports your particular Arduino has.

If you are using an Arduino with only one hardware serial port (like the Arduino UNO) and want to use hardware serial you will have to use "#define nextion Serial" AND will need to remove all code that uses Serial for debugging. If you leave your Serial.print() commands in this case they will send data to the Nextion.
