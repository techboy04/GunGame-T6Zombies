# Gun Game - Plutonium T6 Zombies - 1.0
I decided to recreate a Gun Game mode in Zombies.

Get a certain amount of kills (by default, 8) to upgrade to the next weapon. If you die, you get demoted. There is no end until someone finished the ladder. This game can be played solo or with other players, I tried my best to make it work with 8 players but I haven't been able to test it myself.

Wallbuys and Mysteryboxes are unavailable.

By Default, there is no perk limit

The mode also has custom powerups: (thanks to Ox_ for this part of the code)
- Skull Powerup: Goes to the next tier
- Please Wait Flag: Pack A Punches current weapon
- Bottomless Clip: You get unlimited ammo (by [Ox_](https://forum.plutonium.pw/topic/70/release-gsc-zombies-custom-powerup-unlimited-ammo?_=1719448667279))

# Using the Mod version (Recommended)
## zm_gungame.zip

## Installation
Download zm_gungame zip and put it in your Plutonium T6 mods folder

```%localappdata%\Plutonium\storage\t6\mods\```

# Using the Scripts version
## gungame.gsc, mob_gungame_fix.gsc, and gungame_tomb.gsc

## Installation
Download gungame.gsc and put it in your Plutonium T6 scripts folder

```%localappdata%\Plutonium\storage\t6\scripts\zm\```

Put mob_gungame_fix.gsc in the zm_prison folder located in the scripts folder.

```%localappdata%\Plutonium\storage\t6\scripts\zm\zm_prison```

Put the gungame_tomb.gsc in the zm_romb folder located in the scripts folder.

```%localappdata%\Plutonium\storage\t6\scripts\zm\zm_tomb```

(if the folder isnt there create them)

You will have to open console and type in ```set enable_gungame 1``` to enable this! This is so you can still have the script in your folder while also able to disable it if you want to use other mods!
If youre using the mod version, you dont need to use the console! Its included in **Custom Games** menu!

## Configuration
This script lets you modify some features! On the mod version, these can be changed on the **Custom Games** menu instead!
- enable_gungame - Toggle the mode, best used if you want to keep the mode in your scripts folder when using any other mods.
- gungame_ladder - Sets the gun ladder. The ladder options are as follows.
  - 0 is Regular Guns
  - 1 is Regular and Upgraded
  - 2 is Randomized Regular
  - 3 is Regular and Upgraded but randomized

## Got a Bug or a Suggestion?
As this mode is still being worked on, I accept suggestions and bugs. [Join the Discord server](https://discord.gg/dkwyDzW), Grab the Call of Duty role, and report it to [#technoops-forums](https://discord.com/channels/399600672586203137/1032884888468213811)
