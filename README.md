# M1_module2pro

# 3 Phase PWM

# Project Specification

Brief description
A fixed frequency three phase PWM generation code for an AVR ATMEGA328P/-PU microcontroller and schematic for a variable frequency drive system for an AC induction motor. The schematic for the system consists of an AVR ATMEGA328P-PU controller, SI8234 isolated gate driver, and transistors protected with diodes and bootstrap circuits.

Important note regaring variable frequency logic
Variable frequency was attempted but the implementation logic was not sound (I had just finished 2nd-year electrical engineering and most of the project involved subjects that were new to me). Some additions and changes were made, but ultimately a new lookup table has to be generated to achieve consistent outputs for varying frequencies.
