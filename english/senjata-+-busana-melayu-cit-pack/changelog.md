---
icon: scroll
---

# Changelog

## Release 3 (15/2/2025) \[Java 1.12, 1.20 - 1.20.4, 1.21-1.21.1]

* Heavily simplified the pack's content, to reduce the file size
  * Removed all duplicate texture files, now they're all in the same place for both language options
  * The names of each CITs for both languages are now stored inside a single properties file using regex, instead of using two separate files
* Added support for Jawi names on all CITs
  * The kain sarung CIT accepts both types of hamza, the regular one (کا`ء`ين ساروڠ), as well the high hamza (کا`ٴ`ين ساروڠ) which will show up as the three-quarter high hamza in-game in 1.20+ versions
* Added support for the Chime mod
  * Jawi names are not yet supported when using Chime
* Renamed `Baju` to `Baju Melayu` and `Seluar` to Seluar Melayu for all language sets; as well as `Machete` to `Parang` for English language
  * When updating the pack, be sure to rename any existing items that uses the old name to the new one
* Fixed a bug where all the Kain Sarung's icon texture was accidentally set to the Kasut's icon texture for the Malay variant
* Fixed a bug where all the Kasut's icon are still displayed with the vanilla boot texture, mainly due to the bug above
* Added a credits file in the zip files
* Resized the pack icon from 1080x1080 to 512x512 to reduce file size

## Release 2 (31/8/2024) \[Java 1.12, 1.20 - 1.20.4, 1.21-1.21.1]

* \[SM] Changed the keris texture
  * The old keris texture is now available under the following name: \[Material] Old Keris / Keris Lama \[Bahan]
* \[SM] Changed the machete texture to remove the gold patches on the handles
* \[BM] Changed the diamond tengkolok texture to make the transition between diamond and netherite more seamless
* \[BM] Added the female's variant of the Malay attire (under the type **Busana (P)** in [the item name table](item-table.md))
  * These are compatible with the main Busana Melayu pack's implementation
* Changed the name used to get the men's Baju texture from "\[Material] Baju" to "\[Material] Baju Melayu"
  * This is to resolve the conflict between this and the "\[Material] Baju Kurung" CIT names used by the female variant
* Fixed the issue of the leather item icons not showing up
* Added a credits file into the zip file
* Updated the pack to support 1.21
  * ~~However, the pack will not work at all on versions past 1.20.4, due to~~ [~~the 1.20.5 update breaking the current CIT system~~](https://github.com/sp614x/optifine/issues/7658) Now works on 1.21.x versions via [OptiFine 1.21(.1)\_HD\_U\_J1\_pre9](https://optifine.net/downloads) or [CIT Resewn v1.2.0](https://modrinth.com/mod/cit-resewn/changelog)
* Updated the pack icon

## Release 1 (29/4/2024) \[Java 1.12, 1.20 - 1.20.4]

* Initial Release
* Might work on other versions, but these haven't been tested yet

### Known Issues

* The songkok item icon did not appear at all, but the armor model still works as intended
