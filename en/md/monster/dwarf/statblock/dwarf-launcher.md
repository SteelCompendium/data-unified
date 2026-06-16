---
agility: 0
ev: "8"
free_strike: 4
intuition: 2
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 1
name: Dwarf Launcher
organization: Platoon
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-launcher
size: 1M
speed: 5
stability: 3
stamina: "39"
type: statblock
---

|  Dwarf, Humanoid  |         -         |      Level 1      |     Platoon Hexer     |         EV 8         | 
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:| 
|  **1M**<br>Size   |  **5**<br>Speed   | **39**<br>Stamina |  **3**<br>Stability   | **4**<br>Free Strike | 
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   | 
|  **+1**<br>Might  | **+0**<br>Agility | **+0**<br>Reason  |  **+2**<br>Intuition  |  **+0**<br>Presence  |

> 🔳 **Concussive Grenade (Signature Ability)**
>
> | **Area, Ranged, Weapon** | **Main action** |
> |--------------------------|------------------------------:|
> | **📏 3 cube within 5**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 6 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3; M < 1 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 8 damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** A target [restrained](scc:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.

> 🔳 **Sleep Grenade (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Ranged, Weapon**     |               **Main action** |
> |------------------------|------------------------------:| 
> | **📏 3 cube within 5** | **🎯 Each enemy in the area** |   
>
> **Power Roll + 2:**
>
> - **≤11:** 3 poison damage; I < 0 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 6 poison damage; I < 1 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 8 poison damage; I < 2 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **Effect:** A target [dazed](scc:mcdm.heroes.v1/condition/dazed) this way treats their characteristic scores as 1 lower for the purpose of resisting [potencies](scc:mcdm.heroes.v1/rule.character/potency).

> ⭐️ **Indirect Fire**
>
> The launcher ignores concealment and cover, and doesn't need line of effect to use their abilities as long as a size 1 opening exists between the dwarf and the target.
