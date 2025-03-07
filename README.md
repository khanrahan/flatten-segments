# Flatten Segments
Plugin for [Autodesk Flame software](http://www.autodesk.com/products/flame).

Takes vertically stacked segments and flattens them to just the top most segments.

![screenshot](flatten_segments_demo.gif)

## Compatibility
|Script Version|Flame Version|
|---|---|
|v2.X.X|Flame 2025 and up|
|v1.X.X|Flame 2023 up to 2024.2|

## Installation

### Flame 2025 and newer
To make available to all users on the workstation, copy `flatten_segments.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `flatten_segments.py` to the appropriate path below...
|Platform|Path|
|---|---|
|Linux|`/home/<user_name>/flame/python/`|
|Mac|`/Users/<user_name>/Library/Preferences/Autodesk/flame/python/`|

### Flame 2023.3.2 up to 2024.2
To make available to all users on the workstation, copy `flatten_segments.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `flatten_segments.py` to `/opt/Autodesk/user/<user name>/python/`

### Last Step
Finally, inside of Flame, go to Flame (fish) menu `->` Python `->` Rescan Python Hooks

## Menus
- Right-click selected segments in the Timeline `->` Edit... `->` Flatten Segments

## Acknowledgements
UI Templates courtesy of [pyflame.com](http://www.pyflame.com)
