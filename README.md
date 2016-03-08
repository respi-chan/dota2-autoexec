# Thth's Dota 2 autoexec.cfg

![keybind map](https://cloud.githubusercontent.com/assets/7574985/13619675/7ce8193e-e558-11e5-91d3-5f5668401bb6.png)

*Jam-packed with functionality on prime keyboard real estate!*


## Basis:
* ```1``` - ```5``` + ```G``` items
* ```Q``` ```W``` ```E``` ```D``` ```F``` ```R``` abilities
* ```Z``` ```X``` ```C``` control groups
* ```ALT``` modifier to quickcast items and abilities

## Features:
* League-of-Legends-style center-on-unit ```SPACE``` hotkey with ```dota_camera_lock``` (all the other ways *jiggle* the camera)
* ```ALT``` + ```A``` to quick attack in the style of quick casting with the ALT modifier
* Cycle through all chatwheel options by holding ```T``` and pressing ```Y```
* ```F1``` - ```F8``` bound to quickcast the first item — *for spamming blink after Rearm, Primal Split, or Reincarnation!*
* ```ALT``` + ```Right-Click``` for [pathfinding-disabled move command](http://store.steampowered.com/news/15840/) enabled, updated to function with [the new ```+dota_unit_movetodirection``` toggle](http://store.steampowered.com/news/19087/)!
* ```G``` item hotkey as a reserved slot for Town Portal Scrolls *not* quickcastable with ```ALT```
* ```-``` bound to toggle [automatic repeated right-clicks when right mouse button is held down](http://store.steampowered.com/news/15855/) — *for nabbing that 0 minute rune!*
* ```=``` bound to toggle 'auto attack' and 'auto attack after spell' — *for those exhilarating Naga Siren games!*
* ```n``` and ```m``` bound to move camera to top / bottom rune
* Cheat hotkeys for convenient lobby testing!
* Game-winning, inspirational, and megalegit chat messages such as:
  * ```KP_0``` (team-chat) ```KP_DEL``` (all-chat) "Remember to keep good posture and stay hydrated!"
  * ```LEFTARROW``` "Remember to communicate/ping for Living Armor! (only for damage block at lower lvls)"
  * ```KP_8``` (team-chat) ```KP_9``` (all-chat): *(separated into 5 keypresses to accomodate the chat message length limit)*

    > Soldiers! Don't give yourselves to brutes, men who despise you and enslave you, who regiment your lives,
    > tell you what to do, what to think and what to feel! Who drill you, diet you, treat you like cattle,
    > use you as cannon fodder! Don't give yourselves to these unnatural men- machine men with machine minds and machine hearts!
    > You are not machines! You are not cattle! You are men! You have a love of humanity in your hearts! You don't hate!
    > Only the unloved hate, the unloved and the unnatural. Soldiers! Don't fight for slavery! Fight for liberty!
    > 
    > — [The Great Dictator (1940)](https://www.youtube.com/watch?v=5IvPIWzQcUY)

* *and more!*

## To use:

* Add autoexec.cfg to ```Steam/SteamApps/common/dota 2 beta/game/dota/cfg/```
* Configure Dota 2 to run autoexec.cfg on startup:
  * add the line ```"exec" "autoexec.cfg"``` to "convars" in game_convars.vcfg — located in the same directory
  * *OR*
  * add ```+exec autoexec.cfg``` to Dota 2's launch options (right-click Dota 2 in Steam library > Properties >Set Launch Options)
* Manually configure accompanying hotkeys and options as follows: (because you can't specify modifiers in the autoexec)

**Accompanying in-game hotkeys:**
![Accompanying in-game hotkeys](https://cloud.githubusercontent.com/assets/7574985/13619682/8d0a9580-e558-11e5-9fc2-d1a783f2524b.jpg)
* set ```ALT``` + ```[key]``` to quickcast for abilities and items

**Accompanying in-game options:**
![Accompanying in-game options](https://cloud.githubusercontent.com/assets/7574985/13619687/958292e4-e558-11e5-9ebe-77f2c64e1d2e.jpg)

---

*keybind map made with [keyboard-layout-editor](http://www.keyboard-layout-editor.com/)*
