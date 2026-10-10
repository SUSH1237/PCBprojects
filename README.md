# PCBprojects
archive for pcb schematics, documents, and manufacture/soldering

## Projects

### [Project 1 – 2-Channel LM386 Audio Amplifier](Project1-LM386/)
Stereo audio amplifier built around two LM386N-1 power amps.

- 3.5 mm stereo jack input with a dual-gang 10k volume pot
- Per-channel gain network (pins 1–8) and Zobel output network
- 9 V input with 1N4001 reverse-polarity protection and power LED
- 2-layer through-hole board, 2" × 3", with corner mounting holes
- Top-layer routing, bottom-layer ground pour

### [Project 2 – Temperature Alarm Click Board](Project2-TempAlarm/)
mikroBUS™ Click-format board for remote temperature sensing and alarm indication.

- TMP4718 remote/local temperature sensor over I²C
- Remote sensing transistor (MMBT3904) on a slotted tongue, thermally isolated from the rest of the board
- NC7WZ14 Schmitt-trigger inverter drives ALERT (yellow) and T_CRIT (red) LEDs
- ALERT and T_CRIT also routed to the mikroBUS INT and AN pins for the host MCU
- Jumper-selectable 3.3 V / 5 V supply
- 2-layer, mostly SMD (1206, SOT-23, VSSOP-8, SC-70-6), 1.2" × 1.7"
- Hand-routed, bottom ground pour, Gerbers verified on JLCPCB

## Repository contents
Each project folder contains:
- Altium project, schematic, and PCB files (`.PrjPcb`, `.SchDoc`, `.PcbDoc`)
- Component libraries used (`.SchLib`, `.PcbLib`)
- Fabrication package (Gerber + NC drill, zipped)
- PDF prints of the schematic and layout

## Tools
Altium Designer · JLCPCB / PCBWay for fabrication checks
