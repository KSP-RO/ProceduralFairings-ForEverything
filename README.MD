# Procedural Fairings - For Everything!
[![][shield:ksp-version]][Squad]&nbsp;
[![][shield:ckan]][CKAN]&nbsp;
[![][shield:license]][License]

![pffe:standard]
![pffe:tu]


## Overview
Procedural Fairings For Everything (PFFE) replaces / adds to fairings and fairing bases in mods to use Procedural Fairings instead of the stock fairings, or the various other means that mods have come up with to add fairings to their packs. The more recent versions support the stock part variants as well as coloring from Textures Unlimited.


## Contributors
Felger, blackheart612, Ravenchant, MeCripp, ferram4, PhineasFreak, NathanKell, pap1723


## Features
* Fairing bases upgraded to use Procedural Fairings
* Interstage bases upgraded to use Procedural Interstages
* Decouplers used as Interstage Bases when not available
* Many fairing textures from blackheart612, Ravenchant, MeCripp, and pap1723
* Full colorization using texture masks supported by Textures Unlimited
* Texture Switching using the Part Variant system in stock


## Supported Mods
* Stock
* Ven's Stock Revamp
* KW Rocketry
* NovaPunch
* Realism Overhaul


## Requirements & Installation
These required mods are not included with the download so you will need to get them on your own. We highly reccomend CKAN to install PFFE.
* Procedural Fairings
* Module Manager (should just be included in stock installs from now on!)


## Fairing Shape Reference
With the newest release of Procedural Fairings, you can now completely design your own fairing shape. We have decided to remove all of the individual fairing shapes that were previously released as parts. This cleans up the very cluttered VAB, but with the drawback of not having the pre-built shapes you may have used before. Here is a reference to the settings you should have in order to make the fairing shapes the same as previous parts.

In order to be able to edit the shape of the fairing:
1) Right click on the fairing side
2) Click Base Auto-shape to OFF
3) Click Nose Auto-shape to OFF
4) Input the numbers here

### Conic [Pre-set Part]

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.3
| baseConeShape2   | 0.3
| baseConeShape3   | 0.7
| baseConeShape4   | 0.7
| baseConeSegments | 7
| noseConeShape1   | 0.1
| noseConeShape2   | 0
| noseConeShape3   | 0.7
| noseConeShape4   | 0.7
| noseConeSegments | 11
| noseHeightRatio  | 2

### Ogive (Egg) [Pre-set Part]

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.3
| baseConeShape2   | 0.2
| baseConeShape3   | 1
| baseConeShape4   | 0.5
| baseConeSegments | 7
| noseConeShape1   | 0.5
| noseConeShape2   | 0
| noseConeShape3   | 1
| noseConeShape4   | 0.7
| noseConeSegments | 11
| noseHeightRatio  | 2

### Cone-Egg (Conic Base, Ogive Nose)

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.3
| baseConeShape2   | 0.3
| baseConeShape3   | 0.7
| baseConeShape4   | 0.7
| baseConeSegments | 3
| noseConeShape1   | 0.5
| noseConeShape2   | 0
| noseConeShape3   | 1
| noseConeShape4   | 0.7
| noseConeSegments | 11
| noseHeightRatio  | 2

### Atlas V

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.1
| baseConeShape2   | 1
| baseConeShape3   | 0
| baseConeShape4   | 0.7
| baseConeSegments | 3
| noseConeShape1   | 0.1
| noseConeShape2   | 0
| noseConeShape3   | 0.7
| noseConeShape4   | 0.7
| noseConeSegments | 11
| noseHeightRatio  | 3.5

### Delta

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0
| baseConeShape2   | 0
| baseConeShape3   | 0
| baseConeShape4   | 0
| baseConeSegments | 3
| noseConeShape1   | 0.3
| noseConeShape2   | 0
| noseConeShape3   | 1
| noseConeShape4   | 0.8
| noseConeSegments | 11
| noseHeightRatio  | 2

### Jupiter / Titan

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.3
| baseConeShape2   | 0.3
| baseConeShape3   | 0.7
| baseConeShape4   | 0.7
| baseConeSegments | 3
| noseConeShape1   | 0
| noseConeShape2   | 0
| noseConeShape3   | 0.7
| noseConeShape4   | 0.2
| noseConeSegments | 3
| noseHeightRatio  | 2

### Long March

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.7
| baseConeShape2   | 0.7
| baseConeShape3   | 0.3
| baseConeShape4   | 0.3
| baseConeSegments | 5
| noseConeShape1   | 0.2
| noseConeShape2   | 0
| noseConeShape3   | 0.7
| noseConeShape4   | 0.2
| noseConeSegments | 50
| noseHeightRatio  | 2.8

### Proton

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0
| baseConeShape2   | 0
| baseConeShape3   | 0
| baseConeShape4   | 0
| baseConeSegments | 4
| noseConeShape1   | 1.25
| noseConeShape2   | 0.2
| noseConeShape3   | 0.1
| noseConeShape4   | 0.8
| noseConeSegments | 3
| noseHeightRatio  | 3

### Soyuz

| Setting          | Value
| ---------------- | :---:
| baseConeShape1   | 0.3
| baseConeShape2   | 0.3
| baseConeShape3   | 0.9
| baseConeShape4   | 1
| baseConeSegments | 2
| noseConeShape1   | 0.54
| noseConeShape2   | 0
| noseConeShape3   | 0.52
| noseConeShape4   | 0.035
| noseConeSegments | 10
| noseHeightRatio  | 2.2


## Known Issues
* Procedural Fairings cannot place the "top" node below the fairing start point. KW Expanded Fairings place the payload above the structure. Use the stock offset tool to place the payload onto the structure.
* Some of the interstage node placements don't scale well with the interstage model, you may see some clipping. Again, can fix with the stock offset tool.


## Changelog

### v0.3.0
* Removed the dependency on Firespitter => Using stock part variant system now
* Added full support for Textures Unlimited, if installed, it creates recolorable versions of the included textures
* Added a new style of Fairing called "Procedural Fairing Logos"
  * NASA
  * Angara ISS
  * Angara Roscosmos
  * Falcon 9
  * Falcon Heavy
  * GLONASS
  * GPS
  * Iridium Next
  * KSLO KerbalX
  * Landsat
  * Long March CLEP
  * Long March Chinese Flag
  * NASA Seal
  * NASA Worm
  * NOAA
  * NRO
  * SpaceX
  * SpaceX Vertical
  * TDRS
  * USAF
* Removed the different fairing sides that were created as separate parts
* Removed the base decoupler patch as it is included in Procedural Fairings now
* Removed the Invisible Wall patch as it is included in Procedural Fairings now
* Completely restructured all of the folders to maintain consistency with how most mods organize them now

#### v0.2.0
* Sound patch and don't-create-unloadable-parts patch by khr15714n
* Saturn-Nova stringers texture and the inclusion of working normal maps generally by ferram4
* Repackaged without bundled dependencies--get them separately! Oh and we have a readme now.

#### v0.1.1
* Added PhineasFreak's Invisibility patch to the fairing walls.

#### v0.1.0
* Changed part methodology to duplicate Procedural Fairings parts to reduce risk of forward compatibility.
* Fixed "parts don't want to stay attached to vehicle" bug.

#### v0.0.3
* Added MeCripp's Long March Textures and Shape
* Changed default editor preview texture for all Fairing Walls to their default textures.

#### v0.0.2a
* Added Ravenchant's Soyuz and Tskylon shapes and textures to the fairing walls

#### v0.0.1
* Minor Release, adds Realism Overhaul scaling as a final pass to all fairing and interstage bases.

#### v0.0.0
* Initial Release


[Squad]: https://kerbalspaceprogram.com/index.php
[CKAN]: https://github.com/KSP-CKAN/CKAN
[License]: https://creativecommons.org/licenses/by-nc-sa/4.0/

[shield:ksp-version]: https://img.shields.io/badge/KSP%20Version-1.4.x%20--%201.7-success.svg?style=for-the-badge
[shield:ckan]: https://img.shields.io/badge/CKAN-Indexed-orange.svg?style=for-the-badge
[shield:license]: https://img.shields.io/badge/License-CC--BY--NC--SA-blue.svg?style=for-the-badge
[pffe:standard]: https://github.com/KSP-RO/ProceduralFairings-ForEverything/blob/master/Source/PFFEfairings.PNG?raw=true
[pffe:tu]: https://github.com/KSP-RO/ProceduralFairings-ForEverything/blob/master/Source/PFFEfairingsTU.PNG?raw=true
