# CuraDremelSupport
This project aims to create a configuration set that supports the Dremel 3D printers in the newest Cura releases.

Cura target version: 4.8.0

Printers: Dremel 3D45

## DISCLAIMER
This configuration set is work in progress! Wrong settings can damage your printer!

USE ON YOUR OWN RISK!!!!!!

## Installation
1. Download and install Cura 4.8 from the official ultimaker website https://ultimaker.com/software/ultimaker-cura
2. Copy the resource folder in the installation directory of Cura 4.8 (C:\Program Files\Ultimaker Cura 4.8.0\)

## What's working so far:
- Cura lists the Dremel3D45 as available (definition copied from Dremel Digilab Slicer)
- The 3D model of the build platform is shown on build volume
- Dremel materials can be selected from the material browser (PLA, ECO-ABS, Nylon, PETG)
- The default material is set to the Dremel ECO-ABS when adding a new printer

## What's missing:
I cannot merge the old Digilab slicer quality profiles (C:\Program Files\Dremel DigiLab 3D Slicer\resources\quality\Dremel3D45) into Cura 4.8.
I assume that this has something to do with the "quality_type".

I have tried setting the "version = 4" and "settings_version = 16"


