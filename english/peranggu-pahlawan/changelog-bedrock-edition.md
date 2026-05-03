---
description: 'Changelogs for all Peranggu Pahlawan: Bedrock Edition versions'
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

# Changelog (Bedrock Edition)

## v1.4.0 (2/5/2025) \[MCBE v26.10+]

Updated the addon to support the 26.10 (Tiny Takeover) update

### Additions

* Added support for baby mobs' new armor model
  * Known Issue: The samping and kasut will be invisible when worn by baby mobs. This is due to the way the armor textures are mapped to the model, which made it impossible to adapt the samping and kasut shapes
* Better Organization in the Creative tab!
  * All items are now also grouped inside collapsable menus

### Changes

* Removed the high-definition item's fix included in the pack since the bug is now fixed since 26.0 (see [MCPE-169754](https://bugs.mojang.com/browse/MCPE/issues/MCPE-169754) | Mirror: [Mojira.dev](https://mojira.dev/MCPE-169754))
* Updated loot tables to match vanilla 26.10
* Updated an alias in the credits

### Fixes

* Piglins should now no longer attack the player when wearing one of the attires
* Piglins now can pick-up, admire, and equip golden keris, parang and attires
* Swords now no longer break blocks in creative mode
* Netherite keris, parang and attires no longer burn in lava

## v1.3.0 (13/12/2025) \[MCBE v1.21.130+]

#### Additions

* Bumped the version number to v1.3.0 to match the Java mod's version number
  * The version number is now included in the in-game pack name for both resource and behaviour packs
* Ported the addon to 1.21.130 (Mounts of Mayhem)
* Added copper keris, parang and attire sets
  * Have pretty much the same stats as their vanilla counterparts, aside from the differences listed on the addon's PlanetMinecraft page
* Changed the addon's namespace from ppbe to peranggu\_pahlawan, to match the Java mod
* All items from this mod are now fully integrated into vanilla gameplay alongside their vanilla counterparts
  * Leatherworker and armorer villagers can now sell attire pieces
  * Weaponsmith and toolsmith villagers can now sell keris and parang
  * Zombies, skeletons and some of their variants can now spawn wearing attire pieces
  * Zombies, some of it's variants and Vexes can now spawn with iron keris
  * Vindicators can now spawn with iron parang
  * Piglins can now spawn with golden attires and keris
  * Zombified Piglins can now spawn with golden keris
  * Piglin Brutes can now spawn with golden parang
* Vibrant Visuals is now supported!
* The credits can now be seen again in-game, just in a slightly different place, which is in the pack's description
  * The credits text have been adjusted to support OreUI's text formatting limitations

#### Changes

* Fixed the keris and parang item models not showing up since 1.21.100
* Fixed the Chainmail Gandik translation in the Indonesian translation
  * The item was translated as "Gandil Rantai" instead of "Gandik Rantai"
* Updated the min\_engine\_version number in the addon's resource pack to support Vibrant Visuals
* Adjusted Credits.txt slightly

#### Removal

* Crafting recipes for chainmail armor are now removed, since they can now be found in normal gameplay

## v1.1.0 (8/6/2025) \[MCBE v1.21.80+]

* Updated to be compatible with version 1.21.80 and above
* Added Indonesian translations! Thanks to Dustin945!
* The parang now have a special ability! It can now mine logs in a 3x3 area
  * The parang's mining speed has now been significantly decreased to make it not too op without Efficiency
  * The new 3x3 block breaking functionality only applies to log-like blocks (log, wood, stem, hyphae and it's stripped variants), and not any other wood blocks (planks, slabs, etc.)
* Fixed some stuff in the language files, including the spelling of "armour" in British English using American English spelling "armor"
* Updated credits

## v1.0 (3/2/2025) \[MCBE v1.21.50+]

* Initial release
