Fermento
========

An open-source incubator for fun and profit.

Board
-----

* __Fermento__ is the layout I sent for fabrication to a PCB house.
* __Fermento_1side__ is the homebrew version for home printing. The layout is one-sided for easier printing.

Bill Of Material
----------------

* 2x Tactile switch (through hole)
* 2x Resistor 10K (R1, R3)
* 1x Resistor 1K (R2)
* 4x Capacitor 0.1uF (C1, C2, C3, C5)
* 1x Electrolytic capacitor 47uF (C4)
* 1x 6-pin 90-degrees header
* 1x 6-terminal screw block (Altech MBE-156)
* 1x Relay, 3VDC switching (Omron G6RL-1A-DC3)
* 1x 13mm buzzer (Murata, PKM13EPYH4000-A0)
* 1x DC jack 2.1mm (Kobiconn 163-179PH-EX)
* 1x 32.768kHz crystal (ECS-.327-12.5-13X)
* 1x Mosfet transistor, TO92 (Supertex TP2104N3-G)
* 1x 3.3V Regulator, TO220 (TI TLV2217-33KCSE3)
* 1x Temperature sensor, TO92 (TI LM61CIZ/NOPG)
* 1x 7-segment 4-digit display (Lumex LDQ-N514RI)

Firmware
--------

To install the firmware in your Arduino IDE, do the following.

* Copy the folder `firmware/Fermento` to your local Arduino folder.
* Copy the content of `firmware/hardware` to local `Arduino/hardware`.
* Copy the content of `firmware/libraries` to local `Arduino/libraries`.

Then, chose `Tools -> Board -> ATmega32 on a breadboard`. Choose the sketch
`Fermento` from the sketchbook, and upload it.

In case you don't use the homebrew version, there is one line to comment out in
the sketch to change the pin mapping.

