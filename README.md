[README.md](https://github.com/user-attachments/files/29245959/README.md)
# RocketParts Logistics

RocketParts Logistics adds dedicated containers for RocketParts, Metal, and MetalOre.

This mod allows RocketParts-focused gameplay to fully benefit from the powerful drilling and logistics systems provided by MKS.

## Features

- Dedicated containers for RocketParts, Metal, and MetalOre
- Unique textures for each resource
- Resource-specific storage
- Capacity balancing based on MKS storage density
- MetalOre harvesting support for MKS drills
- Seamless integration with existing MKS logistics containers
- Optional RocketParts Mode for Extraplanetary Launchpads (EL)
- Fully reversible RocketParts Mode
- No changes to existing MKS gameplay mechanics

## Container Capacities

| Size | RocketParts | Metal | MetalOre |
|------|------------:|------:|---------:|
| 1.25m | 200 | 210 | 740 |
| 2.5m | 1600 | 1680 | 5900 |
| 3.75m | 5400 | 5650 | 19900 |
| 5m | 12800 | 13400 | 47200 |

## RocketParts Mode (Optional)

RocketParts Logistics includes an optional RocketParts Mode.

By default, MKS modifies Extraplanetary Launchpads (EL) vessel construction to use MaterialKits and SpecializedParts.

RocketParts Mode restores EL vessel construction and RocketParts transfer recipes to their original RocketParts-based behavior while leaving all standard MKS production chains unchanged.

### What Changes

- EL vessel construction uses RocketParts
- EL RocketParts transfer recipes use RocketParts

### What Does Not Change

- MaterialKits production
- SpecializedParts production
- Machinery production
- ColonySupplies production
- Electronics production
- Robotics production
- Any other MKS manufacturing chains

## Dependencies

### Required

- ModuleManager
- Modular Kolonization System (MKS)

### Automatically Provided Through MKS

- USI Tools

### Required for RocketParts Mode

- Extraplanetary Launchpads (EL)

## Known Issue

In some MKS/USI installations, the RocketParts Kontainer may appear twice in the R&D tech tree.

This is a visual-only issue. The part is not duplicated in the editor, and functionality is unaffected.

## Installation

Extract the contents of the archive into your KSP GameData folder.

### RocketParts Mode

RocketParts Mode is optional.

To enable it, keep the following file installed:

ZZZ_RocketParts_Mode.cfg

To disable RocketParts Mode, rename the file to something such as:

ZZZ_RocketParts_Mode.cfg.delete

Any filename that no longer ends with ".cfg" will prevent ModuleManager from loading the patch.

## Compatibility

RocketParts Mode is implemented entirely through ModuleManager patches.

No MKS files are modified, making the feature fully reversible and compatible with CKAN installations.

## License

CC BY-NC-SA 4.0

## Author

Goodle
