# Embedded Development

Contains firmware source files for AeroLinkers.

## Contents

- **libraries/** — Peripheral and sensor driver libraries
- **headers/** — Project-wide header and pin definition files
- **config/** — Board config, RTOS settings, and linker scripts
- **device-overlays/** — Device Tree / Zephyr overlay files for hardware description

## Building

```bash
west build -b <your_board> embedded-dev/
west flash
```
