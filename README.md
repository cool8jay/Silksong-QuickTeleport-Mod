# Silksong-QuickTeleport-Mod

> **English** | [中文](README_zh.md)

A quick teleportation mod for Hollow Knight: Silksong.

## English Documentation

📍 **Special Note**: The "MEMORIUM" scene (requires double jump to reach) is prone to this issue. If teleported there before unlocking double jump, you will be trapped in the scene, please be extra careful.

#### 🗺️ Map Key Hold Causing Incomplete Teleportation
During cross-scene teleportation, if the teleport key combination includes the map key (gamepad default LB), holding the map key may cause teleportation only to the scene entrance rather than the target coordinates. When this occurs:
- Release the map key
- Teleport to the same coordinate save again
- Or use the Safe Respawn function

💡 **Tip**: While this operation method is uncommon, both keyboard and gamepad can trigger this issue.

</details>

### Usage

#### Keyboard Controls
- `Ctrl + = [equal key]`: **Open QuickTeleport Interface**

```
💡 Note: Default uses main keyboard number keys, NOT numpad keys. All key combinations are fully customizable in the config file, including modifier keys and function keys!
```
### Safety Guidelines

> **⚠️ Important: Please follow these safety guidelines to avoid game bugs and data corruption!**

#### When it's safe to use:
✅ Only save or teleport when your **character is fully controllable**  
✅ In **normal game scenes**, when **not in combat**

#### Dangerous situations - DO NOT use:
❌ **During boss battles**  
❌ **Inside closed combat areas**  
❌ **During cutscenes or animations**  
❌ **When character is controlled or immobilized**  
❌ **During any special states or triggered events**

#### Important Notes:
⚠️ **Avoid multiple teleportations in short time** (like teleporting multiple times within 1 second)  
⚠️ **Do not teleport immediately after death**
---

### Installation

1. Install BepInEx
2. Extract and put the `QuickTeleport.dll` related folder into `BepInEx/plugins/` folder
3. Start game

