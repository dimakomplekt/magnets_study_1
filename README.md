# magnets_study_1
This repository contains files with the implementation of a control system for studying the effect of the plasma flow turbulence degree on heat transfer processes.

This control system is based on two MOSFETs that alternately transmit voltage from the power source to two electromagnets.

Two discrete outputs of the NUCLEO-F401RE debug board (PB4; PB5) are used to generate control pulses.

The closed function "operation(...)" is used to create the necessary switching cycles.

The standard user button "Blue" is used to change the pattern (different duty cycles).

The switching period/frequency is controlled by the variable "period_1" inside the function "operation(...)".

One discrete output is used for the LED, which provides visual control of the pattern change.

The project was developed using the standard ST Electronics programs - "MX CUBE" and "CUBE IDE". The main directory with files is inside a single .zip file here!
