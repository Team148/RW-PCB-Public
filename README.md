# RW-PCBs

Disclaimer: These were only designed, and prototyped but have not been tested.

These PCBs are RW version of the Talon SRX Breakout Board and a simple CAN Bus Daisy Chain Board. This is standardized around
the Molex SL latching type of connector (50-57-9405). This type of connector also connects to US Digital S5 Encoders
```
Talon SRX Breakout Board BOM
  Harwin M50-3000745     Qty 1 (Cut off outer 4 pins)
  Molex 15-91-3053       Qty 1
  Lite-On LTST-C171KRKT  Qty 1 (Optional)
  Susumu RR1220P-222-D   Qty 1 (Optional)
```

CAN Devices need to be wired into a Molex SL type connectors(50-579404) with the H (green) paired in the middle 2 positions,
and the L's on the outer two positions. The twisted pairs need to be next to each other. Devices must be plugged
in Sequentially and the last device must be terminated with an 120 Ohm resistor (can be PDP). These boards can also
be daisy chained if above 14 devices, simply attach port 13 to another board's port 0.The port numbers are just for reference,
they do not have to correspond to CAN ID.
```
RW CAN
  Molex 70543-0108       Qty 14
```
GERBER Files are exported for SEEEDSTUDIO's FUSION Service @ $4.90 + ship.
