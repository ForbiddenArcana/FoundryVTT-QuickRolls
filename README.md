# FoundryVTT-QuickRolls
A module for quicker rolling in FoundryVTT, forked from slcao2's with a handful of bug fixes and the addition of some houserules our table uses.

## Installation
You can install this module in a couple different ways outlined below.
<!--
### Install through FoundryVTT Add-on Modules Tab (Recommended)
* Go to the Add-on Modules tab.
* Click Install Module.
* Search for QuickRolls and click install.
-->
### Direct URL Install
* Go to the Add-on Modules tab.
* Click Install Module.
* Copy https://raw.githubusercontent.com/ForbiddenArcana/FoundryVTT-QuickRolls/main/module.json into the Manifest URL and click install.

### Manual
* Clone and extract the repo into the `Data/modules/quick-rolls-forbidden-arcana` folder.
* You can either clone the repo or download a zip archive from the tags.

## Compatabilities
Anything that overrides the overriden functions in overrideItem, overrideActor, or overrideActorSetup will likely be incompatible.
* [Dice So Nice](https://gitlab.com/riccisi/foundryvtt-dice-so-nice) - Compatible. It should roll properly and respect the immediatelyDisplayChatMessages setting.
* [Tidy5e Sheet](https://github.com/sdenec/tidy5e-sheet) - Compatible. Tested using the sheet styling, maybe even more so than the default sheet since I personally use it when running my games.

All other modules may or may not be compatible.

## Acknowledgements
* Since it was forked, the vast majority of the code remains identical to [Steven Cao's module](https://github.com/slcao2/FoundryVTT-QuickRolls). Thank you for getting us off the ground with this module, as it's been a noticeable QoL improvement for our play!
* A bulk of the code contained in the *Overrides.js file has been taken and modified from similar functions in the [DnD5e System](https://gitlab.com/foundrynet/dnd5e)
* Inspiration for the roll style taken from a combination of [BetterRolls5e](https://github.com/RedReign/FoundryVTT-BetterRolls5e) and [Midi-QOL](https://gitlab.com/tposney/midi-qol)
