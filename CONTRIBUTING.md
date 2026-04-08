# Contributing to Akku-Craft Schematics

Thanks for your interest in contributing to the schematics and PCB work. This repository is focused on the electrical design side of Akku-Craft, so small, careful improvements are usually more valuable than large rewrites.

---

### Before anything else: check the context

Please take a quick look at the project documentation before editing files:

- [README.md](README.md)
- [Akku-Craft Wiki](https://akku-craft.usbverkehrtherum.de/wiki)

This helps keep symbol naming, design intent, and board layout decisions consistent.

---

### Tooling and file expectations

This repository is maintained in **KiCad 9.x**.

- Open the project via `Schaltplan.kicad_pro`
- Main schematic: `Schaltplan.kicad_sch`
- PCB layout: `Schaltplan.kicad_pcb`

Please do not hand-edit KiCad files in a text editor unless you are fixing a merge conflict and know exactly what you are changing.

---

### What kind of contributions are useful

Typical high-value changes include:

- Schematic readability improvements (labels, net clarity, annotations)
- PCB cleanup (placement, routing quality, silkscreen clarity)
- Consistency fixes for footprints, references, and naming
- ERC/DRC issue reductions
- Documentation updates for hardware decisions

If you are planning bigger architecture changes (power stage, connector strategy, safety concepts), open an issue or discuss first.

---

### Pull request guidelines

When opening a PR, keep it focused and explain the engineering reason behind the change.

Please include:

- A short summary of what changed
- Why the change is needed (problem solved, risk reduced, manufacturability improved, etc.)
- Which files were touched
- Screenshots for schematic/PCB changes when useful
- ERC/DRC status (clean, or known remaining warnings/errors with explanation)

Small PRs are easier to review and merge quickly.

---

### Contact

The easiest way to coordinate is via **Discord**:

- **jumpstone4477** (preferred)
- **akku_craft**

If Discord is not an option, use the contact method listed in the Akku-Craft project channels.

---

### One last thing

Hardware changes have long tails: manufacturing, assembly, and safety all depend on details. Please optimize for clarity, traceability, and reviewability.

If you're unsure whether an idea fits, ask early.

We look forward to your contribution.

— _The Akku-Craft Team_
