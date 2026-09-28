# Senior Design PCBs

Editable KiCad projects for the brain, light, power, and pump boards.

## Board previews

3D renders from the KiCad designs. Parts without available 3D models may not appear.

### Brain board

![Brain PCB 3D view](docs/images/brain.png)

### Light board

![Light PCB 3D view](docs/images/light.png)

### Power board

![Power PCB 3D view](docs/images/power.png)

### Pump board

![Pump PCB 3D view](docs/images/pump.png)

## Open the designs

1. Install KiCad 10.0.3 or newer with the standard symbol, footprint, and 3D model libraries.
2. Clone this repository or download and extract the entire ZIP, keeping the folder structure intact.
3. In KiCad, open the project you want:
   - `brain_PCB/brain_PCB.kicad_pro`
   - `light_PCB/light_PCB.kicad_pro`
   - `power_PCB/power_PCB.kicad_pro`
   - `pump_PCB/pump_PCB.kicad_pro`
4. Open its schematic or PCB from the KiCad project manager.

Custom symbols, footprints, library tables, design rules, and the referenced local USB 3D model are included. Local libraries use `${KIPRJMOD}` paths so they work wherever you extract the repository. The USB model is a simplified representation.

Manufacturing outputs, review reports, backups, and personal editor settings are excluded. Generate fabrication files from the projects when needed.

Some power-board 3D models (the 6-pin and 10-pin Molex Micro-Fit connectors and Littelfuse NANO2 fuse) were unavailable in the KiCad 10.0.3 libraries used for verification. Their schematic symbols and PCB footprints are included in the designs; these parts may be absent from the 3D view.
