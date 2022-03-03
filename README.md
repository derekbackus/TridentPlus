# TridentPlus
 350x650 Voron Trident
# Notes
This is an advanced build. Please don’t try this for your first build. It is not easy and takes some mechanical skills. 
- The lead screws on the two Z motors need to be cut.
- All of the extrusions were drilled in-house on a drill press — there are no stock numbers for pre-drilled extrusions provided. There are drill jigs provided in the STL folder.
- You need to tap the extrusions for blind joints. This is easy and goes fast with a hand drill, clamp, tapping fluid and a SHARP 5mm tap.
- Getting 2 build plates level and aligned well enough to do a Z_TILT_ADJUST is not easy. You must perfectly level your printer to make this work.
- Configuring Klipper is a bit more difficult than configuring a Trident. In particular, there are two SSRs for the two bed heaters, and an extra Z motor adding to the z_tilt configuration.
# 3D CAD
All of the custom files are in the STL folder. Everything else should be printed from the stock Trident. Here’s the 3D view in an online version for your viewing pleasure. https://autode.sk/3JmR1mI. I will get the STL file ready. You'll need these so you can see where all the holes in the extrusions need to be drilled.
# Goals
- Build a printer with a print size of approximately 350Y x 650X x 220Z.
- Re-use all Trident parts, where possible, so I don’t have to re-invent the wheel.
- Update Trident parts minimally, where needed.
# Ideas/Plans
- Use 4 integrated lead screw motors in each corner for the Z, reusing all the plastic Trident bed parts, including the MGN9 rails.
- Axis will be rotated 90 degrees. Looking from the front, the print size will be 650 wide (x) with the gantry open on the right.
- Corner posts and bottom base extrusions will be upgraded to 4040.
- The long axis (x) will be upgraded to MGN12 rails.
- Printer will be enclosed to print ABS.
- AL print bed will be 2 350mm magnabeds with 2 heaters on the bottom. 2 PEI WhamBam sheets will be used side-by-side for the print surface.
- Add 14ga or 16ga steel backers to X & Y extrusions for rigidity.
# Possible Issues
- Belts are approximately 2.5 meters. How will they work/stretch, etc? **Seems to be ok. Slightly more ringing, which can be taken care of with input shaper**
- Gantry is 20mm extrusion — is this rigid enough? Will MGN12 rails and backers make them rigid enough? **Yes, it is rigid enough. My bed mesh varies by .1964. This seems pretty good ovoer 650mm**
- How fast can it print? Hopefully 150mm(ish) **Prints great at 150mm perimeters, 60mm external perimeters and 35mm/s cubed volumetric for the rest with a Rapido hot end**
- Will the bed be too heavy for the steppers? **No, the steppers handle the bed with ease**
- Will the 20mm bed rails be rigid enough? **Yes**
# Mods Included
- Klicky
- .075 steel extrusion backers based on these https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/whoppingpochard/extrusion_backers
- Purge bucket/brush based on these https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_&_Nozzle_Scrubber
- Qty. 2 Nevermore 4 filters.
- Runout sensor
