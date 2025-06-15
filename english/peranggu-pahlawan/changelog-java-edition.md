---
description: Changelogs for all Peranggu Pahlawan (Java Edition) versions
icon: scroll
layout:
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
---

# Changelog (Java Edition)

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
