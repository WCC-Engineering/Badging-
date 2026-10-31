# 3D Printing: Step-by-Step

**Design → Export → Slice → Send → Print → Finish**

Most failed prints are decided in steps 1–3, before the printer ever turns on.

## Step 1: Design in Onshape

Follow the design rules on the [Overview page](index.md#design-for-3d-printing).

## Step 2: Export from Onshape

1. Right-click the part in the **Parts list** (or right-click the Part Studio tab to export everything).
2. Choose **Export…**
3. Format: **STL** or **3MF**. Either works with Bambu Studio.
4. Units: **Millimeter**
5. Resolution: **Fine**
6. Download the file.

!!! image-soon "Image coming soon"
    The Onshape Export dialog with STL, Millimeter, and Fine selected.

<!-- When the photo is ready: add images/3d-printing/onshape-export.jpg and replace the box above with ![The Onshape Export dialog with STL, Millimeter, and Fine selected.](../images/3d-printing/onshape-export.jpg) -->

!!! warning "Check your units!"
    If a 50 mm part shows up far too small or far too big in the slicer, it was exported in the wrong units.

## Step 3: Slice in Bambu Studio

A **slicer** turns your 3D model into hundreds of thin layers and the exact path the nozzle will follow (G-code).

1. Open the **Prepare** tab.
2. Printer: **Bambu Lab X1 Carbon 0.4 nozzle**
3. **Plate type:** match the plate actually in the printer.
4. **Filament:** match the spool and AMS slot (for example, Bambu PLA Basic).
5. **Import** your file (drag it in, or Ctrl+I).
6. **Orient it:** use *Lay on Face* (F) and click your big flat face.
7. **Check settings** (table below).
8. Click **Slice plate**, then check the **Preview** tab.

!!! image-soon "Image coming soon"
    A sliced part in the Bambu Studio Preview tab, showing layers and supports.

<!-- When the photo is ready: add images/3d-printing/slicer-preview.jpg and replace the box above with ![A sliced part in the Bambu Studio Preview tab, showing layers and supports.](../images/3d-printing/slicer-preview.jpg) -->

!!! image-soon "Image coming soon"
    The Bambu Studio Prepare tab with the printer, plate type, and filament set, and a part laid flat on the plate.

<!-- When the photo is ready: add images/3d-printing/bambu-prepare-tab.jpg and replace the box above with ![The Bambu Studio Prepare tab with the printer, plate type, and filament set, and a part laid flat on the plate.](../images/3d-printing/bambu-prepare-tab.jpg) -->

| Setting | Start with | Change it when… |
|---|---|---|
| Layer height | 0.20 mm | 0.12 for fine detail; 0.28 for a fast draft |
| Wall loops | 2 | 3–4 for parts that get loaded or screwed into |
| Sparse infill | 15% | 25–40% for strong parts; 10% for display models |
| Supports | Off | Turn on (tree, auto) for overhangs past ~45° |
| Brim | Auto | Tall or small-footprint parts that might tip or lift |

### Read the preview

- Print time fits before class ends
- Layer 1 has lots of solid contact with the plate
- Nothing prints in mid-air with nothing below it
- Supports only where you expect them
- Only one copy of your part on the plate

## Step 4: Send it to the printer

Click **Print plate**, choose our X1-Carbon, and check **Bed leveling**, **Flow dynamics calibration**, and **Use AMS**. Then click **Send**.

!!! image-soon "Image coming soon"
    The Bambu Studio Send dialog with Bed leveling, Flow dynamics calibration, and Use AMS checked.

<!-- When the photo is ready: add images/3d-printing/bambu-send-dialog.jpg and replace the box above with ![The Bambu Studio Send dialog with Bed leveling, Flow dynamics calibration, and Use AMS checked.](../images/3d-printing/bambu-send-dialog.jpg) -->

The first few minutes look like nothing is happening while it heats and calibrates. That's normal.

## Step 5: Print and watch the first layer

- Build plate is clean (no fingerprints or leftover plastic)
- The plate in the printer matches the plate in Bambu Studio
- The right filament is in the AMS slot you chose

!!! tip "Watch the first layer"
    Lines should be flat, slightly squished, and touching each other. If it's lifting, curling, or dragging around, stop and ask for help.

!!! image-soon "Image coming soon"
    A good first layer: flat, slightly squished lines that touch each other.

<!-- When the photo is ready: add images/3d-printing/good-first-layer.jpg and replace the box above with ![A good first layer: flat, slightly squished lines that touch each other.](../images/3d-printing/good-first-layer.jpg) -->

## Step 6: Finish

1. **Let it cool.** Parts pop off more easily.
2. **Flex the plate** gently to release the part.
3. **Remove supports** with pliers. Wear safety glasses.
4. **Reset the printer:** clear scraps and put the plate back.
5. **Measure it** with calipers and compare it to your Onshape dimensions.

<div class="page-next" markdown>

[Next: Check Your Knowledge :material-arrow-right:](check-your-knowledge.md){ .md-button .md-button--primary }

</div>
