#  OVL Calibrator (v1.0)
### SteamVR Base Station 2D Alignment

**OVL Calibrator** (Overlay Visual Link) is a lightweight, standalone 2D diagnostic utility built to help VR users perfectly align their HTC Vive or Valve Index Lighthouse base stations. By flattening your 3D room coordinates into an intuitive 2D bird's-eye blueprint grid, you can eliminate controller tracking blind spots with absolute geometric precision.

---

##  Features
* **Live 2D Sightline Vector Map:** Visualizes your physical hardware nodes and tracking cones in real time.
* **Dual Laser Sight Projection:** Casts independent, locked laser lines out of each sensor face so you can see exactly where your lenses are aiming.
* **1-Meter Blueprint Floor Grid:** Includes a stylized dark-blue grid where every block equals exactly **1 square meter** in reality to easily gauge your room boundaries.
* **Intuitive Wall Angles:** Strips away confusing compass numbers and shows a clean double-digit angle (0° to 90°) relative to your physical corner walls.
* **Automatic Lifecycle Handlers:** Automatically stands by with a caution banner if SteamVR is offline, and automatically shuts down cleanly the moment you close SteamVR.
* **Self-Contained Executive:** Zero python runtimes, command lines, or dependencies required for end-users. Just click and calibrate.

---

##  How to Read the Metrics

* **Active Base Stations:** Automatically identifies hardware configurations (Model 1.0 vs 2.0) and assigns **Station B** to the leftmost unit and **Station C** to the rightmost unit to match your room layout.
* **Sightline Deviation:** Measures the horizontal error offset. A **0.0° Deviation** means the base station is aiming perfectly dead-center at the face of the opposite unit. 
* **Calibration Goal:** Physically swivel your base stations until the laser sights cross directly into the center of the opposite node. When optimal overlapping coverage is reached, the dashboard updates to a solid green **ALIGNMENT OK** status checking banner!

---

##  How to Download & Run

Because this software carries a strict non-derivative legal security framework, the source code scripts are private. You can download the pre-compiled standalone application directly from the official repository release terminal.

1. Navigate to the [**Releases**](https://github.com/fxmboi/OVL-Calibrator/releases/tag/v1.0) module on the right side of this homepage.
2. Download the compressed file container bundle: `OVL_v1.0.zip`.
3. Extract the contents directly onto your Desktop workspace.
4. Turn on your physical VR base stations and wake up **SteamVR**.
5. Launch `ovl_calibrator.exe` and begin aligning!

---

##  Legal License
Distributed under the **Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International (CC BY-NC-ND 4.0)** licensing framework. 
* You are free to copy, share, and redistribute this pre-compiled tool in any medium or format.
* You may **NOT** utilize this material for commercial business profit.
* You are explicitly **forbidden** from reverse-engineering, modifying, or altering the software execution code binary blocks.
