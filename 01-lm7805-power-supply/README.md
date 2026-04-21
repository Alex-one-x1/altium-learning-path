# 01 — LM7805 Power Supply

Simple 5V / 1.5A linear voltage regulator board.

## Description

Fixed 5V output from 7–35V input using LM7805 linear regulator.
LED power indicator on output. Designed as a learning project.

**Specifications:**
- Input voltage: 7–35V DC
- Output voltage: 5V DC (fixed)
- Max output current: 1.5A
- LED indicator current: ~6 mA

**Key components:**
- U1: LM7805 — 5V linear regulator (TO-220)
- C1: 0.33 µF — input bypass capacitor
- C2: 0.1 µF — output bypass capacitor
- R1: 470 Ohm — LED current limiting resistor
- D1: LED — power indicator
- J1: 2-pin connector — power input 9V
- J2: 2-pin connector — power output 5V

## Schematic

![Schematic](./docs/schematic-preview.png)

**LED current:** I = (5V - 2V) / 470R = ~6 mA

## Status

- [x] LED circuit schematic (Day 4)
- [x] Full LM7805 schematic (Day 5)
- [x] PCB created, components placed (Day 6)
- [x] PCB routing complete (Day 7)
- [ ] Gerber files
- [ ] BOM