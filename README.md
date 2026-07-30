# Smart Car Hardware

An open-source hardware project for an intelligent vehicle. This repository is the single source for schematics, PCB layouts, manufacturing packages, and hardware documentation.

## Repository layout

- `hardware/schematic/` - editable schematic source files and exported PDFs
- `hardware/pcb/` - editable PCB layout source files, drill data, and board renders
- `manufacturing/` - Gerber, BOM, pick-and-place, and assembly packages by release
- `docs/` - design notes, bring-up instructions, and revision history
- `mechanical/` - 3D models, drawings, and enclosure-related files

## Workflow

1. Put editable design source in `hardware/`.
2. Create a versioned manufacturing package under `manufacturing/<version>/` only after design review.
3. Record major changes in `docs/CHANGELOG.md` and tag releases for manufacturable revisions.

## Recommended EDA tools

KiCad is recommended for new designs. Source files from EasyEDA may also be stored, provided their project version and exports are documented.

## License

Hardware design files are released under CERN-OHL-S-2.0. Keep license notices when sharing derived boards or schematics.

## Status

Project scaffold created. Add the first smart-car controller schematic and PCB under `hardware/`.