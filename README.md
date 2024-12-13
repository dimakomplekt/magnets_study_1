# magnets_study_1
This repositoy contains the files with realisation of the control system for the study of the plasma flow turbulence degree influence on the heat exchange processes.

This control system is built on the basis of two mosfet transistors, which alternately transmit voltage from the power source to two electromagnets.

Two discrete outputs of the NUCLEO-F401RE development board are used for control pulses generation (PB4; PB5).

The standart "Blue" user-button is used for the pattern changing.

One discrete output is used for the LED, which is provided of the visual control of pattern change.

The private function "void operation(...)" is used for the creating of the needed commutation cycles.
