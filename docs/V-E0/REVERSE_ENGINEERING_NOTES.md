# V-E0 — Reverse-Engineering Notes

## Visible connector panel labels
- USB DEBUG
- BRAKE
- THROTTLE
- SPEAKER
- LED
- DATA
- 5V OUTPUT
- 12V OUTPUT
- FRONT LIGHT

These are label observations, not verified pin functions or electrical ratings.

## Visible PCB / module markings
- SL2550_N02
- T670VC_MB_V1.02_PCB
- MeigLink SLM750 LTE

## Visible signal labels
- BMS-TX / BMS-RX
- MCU-TX / MCU-RX
- SPK- / SPK+
- DB-RX
- DIO
- 3V3
- GND
- 12V
- 12V-LED
- BRAKE-BAT
- VDD5V

Labels alone do not establish connector orientation, pin mapping, voltage, direction, logic standard, or protocol.

## Battery label observation
The photographed label appears to show 46.8 V, 15 Ah, and 702 Wh. Do not infer chemistry, series count, maximum charge voltage, or BMS limits from this alone. Obtain pack documentation and verify with safe measurement procedures before connecting anything.

## Required next evidence
- Connector photographs showing pin numbering and orientation.
- Continuity and voltage measurements with test conditions documented.
- Controller model and electrical ratings.
- Battery chemistry and BMS documentation.
- Passive protocol captures with baud rate and signal-level evidence.
- Measured mechanical dimensions.
- A traceable schematic tied to measurements.
