# Printed Circuit Board Assembly (PCBA) Information

## Assembly info

- Assemble to IPC Class 2 or better
- Bake components that are not moisture sealed to appropriate levels as required.
- Solder paste MUST be leaded.
- Aqueous flux and wash strongly preferred.
   - Clean to NASA Standard "Visibly Clean (VC)": No particles or residues are visible to the naked eye.
- No conformal coating.
- Ship in antistatic protective bag

## Component Specific Assembly  Information

- Press fit nuts may be installed after component placement.
- CM1 and CM2 should be hand placed.
- R1 must be hand placed according to the OreSat deployer SOP.

## Assembly Files

### Bill of materials

| Filename                    | Description                            |
| --------------------------- | -------------------------------------- |
| -bom.csv                    | BOM in Comma Separated Variable format |

### Mounting location files

| Filename             | Description                                 |
| -------------------- | ------------------------------------------- |
| -3u.pos              | Pick and place locations for components     |

### Stencils

| Filename          | Notes                                |
| ----------------- | ------------------------------------ |
| -B_Paste.gbr      | RS274X file for solder paste stencil |
| -F_Paste.gbr      | RS274X file for solder paste stencil |

### Other Assembly Information

| Filename             | Description                             |
| -------------------- | --------------------------------------- |
| -ipc2581.xml         | IPC-2581 netlist and board layout file  |





