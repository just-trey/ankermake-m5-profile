# AnkerMake M5 PrusaSlicer 2.5+ Profiles

[![GitHub release](https://img.shields.io/github/v/release/just-trey/AnkerMake-M5-Profile?display_name=tag&sort=semver&style=for-the-badge)](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest)

![image](https://user-images.githubusercontent.com/10281380/204983009-1b896ab9-774d-414d-adbe-b3f8aad5ccf2.png)

## Overview

These configurations allow you to add the AnkerMake M5 as a new printer in the menus. Ensure you are using at least PrusaSlicer 2.5.0-rc1. (note 2.5 is now GA <https://www.prusa3d.com/page/prusaslicer_424/>)

## Known Issues

- Anything with less than 1 hour of print time will display a considerable remaining time on the printer but does not affect the actual print time.

## Note

The configuration authors strongly believe there is no "one size fits all" profile. These profiles provide an excellent base to get started, but we highly encourage users to learn and adjust their slicer settings to suit their use case.

## Installing the profile

1. Open PrusaSlicer
1. Under the Help Menu, choose "Show Configuration Folder" (keep this folder open for the next several steps).
1. Close out of PrusaSlicer
1. Download [PrusaSlicer-2.5-M5-Profile.zip](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest/download/PrusaSlicer-2.5-M5-Profile.zip)
1. Extract the zip file to a location of your choice and open the folder.
1. Copy the *"vendor"* folder to the Configuration folder you opened in step two.![image](https://user-images.githubusercontent.com/10281380/209450820-d98c5f82-07d5-453b-b5e1-11b294b257ac.png)
1. Open PrusaSlicer, and you should now be able to add a new AnkerMake M5 Printer. (printer Settings tab → Printer drop-down → Add/remove printers
1. In the Configuration Wizard, choose Other Vendors:
1. Select the AnkerMake Checkbox
1. Select AnkerMake FFF under the left menu
1. Ensure the check mark next to the 0.4 mm nozzle is enabled.
1. In the left Navigation, select Filaments and then select all available filaments.  
1. Once you have added any other printers or made changes, click Finish on the Configuration wizard.

You now should have an AnkerMake M5 with some base built-in Printer Profiles.
