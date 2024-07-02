# Gun Game - Plutonium T6 Zombies - Beta 0.6
I decided to recreate a Gun Game mode in Zombies.

I did make this mode a little rough on the edges but it should work pretty well.

NOTE: Mob of the Dead currently does not work! All youre gonna get is an infinite loop which doesnt load the map!

Get a certain amount of kills (by default, 8) to upgrade to the next weapon. If you die, you get demoted. There is no end until someone finished the ladder. This game can be played solo or with other players, I tried my best to make it work with 8 players but I haven't been able to test it myself.

Wallbuys and Mysteryboxes are unavailable.

By Default, there is no perk limit

The mode also has custom powerups: (thanks to Ox_ for this part of the code)
- Skull Powerup: Goes to the next tier
- Please Wait Flag: Pack A Punches current weapon
- Bottomless Clip: You get unlimited ammo (by [Ox_](https://forum.plutonium.pw/topic/70/release-gsc-zombies-custom-powerup-unlimited-ammo?_=1719448667279))

## Installation
Download gungame.gsc and put it in your Plutonium T6 scripts folder

```%localappdata%\Plutonium\storage\t6\scripts\zm\```

(if the folder isnt there create them)

You will have to open console and type in ```enable_gungame 1``` to enable this! This is so you can still have the script in your folder while also able to disable it if you want to use other mods! **YOU MAY HAVE TO START A MATCH BEFORE TO LOAD UP THE DVAR THEN RESTART THE MATCH AFTER YOU SET IT (This isnt needed if you specify it in a config folder for a dedicated server)**

## Configuration
This script lets you modify some features!
- enable_gungame - Toggle the mode, best used if you want to keep the mode in your scripts folder when using any other mods.
- gungame_ladder - Sets the gun ladder, currently there is only 0 (Regular guns) and 1 (Regular + Upgraded). There is more to come!
Other options will be added as the mode gets updated. Stay tuned!

## Got a Bug or a Suggestion?
As this mode is still being worked on, I accept suggestions and bugs. [Join the Discord server](https://discord.gg/dkwyDzW), Grab the Call of Duty role, and report it to [#technoops-forums](https://discord.com/channels/399600672586203137/1032884888468213811)
