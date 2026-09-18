<p align="center"><a href="../../README.md">🏠 Home</a> · <a href="../../hardware/bom/README.md">🛒 BOM</a> · <a href="../../hardware/printing/README.md">🖨️ Print</a> · <a href="../../docs/build-guide/README.md">🔧 Build</a> · <a href="../../docs/wiring-guide/README.md">🔌 Wiring</a> · <a href="../../firmware/README.md">⚡ Firmware</a> · <a href="../../software/sesame-studio/README.md">🎬 Studio</a></p>

---

# CAD Files

3D CAD models for the Sesame Robot Project. Files are formatted in STEP format and F360 format.

Looking for STLs for 3D printing? See [printing](../printing/README.md).

>[!CAUTION]
> Parametric drawings and tools made in the original design files may not properly translate to your system. You may need to re-design certain components if you are making significant size changes.

## Editing the CAD with Free Tools

You do not need a paid CAD suite to remix Sesame’s parts. A few practical workflows:

1. **Fusion 360 personal license** – Autodesk offers a free hobbyist tier that can open the native `.f3d` files. Enable the *Design History* timeline to see how assemblies were built before changing dimensions.
2. **FreeCAD for STEP tweaks** – All parts are exported as `.step`, so you can import them into FreeCAD, adjust sketches, and re-export STL/STEP files without losing references. Use the *Part Design* workbench for parametric edits.
3. **Onshape education account** – Onshape’s free plan lets you upload the STEP files and edit directly in-browser. Great for Chromebook users or when collaborating in real time.
4. **Meshmixer/Blender for quick mods** – If you just need to shave openings or add text, import the STL into Meshmixer or Blender, make the change, and re-export. This is faster for cosmetic tweaks, but stick with the parametric source for anything dimension-critical.

> [!TIP]
> Keep the original STEP/ Fusion file untouched and branch your edits into a copy. That way you can always rebase onto the upstream design if new hardware revisions ship.

