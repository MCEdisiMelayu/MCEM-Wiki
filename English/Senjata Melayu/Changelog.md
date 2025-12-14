---
description: Changelogs for all Senjata Melayu versions
icon: scroll
---

# Changelog

## v1.4.2\_01 (13/12/2025) \[Bedrock]

* Updated the in-game pack name slightly to make it consistent with the Peranggu Pahlawan addon
* Updated the pack's min\_engine\_version to support Vibrant Visuals
* The subpack hints and credits can now be seen again in-game, just in slightly different places (the credits is now in the pack's description)
  * The credits text have been adjusted to work around OreUI's text formatting limitations
* The pack version number is now included in the in-game pack name
* Adjusted Credits.txt slightly

## v1.4.2 (31/8/2025) \[Bedrock]

* Added copper variant for the keris and parang
* Currently not available in-game by default and requires enabling the "Drop 3 2025" setting in the "Experiments" section (until 1.21.110 released)

Note: This pack's settings' description implementation used for displaying the description of subpacks and the credits are no longer supported as of 1.21.100. This feature may return in some form in a future update.

## v1.4.2 (31/8/2025) \[1.13-1.21 + 25w35a]

* Updated the pack.mcmeta file to work with the new supported versions format introduced in 25w31a
  * Note: This pack will only load correctly in 25w34a and above, due to bug [MC-300888](https://bugs.mojang.com/browse/MC/issues/MC-300888)
* \[25w31a+] Added copper variant for the keris and parang

Note: If there are no further changes between now and 1.21.9's full release, this version will be marked as compatible with 1.21.9 on Modrinth

## v1.4.1 (8/6/2025) \[Java 1.7 - 1.21 & Bedrock]

#### Very minor update this time

* \[Java 1.6-1.12] Removed the old keris' CIT definition for the non-existent netherite variant
* Updated the credits text file

## v1.4 (15/2/2025) \[Java 1.7 - 1.21 & Bedrock]

* Changed the texture of empty slot icons for sword and axe into keris and parang respectively
* Added more strings to the language files to replace any mentions of sword and axe into keris and parang respectively
* Renamed `Machete` to `Parang` for English languages
* \[Java] Changed the hotbar attack indicator texture into a golden keris (1.20.2+ Only)
* \[Java] Readded the old keris texture via CIT (rename a keris to a " Old Keris"/"Keris Lama " to see it)
* \[Java] Updated the pack to support 1.21.4
* \[Bedrock] Added an in-game pack settings slider
  * Used for when you are also using the Busana Melayu resource pack and have this pack above it to change all the the icons in the smithing table
  * The pack credits are also shown in the settings window
* \[Bedrock] The "Keris Only" pack are no longer provided
* Resized all pack icons from 1080x1080 to 512x512 to reduce file size

## v1.3 (31/8/2024) \[Java 1.7 - 1.21 & Bedrock]

* Changed the keris texture to the new one, thanks to flurrry for the base texture
* Changed the machete texture to remove the gold patches on the handles
* Updated the pack icon
* Updated the credits file

## v1.2 (15/12/2023) \[Java 1.7-1.20]

* Initial Modrinth release!
* Added 1.20 support
* Removed the `ms_arab_my` language file, as it was no longer used by the JawiCraft Language Pack (which now uses `zlm_arab` instead, which is what is used in-game in 1.19+ versions)
* Added `en_gb`/`en_GB` language files (which is basically a copy of `en_us`/`en_US`)
* \[Pre-1.13] Fixed a not so obvious oversight, which makes the machetes and kerises didn't show up in-game at all
  * The folder for the item textures is mistakenly named _item_ (as it is in 1.13+ packs), not _items_ (as intended for pre-1.13 packs)
    * But it actually works for me somehow, maybe I already fixed it, **but only for my copy of the pack**... I'm so sorry for that blunder
  * Now for anyone that want to use this pack in versions like 1.8 or 1.12, go ahead! It should work as intended now! (hopefully)
* \[Pre-1.13] Added support for Jawi translations (via the JawiCraft Language Pack)

## v1.1.1 Hotfix (16/1/2023) \[Bedrock Only]

* Fixed an error in the pack's UUID

## v1.1 (5/1/2023) \[Java 1.7-1.19 & Bedrock]

* Changed the pack name to Senjata Melayu
* Added machetes/parang, which replace axes
* Credits are updated a bit, to add the credit for the machete idea

## v1.0 (2/9/2022) \[Java 1.7-1.19 & Bedrock]

* Initial release
* Pack is currently known as Keris Melayu
* Swords are changed to Keris
