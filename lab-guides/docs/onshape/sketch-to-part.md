# Onshape: Sketch to Part

Almost every part follows the same pattern: **sketch a 2D shape → turn it into 3D with a feature → repeat.**

## Step 1: Start a sketch

1. Open the **Part Studio** tab.
2. Click **Sketch** (top left toolbar).
3. Click a plane to draw on: **Top**, **Front**, or **Right**. Pick the plane your part would sit on.
4. Press **N** to look straight at the plane.

## Step 2: Draw the shape

Common sketch tools:

| Tool | Shortcut | Use it for |
|---|---|---|
| Line | **L** | Straight edges |
| Corner rectangle | **G** | Boxes and plates |
| Center-point circle | **C** | Holes and round parts |
| Fillet | **Shift + F** | Rounding sharp sketch corners |
| Dimension | **D** | Setting exact sizes |

Draw the rough shape first. Don't worry about exact sizes yet.

## Step 3: Dimension and constrain it

1. Press **D**, click a line or two points, and type the size you want.
2. Add **constraints** to lock relationships, like *horizontal*, *vertical*, *coincident*, *equal*, or *tangent*. Onshape often adds these for you as you draw.

!!! tip "Blue vs. black"
    **Blue** lines aren't fully defined and can still move. **Black** lines are fully defined. Aim for an all-black sketch before you continue. It means your part is exactly the size you meant.

3. Click the green **✓** to finish the sketch.

## Step 4: Make it 3D with a feature

| Feature | What it does |
|---|---|
| **Extrude** | Pushes a sketch straight out into a solid, or cuts a hole through one |
| **Revolve** | Spins a sketch around an axis (cups, knobs, wheels) |
| **Fillet** | Rounds a 3D edge |
| **Chamfer** | Bevels a 3D edge |
| **Shell** | Hollows a part out, leaving walls |
| **Hole** | Adds standard holes, including screw clearance holes |
| **Pattern** | Repeats a feature in a row or circle |

**To extrude:** click **Extrude**, select the sketch region, type a depth, and click **✓**. To cut, sketch on a face of your part, extrude, and choose **Remove**.

## Step 5: Edit later

Everything is in the **feature list** on the left. Double-click any sketch or feature to change it, and everything after it updates automatically.

!!! tip "Use variables for sizes you'll change"
    Click **Variable** (the **(x)** button) to create, for example, `#thickness = 3 mm`. Type `#thickness` instead of a number in any dimension. This is a big help for laser-cut slots: when your sheet measures differently, change one number and every slot updates.

## Designing for a machine

- **Going to the 3D printer?** See the design rules on the [3D Printing page](../3d-printing/index.md#design-for-3d-printing).
- **Going to the laser cutter?** Design flat parts, and see the tips on the [Laser Cutting page](../laser-cutting/index.md#design-tips-for-laser-cutting).

**Next:** [Drawings & Export →](drawings-and-export.md)
