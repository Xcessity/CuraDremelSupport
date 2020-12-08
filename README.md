# CuraDremelSupport
This project aims to create a configuration set that supports the Dremel 3D printers in the newest Cura releases.

Cura target version: 4.8.0

Printers: Dremel 3D45

## DISCLAIMER
This configuration set is work in progress! Wrong settings can damage your printer!

USE ON YOUR OWN RISK!!!!!!

## Installation
1. Download and install Cura 4.8 from the official ultimaker website https://ultimaker.com/software/ultimaker-cura
2. Copy the resource folder from this project into the installation directory of Cura 4.8 (C:\Program Files\Ultimaker Cura 4.8.0\)

## What's working so far:
- Cura lists the Dremel3D45 as available (definition copied from Dremel Digilab Slicer)
- The 3D model of the build platform is shown on build volume
- Dremel materials can be selected from the material browser (PLA, ECO-ABS, Nylon, PETG)
- The default material is set to the Dremel ECO-ABS when adding a new printer
- Quality profiles for 0.05, 0.1, 0.2, 0.3 and 0.34 are now globaly available.
- The temperatures are now taken from the material properties (default_material_print_temperature, material_bed_temperature)
- The default_material_print_temperature in the 0.05 & 0.034 are specified for the material specific temps

## What's missing:
- No network support for starting a print (use USB stick)
- No camera live streaming (you can watch your prints in any browser http://[printerIP]:10123/?action=stream)
- The material profiles supplied by dremel for PETG and Nylon are not very well tuned
- Add more profiles for different 3rd party filaments
- In Cura 4.8 Extensions->Post Processing->Modify G-Code->ChangeAtZ activating "Output to Display" stops the print!

## Links & Resources
3D20 Plugin for Cura https://github.com/timmehtimmeh/Cura-Dremel-3D20-Plugin

Exploring the Dremel 3D45 network capabilities: https://github.com/genepool99/Dremel3D45Hacking

Also a project for the network functions of 3D45: https://github.com/janitz/3d45
