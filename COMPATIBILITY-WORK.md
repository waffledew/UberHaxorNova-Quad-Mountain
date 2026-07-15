# Compatibility work

This page separates preservation-maintainer work from the original mods. It does not claim ownership of upstream content.

## Reptile Mod

- Adapted the available Minecraft 1.2.5 release to Minecraft 1.1 mappings and APIs.
- Repaired the renderer/model registration that initially displayed reptiles as human player models.
- Restored and verified legacy sound registration.

## Legacy audio

- Repaired AudioMod resource-path behavior used by Mo' Creatures and More Creeps and Weirdos.
- Preserved the required legacy `.minecraft/resources/mod` layout.

## Crab and Whales

- Added Forge texture-provider compatibility for their custom item textures.
- Kept the original gameplay behavior and artwork.

## Legacy Skin Fix

- Added asynchronous loading from current Mojang-hosted skin and cape locations for Minecraft 1.1.

## Pam's HarvestCraft

- Ported HarvestCraft 5.2.3 from Minecraft 1.0 mappings to Minecraft 1.1.
- Updated renamed entity-spawn and player-edit hooks.
- Preserved the original foods, crops, recipes, world generation, identifiers, and Forge texture sheets.

## Not Enough Items

- Replaced TooManyItems with Not Enough Items 1.1.2.
- Corrected its installation from the normal mods folder to the required jar-mod position. This early NEI release patches the inventory class and otherwise appears loaded without displaying its interface.
- Moved Inventory Tweaks sorting from `R` to `K` so NEI's recipe key remains usable.

## Organization

- Original recovered downloads, patched test builds, dependencies, metadata, and resource notes are kept separately in the private development instance.
- Public binary distribution remains blocked pending the review described in [PUBLISHING-CHECKLIST.md](PUBLISHING-CHECKLIST.md).
