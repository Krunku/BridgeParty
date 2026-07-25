#THIS SKRIPT IS STILL IN THE WORKS, THIS IS A VERY EARLY VERSION.

There are currently 8 errors when doing /sk reload bridgeparty:
these errors are for a system I was working on and stopped mid way, and do not conflict with the actualy bridge party in any way.



# Bridge Party Skript (1.8)

A fully playable **Bridge Party** minigame made entirely in **Skript** for Minecraft **1.8.x**.

This project includes:
- 🏆 Complete Bridge Party minigame
- 📊 Placeholder addon for scoreboards and placeholders
- ⚡ Fast and lightweight
- 🔧 Easy configuration

---

## Requirements

### Server Version
- Minecraft **1.8.x** (PaperSpigot/Spigot recommended)

### Dependencies
- Skript **2.5**
- skRayFall
- SkLeaf or Sk Mirror
- Bedclutch by hi12167pies: https://www.spigotmc.org/resources/bedclutch.102543/


---

## Installation

1. Install all required dependencies.
2. Copy `bridgeparty.sk` into:
   plugins/Skript/scripts/
3. Copy `bridgepartyplaceholder.sk` into:
   plugins/Skript/scripts/
4. Reload Skript:
   /sk reload bridgeparty
   /sk reload bridgepartyplaceholder

#SETUP AND COMMANDS
RED FINISH MUST BE ON THE BLUE SIDE
BLUE FINISH MUST BE ON THE RED SIDE
SET THE SPAWN IN MULTIPLE AREAS TO CREATE MORE THAN ONE SPAWN OPTION
CLEAR THE SPAWNS FOR A SIDE IF YOU WANT TO CHANGE THE SPAWN
FOR CLUTCH MODE USE THE BED CLUTCH PLUGIN FROM HI PIES, AND SET 1 Map TO 1 SIDE AND THE 2nd ONE TO THE OTHER SIDE:

COMMANDS:

/bedclutch <join/leave> <map>
/bedclutchmaps <setspawn/delete> <map>
| `/setredspawn` | Set the Red team's spawn location. |
| `/setbluespawn` | Set the Blue team's spawn location. |
| `/setredfinish1` | Set the first Red finish region corner. |
| `/setredfinish2` | Set the second Red finish region corner. |
| `/setbluefinish1` | Set the first Blue finish region corner. |
| `/setbluefinish2` | Set the second Blue finish region corner. |
| `/switchteams` | Swap the teams of players in the current match. |
| `/clearredspawns` | Clear all saved Red spawn locations. |
| `/clearbluespawns` | Clear all saved Blue spawn locations. |


---

## Changing the Game World

The arena world is defined inside the Skript.

Simply open `bridgeparty.sk` and change the world name near the top of the file to your own world.

Example:

```vb
options:
    world: bridgeparty
```

Change it to:

options:
    world: YourWorldName

No other setup is required.


## Placeholder Addon

The included placeholder script provides placeholders that can be used with scoreboards, TAB, and other placeholder-supported plugins.

Make sure `bridgepartyplaceholder.sk` is loaded alongside the main game script.

---

## Features

- Score tracking
- Titles
- Sounds
- Custom placeholders
- Timer
- Clutch and bridging mode
- Customizable placeholders




---

## Folder Structure

```
plugins/
└── Skript/
    └── scripts/
        ├── bridgeparty.sk
        └── bridgepartyplaceholder.sk
```

---

## Compatibility

| Component | Version |
|-----------|---------|
| Minecraft | 1.8.x |
| Skript | 2.5 |
| skRayFall | Latest compatible |
| SkLeaf | Latest compatible |

---

## Support

If you find a bug or have a feature request, feel free to open an issue on GitHub.

Pull requests are also welcome.

---

## License

This project is released under the MIT License.
