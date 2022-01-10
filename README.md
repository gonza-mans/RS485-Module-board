# RS485-Module-board
RS485 Module Board for Arduino, STM32, ESP32, ESP8266, etc. Based on SN75176 or MAX485 (both chip have the same pinout). 
The value of R1 is the impedance characteristic of the cable (for twisted-pair cable R1=120 Ohm). 
R2 and R3 are Fail-Safe resistor, it's values depend of R1 (for R1=120 Ohm, R2=R3= 560 Ohn. For other case, see the formula 2 of page 4 of the text https://www.ti.com/lit/an/slla272d/slla272d.pdf). Remember that, only the master has R2 and R3 soldering, for slave devices you just to solder R1.
