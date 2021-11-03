Adds exoskeleton power sources to the game.

Exoskeletons have long been OP in Anomaly. After getting an exoskeleton with a sprint upgrade, the game becomes boring. You run around immune to bullets carrying a Walmart's worth of junk. This addon aims to balance exoskeletons by limiting their power and adding a cost to continually fielding exoskeletons.

IMPORTANT:
Before installing this addon, make sure you are not currently wearing an exo. You will be bricked wherever you are. Alternatively, you can go into debug and spawn yourself a PSU and some batteries after installing.

Exoskeleton batteries:
- Exoskeletons no longer have infinite power. Exoskeletons must be charged with military battery units.
- Exoskeletons have a default power capacity of 100. While jogging, power is slowly drained. While sprinting, power is drained faster. Crouching or walking doesn't consume power at all. These values are completely adjustable.
- If you run out of power, the servos will shut down and you will be extremely slow. You'll still be able to carry your heavy load, so you won't be completely dead in the water.
- Purchase batteries starting at rep level 3 or loot them on dead exoskeleton wearing stalkers. 

Exoskeleton power supplies:
- Power supplies can be installed on exoskeletons. These increase power capacity and efficiency at a cost to carryweight.
- Power supplies can be looted, crafted, and purchased.
- The rarest power supplies have unique powers that can be activated with double-tapping the sprint key.

Installation:
Drag and drop gamedata folder.
Uninstallation:
Open up your game and get rid of any miitary battery units and exoskeleton PSUs. Remove the game files affected.

Credits
- Desman Metzger for providing exoskeleton sounds
- Crepis for new icons
- HarukaSai for contributing electrical nova power

Changelog:
V2.0
- Completely reworked how exo batteries and power sources work. Read the readme!
- Batteries, power supplies are no longer associated with the backpack. They are implicit in the item itself.
- Power check doesn't work yet. Disabled for now.
V1.3.8
- Tweaked exo power drain
- Fixed bug where having exo device with no battery would be automatically reset to full on game load
- Reworked trader logic. Supplies are much more limited now.
- Fixed exo batteries and PSUs being repairable.
- Made the military power supply rarer.
- MCM support
V1.3.7.2
- Reduced power drain of exos (it was too ridiculous). Some under the covers tweaks.
V1.3.7.1
- Monkey patched out dependency on death_manager and used new speed script version that clamps speed minimum to walking speed.
V1.3.7
- New world models and icons for PSUs, courtesy of TDLemon.
V1.3.6.1
- Re-enabled prototype exo power supply, which was disabled for some reason.
V1.3.6
- Fixed trader crash and added rus localization from MoreLove1
V1.3.5
- Major under the covers refactor to be more modular. No more conflicts with native devices (so now compatible with things like Beef NVGs). Tweaked exo PSU drops and drain rate. Power check is now separate addon and localized (to english)
V1.3.4.1
- Small fixes for infinite batteries in power supplies, fixed error message 
V1.3.4
- Added world models from TDLemon for military and prototype PSUs
- More batteries from traders.
- Added patch for separated helmets/backpacks.
V1.3.3
- Adapted to 1.5.1. Major refactor to use my new speed utility, and removed dependency to traders. Now traders will automagically get power supplies and batteries when they have exoskeletons in their stock.
V1.3.2
- Moved some code around to be a little more fluid, and added a function to be used by movement speed addon.
V1.3.1
- Refactored outfit speed check to be less complicated.
V1.3
- Redid slow mechanic. Now running out of power will massively slow the player down instead of depleting their stamina.
V1.2.2
- New icons from TDLemon. Turns out the old icons were SEVA textures.
V1.2.1
- Fixed bug preventing recipes from being readable.
V1.2
- Added bindable key to check exoskeleton power. Currently English text only.
V1.1.3
- Added patches for Trader overhaul (and ported TO to U5 in the process). Two flavors, standard and more rep which increases the rep gates to multiples of 500. 
V1.1.2
- Reduced walking_stamina to 0.15 (now your stamina is capped at 15% without power)
- Fixed LUA issue with backpack, now backpacks are checked for correctly. Some of the errors will still come up but this should stop any crashes I hope.
V1.1.1
- Fixed russian translation
- Fixed broken spawns
- Fixed broken trade files. Evened out sellers of military exo power supplies.
V1.1
- Compatible with update 5.
- Added two more power supply variants.
- Allowed new exo power supplies to drop from enemies.
- Removed critical condition multiplier, to be reimplemented later. Moved exo-related sections to their own files. 
- Custom icons!
- Disassembly and crafting recipes for some PSU models.
- RUS Translation
- Removed Trader Overhaul and Separate Helmets compatibility for now, waiting for official updates to those addons.

V1.0.1
- Compatibility with Fang's Exo from TOC

Credits:
Arszi - general advice
wuut - used his addons as a reference
OnegRiot - kek
K.Cin - playtesting
TDLemon - RUS translation and new icons
Grok - New icons
