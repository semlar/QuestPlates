[![](https://img.shields.io/static/v1?label=Donate&message=CashApp&color=brightgreen)](https://bit.ly/3fyxxSU)

# QuestPlates (Fork)

## Overview
**QuestPlates** is an addon for World of Warcraft that enhances nameplates by displaying quest objectives directly on enemy health bars. This fork builds upon Simlar’s original addon with performance improvements and updated compatibility for modern WoW expansions.

---

## Features
- **Quest Objectives on Nameplates:** Displays the remaining mobs to kill or items to collect directly on the nameplate.
- **Customizable Settings:** Modify the position, size, and appearance of quest icons using simple commands.
- **Compatibility with Other Nameplate Addons:** Works seamlessly with TidyPlates, KuiNameplates, and Blizzard default nameplates.

---

## Usage

To customize icon position and size, use the following commands:

- Move the quest icon from the left to the right side of the nameplate:
  `" /run QuestPlateSettings.AnchorPoint = 'LEFT'; QuestPlateSettings.RelativeTo = 'RIGHT'; ReloadUI() "`

- Adjust the X (horizontal) and Y (vertical) offsets:
  `" /run QuestPlateSettings.OffsetX = -10; QuestPlateSettings.OffsetY = 5; ReloadUI() "`

- Reset settings to default:
  `" /run QuestPlateSettings = nil; ReloadUI() "`

---

## Compatibility
- **Retail (Dragonflight)**
- **Classic WoW**
- **Classic Cataclysm**

---

## Installation
1. Download the addon from [CurseForge](https://www.curseforge.com/wow/addons/questplates).
2. Extract the downloaded file into the appropriate World of Warcraft AddOns directory:
   - For **Dragonflight**: `World of Warcraft/_retail_/Interface/AddOns`
   - For **Classic Cataclysm**: `World of Warcraft/_classic_/Interface/AddOns`
   - For **Classic WoW**: `World of Warcraft/_classic_era_/Interface/AddOns`
3. Restart World of Warcraft and enable the addon in the AddOns menu.

---

## Support the Project

### ☕️ Buy Me a Coffee
If you enjoy this addon and would like to support its development, consider buying me a coffee. Your contributions help me maintain and improve this project!

[![Buy Me a Coffee](https://img.shields.io/badge/☕️-Buy%20Me%20a%20Coffee-orange?style=flat-square&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/donniedice)

---

## Stay Connected

### 💸 Support:
[![Donate via CashApp](https://img.shields.io/static/v1?label=Donate&message=CashApp&color=brightgreen)](https://bit.ly/3fyxxSU)

### 💬 Follow:
- Follow me on [GitHub](https://github.com/donniedice)

### ⭐️ Show Your Support:
- Star this project on [GitHub](https://github.com/donniedice/QuestPlates) ⭐️
- Share it with your friends and guildmates 📢
