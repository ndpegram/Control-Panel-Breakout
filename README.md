# Simple Control Panel Breakout

This pcb allows the remote control of a point motor via 4 wires:

 1. +5v
 2. Gnd
 3. LED indicator (high/low)
 4. Pushbutton (active low)

These four wires must share a common ground with the controller. They assume that the point's position is toggled by pressing the pushbutton which is active low. The board takes the signal on the single LED wire and converts it to two LEDs to indicate whether the point is straight or thrown.
