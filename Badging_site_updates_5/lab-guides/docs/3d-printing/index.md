# 3D Printing: Overview & Safety

[:material-arrow-left: Back to Home](../index.md){ .md-button }

**New to the lab?** Read the [Lab Rules](../lab-rules.md) first. They apply to every machine.

Our printer is a **Bambu Lab X1-Carbon**. It builds parts one thin layer of melted plastic at a time.

!!! image-soon "Image coming soon"
    The Bambu Lab X1-Carbon 3D printer in the WCC Engineering Lab.

<!-- When the photo is ready: add images/3d-printing/x1c-in-lab.jpg and replace the box above with ![The Bambu Lab X1-Carbon 3D printer in the WCC Engineering Lab.](../images/3d-printing/x1c-in-lab.jpg) -->

!!! warning "Before you come to the printer"
    The 3D printers are in **CAS 117**, the same room as the laser cutter.

    Have your part **finished and exported** from Onshape as an **STL or 3MF** file **before** you sit down at the printer's computer.
    **Don't use that computer to model.** Someone else may need it. See [Drawings & Export](../onshape/drawings-and-export.md).

!!! info "Need a computer?"
    Engineering laptops are available for anyone to use in **Cascade, room 112**.

## What is 3D printing?

3D printing builds a part **one thin layer at a time**. It's an *additive* process: it adds material only where your part needs it, unlike a laser cutter, which removes material.

### How it works: FDM

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

## The process

Every 3D print follows the same path:

<div class="flow" markdown>
<div class="flow__group">
<p class="flow__where">Before lab · any computer (engineering laptops in Cascade 112)</p>
<ol class="flow__steps">
<li><span class="flow__app">Onshape</span>Design your part</li>
<li><span class="flow__app">Onshape</span>Export it as an <strong>STL or 3MF</strong></li>
</ol>
</div>
<div class="flow__group">
<p class="flow__where">At the printer · CAS 117</p>
<ol class="flow__steps" style="--flow-start: 2">
<li><span class="flow__app">Bambu Studio</span><strong>Slice</strong> it into layers and check the preview</li>
<li><span class="flow__app">Bambu Studio → Printer</span><strong>Send</strong> the print</li>
<li><span class="flow__app">Printer</span><strong>Watch the first layer</strong></li>
<li><span class="flow__app">You</span>Let it cool, remove supports, measure</li>
</ol>
</div>
</div>

The [Step-by-Step](steps.md) page walks through each step.

??? info "Printer specs (click to open)"
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
- **Leave clearance.** Parts that fit together need a gap. **Start with 0.2–0.3 mm** for PLA on our printer, then **test fit** (see below).
- **Fit the cube.** Max 256 mm on each side, and smaller prints finish faster.
- **Details ≥ 1 mm.** Tiny text and features get lost.

### See the difference

<div class="grid" markdown>

![Good: an L-shaped part printed lying on its big flat face. Bad: the same part standing on its end, needing lots of supports.](../images/3d-printing/orient-flat-face-down.svg)

![Good: a slope of 45 degrees or less prints with no supports. Bad: a flat overhang past 45 degrees needs supports underneath.](../images/3d-printing/overhang-45-rule.svg)

![Good: a peg with a 0.2 to 0.3 millimeter gap fits in its hole. Bad: a peg the exact same size as the hole won't fit.](../images/3d-printing/clearance-fit.svg)

</div>

!!! tip "Test fit before you print the whole thing"
    Plastic shrinks a little as it cools, so **holes and slots often print a bit smaller** than you drew them, and pegs a bit bigger. If your project has parts that fit together, **print just the fitting section first** (a small piece with the hole and a short peg). Check the fit, adjust the gap in Onshape, then print the full part. It saves time and filament.

!!! tip "Layers are the weak spot"
    Parts are strongest *along* their layers and weakest *between* them. Orient your part so the load doesn't pull the layers apart.


## Safety

- **It's hot.** The nozzle goes up to 300 °C and the plate over 100 °C. Don't touch either.
- **Hands off the controls.** Ask before changing filament, settings, or canceling someone else's print.
- **Safety glasses** when cutting or snapping off supports.
- **Report problems** (weird noises, smells, errors) right away.

<div class="page-next" markdown>

[Next: Step-by-Step :material-arrow-right:](steps.md){ .md-button .md-button--primary }

</div>
