# 01 — LM7805 Power Supply

Simple 5V linear voltage regulator board.

## Description

Learning project. Fixed 5V output, LED power indicator.

**Key components:**
- LM7805 — 5V linear regulator (TO-220)
- Input capacitor: 0.33 µF
- Output capacitor: 0.1 µF
- LED indicator + 470 Ohm resistor

## Schematic

![Schematic](./docs/schematic-preview.png)

**LED current calculation:**
I = (9V - 2V) / 470 Ohm = ~15 mA

## Status

- [x] LED circuit schematic (Day 4)
- [ ] Full LM7805 schematic
- [ ] PCB layout
- [ ] Gerber files
- [ ] BOM