Silver Pine CHS - interactive 3D model
=======================================

How to run (VS Code)
1. Unzip this folder anywhere.
2. In VS Code: File > Open Folder... and choose the "silver-pine-3d" folder.
3. Install the "Live Server" extension (by Ritwick Dey) if you don't have it.
4. Right-click index.html > "Open with Live Server".
   The model opens in your browser at http://127.0.0.1:5500/index.html

Don't open index.html by double-clicking it: browsers block the JavaScript modules
over file://, and the model stays on "Building the model from the drawings...".

Everything needed is inside this folder (three.js r160 in /lib), so it works
offline. Only the Google web fonts need internet; without them the page falls
back to system fonts.

Files
  index.html                          the viewer and the building model
  lib/three.module.js                 three.js 0.160.0 (MIT licence)
  lib/addons/controls/OrbitControls.js
  lib/addons/renderers/CSS2DRenderer.js
  lib/addons/utils/BufferGeometryUtils.js

Panel: pick a floor to see its furnished plan, switch Furniture on/off, and try
colour schemes or set each part's colour (outer walls, elevation feature, floor
bands, sunshades, frames, glass, railings, columns, boundary wall, interiors, floors).

Walk through: choose GF, 1st-4th or Roof. For 1st-4th choose the Left or Right
flat (as seen stepping off the stair onto the landing, facing the lift lobby).
Play/pause, scrub, change speed, drag to look around, Space pauses, Esc exits.

Mouse: left-drag rotate, right-drag pan, scroll zoom, click a room for details,
double-click a room to focus on it.
