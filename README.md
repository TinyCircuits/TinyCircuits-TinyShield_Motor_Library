# \[DEPRECATED\] TinyCircuits Motor Driver Arduino Library

*Note: This library was deprecated in favor of the **[ATtiny841 Library](https://github.com/TinyCircuits/TinyCircuits-ATtiny841-Library)** - if using the ATtiny841 Library, be sure to remove the Motor Driver Library from the Arduino/libraries folder so that there are no conflicts between the libraries*

This library is intended for use with TinyCircuits' ASD2302 Dual Motor Driver TinyShield and ASD2303 Servo Controller Tinyshield. These shields use a ATtiny841 microcontroller with firmware that allows the 16 bit PWM outputs to be controlled through I2c. The Arduino library itself allows for easy interface using the TinyDuino platform. Included with the library is the ATtiny841 firmware- it is intended to be hackable and allow for extra functionality to be implemented(full ATtiny register access through I2C).

## Basic Example

Example programs are included that show how to drive motors or servos from the TinyDuino.
