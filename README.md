Lexon Air v1.0.3
# Lexon Air Documentation
Lexon Air is a memory game knockoff similar to the Simon game. This device programmed using Unity animation controllers follows the Simon Air rules to provide a similar experience in VRChat. It uses 49 bits of synced memory. \
This memory game can be purchased here: https://ilexisthemadcat.booth.pm/items/6524622 \
Demo video: [[VRChat] Lexon Air Demo](https://youtu.be/SiyZ2OaVfkg)

Community Server: https://discord.gg/ilexissloft \
Please stop by if you have any questions about setup or want to suggest something. Select Lexi's Assets in onboarding and scroll down the channels for #storefront!

Lexon Air version updates will be announced in the Discord server. Known bugs or planned features will be represented as open issues in this repository.

Contents:
 - [Installation](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#installation)
 - [Usage](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#usage)
   - [How To Play](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#how-to-play)
   - [VRChat-specific](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#vrchat-specific)
   - [Displays](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#displays)
 - [Menus](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#menus)
   - [Main Menu](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#main-menu)
   - [Play CLASSIC](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#play-classic)
   - [Settings](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#settings)

# Installation
For an easy install, start by installing [Modular Avatar](https://modular-avatar.nadena.dev/docs/intro) OR [VRCFury](https://vrcfury.com/download/). You can follow the instructions on that page to install the library via the VRChat Creator Companion app. \
The setup is simple! Drag the prefab into your avatar, then reference the image below for moving it around where it is comfortable. \
<img width="600" height="221" alt="image" src="https://github.com/user-attachments/assets/7836b5a3-563c-425c-bd02-7d1621172586" />

Note: Due do the size of the ROM in the Animator Controller, VRCFury can take over 15 minutes in pre-processing for the avatar to build or enter play mode. \
If your avatar uses any VRCFury components elsewhere, this will apply even if you use the Modular Avatar prefab. Just remove it temporarily if you're testing something else. Sorry!
  
# Usage
### How To Play
To learn how to play, watch this official video: https://youtu.be/WPKeFiXG9ww \
Here are the manuals for the official Simon Air game. Obtained from [ManualsLib](https://www.manualslib.com/manual/1846450/Hasbro-Gaming-Simon-Air.html). \
<img width="391" height="257" alt="image" src="https://github.com/user-attachments/assets/26ca2561-461b-4678-941d-2a5a737be72b" />
<img width="391" height="257" alt="image" src="https://github.com/user-attachments/assets/a83f951b-8ece-4398-80c0-e69781e7d812" />
### VRChat-specific
- Two-player is not included in this package.
- Lighting conditions do not matter in VRChat.
- For convenience, if you are on desktop mode, the unit will automatically be in front of your face and pre-selected to Classic. You can play it this way, or drop it and let friends play it!
- Please keep in mind that this unit is designed to be nearly 1:1 with the original, physical unit, including sound and functionality. The VRC menu buttons are just an accessible way to interact with it.
  - In the original Simon Air game, you do NOT touch the colors! They are not buttons, but photo-sensors! The same applies for VR too. Just hover your hand over the colors and don't clip through!
### Displays
The unit displays two numbers on the front, and who's turn it is. \
<img width="1046" height="406" alt="image" src="https://github.com/user-attachments/assets/c3d7872f-2aac-4cad-affd-66bc269d51e1" /> \
The `. . .` will say "Lexi's turn" when it shows you a new sequence, and "Your turn" when you will repeat it. \
The top, smaller number, shows you which level you are on. This is only applicable to Solo mode; it will always be `1` on Classic mode. \
The bottom, smaller number, shows you not what stage you're on, but how many points you have accured without missing or timing out. \
- In Solo mode, stages are grouped by levels. If you fail a stage in a higher level and you use "The Continue Feature", your points will still start at 0. \
- "The Continue Feature" will have expired if you see the level counter go back down to 1 and the blinking slows down to normal. 
## Menus
<img width="86" height="75" alt="image" src="https://github.com/user-attachments/assets/3b2004d1-f7a5-40f6-97ce-d6cba6e53844" /> \
\* This is the main menu for the Lexon Air. It is installed to the root menu by default.
### Main menu
<img width="376" height="369" alt="image" src="https://github.com/user-attachments/assets/7866229f-6c0a-413e-8450-9ddc5840bedd" /> \
1) Spawn the device
2) [Play CLASSIC](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#play-classic)
4) Contact; Flips the switch leftward, setting it to Solo mode.
5) Contact; Turn the unit on. If on, cycle volume levels; if on+held, reveal the high score for the selected mode.
6) Contact; Flips the switch rightward. setting it to Classic mode.
7) [Settings](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#settings)
5) Drops the unit in the world.
### Play CLASSIC
<img width="376" height="369" alt="image" src="https://github.com/user-attachments/assets/d5dea50c-b3ce-401a-892a-f2a2dd1295a2" /> \
These all correspond to the contacts that VR players interact with to play the game.
- The top two green buttons do the same thing for symmetry.
- Because you can only press one button at a time, you can only progress through Classic mode with the menu.
### Settings
<img width="376" height="369" alt="image" src="https://github.com/user-attachments/assets/08f6cb39-dbc3-4d5b-8b9c-7c732ed05f6c" /> \
1) Turns on the unit and disables automatic shut-off.
2) Allow others to interact with the contacts on the unit. Defaults enabled.
3) Control the volume of all sounds except for the button ASMR.

# End
[Return to top](https://github.com/IlexisTheMadcat/Lexon-Air/blob/main/README.md#lexon-air-documentation)
