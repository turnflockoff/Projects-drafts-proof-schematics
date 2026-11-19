# V-E0 — Project Overview

## Purpose
V-E0 is a neutral codename for independent visual research into the electronics of a shared-ride electric scooter / e-bike platform and the feasibility of a separate ESP32-S3 dashboard/interface concept. This is exploratory documentation, not a claim of successful reverse engineering or a completed retrofit.

## Working hypothesis
The original display/control assembly may combine display functions, low-voltage power distribution, external I/O, serial communications, and cellular/GPS-related hardware. A separate ESP32-S3 interface may be feasible only after connector functions, electrical levels, protocols, battery limits, and mechanical dimensions are measured and validated.

## Observed evidence
Photographs document a multi-board assembly, connector panel, PCB markings, wiring labels, and a battery label. Visible connector labels include USB DEBUG, BRAKE, THROTTLE, SPEAKER, LED, DATA, 5V OUTPUT, 12V OUTPUT, and FRONT LIGHT.

Visible board/module markings include SL2550_N02, T670VC_MB_V1.02_PCB, and MeigLink SLM750. Signal labels include BMS-TX, BMS-RX, SPK-/SPK+, DB-RX, DIO, MCU-TX, MCU-RX, 3V3, GND, 12V, 12V-LED, BRAKE-BAT, and VDD5V.

A battery label appears to state 46.8 V, 15 Ah, and 702 Wh. The apparent cell-configuration marking is not sufficiently clear to establish chemistry or full-charge voltage. Confirm against pack and BMS documentation before electrical work.

## Not established
No verified connector pinout, measured voltage table, decoded protocol, complete KiCad schematic, manufacturing-ready PCB, firmware integration, fabricated replacement board, successful bench test, or powered vehicle test is claimed.

## Independence and safety
V-E0 is an independent research codename. No affiliation, authorization, sponsorship, or endorsement by any scooter operator or manufacturer is claimed. Do not bypass rental locks, payments, geofencing, fleet management, or safety interlocks. Do not connect experimental electronics to throttle, brake, or traction-control circuits without a documented safety case and qualified review.
