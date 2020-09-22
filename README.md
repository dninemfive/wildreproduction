# Wild Reproduction
![version](https://img.shields.io/badge/RimWorld-1.2-brightgreen.svg) ![modVersion](https://img.shields.io/github/v/release/dninemfive/wildreproduction?color=brightgreen&label=Mod%20version) ![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)

[![steamlink](https://raster.shields.io/steam/downloads/2037445541.png?color=blue&label=Workshop&logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=2037445541) [![githubdls](https://img.shields.io/github/downloads/dninemfive/wildreproduction/total?color=blue&label=Github&logo=github)](https://github.com/dninemfive/wildreproduction/releases/latest)

Spiritual successor to WalkingProblem's Wild Animal Sex, allowing wild animals to reproduce. Applies the same effect using only patches, no custom defs or classes.

Specifically, the mod moves the `ThinkNode` which tells animals to mate outside of a `ThinkNode_ConditionalHasFaction`, which in the base game prevents wild animals from reproducing.

In addition, the natural deterioration of fertile eggs is removed. They will still suffer deterioration from being left outside, but for most animals they will still hatch.