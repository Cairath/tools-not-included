<a name="tools-not-included"></a>
# Tools Not Included
Tools Not Included (https://toolsnotincluded.net) is a website with tools for the game [Oxygen Not Included](https://klei.com/games/oxygen-not-included) by Klei.
Currently it features a [Map Browser](#tools-not-included-seed-browser) and [World Trait Tools]() but will be expanded with more tools in the future.

<a name="tools-not-included-map-browser-https-toolsnotincluded-net-map-tools-map-browser"></a>
## <a href="https://toolsnotincluded.net/map-tools/map-browser">Map Browser</a>
The Map Browser is a place for people to browse and share game world maps. The maps can be filtered by a set of rules: combination of counts of geysers, planets, geyser outputs or world traits.  
The map can be uploaded to the database using the [dedicated mods](https://toolsnotincluded.net/map-tools/map-browser/contribute)

<a name="tools-not-included-map-browser-https-toolsnotincluded-net-map-tools-map-browser-current-mod-versions"></a>
### Current mod versions
* Manual mod: v2 (19th Aug 2019)
* Automatic mod: v2 (19th Aug 2019)

<a name="tools-not-included-world-trait-tools-https-toolsnotincluded-net-map-tools-world-trait-finder"></a>
## <a href="https://toolsnotincluded.net/map-tools/world-trait-finder">World Trait Tools</a>
World Trait tools provide info about existing world traits, allow generating seed numbers with specified sets of traits and checking traits for a given seed number.

<a name="support"></a>
# Support
If you like the website and would like to say thanks and/or contribute to the server costs please consider supporting me on Patreon!\
\
[![image](/.README/patreon_button.png)](https://www.patreon.com/bePatron?u=16290546)
\
\
<a name="changelog"></a>
# Changelog
<a name="changelog-august-2019"></a>
### 19 August 2019
* Graphical overhaul
* Mod updates: both automatic and manual versions to v2
  * Moved generating visualization of the world map to the mod - upload per map might be a bit longer, but the server should be more stable now
  * Added error handling (automatic restart) in the automatic mod when map generation error occurs and the game gets stuck on 'Let's try that again'
  * Fixed a bug in the manual uploader that would generate incorrect map visualizations on consecutive uploads. Unfortunately some maps had to be removed (2%).
* Moved World Trait generation tools to the client side (browser)
  * It's now quicker
  * It doesn't bother the server ;)
* World traits are now colored! Yay for colors
* World trait tools: added generating traits for a given seed number in addition to finding seed numbers 

<a name="changelog-august-2019-1"></a>
### 6 August 2019
* Fixed reading config in the automatic mod (still v1)

<a name="changelog-august-2019-2"></a>
### 5 August 2019
* Removed automatic mod version from Steam (v1)
* Added manual mod version to Steam (v1)
* Uploaded automatic mod version to the website, includes auto-restarter every X maps (v1)

<a name="changelog-august-2019-3"></a>
### 4 August 2019
* Added filtering by traits to the map search rules
* Added instructions how to use maps

<a name="changelog-july-2019"></a>
### 30 July 2019
Huge revamp for the Launch Upgrade!
* Multiple asteroid support
* Trait Finder
* Tracking Neural Vacillator, AETN and Printing Pod locations
* Performance optimizations

<a name="changelog-february-2019"></a>
### 21 February 2019
* Released version 1.1 of the Automated Mod

<a name="changelog-january-2019"></a>
### 27 January 2019
* 'Reset all rules' now correctly resets also seed number  

For seeds collected since 7th Jan:
* Added a world and geyser visual map 
* Added world element composition - total masses in starting biome and all biomes
* Added biome size list

<a name="changelog-january-2019-1"></a>
### 12 January 2019
* Added an 'exactly' rule comparator for planet and geyser counts rules
* Brought back the possibility to reset all rules at once
* Ability to import/export rules using a generated code
* Minor styling changes

<a name="changelog-january-2019-2"></a>
### 8 January 2019
* Hotfix for mods addressing issue that was preventing connection.

<a name="changelog-january-2019-3"></a>
### 7 January 2019
Out of beta! Yay! Due to world element composition being collected, worlds uploaded need to be fresh - within 60 seconds of creation and with no cells dug. If your seed turns out to be great mid-game, you can still create a fresh world with that seed and upload it!
* The entire front-end rewritten
* The seed browser filter has been expanded with a custom rule builder
* Seed details page shows a star map
* Various performance improvements

From now on, two mods will be maintained: manual and automatic. Automatic version (aka the seed miner - not suitable for playing, seed uploading only) works in background and automatically generates and uploads new worlds without interaction. For more information please refer to the [Mod Info Page](https://toolsnotincluded.net/map-tools/map-browser/contribute)
* Mod versions 1.0a(utomatic) and 1.0m(anual):
  * Mods do not require debug mode anymore
  * Collecting data about world element composition
* Mod version 1.0m:
  * Constraint: uploaded worlds need to be within 60 seconds of their creation and with no cells dug out.

<a name="changelog-december-2018"></a>
### December 2018
* Updated roughly 1000 seeds so that there are no more seeds left without geyser detailed statistcs or lack of Oil Reservoir info

<a name="changelog-november-2018"></a>
### 23 November 2018
* Mod version 0.3.0 and 0.4.0 (hotfix):
  * Collection of planet and geyser location data

<a name="changelog-october-2018"></a>
### 21 October 2018
* Mod version 0.2.0:
  * Collecting Oil Reservoir data

<a name="changelog-october-2018-1"></a>
### 19 October 2018
Initial demo release  

\
\
\
<span style="color: gray; font-size: 0.7em;">Last readme update: Monday, 19th August 2019, 12:51 am</span>