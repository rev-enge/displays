# Identification of the board

```
STATIC CONTROLS CORPORATION
ASSEMBLY # AD-0952-001 REV 0
```

Copper marking: CB-0952-300 REV A

# Description

This board could not be found anywhere at the site of the manufacturer: http://www.scccontrols.com/ any more.

Sometimes you see them for sale on the internet for a relatively small amount of money.

However I found some documentation about a command protocol but its unsure if
 the board works with this protocol. (Thats the next I'm working on)

This board has an RS422 full-duplex interface: One RS485 tx/rx pair to receive
 the data from a PC or other control system (J3) and one RS485 tx/rx pair to
 send data from the board back to the PC or loop it thru to the next display
 board (J2).

It has a 5-digits of 11(H) x 15(V) 5 mm leds. Horizontal pitch=7.1 mm, vertical pitch=7.6 mm. The PCB size is: X = 423 mm, Y = 165 mm

J1 is the power connector: A molex MLX series 42021 6.35mm pitch Vertical 2 Circuits, PA Polyamide Nylon 50-84-1020

J2/J3 are RJ12/6-4 sockets.

The boards probably originate from around 2000 according to date codes on the ICs.

# Pin connections

Pinouts of theplugs.

```
Power plug:
J1-1 = GND
J1-2 = +5V

Downstream port:
J2-1 = na
J2-2 = Driver RS485 (+) : U17-9
J2-3 = Driver RS485 (-) : U17-10
J2-4 = Receiver RS485 (+) : U11-12 + R18(120E)
J2-5 = Receiver RS485 (-) : U11-11 + R18(120E)
J2-6 = na

Upstream port:
J3-1 = na
J3-2 = Receiver RS485 (+) : U11-12 + R12(120E)
J3-3 = Receiver RS485 (-) : U11-11 + R12(120E)
J3-4 = Driver RS485 (+) : U11-9
J3-5 = Driver RS485 (-) : U11-10
J3-6 = na
```

# Utilities used to create the drawings

The schematic diagram is made with KiCad 6.0.11
