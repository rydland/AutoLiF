# AutoLiF  v1.4
### _*Library of automated scripts for LiF*_ 
##### _*Created by [McBenis](https://i.kym-cdn.com/photos/images/original/001/171/120/b2d.jpg) — [STEAM_0:0:7572](https://steamcommunity.com/id/mcbenis/) — [github/rydland](https://github.com/rydland)*_
* Optimised for clients running at 60 FPS in "Windowed Borderless" display mode.
* Optimised for __6__/11 Windows mouse sensitivity and disabled "enhanced pointer precision" (mouse acceleration).
* __10__/200 mouse sensitivity in-game.
  * You may want to modify your mouse DPI if the aforementioned sensitivities are too fast/slow for you. Mouse DPI is usually based on hardware and not within Windows, so changing it will not affect the performance of scripts.
* Optimised for characters with 10 agility, without "Barefoot" debuff. If you've got more than 10 agility on your PvE characters, you should reconsider using macros that require movement.
  * __1*∞__ = 1 tile by infinite tiles walking pattern (straight pattern).
  * __2*∞__ = 2 tiles by infinite tiles walking pattern (zigzag pattern).
* We're using VoiceAttack to avoid being flagged by process sniffers as this is a legit tool mainly used for simulators and users with disabilities.
### Disclaimer
[AutoLiF](https://github.com/rydland/autolif) is stricly for __educational purposes only__ — standard copyrights© still apply for any and all images and .vap files.
Do not use these scripts to alter your gameplay in any way, shape or form. I, the author, do not use any scripts/macros, nor will you ever find me using them. Automating gameplay is stricly forbidden and may result in a game ban. LiF's Rules of Conduct reads as follows: _"You may not use any third-party program (such as a “bot”) in order to automate gameplay functions, including playing, chatting, interacting, or gathering items within LiF. You may not assist, relay, or store currency or items for other players who are using these processes. However the use of simple ‘autoclickers’ is allowed for repetitive single step actions. Using an ‘autoclicker’ to automate anything beyond simple one step processes is considered botting and is forbidden"._
## Instructions
1. [Download AutoLiF](https://github.com/rydland/autolif/archive/master.zip) from my GitHub repository.
2. Run and install VoiceAttackInstaller.exe (autolif-master\VoiceAttackInstaller.exe).
3. Launch VoiceAttack.
4. Select the 'Import Profile' item in the profile list.
5. Select the .vap-file (autolif-master\autolif_v✗.✗-Profile.vap) you've downloaded from my GitHub.
6. Select the profile and click, 'Open'.
* _Scripts are now imported and ready to be used as soon as you've selected the correct VoiceAttack profile._
* _You can execute scripts by pressing hotkeys for the corresponding features._
#### [How to remove fog weather effect in LiF](https://github.com/rydland/autolif/blob/master/remove_fog/README.md)
  * Useful during PvP, especially if you wish to scout or snipe enemies with a crossbow.
#### [How to run multiple instances of LiF (multiboxing)](https://github.com/rydland/autolif/blob/master/multibox/README.md)
  * Useful during PvP to scout home base while you're out raiding or for a rendezvous point to heal your other characters.
#### [How to add reticles & crosshairs to LiF](https://github.com/rydland/autolif/blob/master/reticle_overlay/README.md)
  * Useful if you're doing PvE with a larger display resolution as the current reticle in LiF is too small to be properly seen. However, having a reticle during PvP will prove the opposite as you'll want to turn your attention to your enemy, not your reticle.
## Features & Hotkeys
* __Boost__
  * _[Shift + F12]_
    * Boosts your FPS & Ping in LiF - assigns high/128 priority to "cm_client" & kills "launcher.exe" via PowerShell. We are using high/128 priority instead of realtime/256 priority due to it's high chance of causing pixel skipping and problems with alt-tabbing as the rest of your system will be brought to a halt during high loads. Terminating the LiF launcher is also beneficial because it's forced P2P-connection will bottleneck your bandwidth. This script will do all of this for you once executed after launching LiF.
* __Stop__
  * _[Shift + Esc]_
    * Cancels all running scripts.
* __AutoFarm 1*∞__
  * _[Shift + F1]_
    * Automatically sows seeds or harvests crops on current and the next tiles in a straight walking pattern. Requires "Sow" as your left-click option on soil tiles and "Harvest" as your left-click option on crop tiles.
* __AutoHerb__
  * _[Shift + F2]_
    * Automatically looks for herbs on current tile and gathers them. Requires "Look for Herbs" as your left-click option on grass tile. Make sure you're standing in the centre of a compatible tile.
* __AutoGather__
  * _[Shift + F5]_
    * Automatically looks for materials (branches, flint, stones and plant fiber) on current tile and gathers them. Requires "Look for Materials" as your left-click option on grass tile. Make sure you're standing in the centre of a compatible tile.
* __AutoGather_FiberOnly__
  * _[Shift + F6]_
    * Automatically looks for plant fiber only on current tile and gathers them. Requires "Look for Materials" as your left-click option on grass tile. Make sure you're standing in the centre of a compatible tile.
## WIP a/o 26/03/2019
* AutoGather
  * AutoGather_FiberOnly
* AutoPlant
* AutoFish
* AutoMinorExp
* Sensitivity-, resolution- & FPS presets
* QuickLootGraves
* QuickLootIB
* PvP combos w/ animation cancels & hold last hit until key release
* Backswing-Stamina abuse
* Swordsman special attack abuse
* Freelook w/ camera reset upon key release
## Changelogs
* _25/03/2019_
  1. Project created.
  2. Added AutoFarm_1*∞.
* _26/03/2019_
  1. Added Boost
  2. Added AutoHerb
* _26/03/2019_
  1. Added multibox
  2. Added reticle_overlay
* _27/03/2019_
  1. Added AutoGather

