# mission-unified-hardware

Hardware files for Mission Unified, a hybrid UAV–UGV system built as a final year project at the Air Force Institute of Technology (AFIT), Kaduna. The vehicle is a quadcopter carried on a wheeled ground chassis, so the same platform can fly and drive.

## What's in here

The `renders` folder has three CATIA views of the assembly: front, isometric and side. The `flight-controller/betaflight` folder has the Betaflight configuration for the flight controller, an OMNIBUSF4SD board (STM32F405) running Betaflight 2025.12.2.

`betaflight-diff.txt` holds only the settings that differ from Betaflight's defaults. Paste it into the Betaflight CLI to restore them. `betaflight-full-dump.txt` is the complete dump, kept for reference. The chip's unique ID has been removed from both.

This repository doesn't yet include the native CATIA files or STEP exports.

## Third-party parts

Some component models in the renders, such as motors, propellers and wheels, may come from their manufacturers and stay their property. The licence below covers our own work only.

## Licence

Creative Commons Attribution 4.0 International. See [LICENSE](LICENSE).

Copyright 2026 John Obaloluwa Ayodele, Divine Ehmoyi Waziri and Oluwapelumi Temitayo Falade.

## Team

- Oluwapelumi Temitayo Falade: https://github.com/faladeemmanuel55-ai
- John Obaloluwa Ayodele: https://github.com/Official-John
- Divine Ehmoyi Waziri: https://github.com/Mr-Gold04

Supervisor: Engr Rexcharles Enyinna Donatus.

## Related repositories

- [mission-unified](https://github.com/Mission-Unified/mission-unified), the project overview
- [mission-unified-software](https://github.com/Mission-Unified/mission-unified-software), the software
