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

Then follow the [3D Printing Step-by-Step](../3d-printing/steps.md).

## For the laser cutter: make a drawing, then export DXF

### Make the drawing

1. Click the **+** at the bottom left (next to the tabs) and choose **Create Drawing**.
2. Pick your part. For laser cutting, choose a template **without a border or title block** if one is offered. Otherwise you'll delete those later.
3. Place a single **view of the flat face** you want cut (usually the **Top** view).
4. Set the view's **scale to 1:1**. Click the view and check its scale.

!!! danger "1:1 or the laser cuts the wrong size"
    If the view isn't 1:1, your part comes out bigger or smaller than you designed it.

5. Don't add dimensions to the laser drawing. Every line in the file may get cut.

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
