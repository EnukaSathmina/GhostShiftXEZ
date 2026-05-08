# 👻 GhostShiftXEZ — Fabric 1.21.4 Client Mod

![Minecraft](https://img.shields.io/badge/Minecraft-1.21.4-brightgreen?style=for-the-badge)
![Loader](https://img.shields.io/badge/Loader-Fabric-blue?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Educational-red?style=for-the-badge)

**GhostShiftXEZ** is a client-side **Fabric 1.21.4** Java mod created for learning, testing, and private Minecraft environments.

It includes visual overlay modules, player/chest rendering tools, health indicators, radar UI, movement utilities, and configurable client-side features.

> ⚠️ **Important Notice**  
> This project is for **educational and private testing purposes only**.  
> Do **not** use this mod on multiplayer servers without permission.  
> Using client-side advantage mods on public servers may violate server rules and can result in bans.

---

## 📷 Preview

> ![GhostShiftXEZ Preview](https://github.com/EnukaSathmina/GhostShiftXEZ/blob/main/Preview.png?raw=true)

---

# 📦 Requirements

Before building or running the mod, make sure you have:

- Minecraft 1.21.4
- Java 21
- Fabric Loader for 1.21.4
- Fabric API
- Mod Menu
- Cloth Config

---

## ✨ Features

### 👁️ Visual Modules

- Player ESP
- Chest ESP
- Realtime player health bars
- Radar overlay
- Custom player outline colors
- Player whitelist support

### 🕹️ Utility Modules

- In-game click GUI
- Config reload command
- Mod Menu config screen
- Profile-based configuration system
- Performance-friendly tick handling

### ⚙️ Combat & Movement Testing Modules

- Aim Assist
- Anti-AFK
- Anti-Blind
- Boat Fly
- Fly
- Auto Totem
- Bow Aimbot
- Water Walk

> These modules are intended for private worlds, local testing, or controlled environments only.

---

## 🎮 Controls

| Key | Action |
|---|---|
| `P` | Toggle Player ESP |
| `C` | Toggle Chest ESP |
| `H` | Toggle Health Bars |
| `R` | Toggle Radar |
| `Right Shift` | Open In-Game Click GUI |
| `V` | Hold Aim Assist |
| `K` | Toggle Anti-AFK |
| `N` | Toggle Anti-Blind |
| `B` | Toggle Boat Fly |
| `G` | Toggle Fly |
| `X` | Hold Bow Aimbot |
| `O` | Toggle Water Walk |

---

## 💬 Commands

### Player ESP

```mcfunction
/pesp color <r> <g> <b>
```
- Changes the player outline color.

- Color values must be between:

- 0.0 - 1.0

Example:
```
/pesp color 0.0 1.0 0.5
```

## Player Whitelist
### Adds a player to the Player ESP whitelist.
```
/pesp whitelist add <player>
```
### Removes a player from the whitelist.
```
/pesp whitelist remove <player>
```
### Clears the whitelist.

- If the whitelist is empty, all players are shown.
- If the whitelist contains names, only those players are shown.
```
/pesp whitelist clear
```
