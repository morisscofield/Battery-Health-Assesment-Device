This repo describes the analysis and design of a prototype battery health assessment device. The described device
consists of an ATmega 328P microcontroller that outputs a Pulse Width Modulation (PWM) signal. This signal drives a constant
current load circuit that is used to determine the nominal voltage and internal resistance of a AA battery. The battery information
is determined by the microcontroller and is then output on an LCD screen. Moreover, the device is designed to work with a LR6
alkaline battery with 1.5 V maximum nominal voltage and 0.15 internal resistance.

#Use LTspice to run the simulation
#Parameters pre-moded in C
