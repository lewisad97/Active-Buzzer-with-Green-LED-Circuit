# Active-Buzzer-with-Green-LED-Circuit
A simple DC powered parallel circuit with Active Buzzer and Green LED.

Overview:

This project demonstrates a simple parallel circuit consisting of a current-limited LED and an active buzzer, powered from a 9V battery via a 5V breadboard power supply module.

A 9V battery is connected to the power supply module, which regulates the voltage to a stable 5V and distributes it to the power rails of an 830 tie-point breadboard. When the power module is switched on, both branches of the circuit are energised simultaneously.

One branch of the circuit contains a green LED in series with a current-limiting resistor. The resistor is used to restrict the current through the LED to a safe level, preventing damage. The forward voltage of the LED was measured at approximately 2.40V using a multimeter.

The second branch of the circuit supplies power to an active buzzer via jumper wires connected to the breadboard power rails. The buzzer emits an audible tone when the power supply module is switched on.

This circuit demonstrates the principles of parallel circuits, safe component protection, and regulated power distribution on a breadboard.

What Was Learned?

How to construct parallel loops on a breadboard using shared power rails.
How to measure LED forward voltage using a multimeter for the first time.
The importance of current limiting using a resistor to safely protect an LED after initially overpowering it.
How a physical breadboard circuit translates into a formal electrical schematic.
How to design and document a schematic using KiCad for the first time.

Further Improvements:

Power the LED and buzzer via the Elegoo R3 microcontroller I/O pins instead of directly from the power rails.
Use software written in C/C++ to add conditions and logic control to the components.
Implement independent control of each component (e.g. timed outputs or conditional activation).

This project emphasised the importance of safe power management and accurate documentation in electronic design.
