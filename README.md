# Introduction

This is a simple modification to increase the outpost and homesite radius by a small amount in State of Decay: Year One Survival Edition (YOSE). [Original Nexus Mods release](https://www.nexusmods.com/stateofdecay/mods/502).

## Installation

1. To install, first choose the directory where you want the mod to be applied to:
- class3/ (story mode)
- class3.1/ (breakdown)
- class3.2/ (lifeline)

Place the contents into your Steam directory of your State of Decay YOSE game. For example, **"C:\Steam\steamapps\common\State of Decay YOSE\Game"**.

2. To uninstall, simply remove ```homeenclaves.win.bmd```, ```homeenclaves.xml```, ```rtsevents.win.bmd```, and ```rtsevents.xml``` under the directory of the mode. For example, if you want to remove the mod on Breakdown, the directory would be **libs/class3.1/rts/**.

## Contributions

Contributions are welcome! Please create a new branch and make a pull request to the main branch so that I'll review the changes and approve it if it's beneficial enough.

## Compatibility

Not compatible with mods that modify ```homeenclaves.win.bmd```, and ```rtsevents.win.bmd```. If you wish to use this mod with other mods that modify the same files, check out the changed lines in this repository so you know where to make your changes in ```homeenclaves.xml```, and ```rtsevents.xml```. After making changes, you must download ```xml2bmd``` from **dude1234** and drag your edited .xml in there to create a new .bmd file. For example, if you want to include the mod on Breakdown, you must drag the new .bmd file into your **libs/class3.1/rts/** directory.

## Credits

- To Undead Labs for making a wonderful game.
- To dude1234 for creating the xml2bmd application.
- To Chimedtseren of Nexus Mods for the suggestion of a Breakdown version. I also included the Lifeline version while I'm at it.
