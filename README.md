# Heightmap-Based Water Shader for OpenMW 0.51
### Ver. 1.0.1
This is a core shader mod for OpenMW 0.51 that attempts to improve the look of the default water.

<img src="https://i.imgur.com/YdordQS.png" alt="Seyda Neen Coastline">
<details>
  <summary>Screenshots</summary>
  <img src="https://i.imgur.com/dMKih1v.png" alt="Rain at Wolverine Hall">
  <img src="https://i.imgur.com/koFwAHl.png" alt="Kushtashpi">
</details>

## Features

Instead of scrolling normal maps, this shader uses heightmaps to simulate the water surface, allowing for a more dynamic wave effect.
Other features include exponential light absorption and fogging for refraction, tweaked reflection sampling, and a few miscellaneous bugfixes.

## Installation

1. Find the resources directory inside your OpenMW installation and make a backup of it. Don't put anything in this backup, it's just for uninstalling/reinstalling.
2. Copy the contents of the resources directory provided by this mod into OpenMW's resource directory. This will overwrite several files.
3. Done.

### Compatibility
This shader was created to work with OpenMW 0.51. If you want to use it with development builds of 0.52, you'll need to use the OMW-prerelease branch.

This will likely conflict with other core shader mods. Combine them with caution.

## Credits

Qlonever - Mod author, shader modification

OpenMW contributors - Wrote the shader code this mod is built off of
(https://gitlab.com/OpenMW/openmw/-/tree/openmw-51)
