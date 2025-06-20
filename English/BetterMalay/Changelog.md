---
description: Changelogs for all BetterMalay Language Pack versions
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

# Changelog

## v1.2.2 Hotfix (14/3/2025) \[1.20-1.21]

* Removed all post-1.19.2 strings from the ms\_my.json file, as the Rumi Malay translations are now always up-to-date across all versions after 1.19.2

## v1.2.1 (21/2/2025) \[1.13-1.21]

* \[1.13+] Updated base translation file to 25w08a
* \[1.13-1.19] Added the entire zlm\_arab.json file from JawiCraft, so the Jawi Malay translations are guaranteed to be up-to-date
* \[1.19+] Fixed Jawi translations of Deep Lukewarm Ocean biome name (slight typo) and the `Armor Toughness` text (previously accidentally translated as just `Armor`) (taken from JawiCraft)
* \[1.20+] Removed all post-1.19.2 strings from the zlm\_arab.json file, as the Jawi Malay translations are now always up-to-date across all versions after 1.19.2
* \[1.20+] Updated the credits to be based on the 1.21.4 revision
* \[1.21+] Renamed "Creator (Music Box)" disc name to "Creator (Kotak Muzik/کوتق موزيک)"
  * According to the glossary the "Music Box" portion of the disc name is translatable
* Fixed the BetterMalay's credits section title being displayed as "JawiCraft Language Pack"
* Updated the pack to support 1.21.4

## v1.2 (31/8/2024) \[1.6 - 1.21]

* Fixed many errors in the language files, which means that the files should work now!
* Updated the pack to support 1.21
* Updated the pack icon for 1.20.x-1.21.x to reflect the 1.21 update, with some aspects of the 1.20 update still intact
* Updated some splash texts

***

## v1.1 (1/5/2024) \[1.6 - 1.20]

* First release of 2024!
* Version listing for the following Minecraft versions is heavily simplified; to reflect the simplification happened with the JawiCraft project
  * The 1.6 & 1.7-1.8 packs have been merged into **1.6-1.8** pack; the 1.13-1.14, 1.15-1.16 and 1.17-1.19 packs all have been merged into a single **1.13-1.19** pack
    * The resource pack icon has been updated for the 1.13-1.19 pack, with a cameo appearance from EmpAhmadK, who helped a ton during the development of JawiCraft!
  * This is done to make the updating process in the future easier, especially when counting the pre-1.13 packs
  * When loading up the pack in versions 1.13-1.18, ignore the warning given, as it should've worked regardless
* Updated lots of translations, which can be seen in full [here](https://github.com/Minecraft-EdisiMelayu/MCEM-Wiki/wiki/Terjemahan-Baharu-untuk-1-Mei)
* Fixed some Rumi (and Jawi) translations that didn't make it into 1.20.5 in time
* Ported some translation and the Three-Quarter High Hamza fixes from JawiCraft for the Jawi translations (1.19+ only)
  * To fully experience Jawi in versions before 1.19, download the full pack and apply it above the BetterMalay pack in the resource pack list (or below if you don't want to use the Jawi splash texts)
* Fixed a few typos in the translation

***

## v1.0 (15/12/2023) \[1.6 - 1.20]

* Initial Release
* 1.13+ translations are based on the 1.20.x translations
* 1.13+ translations are backported to pre-1.13 versions
* Added Malay translations of the End Poem, splash texts and job position names within the credits
  * Original translations are taken from the [MCSplahes](https://github.com/SmajloSlovakian/MinecraftSplashTextTranslation) project, by SmajloSlovakian
* Changed the "Java Edition" subtitle to "Edisi Java"
* Fixed some untranslated painting names (1.19.3+)
* Added translations exclusive to Combat Test 8c (1.16.2)
* Un-Jawi-fied the "Copyright Mojang AB" text for `zlm_arab` (Jawi Malay), due to the alignment issues which cause some characters to be rendered out of bounds (1.20.2+)
* Additional splash texts are grabbed from the JawiCraft Language Pack's list of splash text
* Added pack credits, both in-game and as a text file in each zip files
