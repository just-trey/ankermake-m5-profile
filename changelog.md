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
