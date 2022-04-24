REQUIREMENTS

INTRODUCTION
This project uses an ultrasonic sensor to indicate the distance of any object from it. Here we have made a setup based on a microcontroller in which real time distance is sensed by an ultrasonic sensor and displays measured distance on an LCD display.

RESEARCH
The source code is to be compiled in VS CODE with AVR compiler. This DISTANCE FINDER in EMBEDDED C is not designed to run on the Turbo C versions. The source code for this mini project is around 1000 lines, so I didn't want to display it here.

COMPONENTS REQUIRED
Hardware: ATMEGA328P, Power supply (5v), AVR-ISP PROGRAMMER, JHD_162ALCD (16x2LCD), 1000uF capacitor, 10K resistor (2 pieces), HC-SR04 sensor.

4'W and 1'H

WHAT
Distance Measurement

WHERE
Determining the distance of an object from another object or obstacle without any physical contact involved 

WHEN
Measure the distance to a wide range of objects regardless of shape, color or surface texture.

WHY
Manual distance measuring is always done at the expense of human error.

HOW
Transmit sound waves toward a target and will determine its distance by measuring the time it took.

APPLICATION
The device can be used in many different fields and categories like distance calculation in construction field, robots, car sensor to avoid obstacles and many other applications.

HIGH LEVEL TEST PLAN
# Test Case
### Table
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 | LCD Message Display |switch on| "HELLO WORLD" |Pass|
| T_02| Universal Asynchronous Receiver Transmitter(USART) communication| data  | data |Pass|
| T_03 | Pulse With Modulation in sensor |in static|  successfully added |Pass|
| T_04| Voltage changes |5v| distance(173in,441cm)|Pass|

LOW LEVEL TEST PLAN
## Table no : Low Level test plan
| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  When switch is close | switch closed | No LCD Displays |
| L_02| When Potentiometer is set at 0|0v |0 distance|
