# Laser Cutting: How to Engrave

[:material-arrow-left: Back to Laser Cutting](index.md){ .md-button }

Want to put **text or a picture** on something? You can do it all in **CorelDRAW**. **You don't need Onshape** for engraving.

<div class="flow" markdown>
<div class="flow__group">
<p class="flow__where">All at the laser · CAS 117 computer · no Onshape needed</p>
<ol class="flow__steps">
<li><span class="flow__app">Laser</span>Prepare the machine</li>
<li><span class="flow__app">CorelDRAW</span>New page the size of your material</li>
<li><span class="flow__app">CorelDRAW</span>Add your <strong>text or picture</strong></li>
<li><span class="flow__app">CorelDRAW</span>Set the <strong>colors</strong></li>
<li><span class="flow__app">CorelDRAW → Rayjet Manager</span><strong>File → Print</strong></li>
<li><span class="flow__app">Rayjet Manager → Laser</span>Check the preview, press <strong>START</strong></li>
</ol>
</div>
</div>

!!! tip "Engraving and cutting in one job"
    You can engrave **and** cut in the same file. For example, engrave a name, then cut a shape around it. The laser engraves first and cuts last.

## Step 1: Prepare the machine

Do [Prepare the Machine](prepare-machine.md) first: fan on, power on, calibrate Z on **this** material, and position the laser. Then come back here.

## Step 2: Start a new CorelDRAW page

1. Open **Rayjet Manager** and **CorelDRAW**.
2. In CorelDRAW, **File → New**. Set the page to the size of your material (max 29" × 17").

## Step 3: Add your text or picture

=== "Text"

    1. Click the **Text tool** (the **A** in the left toolbar).
    2. Click on the page and type.
    3. Pick a **font** and **size** in the toolbar.

    !!! tip
        Thick, bold fonts engrave best. Very thin or tiny letters can disappear.

    !!! image-soon "Image coming soon"
        CorelDRAW with the Text tool selected and a name typed on the page.
    
    <!-- When the photo is ready: add images/laser/coreldraw-text.jpg and replace the box above with ![CorelDRAW with the Text tool selected and a name typed on the page.](../images/laser/coreldraw-text.jpg) -->
    

=== "Picture"

    1. **File → Import** and choose your picture (JPG or PNG).
    2. Click on the page to place it, then drag a corner to resize it.

    !!! tip
        Simple, high-contrast pictures (like a logo or a black-and-white drawing) engrave best. Use your own picture or one you have permission to use.

    !!! image-soon "Image coming soon"
        A picture imported into CorelDRAW and sized on the page.
    
    <!-- When the photo is ready: add images/laser/coreldraw-picture.jpg and replace the box above with ![A picture imported into CorelDRAW and sized on the page.](../images/laser/coreldraw-picture.jpg) -->
    

## Step 4: Set the colors

The color tells the laser what to do:

| You want to… | Make it | Process |
|---|---|---|
| Fill in text, a logo, or a picture | :black_circle: **Black** fill | Raster Engrave |
| Draw a thin line on the surface | :blue_circle: **Blue** outline | Vector Engrave (scoring) |
| Cut a shape out around it | :red_circle: **Red** outline | Vector Cut |

- **Text:** select it and **left-click black** so the letters are filled in.
- **Cut it out too?** Draw a shape around your design with the **Rectangle** or **Ellipse** tool, then **right-click red** so the outline cuts.

!!! tip
    **Right-click** a color swatch = line (outline) color. **Left-click** = fill color.

## Step 5: Send it from CorelDRAW to Rayjet Manager

Choose **File → Print**. This sends your design to **Rayjet Manager**.

## Step 6: Send it from Rayjet Manager to the laser

!!! image-soon "Image coming soon"
    Rayjet Manager showing the preview of an engraving on the material.

<!-- When the photo is ready: add images/laser/rayjet-engrave-preview.jpg and replace the box above with ![Rayjet Manager showing the preview of an engraving on the material.](../images/laser/rayjet-engrave-preview.jpg) -->

- [ ] Check the preview: is your text or picture there, the right size, in the right spot?
- [ ] Ventilation fan is ON
- [ ] Z calibrated on **this** material, and the calibration tool is back in its spot
- [ ] Lid closed, then press **START** on the computer in the Rayjet software

!!! danger "Never walk away while it's running."

## After the engraving

1. **Wait for the smoke to clear** before opening the lid.
2. **Check it before moving anything.** Too light? Run it again *without moving the material*.
3. **Remove your piece** and clean the machine.

!!! success "You know how to engrave!"
    - Something went wrong? Check [Troubleshooting](troubleshooting.md).
    - Still stuck? Find Jonathan, a peer mentor, or an instructor. See [Ask for Help](../help.md).

**Next:** [Troubleshooting →](troubleshooting.md)
