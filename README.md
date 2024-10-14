# Block-JAN6418

A simple yet flexible gain stage based on the JAN6418 subminiature pentode.

## Features

- Filament supply options:
    - 2x resistor voltage drop
    - LM317L direct regulation
- Pentode/Triode mode:
    - Triode: Jumper (0 Ohm resistor) S2 to the plate
    - Pentode: Solder a resistor between S2 and the plate, and S2 and ground
    - Pentode: Solder leads to an off-board potentiometer in lieu of the two
      resistors
- Star ground: Every on-board ground connection has its own trace to `Sig_gnd`

## Background

I've been designing a blues harp preamp for a buddy of mine, and it occurred to
me that all valve gain blocks are essentially the same, just with some variance
in component values. Because I tend to have different ideas for an individual
gain block, and different ideas about interstage connections (capacitor types,
tone stack, delay/echo, etc), having this board allows me to play with different
ideas more easily than pulling up components from the breadboard, but at the
cost of components soldered into place.

