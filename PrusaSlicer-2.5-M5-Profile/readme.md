# AnkerMake M5 PrusaSlicer 2.5+ Profiles

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/just-trey/AnkerMake-M5-Profile?sort=semver&style=for-the-badge)

![image](https://user-images.githubusercontent.com/10281380/204983009-1b896ab9-774d-414d-adbe-b3f8aad5ccf2.png)

## Overview

These configurations allow you to add the AnkerMake M5 as a new printer in the menus. Ensure you are using at least PrusaSlicer 2.5.0-rc1. (note 2.5 is now GA <https://www.prusa3d.com/page/prusaslicer_424/>)

## Known Issues

- Anything with less than 1 hour of print time will display a considerable remaining time on the printer but does not affect the actual print time.

## Installing the profile

1. Ensure you have run PrusaSlicer at least once
1. Ensure PrusaSlicer is closed
1. Download [PrusaSlicer-2.5-M5-Profile.zip](https://github.com/just-trey/AnkerMake-M5-Profile/releases/latest/download/PrusaSlicer-2.5-M5-Profile.zip)
1. Extract the zip file to a location of your choice.
1. Go into the extracted files → PrusaSlicer-2.5-M5-Profile folder.
1. Copy the Vendor folder to:

- PC: C:\Users\[USER]\AppData\Roaming\PrusaSlicer
- Mac: “HDD” → ⁨Users⁩ → ⁨username⁩ → ⁨Library⁩ → ⁨Application Support⁩ → ⁨PrusaSlicer
- Linux: ~/.config/PrusaSlicer

1. Open PrusaSlicer, and you should now be able to add a new AnkerMake M5 Printer. (printer Settings tab → Printer drop-down → Add/remove printers
1. In the Configuration Wizard, choose Other Vendors:
1. Select the AnkerMake Checkbox
1. Select AnkerMake FFF under the left menu
1. Ensure the check mark next to the 0.4 mm nozzle is enabled.
1. In the left Navigation, select Filaments and then select all available filaments.  
1. Once you have added any other printers or made changes, click Finish on the Configuration wizard.

You now should have an AnkerMake M5 with some base built-in Printer Profiles.
