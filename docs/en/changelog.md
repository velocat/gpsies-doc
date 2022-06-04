<!-- markdownlint-disable-next-line first-line-heading -->
### General data for the editor and storage

### vers 3.2.1 02.06.2022

- [NEW] Added the ability to enable the "guide line" for the cursor in the track drawing mode in the settings
- [NEW] Added the ability to include a block of information (distance, direction, etc.) above the cursor in edit mode
- [FIX] When deleting the point area, the existing notes to these points were not deleted
- [FIX] When the point area deletion mode is enabled, the ability to move track points is disabled
- [FIX] In the point area deletion mode, an error has been fixed in which a new point was placed at the moment when the area was circled with the mouse
- [FIX] In the absence of the ORS API key, an error was fixed in which a warning was displayed when trying to select it in the "auto-bookmarks" list
- [FIX] Fixed the z-index (location) of information pop-ups, previously they appeared under the top navigation bar.
- [FIX] Fixed a bug that caused a comment to remain visible after deleting one point.
- [FIX] Fixed a bug that caused the hint to be moved to this point of the track after creating a new point from the midpoint marker on the line
- [FIX] In the section "General information about the editor" in the side menu, the link to this documentation has been corrected
- [FIX] When using an internal elevation server, this is indicated in the prompt instead of the ORS previously installed by default.
- [FIX] Fixed the length of some text values for correct display in different browsers
- [UPD] When you open the add/edit note window, the text input field immediately comes into focus
- [UPD] Disabled the ability to upgrade to a previous version due to backward incompatibility of versions

#### 26.01.2022

- [FIX] Fixed a bug where the color of the track in the #HEX format gave an error in the BaseCamp program. The color of the track is saved by name, red by default.

#### 25.01.2022

- [UPD] Updated documentation on the "Optimizer" tool
- [NEW] Added "Optimizer" - a built-in tool for optimizing the number of track points
- [UPD] The allowed size of uploaded files to the editor has been increased to 2MB.

#### 22.01.2022

- [NEW] Added "Map configuration" - sorting, display in the list
- [NEW] Added "Custom Maps": add/save/import/export. Basic, Overlays, WMS, WMTS
- [UPD] Updated documentation on new overlays/maps

#### 21.01.2022

- [UPD] Added new layers to the base maps (Jawg, regional OSM, OPNVKarte, etc.)
- [UPD] Added WaymarkedTrails overlays (routes): hiking, mtb, slopes, horseback riding, roller skates
- [UPD] Added OpenSnowMaps overlay: for skiers
- [UPD] Added OpenSeaMaps overlay: Marine navigation

#### 18.01.2022
  
- [UPD] Added the time scale and the length value to the height graph
- [UPD] Added names to the data in the hint on the height chart (when viewing the track)
- [FIX] Fixed accidental addition of a dot when selecting an area to delete in edit mode
- [FIX] Fixed the error of displaying all points when loading a large track from storage without taking into account the restriction
- [FIX] Fixed the error of enabling the language pack when switching to English

#### 17.01.2022

- [NEW] The release of the editor documentation v1.0.0
has been released - [FIX] The ability to switch metric/imperial values in the height profile has been added, depending on the editor settings
- [FIX] Fixed accidental addition of a point when clicking on the full-screen view button in edit mode
- [NEW] Added a map rotation controller on the screen

#### 13.01.2022

- [UPD] Changed the activity switch from selector to buttons-images

#### 20.12.2021 - 12.01.2022

- [UPD] The styles of the editor and the viewing pages have been adjusted for the new design
- [NEW] Added sorting of basic (preset) maps
- [NEW] Added the ability to recalculate the heights and corresponding statistics of available tracks from the viewing page
- [FIX] Fixed incorrect display of marker legend (page view)
- [FIX] Fixed incorrect display of segment legend (page view)
- [FIX] Fixed errors in displaying data and elevation profile for segments selected in the legend
