                                          # 7-Segment Display Interfacing with Atmega328 #
## Abstract
- Seven-segment displays are electronic display devices used as an easy way to display decimal numerals and an alterative to the more complex dot-matrix displays.
- The LDS-C303RI, a common seven-segment display, will be examined. Common anode vs. common cathode will be outlined.
- LED drivers such as the CD74HC4511E will also be discussed. Design applications such as digital
  clocks and electronic meters will be covered briefly.
  
  ## Introduction
 - 7-segment displays are made up of 8 LED segments. 7 of these LED segments are in the shape of a line, whereas 1 segment is circular.
 - The 7 line-shaped LED segments are used for displaying numbers 0 to 9 and a few letters like A, c, d, e, F, H, L, O, P, U, etc. The circular segment is used for          displaying a decimal point.
 - Each of the 8 elements has a pin associated with it which can be driven HIGH or LOW according to the type of display and the number or alphabet to be display.
 - The common anode and common cathode types are available in a 7-segment display. 
 - Depending on which type is used, the control signal required to light up a segment in  the display changes.
 - Common anode requires a LOW signal whereas common cathode requires a HIGH signal to light up a segment.
 
 ![led display](https://user-images.githubusercontent.com/101447131/164503048-25fe51e0-c664-4582-b301-e9f64cd382c3.jpg)

## Objective
 - 7-segment displays are made up of 8 LED segments. 7 of these LED segments are in the shape of a line, whereas 1 segment is circular.
 - The 7 line-shaped LED segments are used for displaying numbers 0 to 9 and a few letters like A, c, d, e, F, H, L, O, P, U, etc. The circular      segment is used for displaying a decimal point.
 - Each of the 8 elements has a pin associated with it which can be driven HIGH or LOW according to the type of display and the number or alphabet    to be displayed.
 - The common anode and common cathode types are available in a 7-segment display. Depending on which type is used, the control signal required to    light up a segment in    the display changes. Common anode requires a LOW signal whereas common cathode requires a HIGH signal to light up a      segment.

## Methods
  Seven-Segment Display
  - When dealing with seven-segment displays, there are two types. Common anode and common cathode; 
  - In common anode all the anodes on the display are tied to a common pin, typically the power source, and the LED are controlled via the             cathodes with ground being on     and power being off.
  - In common cathode all the cathodes are tied to a common pin, in this case generally ground, and the LED are driven by the state of the anodes      where ground is off and power is on. 
 
  ![CA](https://user-images.githubusercontent.com/101447131/164504368-8bb93fef-9ec7-4203-8eec-278a26a337a0.jpg)

  ![cc](https://user-images.githubusercontent.com/101447131/164504410-fc7b9787-7796-4bc6-badd-188e545654c5.jpg)
