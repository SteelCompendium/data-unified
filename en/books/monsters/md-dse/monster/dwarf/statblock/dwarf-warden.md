---
agility: 0
ev: "8"
file_basename: dwarf-warden
file_dpath: monster/dwarf/statblock
free_strike: 5
intuition: 1
item_id: dwarf-warden
item_name: Dwarf Warden
keywords:
    - Dwarf
    - Humanoid
level: 2
might: 2
name: Dwarf Warden
organization: Platoon
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-warden
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "59"
type: statblock
---

|  Dwarf, Humanoid  |         -         |      Level 2      |     Platoon Brute     |         EV 8         | 
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:| 
|  **1M**<br>Size   |  **5**<br>Speed   | **59**<br>Stamina |  **3**<br>Stability   | **5**<br>Free Strike | 
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   | 
|  **+2**<br>Might  | **+0**<br>Agility | **+0**<br>Reason  |  **+1**<br>Intuition  |  **+0**<br>Presence  |

> 🗡 **Concussive Maul (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.

> 🔳 **Concussive Shockwave (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Weapon**       |               **Main action** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; A < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 8 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; A < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; A < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.

> ⭐️ **Escort the Prisoners**
>
> Whenever the warden moves, they can carry an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) enemy as if the enemy were [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by them.
