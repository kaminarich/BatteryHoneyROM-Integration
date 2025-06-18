# BatteryHoney - Native ROM Integration (Rust)

BatteryHoney is a lightweight background service written in Rust for Android ROMs. It optimizes power usage by adjusting CPU frequency based on screen state.

## Description

- Locks CPU frequency to minimum when the screen is off.
- Restores original CPU settings when the screen is on.
- Runs natively via `init.rc` without requiring Magisk or root modules.

## Integration

For installation and integration steps, refer to `guide.txt`.

## License

Licensed under the Kaminarich License v1.0.

- Free for personal and non-commercial use.
- Redistribution is allowed as-is with proper attribution.
- Modification of authorship or commercial distribution is prohibited.

See `LICENSE` for full terms.