# bp-bot

## Inspiration
* **Tired of wasting your life away on Block Party, but you still want to earn those points?**

* **Are your fingers sore from playing too much, but you still want to earn those points?**

* **Or do you just want to step away from the computer for a moment, and still earn those points?**

This minecraft client helps prevent carpal tunnel syndrome by automating game play for the weary.

## What does it do?
This is a standard minecraft client (currently v 1.12) which has some additional code to automate your player.

When BPBot is enabled, the following occur:
* Scans the floor to detect the blocks.
* When the color is called, it will run the player to the closest block.
* After stopping on a block, the BPBot will perform some intermission moves.
* Once a new floor is loaded, BPBot will reposition your player at location (where most colors are).

## Installation

* #### Locate your minecraft versions folder:
| OS   |      Location      |
|----------|:-------------|
| Windows |  %APPDATA%\\.minecraft\versions |
| macOS |    ~/Library/Application Support/minecraft/versions   |
| Linux | ~/.minecraft/versions  |

More details can be found here [https://minecraft.gamepedia.com/.minecraft](https://minecraft.gamepedia.com/.minecraft).

* ####  Copy the files in this repo into a new folder in the versions directory:

```
.minecraft\versions\BPAuto'
```

* ####  Start the minecraft launcher and create a new profile
![Create New Profile](img_01.png)

* ####  Select the newly added version (release BPBot)
![Create New Profile](img_02.png)

* ####  Play the newly create profile
![Create New Profile](img_03.png)


## Instructions

* Once in game, press the `m` key to open the menu.  
* With the menu open, press the `1` key to enable BP Auto mode.  
* Press the `m` key once again to close the menu.

### Controls
* `m` - toggles the main menu
* `1` - toggles BP Auto mode
* `d` - toggles debug logging messages
* `u` - enable high stepping
