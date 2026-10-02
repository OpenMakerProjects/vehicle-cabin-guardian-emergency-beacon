# Vehicle Cabin Guardian Emergency Beacon

Build a smart vehicles prototype that uses camera to send location after a confirmed emergency. Include setup instructions, a circuit diagram, tested firmware, and sample output.

> Build and test at safe low voltage. Real machinery, vehicles, aircraft, pumps, and power systems require qualified engineering review and certified safeguards.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 799 |
| Category | Smart Vehicles |
| Platform | Arduino Nano 33 BLE |
| Difficulty | Intermediate |
| Estimated build time | 24 hours |
| Connectivity | BLE |
| Core components | camera |
| Control mode | safety latch |

## Repository layout

- `firmware/vehicle-cabin-guardian-emergency-beacon/vehicle-cabin-guardian-emergency-beacon.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/vehicle-cabin-guardian-emergency-beacon/vehicle-cabin-guardian-emergency-beacon.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Nano 33 BLE**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Emergency Beacon demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
