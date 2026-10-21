# BAR Maps

Maps for [Beyond All Reason](https://www.beyondallreason.info/).

## Simmering Ravine 1.5

`simmering_ravine_1.5.sd7`: a 14 × 20 map, mirrored top to bottom (Team A north, Team B south). It is built on All That Simmers by Nikuksis, in its textures and colours.

- **Cliffs** 450 high beside each base, with switchbacks of stone stairs cut into them. Bots and amphibious units climb them; tanks, the Thor and hovercraft can't.
- **The central route** is closed at each side by a destructible door in a stone rampart. The door is the only way down for vehicles and hovercraft.
- **The rampart** stops every unit but spiders and aircraft, and has a flat top to build turrets on. A commander's D-Gun flattens a stretch of it.
- **The river** is crossed by two stone bridges and a gravel ford.
- **Metal:** 54 spots, 62.4 metal/s a side, and 4 geothermal vents.

### Install

Copy `simmering_ravine_1.5.sd7` into BAR's `maps` folder (usually `%LOCALAPPDATA%\Programs\Beyond-All-Reason\data\maps`).

BAR's lobby only shows pictures for maps it already knows. To see this map's picture on the setup screen, also copy this repo's `LuaMenu` folder into BAR's data folder (the one that holds `maps`), then restart the lobby. That adds `LuaMenu\Images\Minimaps\Simmering_Ravine_1.5.jpg`. Each player's lobby reads its own data folder, so other players see the picture only if they copy it too.
