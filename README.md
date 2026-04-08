# Akku-Craft Schematics

Schematics and PCB layout files for the Akku-Craft hardware platform.

This repository contains the electrical design source used for battery management and monitoring hardware development.

![Schematic Preview](https://akku-craft.usbverkehrtherum.de/wiki/schaltplan.png)

## Scope

This repo focuses on:

- Schematic design (`.kicad_sch`)
- PCB layout (`.kicad_pcb`)
- KiCad project configuration (`.kicad_pro`)

Firmware, web, and mechanical assets are maintained in separate repositories.

## Requirements

- KiCad 9.x (recommended)
- Git for version control

Download KiCad: https://www.kicad.org/

## Quick Start

1. Clone this repository.
2. Open `Schaltplan.kicad_pro` in KiCad.
3. Work from the project root (do not move files out of this directory).

## Repository Structure

```text
Schaltplan.kicad_sch      # Main schematic
Schaltplan.kicad_pcb      # PCB layout
Schaltplan.kicad_pro      # KiCad project file
Schaltplan.kicad_prl      # KiCad local project settings
Schaltplan-backups/       # Automatic KiCad backups
```

## Recommended Workflow

1. Create a branch for your change.
2. Edit schematic and/or PCB in KiCad.
3. Run ERC and DRC before opening a pull request.
4. Keep commits focused and easy to review.

For contribution expectations, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Backups

KiCad can generate backup archives in `Schaltplan-backups/`.

- Keep backups out of commits unless explicitly needed for recovery/documentation.
- If backup files are included intentionally, mention why in the PR description.

## Documentation

- Project wiki: https://akku-craft.usbverkehrtherum.de/wiki
- Contribution guide: [CONTRIBUTING.md](CONTRIBUTING.md)

## License

This project is licensed under the CC BY-NC-SA 4.0 license.
See [LICENSE](LICENSE) for details.
