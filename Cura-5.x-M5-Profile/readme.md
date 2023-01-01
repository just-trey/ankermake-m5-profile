# AnkerMake M5 Cura 5.1+ Profiles

[![GitHub release](https://img.shields.io/github/v/release/just-trey/AnkerMake-M5-Profile?display_name=tag&sort=semver&style=for-the-badge)](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest)

![image](https://user-images.githubusercontent.com/10281380/204983009-1b896ab9-774d-414d-adbe-b3f8aad5ccf2.png)

## Known Issues

- Printed speed will report and warn higher than 5x because of how Cura calculates speed. There are no significant quality or other impacts on the actual print.
- Sequential printing (print sequence: one at a time) has weird quirks:
  - Adjusting the fan speed from the display during print, will cause the fan speed to no longer regulate itself in subsequent objects. It will keep the set fan speed until the end of the object, drop down to the 'first layer(s)' setting and then remain at that. It will no longer spin back up.
  - Pausing the print from the display during printing, will cause the extruder to move directly to FRONT left of the build plate. It will not raise the Z-axis and thus will collide with any objects along it's path.
  - Ankerslicer preview doesn't display the per object skirts correctly (they will print correctly)
  - Ankerslicer preview will not display layers properly for any object after the first. It will instead pop in the entire object into view after the first layer is shown by layer selector on the right
  - **Note:** The gantry is roughly 30mm tall, however the X-axis stop on the left of the extruder brings this down to 23mm
  

## Note

The configuration authors strongly believe there is no "one size fits all" profile. These profiles provide an excellent base to get started, but we highly encourage users to learn and adjust their slicer settings to suit their use case.

## Overview

These profiles will allow you to add the AnkerMake M5 as a new printer in the menus.
Installing the profile:

1. Open Cura
1. Under the Help Menu, choose "Show Configuration Folder" (keep this folder open for the next several steps).
1. Close out of Cura
1. Download [Cura-5.x-M5-Profile.zip](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest/download/Cura-5.x-M5-Profile.zip)
1. Extract the zip file to a location of your choice and open the folder.
1. Copy the Contents of this folder to the Configuration folder you opened in step two. (Note you will be adding files to the directories)
1. Open Cura, and you should now be able to add a new AnkerMake M5 Printer.
![image](https://user-images.githubusercontent.com/10281380/204983099-ebb1007c-1171-4e68-a2e7-a2620efcca1b.png)
Optional: Enter a new Printer Name
Complete the printer setup
You now should have an AnkerMake M5 with some basic built-in Printer Profiles.

## Licences

- Cura profiles are under released under the [GNU LESSER GENERAL PUBLIC LICENSE v3.0](Cura-5.x-M5-Profile/LICENSE).

## Changelog

[View Changelog](/changelog.md)
