# Configuration Summary

Derived from `Hex_Cfg.h` in the uploaded source.

## Motion architecture
- 6 legs
- 3 DOF per leg (18 DOF total)
- Controller path: BotBoarduino-compatible Arduino sketch
- Servo controller path: SSC-32 serial at 38400 baud
- Input path: PS2 controller via PS2X library

## Pin summary (BotBoarduino profile)
- SOUND_PIN: 5
- PS2_DAT: 6
- PS2_CMD: 7
- PS2_SEL: 8
- PS2_CLK: 9
- SSC TX (to SSC-32 input): 12
- SSC RX (from SSC-32 output): 13

## Geometry values in current config
- Coxa length: 35 mm
- Femur length: 100 mm
- Tibia length: 100 mm
- Initial Y: 60 mm
- Initial XZ radius: 120 mm

## Notes
- The included `Hex_Cfg-Orig.h` was retained as a legacy reference snapshot.
- Main sketch include was normalized to `Hex_Globals.h` for cleaner case-sensitive file handling.
