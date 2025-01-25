# Lexon Air Documentation
Lexon Air is a memory game knockoff similar to the Simon game. This device programmed using Unity animation controllers follows the Simon Air rules to provide a similar experience in VRChat. \
This memory game can be purchased here: https://ilexisthemadcat.booth.pm/items/6524622

Community Server: https://discord.gg/ilexissloft \
Please stop by if you have any questions about setup or want to suggest something. Select Lexi's Assets in onboarding and scroll down the channels for #💬lexon-air!

Lexon Air version updates will be announced in the Discord server. Known bugs or planned features will be represented as open issues in this repository.

Contents:
 - [Installation](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#installation)
 - [Usage](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#usage)
   - [Displays](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#displays)
 - [Menus](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#menus)
   - [Root Menu](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#root-menu)
   - [Main Menu](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#main-menu)
   - [Settings](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#settings)

# Installation
For an easy install, start by installing [Modular Avatar](https://modular-avatar.nadena.dev/docs/intro). You can follow the instructions on that page to install Modular Avatar via the VRChat Creator Companion app. \
The setup is simple! There are two easy ways. \
Drag the prefab into your avatar, position the Lexon Air Target object in front of your hand, then:
- add your hand bone as a source to the target's constraint, then press Activate.
- move the Lexon Air Target object into your avatar's armature under the respective hand bone.

Minimum parameter usage: 33 \
Maximum parameter usage: 49 \
Go into the Lexon Air's MA Parameters component to change the behavior of the [Displays](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#displays) on remote machines. \
This does not affect the functionality of the game unit.
- 33 - Unsync `LA/Points` to unsync the point display across the network.
- 41 - default (points work but not levels)
- 49 - Sync `LA/Levels` to sync the level display across the network.
  
# Usage
Here are the manuals for the official Simon Air game. Obtained from [ManualsLib](https://www.manualslib.com/manual/1846450/Hasbro-Gaming-Simon-Air.html).
- Two-player is not included in this package.
- Lighting conditions are not a real threat to this virtual version.

![image](https://github.com/user-attachments/assets/74804969-bd74-4011-b542-11457c088d12)
![image](https://github.com/user-attachments/assets/d0421e76-72c1-4c70-8a2c-64f6f4dab790)
## Displays
The unit displays two numbers on the front. \
![image](https://github.com/user-attachments/assets/7ff52962-7b6c-4214-a57c-30def6703e60)

## Menus
### Root menu
![image](https://github.com/user-attachments/assets/767e3b4a-1d5a-466a-abc6-a08c3e1ce932) \
\* This is the main menu for the Lexon Air. It is installed to the root menu by default.
### Main menu
![image](https://github.com/user-attachments/assets/64f32a39-f51f-460b-b68a-b4aa87861d7d) \
Buttons 2-4 are contacts on the physical unit, these buttons emulate their actions.
1) Drops the unit in the world.
2) Flips the switch leftward.
3) Turn the unit on.
   - (If on, press: Cycle volume levels)
   - (If on, hold: Reveal highest score for the selected mode)
4) Flips the switch rightward.
5) Settings
### Settings
![image](https://github.com/user-attachments/assets/841f7a3d-0f69-4bea-ab0c-0018b4ecbc7f)
1) Reveal the unit. It is attached to your hand until dropped.
2) Turns on the unit and disables automatic shut-off.
3) Allow others to interact with the contacts on the unit.
4) Control the volume of all sounds except for the button ASMR.

# End
[Return to top](https://github.com/IlexisTheMadcat/Lexon-Air/tree/main?tab=readme-ov-file#lexon-air-documentation)
