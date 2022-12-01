# AnkerMake M5 Cura 5.1+ Profiles

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/just-trey/AnkerMake-M5-Profile?sort=semver&style=for-the-badge)

![image](https://user-images.githubusercontent.com/10281380/204983009-1b896ab9-774d-414d-adbe-b3f8aad5ccf2.png)

# Overview

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

### 1.3 - 11/16/2022

- Added “machine_head_with_fans_polygon” for one-at-a-time printing
- Renamed image and platform object to match with GitHub submission. (<https://github.com/Ultimaker/Cura/pull/13628/>)
- Slight modification to the file structure
- Updated directions.

### 1.2 - 10/22/2022

Fixed retraction amount defaults.
Adjusted acceleration to AnkerMake recommended settings.
Completely rebuilt settings from Anker profiles, so the values are consistent.
Update start and end gcode to Anker defaults
Added custom bed png image
Added more detailed settings provided by others

### 1.1 - Bug Fixes

### 1.0 - Initial Release
