# Simple Control Panel Breakout

This pcb allows the remote control of a point motor via 4 wires:

 1. +5v
 2. Gnd
 3. LED indicator (high/low)
 4. Pushbutton (active low)

These four wires must share a common ground with the controller. They assume that the point's position is toggled by pressing the pushbutton which is active low. The board takes the signal on the single LED wire and converts it to two LEDs to indicate whether the point is straight or thrown.

The button and LEDs can be mounted directly onto the PCB and the PCB attached to the rear of the panel using the included screw hole. In this case, through-hole (THT) LEDs are recommended. The tactile switch should have a shaft long enough to protrude through the panel fascia. Included is a drilling template (created in FreeCAD) which can be used to drill the button and LED holes. Note that surface-mount (SMD) LEDs could be used by soldering them between the LED pads on the PCB.

Alternatively, the PCB can be mounted elsewhere, and the LEDs and button connected via wires to the appropriate holes on the PCB. 
