# AnkerMake M5 PrusaSlicer 2.5+ Profiles

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/just-trey/AnkerMake-M5-Profile?sort=semver&style=for-the-badge)

![image](https://user-images.githubusercontent.com/10281380/204983009-1b896ab9-774d-414d-adbe-b3f8aad5ccf2.png)

## Known "Issues"

- Printed speed will report and warn higher than 5x because of how Cura calculates speed. There are no significant quality or other impacts on the actual print.

## Overview

These profiles will allow you to add the AnkerMake M5 as a new printer in the menus.
Installing the profile:

1. Open Cura
2. Under the Help Menu, choose "Show Configuration Folder" (keep this folder open for the next several steps).
3. Close out of Cura
5. Download [Cura-5.x-M5-Profile.zip](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest/download/Cura-5.x-M5-Profile.zip)
6. Extract the zip file to a location of your choice and open the folder.
7. Copy the Contents of this folder to the Configuration folder you opened in step two. (Note you will be adding files to the directories)
8. Open Cura, and you should not be able to add a new AnkerMake M5 Printer.
![image](https://user-images.githubusercontent.com/10281380/204983099-ebb1007c-1171-4e68-a2e7-a2620efcca1b.png)
Optional: Enter a new Printer Name
Complete the printer setup
You now should have an AnkerMake M5 with some basic built-in Printer Profiles.

## Changelog

### 1.7 - 12/4/2022

- Significant quality updates based on feedback from @Tenson_UK
  - For the normal profile, set the first layer height to match the rest of the print. (0.2)
  - Set "Initial Layer Horizontal Expansion" and "Hole Horizontal Expansion" to improve quality
  - Set "Top/Bottom Thickness" to improve quality
  - Changed infill logic to increase infill speeds.
    - NOTE: Part strength is slightly weaker, so adjust as needed.
  - Changed print temperature logic for more consistency
  - Changed "Top/Bottom Flow" and "Initial Layer Flow" to improve print quality
  - Set "Combing Mode" to "Within Infill" to reduce the number of retractions.
  - Complete rework of support settings that provides easy removal and good part support.
    - NOTE: Tree supports have no optimization at this time.
  - Adjusted the following experimental settings to improve print quality.
    - "Overhanging Wall Angle"
    - "Overhanging Wall Speed
    - "Small Hole Max Size"
    - "Small Feature Initial Layer Speed"
- Regrouping/ordering of overrides to match base setting order

### 1.6 - 12/4/2022

- set retraciton speed to 60 to match AnkerMake defaults

### 1.5 - 12/1/2022

- add back in "extruder_nr": { "default_value": 0 }, to pass unit test and fix bug.
- fix typos in this readme.md

### 1.4 - 12/1/2022

- Complete refactor based on feedback from the Cura team to simplify the profile
  - Updated to follow new linting rules and suggestions
  - Significant reduction of base configuration overrides
  - Tested to ensure high-speed printing is functioning
  - Updated printing temperature logic to work correctly.
  - Added slight extrusion to start gcode to compensate for over-retraction after prime
- Clarified instructions to locate folders
- Migrated instructions From Google Docs to GitHub
- Reversed the order of the changelog to show the newest first

### 1.7 - 12/7/2022

- Migrated instructions From Google Docs to GitHub
- Reversed the order of the changelog to show the newest first

### 1.3-1.7 - 12/7/2022

- There is no cahnges for these release of teh PrusaSlicer Profiles.

### 1.2 - 10/22/2022

- Set default filament to PLA+
- Enabled detect bridging perimeters
- Increase skirt count from 1-3
- Disabled filament override for max volumetric speed.
- Change fan to be disabled from 1 to 2 layers
- Turned off enabled auto cooling to prevent speed reduction
- Adjusted first_layer_temperature for all filaments to match Anker slicer
- Adjusted bed temperatures for ABS
- Fix PLA+ inheriting values from PLA

### 1.1 - Removed thumbnail generation to prevent wifi upload error

### 1.0 - Initial Release
