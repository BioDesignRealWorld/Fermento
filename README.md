Fermento
========

An open-source incubator for fun and profit.

__Fermento__ is the layout I sent for fabrication to a PCB house.
__Fermento_1side__ is the homebrew version for home printing.

To install the firmware in your Arduino IDE, do the following.

* Copy the folder `firmware/Fermento` to your local Arduino folder.
* Copy the content of `firmware/hardware` to local `Arduino/hardware`.
* Copy the content of `firmware/libraries` to local `Arduino/libraries`.

Then, chose `Tools -> Board -> ATmega32 on a breadboard`. Choose the sketch
`Fermento` from the sketchbook, and upload it.

In case you don't use the homebrew version, there is one line to comment out in
the sketch to change the pin mapping.
