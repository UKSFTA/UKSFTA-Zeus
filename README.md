# UKSFTA Zeus Modpack

Tools, functional assets, and quality-of-life improvements for UKSFTA Zeus
operators and mission makers.

## Quick Start

1. Initialize Tools:
   ```bash
   git submodule update --init --remote
   python3 .uksf_tools/setup.py
   ```

2. Sync Dependencies:
   ```bash
   python3 tools/manage_mods.py
   ```

3. Build and Release:
   ```bash
   python3 tools/release.py
   ```

## Structure

- `addons/`: Custom unit modules and mission assets.
- `keys/`: Public signing keys.
- `.uksf_tools/`: Automation submodule.

## Mod Sources

Mission-maker dependencies are managed in `mod_sources.txt`. This pack provides
the necessary logic and assets for mission orchestration.
