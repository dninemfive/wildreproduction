# Wild Reproduction
![version](https://img.shields.io/badge/RimWorld-1.4-brightgreen.svg) ![modVersion](https://img.shields.io/github/v/release/dninemfive/wildreproduction?color=brightgreen&label=Mod%20version) ![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)

[![steamlink](https://raster.shields.io/steam/downloads/2236146674.png?color=blue&label=Workshop&logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=2236146674) [![githubdls](https://img.shields.io/github/downloads/dninemfive/wildreproduction/total?color=blue&label=Github&logo=github)](https://github.com/dninemfive/wildreproduction/releases/latest)

Spiritual successor to WalkingProblem's [Wild Animal Sex](https://steamcommunity.com/sharedfiles/filedetails/?id=1224175982), allowing wild animals to reproduce. Applies the same effect using only patches, no custom defs or classes.

## Details
Specifically, the mod moves the `ThinkNode` which tells animals to mate outside of a `ThinkNode_ConditionalHasFaction`, which in the base game prevents wild animals from reproducing.

In addition, the natural deterioration of fertile eggs is removed. They will still suffer deterioration from being left outside, but for most animals they will still hatch.

Note: certain features, like WAS' spawning of extra prey in some cases, will not be included, as I consider them superfluous.

## Compatibility
This should be compatible with basically anything. Mods which add behavior between the "satisfying needs" and conditional colony animal behavior may have unpredictable effects, but nothing too bad should happen. Mods which modify colony animal mating behavior via the ThinkTree will not function, but I'm not aware of any such mods.

The egg changes will apply to any mod whose eggs inherit EggFertBase. Mods which don't do this probably don't want to be affected, anyway.