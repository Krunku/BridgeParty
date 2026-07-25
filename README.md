#THIS SKRIPT IS STILL IN THE WORKS, THIS IS A VERY EARLY VERSION.

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
- SkLeaf

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
   or simply restart the server.

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
