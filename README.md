# Librum (for Skyrim VR)
Wabbajack modlist installer for Librum

- [Librum](#librum-for-skyrim-vr)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
        - [Set the Game language to English](#set-the-game-language-to-english)
        - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-up-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Post-Installation](#pnost-installation)
      - [Copy "Game Folder Files"](#copy-game-folder-files)
      - [Starting Librum and Choosing Optional Plugins](#starting-librum-and-choosing-optional-plugins)
      - [Start Skyrim... again](#start-up-skyrim-again)
      - [MCM Settings](#configure-the-mcm)
  - [Updating](#updating)
  - [Features of Librum](#features-of-librum)
    - [General Philosophy](#general-philosophy)
    - [Leveling and Skills](#leveling-and-skills)
    - [User Interface and Controls](#user-interface-and-controls)
    - [Dynamic World](#dynamic-world)
    - [Survival and Realism](#survival-and-realism)
    - [Combat and Enemies](#combat-and-enemies)
    - [Magic](#magic)
    - [Quests and Adventures](#quests-and-adventures)
    - [Followers](#followers)
    - [Graphics and Ambience](#graphics-and-ambience)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)
  - [Discussions](#discussions)
 
## Preamble
![Alt text](Resources/Banner3.png?raw=true "I made this image myself, and I am proud of it.")

_You're lost in the woods, having narrowly escaped after scaring off a pack of wolves with a summoned flame atronach. Your torch finally fades out, and it's getting cold. You can conjure basic foods, and your summoned atronach provides enough heat for the time being, but you'll need to gather wood in order to sustain a fire and survive the night. With little time to spare, you can't search far for materials -- luckily, you've fashioned a basic hatchet the night before, and you can chop down a nearby tree for lumber. You fall asleep next to your fire, having placed several runes nearby to dispatch would-be predators. Despite a few interruptions in the night, the morning comes at last, and the sun finally breaks over the horizon._

Skyrim VR is a wonderful experience, but it's a very familiar one. Even in stunning 3D, we visit the same locales and repeat the same adventures we have since the end of 2011.

_Librum_ is a comprehensive gameplay, graphics, and content overhaul that attempts to change all of this. Combining together some of the best and most popular mods for Skyrim SE, a suite of new quests and adventures that outnumber Skyrim's own, the tradition of great "hardcore" gameplay overhauls that have come before -- like Skyrim's _Requiem_ and _YASH_ or Oblivion's _Oscuro's Oblivion Overhaul_ -- and a host of unique-to-VR immersion improvements, Librum brings new life (and new challenge!) to Skyrim in a way that has never been experienced before.

## Installation

Librum makes use of the excellent [Wabbajack](https://www.wabbajack.org/#/) program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:

1. Clean your Skyrim folder and disable the Steam overlay.
2. Install the Wabbajack desktop client from [here](https://github.com/wabbajack-tools/wabbajack/releases).
3. Navigate to Librum under the _Browse for Modlists_ tab.
4. Install Librum to a new folder, outside of `Program Files`.
5. Copy the `Game Data Files` folder to your Skyrim VR directory.
6. Start a new game, and wait until mod installation notes finish appearing.
7. Configure the Mod Configuration Menu according to the [instructions that follow](#mcm).

### Pre-Installation

These steps are only needed if you are installing Librum for the first time. If you only want to update Librum, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

##### Set the Game language to English

Librum is entirely in English, as many excellent mods are English-exclusive. This may change in the future, but for now, I highly recommend playing the game in English.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

##### Clean Skyrim

If your Skyrim VR installation is not newly installed, I recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim VR` folder in `Documents/My Games/` by deleting the contents in it.

#### Start up Skyrim

After you have done everything above and have a clean Skyrim VR installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about the graphics settings at this point, as the Librum installation will replace them. 
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack.
2. Download the modlist from [here](must update link) and choose the  _Install from Drive_ option in Wabbajack.
3. Once the download is complete, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like `C:/Modlists/Librum`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
6. If you run into any issues, see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

***Could not download X.*** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Librum.

***X is not a whitelisted download.*** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

***Wabbajack could not find my game folder.*** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

***Windows is reporting that a virus has been detected.*** Windows 10 has started to auto-quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

### Post-Installation
Now that Librum is installed, it is time to start the game up for real and create your character. The character creation process has changed with Librum, so we will give details below. Moreover, it is highly recommended that you **configure the MCM after race selection** as described below.

#### Copy "Game Folder Files"
Navigate to the installed Librum folder, where you will find a folder titled `Game Folder Files`. Copy the contents of this folder to the Skyrimv root folder.

#### Starting Librum and Choosing Optional Plugins
Navigate back to the installed Librum folder, and launch the program `ModOrganizer2.exe`. Before launching the game itself, take a look at the _Optional_ category at the bottom of the Mod Organizer 2 mod list. I will go over each below.

***End Times*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/39201)]. This plugin adds a sense of urgency to the Main Quest, and it ties in nicely with Librum's re-centering of Skyrim around being the Dragonborn. Specifically, if you do not defeat Alduin within a certain amount of time (365 days by default, but configurable in the MCM), he will swallow the world (accompanied by a nice visual), and you will have to reload and try again. You will have a _Doomsday Clock_ spell available, as well as configurable regular updates, to tell you how much time you have left.

If you do not want this plugin, disable it in MO2.

***Dragons from the Start*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/41453)]. This plugin enables dragon encounters from the very beginning of the game. This is highly recommended for Librum's Dragonborn-centric play, and it is especially important if you use the next optional plugin. 

If you do not want this plugin, disable it in MO2.

***No Perks on Level-Up***. This is a core feature of Librum, so it is highly recommended. With this plugin, you will no longer earn perks when you level up; rather, you will have to spend dragon souls in order to earn perk points. This accomplishes two things. First, along with other mods from the core modlist, this re-centers the Skyrim experience on you _actually being the Dragonborn_. You will not progress without hunting dragons and progressing the main quest. Secondly, this reframes the role of perks in the Librum experience. Because (especially at the beginning) they are much harder to obtain, they will form a much smaller part of your character's identity, and your character will spend a longer time being a "normal person".

If you do not want this plugin, disable it in MO2.

***High Fidelity ENB - LCD vs OLED*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/27308)]. Librum makes use of the excellent _High Fidelity ENB_, which fixes Skyrim's lighting while retaining the high framerates necessary for a good experience. If you have an LCD-based headset (Valve Index, Rift S), enable only the LCD version. If you have an OLED-based headset (Vive, Rift CV1), enable only the OLED version.

Choose the appropriate plugin.

***WICO Non-Nude Meshes*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/2136)]. Librum uses WICO as a base, in order to overhaul character appearances in a natural-looking way. If you do not want nudity in your game, enable this plugin.

If you want this plugin, enable it in MO2.

#### Start up Skyrim... again
To start the game for real, start SKSE through Mod Organizer 2. This will be necessary every time you start the game; if you try to launch Skyrim through its default folder or through Steam, the game will be entirely vanilla.

Start a new game once you get to the main menu. The "yes/no" dialogue in the _New Game_ menu does not always indicate which you are selecting, but the buttons will work as expected. You will start in the character creation area from [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223). Here are some things to know as you create your character:

1. Race and gender differences are changed in accordance with [Race Abilities Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/23223) and [Genders are Boringly Indistinct](https://www.nexusmods.com/skyrimspecialedition/mods/23145), but with the modifications made by [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Namely, Orcs are 50% resistant to earth magic, and Argonians are 50% resistant to water magic.
2. Standing stones are changed in accordance with [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910). However, **the standing stone you choose in the Realm of Lorkhan is final**. That is, you will not be able to change it without first returning to the Realm of Lorkhan.
3. Be particular with the items, spells, and powers you bring back from the Realm of Lorkhan. Much moreso than in vanilla Skyrim, having additional weapons, armors, spell tomes, gold, or even food items can start you out with a significant advantage. If you do not want this advantage, do not take anything with you.

#### Configure the MCM
Once you have created your character, open up the in-game settings and navigate to the _Mod Configuration Menu_ (MCM). You will need to make several changes here to adhere to the suggested Librum setup. Unfortunately, very few of the mods used in Librum support FISS, so you will need to do this each time you create a new character.

The suggested MCM options are as follows:
1. **Bounty Gold.** In the left column, set "Bandits" to 300, "Forsworn" to 350, "Giants" to 400, and "Dragons" to 500. These match the default values of The Notice Board.
2. **Campfire.** Under the _Advanced_ tab, disable "Advanced Object Placement". It conflicts with VR.
3. **Clockwork.** Turn off "Recall Spell Fast-travel Check". This makes the Clockwork Recall spell a very good reward, which fits new difficulty of surviving during Clockwork's questline.
4. **Cobb Encumbrance.** In the _Presets_ tab, apply the preset "Classic (SEM)".
5. **Complete Alchemy and Crafting Overhaul.** Apply the following changes:
  - _Alchemy_ tab: change all potion/poison durations to 10s. 
  - _Harvest_ tab: change _Food containers_ frequency to "scarce", and quantity to "reduced".
6. **Dynamic Things.** Apply the following changes:
  - _Containers/Activators_ tab: deactvivate "Dynamic Safe Containers".
  - _Advanced Options_ tab: activate "Containers are destructible", "Realistic amount of wood per tree", "Realistic chopping time", and "No food containers".
7. **End Times.** Adjust to taste -- I leave this at 365 days.
8. **Frostfall**. Apply the following changes:
  - _Overview_ tab: Activate the mod. 
  - _Gameplay_ tab: "At max exposure" -> "death", and disable fast travel and waiting while outdoors.
  - _Meters_ tab: "Layout preset" -> "bottom left" recommended.
9. **Hunterborn**. Start the mod, and then under the _Enable_ tab, disable the Hunterborn config power.
10. **iNeed.** Apply the following settings:
  - _Basics_ tab: Automate eating and drinking, and set the timescale to 8.
  - _Difficulty_ tab: "Food spoilage" -> "numbers".
  - _Notifications_ tab: "Widget style" -> "disabled".
11. **MageVR.** Spawn MageVR backpack, and "Archery Mode" -> "Realistic".
12. **OBIS - Bandits.** Apply the following settings:
  - _Settings_ tab: Enable extra spawns.
  - _Special_ tab: Enable minotaurs and spiders.
13. **OBIS - Patrols.** Enable under _Settings_.
14. **SkyUI.** Under _General_, disable the Active Effects HUD.
15. **SkyVoice.** Remove the Skyvoice Options Spell.
16. **Sleep to Level Up.** Disable "Require Sleep to spend Perk Points".
17. **Smart Training.** Disable "Training Perk Points" and activate the mod.
18. **Sneak Tools.** Under the _Patch_ tab, disable Horstar's extra dialogue. It is not voiced, unfortunately.
19. **Sounds of Skyrim.** Adjust to taste, but I don't disable anything.
20. **Sands of Time Sleeping Encounters.** In the left column, disable home invasions, set "Jorrvaskr Hall HQ" and "College Ambush Odds" to 0, set "Dungeon Ambush Odds" and "Draugr Keep Ambush Odds" to 50, and set "All Other Places" to 25.
21. **Souls Do Things 2.** Under _Settings_, enable "Conversion Spell Learned" if and only if you disabled perk points on level-up earlier.
22. **Spell Research.** Import all spells.
23. **Tentapalooza.** The tents _should_ provide Frostfall support without changing these settings, but let me know if this fails.
24. **Trade & Barter.** Under _Barter Rates_, enable "Modify Barter Settings" and set "Barter Presets" -> "Hardcore".
25. **WeaponThrowVR.** Under _Presets_, enable either "Cangar's Selection" or "Classic Medium", depending on whether you think the awesome auto-return animation is worth a slight lack of realism.
26. **Wildcat Combat.** Enable "Allow Wildcat to manage difficulty" and "Burst injuries".

Further, there are a few settings to change using mod configuration spells:
1. **Destructible Skyrim.** Simply click "remove spell".
2. **Obsidian Weathers.** Enable seasonal effects, and choose the "Bleak" preset.

Congratulations! You've completed the Librum setup, and you are ready to play. The next several sections will explain what Librum is and does, as well as provide support.

## Updating
If Librum receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Librum will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _Overwrite existing modlist_ button.

## Features of Librum
Librum significantly affects nearly every aspect of gameplay; in this section, I explain all of the significant changes that have been made, and how they change the Skyrim experience. I will separate it here into various "modules" for ease of explanation -- however, this does not reflect any clean-cut separations of Librum mechanics. Changes from the various modules overlap, affect one another, and work together to create a consistent Librum experience. For instance, _Spell Research_ forces mages to interact with the survival elements of Librum, and these survival elements turn a quest like _Clockwork_ into a precarious and time-sensitive escape mission.

With this in mind, here is a rough breakdown of what Librum accomplishes.

### General Philosophy
With every change, Librum attempts to adhere to the points of its _core philosophy_:

1. Librum is a game about _being Dragonborn_. Your dragon soul is a fundamental part of your character's development, and there is no way to indefinitely avoid this destiny.
2. The world is static in ways that make sense, but dynamic in all others. The world is not centered around you, but it reacts realistically to the actions you take and the choices you make. In particular, the ways in which you interact with the world change as you become more powerful.
3. Magic in all forms is a dangerous, arcane, and powerful force. Magic can solve most any problem you have, but -- as an example -- acquiring a single Master-level spell might take a whole playthrough.

### Leveling and Skills
Librum makes several major changes to character progression, described by the following comparison table:

 | Vanilla Skyrim | Librum
 | -------------- | ------
 | Character progression happens primarily as you level, and primarily through the allocation of perk points.	  | Character progression occurs through three unrelated aspects of your character: spell/equipment progression, character level, and collected dragon souls.
 | Available equipment and enemies depend exclusively on your level.	| Librum's loot distribution is based on [Morrowloot Ultimate](https://www.nexusmods.com/skyrimspecialedition/mods/3058), so equipment and enemies (with the exception of dragons -- see below) are entirely unleveled.
 | Higher level equipment can be made and improved at any time, mitigating any effect of leveled weapons and armor	| Smithing now requires more knowledge than just a perk point; for instance, you need to acquire the _[Ancient Knowledge](http://en.uesp.net/wiki/Skyrim:Powers#Ancient_Knowledge)_ effect to make any Dwarven equipment, and Daedric smithing requires uncovering the secret of its construction. Improving equipment is no longer as effective.
 | Available spell tomes depend exclusively on your skill level, but are readily available at spell merchants.	| Spell tomes do not exist, by and large, with the exception of select hand-placed tomes. Rather, all spell progression is done through [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983).
 | Perk points are gained when you level up.	| You do not gain perk points through leveling. Using [Souls Do Things 2](https://www.nexusmods.com/skyrimspecialedition/mods/33518), you will have a power to convert one dragon soul to one perk point. Leveling will continue to grant you 10 Health, Magicka, or Stamina.
 | Dragon souls are exclusively used to unlock dragon shouts.	| Dragon souls have three purposes. They can be used to unlock shouts, they can be used to unlock perk points (as mentioned above), and finally, you will have passive buffs applied depending on the number of unspent souls in your collection.
 | You can level up at any time by opening the Skills menu.	| You must sleep for 8 hours in order to level up, in order to prevent level-ups in dangerous locations.
 | Perks are typically straight buffs to your existing skills, and form the core part of your character's identity.	| Librum uses [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176) to mix up perk benefits and to help balance around having only a small handful of perks; a single perk investment in any tree replaces vanilla's "20/40/60/80/100%" improvement perks or "Novice/Apprentice/Adept/Expert/Master" perks.
 | Standing Stones provide moderate benefits to an existing character build, and can be changed at any time.	| Standing Stones entirely change your character's make-up, thanks to [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910), but they can only be chosen during character creation.
 | Your race typically gives you a once-a-day power, as well as some moderate resistances. Your gender has no effect.	| Through [Race Abilities Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/23223) and [Genders are Boringly Indistinct](https://www.nexusmods.com/skyrimspecialedition/mods/23145/), your race and gender confer significant passive strengths and weaknesses. In particular, certain skills will increase faster than others, and your racial bonuses will improve with your level.

### User Interface and Controls
Librum makes a few changes to the default user interface, to (a) create a unique visual experience and (b) to improve the VR experience. For the first point, Librum uses [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604) along with the excellent [Adventurer Theme Mod](https://www.nexusmods.com/skyrimspecialedition/mods/35568) and [Natural Colored Map Markers](https://www.nexusmods.com/skyrimspecialedition/mods/27503) in order to blend a Skyrim-style modern UI with touches of a more Oblivion-style classic visual theme:

![Alt text](Resources/UI.jpeg?raw=true "Adventurer Theme Mod, Rendered in Skyrim SE")

Librum makes larger changes in terms of controls. For one, it includes [Dual Wield Block VR](https://www.nexusmods.com/skyrimspecialedition/mods/28456), [Weapon Throw VR](https://www.nexusmods.com/skyrimspecialedition/mods/31374), [Sprint Jump VR](https://www.nexusmods.com/skyrimspecialedition/mods/28354), [VR Power Attack Fix](https://www.nexusmods.com/skyrimspecialedition/mods/28004), [Haptic Skyrim VR](https://www.nexusmods.com/skyrimspecialedition/mods/20364), and [Realistic Mining VR](https://www.nexusmods.com/skyrimspecialedition/mods/16692) in order to better match player motions to character actions. With this suite of mods, VR combat is a much more natural experience, and you have all the options -- such as blocking with an off-hand weapon or throwing your weapon -- that you would expect. In particular, as we will further discuss in the next section, you can swing your pickaxe at _any_ in-game rock (including, but not limited to standard ore veins) and swing your woodcutter's axe at (most) any in-game tree or wooden object to get the resources you expect.

In a similar vein, Librum includes [Dragonborn Speaks Naturally](https://www.nexusmods.com/skyrimspecialedition/mods/16514) and [SkyVoice](https://www.nexusmods.com/skyrimspecialedition/mods/17840) to have the world respond naturally to your voice. When you say "hello" or "excuse me" to an NPC, they will begin conversation; when you begin reciting a dialogue option, the game will select it for you; and when you say the words of a learned dragon shout, you will use that shout in game. Not to worry, of course -- thanks to [Shout Pronunciations](https://www.nexusmods.com/skyrimspecialedition/mods/18572), the dragon language words of each shout will be shown in your shout menu.

Last but not least, Librum includes [MageVR](https://www.nexusmods.com/skyrimspecialedition/mods/21297), which generally overhauls the way you interact with spells and equipment. I recommend thoroughly reading its mod page for more information, but in short, it adds the following features:
1. Spells can be slotted to drawn "glyphs". You can re-draw the glyph later to either equip or auto-cast the slotted spell, all without entering your menu.
2. You can store weapons and potions/poisons on your back, all accessible by reaching behind you and "pulling" out the weapon, potion, or poison, again without opening a menu.
3. Archery is realistic. You will need to manually retrieve an arrow from your quiver in order to fire another shot.
4. You can quickslot shouts and powers in a similar way to weapons.
5. You are able to "immersively" loot a container, in which you manually drag loot from the container to your backpack.
6. You are able to "immersively" lockpick, in a way resembling the real procedure for a tumbler lock.

### Dynamic World
Continuing on with the theme of the last section, Librum includes a suite of mods designed to make static objects react to your actions. Along with the mods mentioned before, the key players here are [Dynamic Things](https://www.nexusmods.com/skyrimspecialedition/mods/19520), [Dynamic Things Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/19521?tab=posts), [Destructible Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/28291), and [Sneak Tools](https://www.nexusmods.com/skyrimspecialedition/mods/1863) (which will come up again later).

The combined effects of these mods are as follows:
1. Any haypile or stack of wood you find in the game can be looted, and will decrease in size as you loot them.
2. Almost all "static" containers in Skyrim -- crates, barrels, and others -- can now be looted. They can also be destroyed with a woodcutter's axe, which will drop all of their contents and firewood.
3. Most rocks can be mined with a pickaxe, giving you Hearthfire resources.
4. Most trees can be cut down with any axe, giving you firewood and other resources.
5. You can drink or bottle liquids from mead barrels and similar containers.
6. Using your weapons or Destruction magic on training dummies and archery targets will yield experience.
7. You can harvest mammoth tusks from mammoth skulls you find.
8. Most "standard" objects, like barrels, urns, and small furniture, will be destroyed if you hit them.
9. Light sources around Skyrim can be ignited and put out, either by standard fire/frost effects or by the fire/water arrows included in Sneak Tools.

### Survival and Realism
On the flip side, _you_ have to appropriately react to Skyrim's environment. The core of this, of course, is [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667) and [Frostfall](https://www.nexusmods.com/skyrimspecialedition/mods/671). Along with some more resource-adding mods (notably, [Tentapalooza](https://www.nexusmods.com/skyrimspecialedition/mods/652)), these mods add a complete cold-weather survival system to Skyrim. Your character will be subject to Skyrim's harsh climate, and you will need to bundle up, set up camp frequently, and avoid frigid water and inclement weather in order to survive. Mages will have various options to escape the cold (all compatible with Librum's [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983) mechanics!): summoning cloaks or various tents and shelters, transmuting or summoning materials, summoning a Fire Atronach for heat, or teleporting to safety, among others. Finally, your character's survival skills will improve over time, unlocking various survival-themed perks available at a campfire.

![Alt text](Resources/Campfire.jpg?raw=true "This is a generic picture of a dude at a campfire.")

You will also need to keep track of your hunger, thirst, and fatigue, thanks to [iNeed (Continued)](https://www.nexusmods.com/skyrimspecialedition/mods/19390). Although you will eat and drink automatically (to avoid more menu-searching than is necessary), you will need to maintain a supply of water (or alcohol!) and fresh or salted food in order to survive. Thankfully, these resources can be obtained from many sources. You can get water from snowbanks, wells, rivers, or the ocean -- although it may have to be boiled for hygiene's sake -- and many NPCs are happy to share or sell water, if you ask nicely. 

Getting food is a more involved process, thanks to [Hunterborn](https://www.nexusmods.com/skyrimspecialedition/mods/7900). When you hunt an animal, you now need to properly dress and skin the carcass, using a hunting knife. On the other hand, you will have access to many more resources when you harvest from an animal carcass: more kinds of meats and animal products, pelts from each animal, and animal bones. Your hunting, foraging, bone-carving, and cooking skills will improve with each use, improving your harvests and giving access to new recipes over time.

_Sleep_ is also more complicated than it may seem. Although it is necessary both for general survival and to [level up](https://www.nexusmods.com/skyrimspecialedition/mods/32357), it is fairly dangerous to fall asleep in Skyrim's wilderness or in its dungeons. Thanks to [Sands of Time Sleeping Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/8257), any time you fall asleep, you will have a location-dependent chance of being attacked during the night. This is particularly true in dungeons, making it imperative to either (a) quickly get to safety or (b) bring along a follower or lay traps.

Finally, through the _Dangerous Diseases_ addon to iNeed, diseases have become much more dangerous. Instead of applying a minor debuff to your stats, each disease will now progress through various stages, with many becoming deadly if left untreated. To avoid this all-new danger, you will need to take care to apply _Resist Disease_ effects, properly prepare your foods and water, and try not to get bitten or scratched in fights with wild animals. If you _do_ contract a disease, and it doesn't go away on its own, you will have to rest up, find an alchemical cure (unique to each disease), or pay through the nose for a priest to dispel your illness.

### Combat and Enemies
Librum uses a slew of mods to improve the combat experience overall, with a strong focus on making each fight (within reason) a dangerous and harrowing experience.

For general combat, Librum combines its many [new VR options](#user-interface-and-controls) with [Wildcat](https://www.nexusmods.com/skyrimspecialedition/mods/1368), [Mortal Enemies](#https://www.nexusmods.com/skyrimspecialedition/mods/4881), [Advanced Adversary Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/6843?tab=description), and [Morrowloot Ultimate](https://www.nexusmods.com/skyrimspecialedition/mods/3058). The former two mods add an element of dynamism to combat -- instead of standing and swinging your Touch controllers wildly, you will need to duck, weave, and carefully time both your attacks and your blocks. If you interrupt an opponent's power attack pullback or bow draw, or if you hit them from behind or while staggered, you will gain massive "attack of opportunity" damage bonuses. Similarly, if you properly time your block, you can negate most damage and stagger your opponent (thus allowing for an attack of opportunity). Of course, the same effects apply to your opponents, so you will need to keep your guard up as you fight.

On the flip side, you (and your opponents) will have to be much more careful in order to avoid Wildcat's all-new injuries, which can quickly turn the tide of combat. Any time someone sustains a major attack (30% or more of their total health), they have a chance of injuring your head, chest, arms, legs, or back, and thus facing major body-part-specific penalties to their combat abilities.

The latter two mods, AAE and MLU, step in before you've even started a fight. The latter delevels all enemies, so you'll have to make sure you're properly prepared to be wherever you're going. The former drastically changes enemies' resistances, weaknesses, and abilities, forcing you to plan in advance before a difficult fight. You will now _need_ to pack a silver, Daedric, or magical weapon in order to fight ghosts, for instance, and you'll need to clobber skeletons instead of shooting at them. Furthermore, opponents will use all of the tools at their disposal. From the mod page, "witches will now summon spriggans and use poison spells to their advantage, Thalmor will try to subdue their foes by way of paralysis, while vampires can use hand to hand combat, as well as summon gargoyles, and even morph into a swarm of bats while in combat". Combined with AI tweaks from Wildcat and more minor mods (like [Multiple Floors Sandboxing](https://www.nexusmods.com/skyrimspecialedition/mods/4524)), these improvements will make any fight a life-or-death experience.

![Alt Text](Resources/Trident.png?raw=true "Glass trident, from Heavy Armory")

Combining nicely with these AI and combat tweaks, Librum adds several new classes of weapons through [Heavy Armory](https://www.nexusmods.com/skyrimspecialedition/mods/6308) and other, smaller weapon mods. You can now wield anything from spears and tridents to staves and clubs, and all of the new weapons control smoothly under VR. In particular, a spear will "feel" like a spear, instead of the slightly-more-awkward-sword it was consigned to be in 2D Skyrim. You can also throw any of these weapons, allowing you to finally play the javelineer you've dreamed of.

Special attention has been given to wild animals, combining [SkyTEST - Realistic Animals and Predators](https://www.nexusmods.com/skyrimspecialedition/mods/1104) with [Savage Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37768). Animals will go about normal animal behaviors: hunting prey, running from predators or competing with other predators, raising cubs, and finding mates. Animals will search for food and water, bears will hibernate in the winter, and, importantly, not reporting your crimes. There will also be significantly more variety in different animals, with many animals now sporting different colorations:

![Alt Text](Resources/Wolves.jpeg?raw=true "New wolf colorations from Savage Skyrim")

Savage Skyrim goes one step further, however, combining the several graphical mods from Rougeshot over the years. Many enemies now have more unique, more characteristic, and (often) more terrifying body structures. Dragons and vampire lords have gotten larger wings; Dwemer constructs, spriggans, and spiders have become more imposing; and _many_ other animals and creatures have undergone similar changes.

Of course, dragon combat still forms the foundation of Librum, and dragons are not excluded from our tweaks here. Firstly, there is now a _much_ wider variety of dragon types available, thanks to [Splendor](https://www.nexusmods.com/skyrimspecialedition/mods/9670) and [Diverse Dragons Collection](https://www.nexusmods.com/skyrimspecialedition/mods/695). They have all each been given unique names through [Zim's Dragon Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/38693), and they all [talk to you](https://www.nexusmods.com/skyrimspecialedition/mods/26955) during your fights. Along with changes to make dragon combat more difficult and dynamic, this combination turns each dragon fight into a unique boss fight, rather than another generic Skyrim opponent.

![Alt Text](Resources/Dragon.jpeg?raw=true "Named dragon from Zim's Dragon Improvements")

Finally, Librum turns Skyrim's half-baked sneaking mechanic into a stealth experience worthy of the _Thief_ franchise. With the many thoroughly researched changes from [Realistic AI Detection](https://www.nexusmods.com/skyrimspecialedition/mods/2345), you will now need to use darkness and silence to your advantage. Many dungeons have undergone [significant lighting improvements](https://www.nexusmods.com/skyrimspecialedition/mods/8586), which you need to make use of as you sneak around enemies' now-more-realistic detection skills. Speaking of the _Thief_ franchise, Librum adds many new tools of the trade to aspiring rogues, courtesy of [Sneak Tools](https://www.nexusmods.com/skyrimspecialedition/mods/1863). You can now knock unsuspecting opponents out with your bare hands or a blackjack, ignite and extinguish light sources with fire/frost magic or fire/water arrows, and better navigate your environment with rope arrows. You can also set things ablaze after hitting them with oil arrows, fool opponents with noisemaker arrows, and conceal your identity with various masks and hoods (a la Grey Cowl of Nocturnal). 

### Magic
If anything, Librum makes _more_ significant changes to the mage experience than the warrior or thief experiences mentioned in the last section. First and foremost, the process for obtaining new spells adheres to the [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983) format. In short, ***spell tomes no longer exist***, by and large, with the exception of certain hand-placed tomes. This means that you will need to _research_ to discover each new spell, in one of three general fashions:
1. _Researching existing spells_. Using your research journal, you can spend time studying any spell already in your possession, in order to increase your knowledge of the spell's various archetypes. For instance, studying _Lesser Ward_ would improve your knowledge of Restoration magic, of shielding spells, of "magical force" inducing spells, of self-targeting spells, and of concentration spells. This is slow, but a very straightforward method of progression for existing mages.
2. _Distilling and studying alchemical ingredients_. Using an alembic or a cauldron, you can distill alchemy ingredients into concentrated serums, which you can then (a) use for interesting crafting recipes or (b) study to improve your knowledge of their effects. This is relatively fast, but expensive and terribly confusing.
3. _Beating the shit out of valuable artifacts_. Along your adventures, you will come across all manner of new magical artifacts, ranging from the relatively commonplace enchanted weapon fragments to the dangerous and rare _Grimoires_. By studying magical items, translating old tomes, or destroying all of these artifacts, you can learn a huge amount about various spell archetypes, or even gain new spells automatically. However, these methods can be finnicky and dangerous, and they may harm you more than they help.

Once you've learned enough about the spell archetypes you're interested in, you can attempt to write "magical theses" and apply them towards gaining a new spell. If you are skillful, lucky, and not mentally drained, you may discover a new spell that fits the archetypes of the theses you wrote.

Now, there are several important gameplay consequences of this system. Existing mages will have an easier time learning new spells than new apprentices -- if you don't have any spells to start with (which may well be the case, thanks to [RAE](https://www.nexusmods.com/skyrimspecialedition/mods/23223)), you must study alchemical ingredients or artifacts in order to improve. Furthermore, as spell tomes are largely unavailable, you will have to make do with lower level magic than is otherwise the case; learning your first _Adept_ or _Expert_ spell, for instance, is a very difficult process.

On the other hand, Librum adds many new spells and classes of magic, organized loosely around the [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839) framework. Mysticism itself rebalances all of the vanilla spells, and it adds a wide swath of new spells corresponding to those of "legacy" Elder Scrolls games. The list below gives some examples, but is _noncomprehensive_:

 - ***Open X Lock.*** Instantly open any lock of the corresponding level.
 - ***Mark and Recall.*** Set a location with _Mark_, and instantly teleport there with _Recall_.
 - ***Absorb Health.*** Drain a target's health pool, and restore your own the same amount.
 - ***Weakness to X.*** Inflict a target with weakness to a given spell type.
 - ***Reflect Damage.*** For X seconds, a percentage of received melee damage is reflected back at your attacker.
 - ***Command.*** For X seconds, targets up to a given level are placed under your control.
 - ***Slow Time.*** For X seconds, the caster's perception of time is slowed by a given percentage.

Mysticism makes these effects -- and many more -- available in a number of different formats. This pairs particularly nicely with Spell Research, because each spell type is available in a variety of archetypes, and so the spells you discover are truly unique to your character. For instance, each elemental effect is now available in cloak, bolt, "stream", on-touch, wall, and rune formats, each at several different magic levels. This means that, where vanilla only had the novice "Flames" spell in the stream format, Mysticism gives the novice "Flames", the adept "Greater Flames", and the (very well-animated) master "Flames of Oblivion" spells.

In addition, unique spells from previous games make a comeback. These range from Destruction spells like "Finger of the Mountain" and the fan-favorite "Enemies Explode" to unique Conjuration spells, allowing you to summon any type of weapon as well as various types of Dremora, Skeletons, and other creatures.

![Alt Text](Resources/Shield.jpeg?raw=true "Shield of Awe, from Triumvirate's Cleric school")

This is just the core of Librum's magic offerings, however. Through the addition of several curated spell packs, Librum opens up many more-specific branches of magic:

 - ***Earth, Wind, and ~Fire~ Water Magic.*** Cast the same Mysticism-style destruction spells for the elements of earth, wind, water, and poison, thanks to [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Certain enemies will resist or be weak to these elements, and Vokrii perks have been changed to reflect these new additions. You can also summon earth, wind, and water atronachs, in the same style as the vanilla elements, and you can apply enchantments that make use of these new elements.
 - ***Shadow Magic.*** Teleport through shadows, cloak areas in darkness or reveal important items in existing darkness, and draw power from the shadows around you, with [Triumvirate's](https://www.nexusmods.com/skyrimspecialedition/mods/39170) expansive Shadow magic options. You can also deal all-new "shadow damage", petrify opponents, and apply shadow-based curses, combining Triumvirate's more aggressive options with [Shadow Spell Package](https://www.nexusmods.com/skyrimspecialedition/mods/13299).
 - ***Blood Magic.*** Use your health in place of your Magicka to cast spells, with [Ace Blood Magic](https://www.nexusmods.com/skyrimspecialedition/mods/16995). You can also manipulate blood in the environment, with bleeding effects, blood-mists that can infect opponents, and defensive orbs or pools of blood. Vampires have their own sort of blood magic, through [Sacrosanct's](https://www.nexusmods.com/skyrimspecialedition/mods/3928) "Hemomancy" mechanic. The more you feed, the more hemomancy spells you unlock.
 - ***Nature Magic.*** Follow the path of the druid, using nature-themed spell schools from Triumvirate and [Forgotten Magic Redone](https://www.nexusmods.com/skyrimspecialedition/mods/12711). Draw power or healing from the environment, infect your target with damaging spores or poisons, or grow various damaging brambles, vines, or mushrooms around your opponent. You can also call unique animals to aid you in combat, or take the form of these animals to gain unique abilities.
 - ***Expanded Fire/Frost/Shock Magic.*** Use Forgotten Magic Redone's heavily expanded elemental options to add new combat mechanics to your Destruction mage. Teleport around the battlefield through shock gates, surround yourself with a glacial fortress or freeze would-be attackers solid, or drop meteors on distant opponents. 
 - ***Holy Magic.*** Call upon the Divines to aid you in your quest, using spells from [Dawnguard Arsenal](https://www.nexusmods.com/skyrimspecialedition/mods/25094) as well as Triumvirate and Forgotten Magic Redone. Sun spells have been expanded to match the other elements, but you can also bless your weapons in combat, protect and buff nearby allies, or summon divine weapons or guardians to fight on your behalf.
 - ***Shaman Magic.*** Triumvirate offers something for the follower of the ancient Nordic pantheon, as well. Summon Nordic totems to heal you or damage your opponents, consecrate your surroundings to gain an easily-accessible sanctuary, or look upon the land from the eye of a bird. 
 - ***Celestial Magic.*** Applying the two spell schools from _Cosmic Spells_, you can unlock the powers of the Magna-Ge. Teleport targets through wormholes or draw them with gravitational force toward a summoned body, place "Umbral Orbs" or "Luminous Crescents" around the battlefield to extend your cosmic powers, or deal _lunar_ or _void_ damage to your opponents. 
 - ***Daedric Magic.*** Through Triumvirate, Forgotten Magic Redone, and [Zim's Dremora Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/12128), unlock the magic of the Daedra. Cast the same (now heavily-expanded) fire-based protection and Destruction spells as Dremora, summon all manner of new Daedra, or banish targets to Oblivion. You can also apply a whole selection of new curses, or bind enemy spirits into your summons for stronger effects. 

In addition to the above list, Librum includes a ton of new "miscellaneous" spells -- for instance, from [Tentapalooza](https://www.nexusmods.com/skyrimspecialedition/mods/652), [Caranthir Tower Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/4269) or [Immersive College of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/17004), or from any of Librum's many quest mods -- that do not fit neatly into these categories. It also includes mods like [Thunderchild](https://www.nexusmods.com/skyrimspecialedition/mods/1460), [Summermyst](https://www.nexusmods.com/skyrimspecialedition/mods/6285), and [Complete Alchemy and Crafting Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/19924), which, along with some of the mods from Librum's other "modules", allow for mage-tangent playstyles utilizing enchantments, alchemy, or shouts primarily.

Note that almost all of the above spells must be discovered on your own, through Spell Research. Because of this, you will naturally tend toward a specific magical niche (which may not align at all with the spell "classes" listed above), dependent on your experience in the different magic archetypes. In this fashion, Librum turns Skyrim's vanilla "eat a book" magic system into a truly immersive research experience; you will be able to discover nearly any sort of magic you can imagine, but you need to dedicate yourself to studying the secrets of magic.

Finally, Librum adds a new element of challenge in the form of [FIZZLE](https://www.nexusmods.com/skyrimspecialedition/mods/18180). If your magic skill isn't high enough to comfortably cast a certain spell, there is a chance that it will fail on the spot (but still drain your Magicka!). This is affected by other environmental factors, forcing mages to adapt appropriately to Skyrim's harsh climate; for instance, if you are suffering from frostbite, your magic skills will be significantly reduced, and most of your spells will fail.

## Bugs
Cure disease spell. Yes/no in menus. 

Campfire placement not working.
