# Laser Cutting: Overview & Safety

[:material-arrow-left: Back to Home](../index.md){ .md-button }

**New to the lab?** Read the [Lab Rules](../lab-rules.md) first. They apply to every machine.

The laser cutter available for student use is in the WCC Engineering Lab, **CAS 117**. It's a **TROTEC Rayjet 300**, a CO₂ laser with a bed size of **29" × 17"**.

![The Trotec Rayjet 300 laser cutter on its stand in CAS 117, with the lid closed.](../images/laser/rayjet-in-lab.jpg)

!!! warning "Before you come to the laser cutter"
    You need a **finished laser cut drawing** in Onshape **before** you sit down at the CAS 117 computer:

    - A **blank sheet**: no border, no title block, no dimensions
    - One **1:1 view of each part** you want cut
    - Ready to **export as a DXF**

    **Don't use the CAS 117 computer to model.** Someone else may be waiting to cut. See [Drawings & Export](../onshape/drawings-and-export.md).

!!! info "Need a computer?"
    Engineering laptops are available for anyone to use in **Cascade, room 112**.

## What is laser cutting?

A laser cutter uses a focused beam of light to **cut or engrave flat sheets** of material, like plywood, acrylic, and cardboard. You give it a 2D drawing, and it follows the lines.

### How it works

A **CO₂ laser tube** makes an invisible infrared beam. **Mirrors** bounce it to the cutting head, where a **lens** focuses it to a tiny, very hot spot. The material **burns or vaporizes** along the path, and the **ventilation fan** pulls the smoke out.

It's a *subtractive* process: it removes material, unlike a 3D printer, which adds it.

!!! info "The laser only cuts straight down"
    The beam always points **straight down** through the material. Every cut edge comes out **vertical (90° to the sheet)**.
    The laser **can't** cut angles, bevels, or chamfers through the thickness, and it can't cut a 3D shape. It cuts a flat outline, like a cookie cutter.
    Need an angled or 3D part? Build it from flat parts that slot together, or 3D print it instead.

!!! video-soon "Video coming soon"
    A video of our laser cutter cutting plywood, so you can see the beam cut straight down.

## The process: from Onshape to the laser

Every laser job follows the same path through three programs:

<div class="flow" markdown>
<div class="flow__group">
<p class="flow__where">Before lab · any computer (engineering laptops in Cascade 112)</p>
<ol class="flow__steps">
<li><span class="flow__app">Onshape</span>Make your part</li>
<li><span class="flow__app">Onshape</span>Make a <strong>laser cut drawing</strong>: outlines only, 1:1</li>
</ol>
</div>
<div class="flow__group">
<p class="flow__where">Before lab (bring it on a USB drive) or at the laser</p>
<ol class="flow__steps" style="--flow-start: 2">
<li><span class="flow__app">Onshape</span>Download it as a <strong>DXF</strong></li>
</ol>
</div>
<div class="flow__group">
<p class="flow__where">At the laser · CAS 117 computer</p>
<ol class="flow__steps" style="--flow-start: 3">
<li><span class="flow__app">CorelDRAW</span>Open your DXF</li>
<li><span class="flow__app">CorelDRAW</span><strong>Change line colors</strong> to cut or engrave</li>
<li><span class="flow__app">CorelDRAW</span><em>Optional:</em> add <strong>text or a picture</strong> to engrave</li>
<li><span class="flow__app">CorelDRAW → Rayjet Manager</span><strong>File → Print</strong> sends your design to Rayjet Manager</li>
<li><span class="flow__app">Rayjet Manager → Laser</span><strong>Prepare the machine</strong>, then send the job and press <strong>START</strong></li>
</ol>
</div>
</div>

The [Prepare Your Design](prepare-design.md) page walks through each step.

!!! tip "Adding text or a picture?"
    **Before** you cut your parts from Onshape, add the text or picture **in CorelDRAW** (step 6) and engrave it in the **same job** as your cut. See [Prepare Your Design](prepare-design.md#step-6-add-text-or-a-picture-to-engrave-optional).

## Cut, etch, or engrave?

The laser doesn't know what you intend. It decides what to do from the **color of each line** in your file.

![A laser-cut hexagon keychain labeled to show a red vector cut around the outside, blue vector engraving of an orca outline, and black raster engraving of the words WCC Engineering.](../images/laser/color-code-keychain.jpg)

| Color | Process | What it does |
|---|---|---|
| :red_circle: **Red** | Vector Cut | Cuts all the way through |
| :blue_circle: **Blue** | Vector Engrave (also called *Etching*, *Marking*, or *Scoring*) | Marks a line on the surface |
| :black_circle: **Black** | Raster Engrave | Fills in an area, like text or a logo |

The laser engraves first and cuts last, so parts don't shift before the engraving is done.

## What can go in the laser?

!!! danger "Ask before you cut ANY material not provided"
    **Always get your material approved by Jonathan or an instructor before you cut it, even if it's on the OK list.** Bringing your own material? Get it approved first.
    Some materials give off **toxic gas** or **catch fire** in the laser, and many of them look alike.

<div class="grid" markdown>

!!! success "OK, with approval"
    - Plywood (thin, laser-grade)
    - MDF
    - Cast acrylic
    - Cardboard, chipboard, paper
    - Natural leather, cork, felt

!!! failure "NEVER put these in the laser"
    | Material | Why it's dangerous |
    |---|---|
    | **PVC / vinyl** | Releases **chlorine gas**, which is toxic to breathe and damages the machine |
    | **Polycarbonate (Lexan)** | **Catches fire** and doesn't cut cleanly |
    | **ABS, HDPE** | **Melt and catch fire** |
    | **Fiberglass, coated carbon fiber** | Give off **harmful fumes and dust** |
    | **Metal** | **Reflects the beam** and won't cut |
    | **Anything you can't identify** | It could be any of the above. **Ask first.** |

</div>

## Safety

!!! danger "Fire is the #1 risk"
    Small flames at the cut point are normal. A flame that **keeps burning after the head moves on** is not.
    **Never leave the room while the laser is running.** If something catches fire: press pause, keep the lid closed, and get the instructor.

- **Ventilation fan always on.** No fan, no laser.
- **Lid stays closed.** The beam is invisible. Never open the lid or reach in mid-job.
- **Know where things are:** fire extinguisher, the pause button, and who to tell.

## Design tips for laser cutting

- **Think in flat parts.** Build 3D shapes by slotting flat parts together (tab & slot, finger joints).
- **Measure your sheet's length and width** with a ruler or tape measure, so your parts fit on it and your CorelDRAW page matches it.
- **Account for kerf.** The beam burns away a thin strip of material, so slots come out a little loose. How much depends on the material and how the laser is set up, so **don't rely on a set number. Do a test fit for your own project**: cut one small slot and tab from your material, check the fit, and adjust your Onshape sizes before cutting the whole thing.
- **Leave 2–3 mm between parts.**
- **Keep features at least as thick as the sheet.**

!!! warning "Don't use Transform to scale a laser-cut design"
    Want your design bigger or smaller? **Don't use Onshape's Transform (scale) feature.** Scaling shrinks or grows **every** dimension, including the slots and tabs that are sized to your material's thickness.
    Your sheet doesn't get thinner or thicker, so the scaled slots won't match it and the parts **won't fit together**.

### See the difference

!!! image-soon "Image coming soon"
    Side-by-side examples of good and bad laser cut designs: kerf and slot fit, spacing between parts, and feature thickness.

<div class="page-next" markdown>

[Next: Prepare Your Design :material-arrow-right:](prepare-design.md){ .md-button .md-button--primary }

</div>
