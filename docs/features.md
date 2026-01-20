# Core Features

## Precision Face Normal Alignment (FNA)

Extract perfect rotation directly from geometry—no more manual angle adjustments or snapping guesswork.

### Object Mode
Click a button ("**to X/Y/Z**") -> cursor becomes crosshair -> **left-click any face** to instantly align the object's chosen axis to that normal.

### Edit Mode
Select one or more faces -> click "**to X/Y/Z**".
*   Multiple faces use **averaged normals** for balanced, natural orientation on complex or irregular surfaces.
*   This is ideal for attaching bolts to curved panels or aligning props to slanted walls perfectly on the first try.

---

## Infinite Jog-Dial Control (Rotate & Move)

A breakthrough in tactile transformation—feels like using a real-world precision dial.

1.  Click any **Jog button** (X/Y/Z for Rotate or Move).
2.  **Hold left mouse and drag horizontally** for smooth, infinite adjustment along the axis.
3.  **Dynamic Sensitivity**: While dragging, scroll the **mouse wheel** to instantly shift "gears"—increase for fast coarse placement or decrease for ultra-precise sub-unit tweaks (down to 0.01 sensitivity). Current value shows in the status bar.
4.  Operations are fully undoable and respect your chosen orientation (Local/Global).

---

## Visual Axis Guidance

Stay perfectly oriented in 3D space.

*   During Jog operations, **infinite colored guide lines** draw automatically: Red (X), Green (Y), Blue (Z).
*   Lines extend in both directions from the object origin and adapt to your current Local or Global mode.
*   Provides instant visual confirmation of the active axis, reducing disorientation in complex scenes.

---

## Set Origin to Surface / Selection

Professional origin adjustment without moving visible geometry.

### Object Mode
Click the button -> crosshair cursor -> **click a face** to snap origin to its center.

### Edit Mode
Select vertices/edges/faces -> button click moves origin to selection centroid. Combine with FNA for rapid **"snap to surface + perfect origin"** workflows.

---

## Quick Rotate & Utilities

*   **Quick Rotate**: One-click buttons for common angles (**±15°, 30°, 45°, 60°, 90°**) in Local or Global mode.
*   **Multi-Object Tools**:
    *   **Match Rotation (Move)**: Copy active object's rotation to selected (geometry moves).
    *   **Match Axis (Keep Geo)**: Align local axes only (geometry position preserved).
    *   **Match Origin (Keep Geo)**: Move origins to active object's location (geometry stays put).
*   **Single-Object Helpers**: Reset Rotation, Apply Rotation, Origin to Center of Mass.

---

## Professional Safety Features

*   **Instant Revert**: During any Jog drag, press `ESC` or `right-click` to cancel—object snaps back to exact pre-operation state.
*   **Non-Destructive**: All alignments preserve scale; matrix math ensures clean, stable results.
*   **Continue Edit Mode Option**: Automatically return to Edit Mode after alignment/origin operations for seamless workflows.
