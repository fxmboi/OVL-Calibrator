#  OVL Calibrator
### SteamVR Base Station 2D Alignment & Blueprint Mapping Utility

**OVL Calibrator** (Overlay Visual Link) is a lightweight, standalone 2D diagnostic utility built to help VR users perfectly align their HTC Vive or Valve Index Lighthouse base stations. By flattening your 3D room coordinates into an intuitive 2D bird's-eye blueprint grid, you can eliminate controller tracking blind spots with absolute geometric precision.

---

## Features

| Main Tracking Map Features | Dynamic Scanning Features (v1.2) |
| :--- | :--- |
| Live 2D sightline vector map | Infinite multi-point room scanner |
| Dual laser sight projection | Two-point 3D elevation scan |
| Dark greyish-black mode sheet canvas | Live headset and controller tracking nodes |
| Unified component layer alignment | Standby metric data masking |
| Automatic lifecycle standby handlers | Room setup lockout safety protocol |
| Self-contained executable package | Imperial unit conversion matrix |


---

##  Live Metrics & Visualization Dashboard


<p align="center">
  <img src="active_map.jpg" alt="OVL Calibrator Interface Map Active Dashboard" width="750">
</p>

<p align="center">*This preview shows a more updated UI with more features and a new set of stats!*
</p>

---

## (FAQ)

### Q: How is OVL better than just replacing the lighthouse model with a calibration model?
**A:** While manually swapping model files in SteamVR directories is a clever workaround, it is entirely static and lacks interactivity. OVL provides a dedicated, user-friendly graphical interface that lets you place and adjust your base stations on the fly without digging through local files or dealing with tedious manual overrides. 

### Q: Does OVL work if I have modified my lighthouse model files?
**A:** No, or at least not as intended. OVL does not rely on static asset replacements. Instead, it actively queries SteamVR to locate your base stations, parse their live tracking coordinates, and dynamically render visual aids (such as directional lines, cones, angles, and deviation metrics) in real time. 

### Q: Why should I use OVL instead of manual configuration?
**A:** OVL is built for ease of use and precision. It saves you from the friction of repetitive file-swapping and gives you an intuitive UI to instantly visualize your tracking setup, check alignment boundaries, and manage your base stations seamlessly.

---
##  How to Download & Run

Because this software carries a strict non-derivative legal security framework, the source code scripts are private. You can download the pre-compiled standalone application directly from the official repository release terminal.

1. Navigate directly to the public [Releases](https://github.com) module link.
2. Download the newest release.
3. Extract the contents directly onto your local Desktop workspace.
4. Turn on your physical VR base stations and wake up **SteamVR**.
5. Launch `ovl_calibrator.exe` and begin aligning!

---

##  Legal License
Distributed under the **Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International (CC BY-NC-ND 4.0)** licensing framework. 
* You are free to copy, share, and redistribute this pre-compiled tool in any medium or format.
* You may **NOT** utilize this material for commercial business profit.
* You are explicitly **forbidden** from reverse-engineering, modifying, or altering the software execution code binary blocks.
