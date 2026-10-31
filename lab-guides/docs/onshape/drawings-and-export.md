# Onshape: Drawings & Export

How you get your design out of Onshape depends on the machine.

| Going to… | Export from | Format |
|---|---|---|
| **3D printer** | The **part** (Part Studio) | **STL** or **3MF**, in millimeters |
| **Laser cutter** | A **Drawing** tab | **DXF**, at **1:1 scale** |

## For the 3D printer: export the part

1. In the Part Studio, right-click your part in the **Parts list** (bottom left).
2. Choose **Export…**
3. Format: **STL** or **3MF**
4. Units: **Millimeter**
5. Resolution: **Fine**
6. Click **Export** to download it.

!!! image-soon "Image coming soon"
    The Onshape Export dialog for a part, with STL, Millimeter, and Fine selected.

<!-- When the photo is ready: add images/onshape/export-stl.jpg and replace the box above with ![The Onshape Export dialog for a part, with STL, Millimeter, and Fine selected.](../images/onshape/export-stl.jpg) -->

Then follow the [3D Printing Step-by-Step](../3d-printing/steps.md).

## For the laser cutter: make a drawing, then export DXF

### Make the drawing

!!! warning "A laser cut drawing is not an engineering drawing"
    The laser cuts **every line** in the file. A laser cut drawing is a blank sheet with **only the outlines of the parts** you want cut: no border, no title block, no dimensions. See the [side-by-side example](../laser-cutting/prepare-design.md#step-2-make-a-laser-cut-drawing-in-onshape).


1. Click the **+** at the bottom left (next to the tabs) and choose **Create Drawing**.
2. Pick your part. Start from a **blank sheet: no border and no title block**.
3. Place one **view of the flat face** of **each part** you want cut.
4. Set the view's **scale to 1:1**. Click the view and check its scale.

!!! danger "1:1 or the laser cuts the wrong size"
    If the view isn't 1:1, your part comes out bigger or smaller than you designed it.

5. Don't add dimensions to the laser drawing. Every line in the file may get cut.

!!! image-soon "Image coming soon"
    A finished laser cut drawing in Onshape: a blank sheet with a 1:1 top view of each part, no border or title block.

<!-- When the photo is ready: add images/onshape/laser-cut-drawing.jpg and replace the box above with ![A finished laser cut drawing in Onshape: a blank sheet with a 1:1 top view of each part, no border or title block.](../images/onshape/laser-cut-drawing.jpg) -->


### Export it

1. Right-click the **Drawing** tab and choose **Export…**
2. File name: **Student Name - Project**
3. Format: **DXF**
4. Click **Export** to download it.

Then follow [Laser Cutting: Prepare Your Design](../laser-cutting/prepare-design.md).

## Formal engineering drawings

For class assignments that need a full engineering drawing, use a drawing template **with** a title block, then add:

- The standard **views** (front, top, right, and often an isometric view)
- **Dimensions**, so someone else could make your part
- Your **name**, **part name**, **units**, and **scale** in the title block

Export it as **PDF** to submit.

**Next: pick a badge.**

<div class="page-next" markdown>

[3D Printing :material-arrow-right:](../3d-printing/index.md){ .md-button .md-button--primary }
[Laser Cutting :material-arrow-right:](../laser-cutting/index.md){ .md-button .md-button--primary }

</div>
