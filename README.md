# About

Base structure for my games, using **Heaps** framework (https://heaps.io) and **Haxe** language (https://haxe.org).
# Prereq for good dev experience
Install the latest if the following
```
haxe
hashlink
```

# Installation
- Install all dependencies
```
 haxelib install all | yes 
```
- Modify your debug file
```
# linux
hl.hlsdl.hxml

# windows
# -lib hldx
-debug
```
- Build your game on hashlink
```
haxe hl.debug.hxml
```
- Start the executable
```
hl bin/client.hl
```

# Usage

Please check this documentation for every details: https://deepnight.net/tutorial/using-my-gamebase-to-create-a-heaps-game/

For localization, you can check the following guide: https://deepnight.net/tutorial/part-4-localize-texts-using-po-files/

If you need some extra "advanced features", you can also give a try to the **advancedBase** branch: https://github.com/deepnight/gameBase/tree/advancedBase

 * Status effects on Entity.hx (like Stun or whatever you could think of)
 * Stackable slow-motions management for Game.hx
 * Level marks (can be useful for AI coding, for example by marking platform ends)
 * A few very basic extra UI components that should be useful for any game projects (like a Bar).
 * etc.
