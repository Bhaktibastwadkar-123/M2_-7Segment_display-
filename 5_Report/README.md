# Seven Segment Display

- 7-segment displays are made up of 8 LED segments. 7 of these LED segments are in the shape of a line, whereas 1 segment is circular.
- The 7 line-shaped LED segments are used for displaying numbers 0 to 9 and a few letters like A, c, d, e, F, H, L, O, P, U, etc. The circular segment is used for         displaying a decimal point.
- Each of the 8 elements has a pin associated with it which can be driven HIGH or LOW according to the type of display and the number or alphabet to be displayed.
- The common anode and common cathode types are available in a 7-segment display. Depending on which type is used, the control signal required to light up a segment in     the display changes. 
- Common anode requires a LOW signal whereas common cathode requires a HIGH signal to light up a segment.
- Seven-segment displays first became widely used as a popular way of displaying numbers. Today they are used as displays in home appliances, cars, and various digital     devices.
- It is capable of displaying the numbers 0-9 and the letters A-F by lighting the appropriate segments.

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
  
  # Display Driver
  Controlling a seven-segment display will require eight pins for most displays and nine pins if it has a decimal point. This adds a lot of wiring to the circuit;       however the use of a display driver can simplify this by reducing the number of pins required to four. A display driver is a simple logic based device that is passed   a 4-bit binary input which is decoded and translated into the correct pin values for the display, see Appendix for chip schematic. So if we wanted the display
  to show a C representing the number 12 we would pass it the 4-bit representation 1100. It must be kept in mind however that not all drivers are capable of displaying   the letters A-F. 
  
 # Discussion
  Seven-segment displays are very convenient to use and simple to design. The specific application of using a seven-segment display as a method of showing a numerical   output for a binary counter was discussed here. However, the basic framework provided here should yield other applications as well. The displays are highly versatile   and with proper input can display a variety of numbers, letters, and figures. If the case occurs where multiple digits are needed to be displayed, then by expanding   on the applications provided serial inputs should be found that allow control of a set of digits from only a few inputs. 
