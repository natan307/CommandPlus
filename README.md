# CommandPlus
![Banner](https://raw.githubusercontent.com/natan307/CommandPlus/refs/heads/main/banner.png) 
![Minecraft](https://img.shields.io/badge/Minecraft-1.21%20--%2026.3-brightgreen)
![Java](https://img.shields.io/badge/Java-21%2B-orange)
![Platform](https://img.shields.io/badge/Paper%20%7C%20Spigot-supported-blue)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red)
A utility plugin for Minecraft server admins and moderators with **48 commands**: sign and block tracking, structure finding with instant teleport, over-limit enchanting, area mining, player effects, staff chat and more.

**[Download](https://github.com/natan307/CommandPlus/releases/download/1.0.0/CommandPlus-1.0.0.jar)** · **[Wiki](https://github.com/natan307/CommandPlus/wiki)**

## Compatibility
| | |
|---|---|
| Platforms | Paper, Spigot, Bukkit, Purpur, Folia |
| Minecraft | 1.21.x and newer |
| Java | 21 |
| Storage | SQLite or MySQL/MariaDB |
| Optional | PlaceholderAPI, LuckPerms |

Folia support is experimental for veinminer and drill, and `/tick` is not available on Folia.

## Highlights
| Command | What it does |
|---|---|
| `/find` | Like `/locate`, but teleports you to the structure, biome or entity |
| `/logblock` | See who placed or broke the block under your crosshair |
| `/signspy` | Watch signs as they are written: coordinates, 4 lines and author |
| `/unsafeenchant` | Enchantments beyond vanilla limits, up to level 255 |
| `/drill` | Break a width x height area in one go |
| `/veinminer` | Mine a whole ore vein or tree at once |

And more: freeze, measure, poison, luck, remote hit, lore with color and hex support, staff chat, lockdown, lag check, countdown and others. See the full list on the wiki.

## Permissions
Every command has its own permission and is **OP-only by default**. Commands that affect other players use a separate `.others` permission.

```
/lp group helper permission set commandplus.signspy true
/lp group helper permission set commandplus.poison.others true
```

## Installation
1. Download the jar from Release/Modrinth.
2. Put it in your server's `plugins/` folder.
3. Start the server and edit `plugins/CommandPlus/config.yml` if needed.

Details are on the [Wiki](https://github.com/natan307/CommandPlus/wiki/Installation).

## Support
Found a bug? Open an issue and include:
- Server software and version
- Command+ version (`/commandplus about`)
- What you typed and the full console error

## Note
This repository hosts documentation and issue tracking. The plugin's source code is not published here.
