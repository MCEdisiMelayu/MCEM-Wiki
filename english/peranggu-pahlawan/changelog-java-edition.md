---
description: Changelogs for all Peranggu Pahlawan (Java Edition) versions
icon: scroll
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
  metadata:
    visible: true
  tags:
    visible: true
---

# Changelog (Java Edition)

## v1.3.0 (12/12/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.11, Forge 1.20.1, NeoForge 1.21.1]

#### Additions

* Ported the mod to 1.21.9 (The Copper Age) and it's hotfix version (1.21.10) for the Fabric and Quilt mod loader
* Ported the mod to 1.21.11 (Mounts of Mayhem) for the Fabric and Quilt mod loader
* Copper Keris, Parang and Attires!
  * Have pretty much the same stats as their vanilla counterparts, aside from the differences listed on the mod's Modrinth page
  * These copper additions are also backported to **all** supported versions, with some caveats
    * These copper items are **not obtainable in survival**, and are currently creative-only items
    * Equipping copper attires uses the same sounds as equipping iron armor
    * The `copper_tool_materials` item tag have been backported to all supported versions
* Added Old Spelling Indonesian (Bahasa Indonesia edjaän lama) translation
  * Thanks to Dustin945 for the translation (and the addition of the language to Minecraft)
* \[1.21.1] Added support for Epic Fight for NeoForge 1.21.1

#### Changes

* The `head_armor`, `chest_armor`, `leg_armor` and `foot_armor` item tag files have been moved to the top `tags/item` sub-directory from `tags/item/enchantable`
  * The `durability` and `equippable` item tag files have been removed, as it's now redundant thanks to the change above, but nothing should have changed in-game
* Fixed iron tengkolok and gandik being in the diamond tier for mob equipment
* Gold armor sets can now spawn on mobs again (both vanilla armor and this mod's attires)
* The mob equipment code have been changed to better match vanilla behaviour

#### Chainmail Attires' Crafting Recipes

* Now re-added into the mod, but are not visible in the recipe book, and you must install [Sumbaii999's Craftable Chainmail Armor](https://modrinth.com/datapack/craftable-chainmail-armor-by-sumbaii999/) mod to be able to craft them in-game
  * Not necessarily vanilla-like, but the option is there if you want to craft them
  * If you are playing on versions that are not supported by the Polymorph mod (1.21.4+), you must fill all the remaining slots with Iron Nuggets when crafting a Chainmail Baju Melayu or Seluar Melayu
    * This is to avoid conflicts with vanilla Chainmail Chestplate's and Leggings' crafting recipes (which are the same shape and also not visible in the recipe book)

## v1.2.1 (6/9/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.8, Forge 1.20.1, NeoForge 1.21.1]

### Changes

* Fixed the following issues with the language files
  * \[ALL] Fixed a very minor typo in the Indonesian translations that neither me nor the translator noticed
    * It's the Chainmail Gandik being translated as "Gandi**l** Rantai"
  * \[1.21.8] Fixed a missing comma in the json file for the Malay translation file; now Malay translations for the modified advancement descriptions should work again
  * If you're affected by these (minor) issues, you may want to update to this version.

### Notes

**This version is compatible with servers running Peranggu Pahlawan v1.2.0** (on both native Fabric and via Connector), as the only thing changed in this version are the language files, and none of the codes are changed

## v1.2.0 (31/8/2025) \[Fabric & Quilt 1.20.1/1.21.1/1.21.4-1.21.8, Forge 1.20.1, NeoForge 1.21.1]

### Additions

* \[Fabric/Quilt] This mod is now ported to all game drops since 1.21 for the Fabric and Quilt mod loaders
  * The Garden Awakens (1.21.4)
  * Spring to Life (1.21.5)
  * Chase the Skies (1.21.6) and it's two hotfix updates (1.21.7 and 1.21.8)
  * Please note that backports to versions older than 1.20.1/1.21.1 are not planned.
* \[1.21.1 NeoForge] Added translation key for the mod's description when using NeoForge without Better ModList mod (which also appears when using the Catalogue mod)
* \[1.20.1 & 1.21.1] Added Polymorph as an optional dependency
* \[ALL] All items from this mod are now fully integrated into vanilla gameplay alongside their vanilla counterparts
  * Leatherworker and Armorer Villagers can now sell attire pieces
  * Weaponsmith and Toolsmith Villagers can now sell keris and parang
  * Zombies, Skeletons, Husks and Strays can now spawn wearing attire pieces
  * Zombies, Husks and Vexes can now spawn with iron keris
  * Vindicators can now spawn with iron parang
  * Piglins can now spawn with golden attires and keris
  * Zombified Piglins can now spawn with golden keris
  * Piglin Brutes can now spawn with golden parang
* \[ALL] Golden items are now included in the `piglin_loved` tag

### Removals

* Crafting recipes for chainmail armor are now removed, since they can now be found in normal gameplay

### Changes

* Item tags for all 9 attire pieces are now split into their own tags instead of being grouped by their armor slots
  * The old tags are still there, but are changed to refer to these new tags instead
* The `swords` and `axes` item tags now respectively refers to the `keris` and `parang` tags directly instead of listing all items in those tags again
* The "Cover Me in Debris" advancement's requirements have been tweaked so that having a full set of any combination of the two attire types grants the advancement instead of needing to have a full set of a single attire type

|                                                                                                                                                                                                    v1.1.0 Behavior                                                                                                                                                                                                    |                                                                                                                                                                                                    v1.2.0 Behavior                                                                                                                                                                                                    |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| ![](https://wsrv.nl/?url=https%3A%2F%2Fwww.gitbook.com%2Fcdn-cgi%2Fimage%2Fdpr%3D2%2Cwidth%3D1168%2Conerror%3Dredirect%2Cformat%3Dauto%2Fhttps%253A%252F%252Ffiles.gitbook.com%252Fv0%252Fb%252Fgitbook-x-prod.appspot.com%252Fo%252Fspaces%25252FTE5gKTpTSgEDzTm1dxrq%25252Fuploads%25252FRVOs3odBs2X4fSrwpgge%25252Fpp_v1.1.0_check.png%253Falt%253Dmedia%2526token%253D8ff61922-3c02-4b0c-aaa4-26ba5a4b2d76\&n=-1) | ![](https://wsrv.nl/?url=https%3A%2F%2Fwww.gitbook.com%2Fcdn-cgi%2Fimage%2Fdpr%3D2%2Cwidth%3D1168%2Conerror%3Dredirect%2Cformat%3Dauto%2Fhttps%253A%252F%252Ffiles.gitbook.com%252Fv0%252Fb%252Fgitbook-x-prod.appspot.com%252Fo%252Fspaces%25252FTE5gKTpTSgEDzTm1dxrq%25252Fuploads%25252FxbL67bhmYMcX2lHEd2xm%25252Fpp_v1.1.1_check.png%253Falt%253Dmedia%2526token%253Dc3f2c0b2-9a2f-450d-a619-9184bb220f20\&n=-1) |
|                                                                                                                                                                     Only the first two combinations grant the advancement, one for each attire set                                                                                                                                                                    |                                                                                                                                                                            Any combination of the two attire sets all grant the advancement                                                                                                                                                                           |

## v1.1.0 (8/6/2025) \[Fabric & Quilt 1.20.1/1.21.1, Forge 1.20.1, NeoForge 1.21.1]

### Additions

* Indonesian translations! Thanks to Dustin945!
* Sword Blocking Mechanics support for Keris and Parang!
* \[1.20.1] Epic Fight support for Keris and Parang!
* \[1.21.1] `keris` and `parang` item tags
* \[1.20.1] Backports of all the mod's item tags from 1.21.1 version

### Changes

* The parang now have a special ability! It can now mine logs in a 3x3 area
  * The parang's mining speed has now been significantly decreased to make it not too op without Efficiency
  * The new 3x3 block breaking functionality only applies to log-like blocks (log, wood, stem, hyphae and it's stripped variants), and not any other wood blocks (planks, slabs, etc.)
* Fixed some stuff in the language files, including the spelling of `armour` in British English using American English spelling `armor`
* The loot table code has been altered so that the two attire variants appear in one single call instead of two separate ones
  * The chance for each call is also doubled as a result
* Fixed the leather gandik in village tannery's chest accidentally being set to generate with high level enchants
* Changed Sinytra Connector's modid defined in (`neoforge.`)`mods.toml` files from `connector` to the proper id `connectormod`
* \[1.21.1] Removed the Forge dependency from the `neoforge.mods.toml` file
* Updated credits

## v1.0 (3/2/2025) \[Fabric & Quilt 1.20.1/1.21.1, Forge 1.20.1, NeoForge 1.21.1]

* Initial release
