# 7- Segment Display Pinout Diagram Details
 - This section lists the description of all pins for both common anode and common cathode types.
     ![pin diagram](https://user-images.githubusercontent.com/101447131/164520155-a65f1c6e-a303-4f41-8122-74d2128f7cb1.jpg)
     
   A simple truth table can be used to show how to display each number and letter. This can be
   seen in Table 1. For example, it can be seen that if a 0 is wanted to be displayed the a-f LED
   segments need to be turned on while the g segment is off. Note that B and D are displayed as b
   and d; this is done to obtain a unique, unambiguous shape for each letter. Otherwise, a capital D
   would look identical to a 0 and a capital B would look identical to an 8.
   
   ![inpo](https://user-images.githubusercontent.com/101447131/164529057-70858223-bccb-476f-b0b1-06bff8d8c7fb.png)

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
