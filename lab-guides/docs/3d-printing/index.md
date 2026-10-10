# 3D Printing: Overview & Safety

Our printer is a **Bambu Lab X1-Carbon**. It builds parts one thin layer of melted plastic at a time.

## How it works: FDM

**Fused Deposition Modeling** works like a very precise robotic hot glue gun:

1. **Filament:** 1.75 mm plastic on a spool
2. **Extruder:** gears push the filament forward
3. **Hot end:** melts it (around 220 °C for PLA)
4. **Nozzle:** a 0.4 mm opening draws a thin line
5. **Build plate:** heated; the part grows layer by layer

### Words you'll need

| Term | Meaning |
|---|---|
| **Layer height** | How thick each layer is |
| **Walls** | The solid outer shell lines |
| **Infill** | The pattern inside the part, rarely 100% solid |
| **Supports** | Temporary scaffolding under overhangs |

## Meet the X1-Carbon

| | |
|---|---|
| Build volume | 256 × 256 × 256 mm |
| Nozzle | 0.4 mm hardened steel |
| Max nozzle temperature | 300 °C |
| Enclosure | Fully enclosed |
| AMS | Holds up to 4 spools for color/material swaps |
| Smart features | Automatic bed leveling; micro lidar and AI camera inspect the first layer and spot "spaghetti" failures |

## Design for 3D printing

- **Big flat face down.** A large, flat bottom sticks to the plate and needs no supports.
- **The 45° rule.** Overhangs steeper than ~45° from vertical need supports.
- **Walls ≥ 0.8 mm.** That's two nozzle widths.
- **Leave clearance.** Parts that fit together need a 0.2–0.3 mm gap.
- **Fit the cube.** Max 256 mm on each side, and smaller prints finish faster.
- **Details ≥ 1 mm.** Tiny text and features get lost.

!!! tip "Layers are the weak spot"
    Parts are strongest *along* their layers and weakest *between* them. Orient your part so the load doesn't pull the layers apart.

## Safety

- **It's hot.** The nozzle goes up to 300 °C and the plate over 100 °C. Don't touch either.
- **Door stays closed** while printing. Don't reach in.
- **Hands off the controls.** Ask before changing filament, settings, or canceling someone else's print.
- **Safety glasses** when cutting or snapping off supports.
- **Log your print** and **report problems** (weird noises, smells, errors) right away.

**Next:** [Step-by-Step →](steps.md)
