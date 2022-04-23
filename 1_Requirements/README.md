# Required Components:

 ## Atmega328 :
  ATmega328 is an 8-bit, 28-Pin AVR Microcontroller, manufactured by Microchip, follows RISC Architecture and has a flash-type program memory of 32KB.
  Atmega328 is the microcontroller, used in basic Arduino boards i.e Arduino UNO, Arduino Pro Mini and Arduino Nano.
  It has an EEPROM memory of 1KB and its SRAM memory is 2KB.
  It has 8 Pins for ADC operations, which all combine to form PortA ( PA0 – PA7 ).
  It also has 3 built-in Timers, two of them are 8 Bit timers while the third one is 16-Bit Timer.
  You must have heard of Arduino UNO, UNO is based on atmega328 Microcontroller. It’s UNO’s heart. 
  It operates ranging from 3.3V to 5.5V but normally we use 5V as a standard.
  Its excellent features include cost-efficiency, low power dissipation, programming lock for security purposes, real timer counter with separate oscillator.
  It’s normally used in Embedded Systems applications. 
      
 ##  Resister :
          100 ohm
          
##  Display :
       7 segment 
       
## High Level Requirements:

| ID   | Description                                              | Category  | Status      |
| ---- | -------------------------------------------------------- | --------- | ----------- |
| HR01 | User shall be able to display                            | Techincal | IMPLEMENTED |
| HR02 | Admin shall be able to display                           | Techincal | IMPLEMENTED |
| HR03 | User shall be able to give input                         | Techincal | IMPLEMENTED |
| HR04 | User shall be able to update system                      | Techincal | IMPLEMENTED |
| HR05 | User shall be able to perform operation                  | Techincal | IMPLEMENTED |
| HR06 | User shall be able to check the output                   | Techincal | IMPLEMENTED |
| HR07 | Admin shall be able to perform operation of the system   | Techincal | IMPLEMENTED |
| HR08 | Admin shall be able to view Output                       | Technical |  FUTURE     |
| HR09 | System will be maintained                                | Scenario  |  FUTURE     |


## Low level Requirements:
| ID   | Description                                              | HRId   | Status (Implemented/Future) |
| ---- | -------------------------------------------------------- | ------ | --------------------------- |
| LR01 | User choice can be given to set input                    | HR01   | IMPLEMENTED                 |      
| LR02 | User can see the results displayed                       | HR6    | IMPLEMENTED                 |
| LR04 | other applications can be added                          | HR06   | FUTURE                      |
