<p align="center"><a href="../../README.md">🏠 Home</a> · <a href="../../hardware/bom/README.md">🛒 BOM</a> · <a href="../../hardware/printing/README.md">🖨️ Print</a> · <a href="../../docs/build-guide/README.md">🔧 Build</a> · <a href="../../docs/wiring-guide/README.md">🔌 Wiring</a> · <a href="../../firmware/README.md">⚡ Firmware</a> · <a href="../../software/sesame-studio/README.md">🎬 Studio</a></p>

---

# 3D Printing Guide

Sesame is designed to be printed in **PLA**. Most parts print without supports, but the top cover needs supports in targeted areas. Below is a quick reference for each component:

Note: There are 3 different top cover styles currently available. **Enclosed v91 is recommended** as it's the most modern design with magnetic hat mounts, covered display wires, and multicolor detail support. See [Top Covers](stl/top-covers/) for details on all styles.

> [!NOTE]
> **Battery Upgrade:** The internal frame design has been slightly altered to fit the new recommended battery (Bambu Lab 14500 Li-ion). If you have an older Sesame and want to upgrade to this battery, simply print the new internal frame and install it.

## Recommended Settings

* **Material:** PLA / PLA+
* **Infill:** 8-10%
* **Wall Loops:** 2
* **Infill Pattern:** Honeycomb

## 3D Printed Components Support Guide

| Component      | Supports Required | STL Link                                            |
| -------------- | ----------------- | --------------------------------------------------- |
| Joint R1       | No                | [R1-v117.stl](stl/R1-v117.stl)                         |
| Joint R2       | No                | [R2-v117.stl](stl/R2-v117.stl)                         |
| Joint R3       | No                | [R3-v117.stl](stl/R3-v117.stl)                         |
| Joint R4       | No                | [R4-v117.stl](stl/R4-v117.stl)                         |
| Joint L1       | No                | [L1-v117.stl](stl/L1-v117.stl)                         |
| Joint L2       | No                | [L2-v117.stl](stl/L2-v117.stl)                         |
| Joint L3       | No                | [L3-v117.stl](stl/L3-v117.stl)                         |
| Joint L4       | No                | [L4-v117.stl](stl/L4-v117.stl)                         |
| Internal Frame | No                | [Internal-Frame-v121.stl](stl/Internal-Frame-v121.stl) |
| Bottom Cover   | No                | [Bottom-Cover-v121.stl](stl/Bottom-Cover-v121.stl)     |
| Top Cover      | Yes               | [Top Covers](stl/top-covers/)                          |

### Top Cover Settings (Original Style)

Brim: Outer brim only
Support type: Normal (Manual)

Manual support locations:

<img src="assets/topcover-supports2.png" alt="topcover-supports2" width="70%">

This is what the part should look like sliced:

<img src="assets/sliced-topcover.png" alt="sliced-topcover" width="70%">

### Recommended Print Orientation for Joints:

Using the auto orientate tool will place these the correct way.

<img src="assets/joints-orientation.png" alt="sliced-topcover" width="70%">
