<img width="450" alt="Screenshot 2024-05-15 at 2 08 55 PM" src="https://github.com/sbh2019a1/AMU-3d-printer/assets/63435930/a814f1b7-d69b-4aed-9dde-7d750bcac931">

## Overview
This an open source 3D printer project that aims to be relativley simple to source and build. Feel free to use this design for your own purpose.

This is a work in progress project. The 3d printer is not built yet, and parts are not guaranteed to fit together. The first build and klipper config is scheduled for august 2024.

## Design Goals
 - Extrusion box frame

The frame is a simple box, there is no need for adjustment given that the extrusions are straight and accurate. Blind joints are recommended for the assembly.


 - 10mm linear rods for all axes

Linear rails are generally better and easier to design with. However, I have encountered binding and general quality control issues with cheap rails while rails from reputable manufacturers were too expensive for the target BOM cost of ~600$. There are good middle ground options, but perfect and cheap rails don't exist.

This design uses linear rods which simplifies sourcing. Hardened steel rods from Misumi are enough for 3d printers, and carbon fiber rods are a future possibility.


 - simplified fastener sourcing 

All M3 screws are 8/12/20/40mm socket heads, and all M5 screws are 10/15/20mm button heads. Few extra M4 screws are needed to mount the power supply.

 - Hotend choice

Currently the hotend supports a V6 groove mount and the LDO orbiter v2 hotend. 

A mount for the LDO smart orbiter V3 is in the works.
