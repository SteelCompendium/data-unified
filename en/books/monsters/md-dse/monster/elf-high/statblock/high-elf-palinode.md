---
agility: 0
ev: "6"
file_basename: high-elf-palinode
file_dpath: monster/elf-high/statblock
free_strike: 3
immunities:
    - Psychic 5
intuition: 2
item_id: high-elf-palinode
item_name: High Elf Palinode
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Palinode
organization: Platoon
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-palinode
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

|  Fey, High Elf, Humanoid  |         -         |      Level 1      |    Platoon Support    |         EV 6         |
|:-------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|      **1M**<br>Size       |  **5**<br>Speed   | **30**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
| **Psychic 5**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|      **0**<br>Might       | **0**<br>Agility  |  **0**<br>Reason  |  **+2**<br>Intuition  |  **+1**<br>Presence  |

> 🏹 **Instill Regret (Signature Ability)**
>
> | **Magic, Ranged, Strike** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Ranged 8**           | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 psychic damage
> - **12-16:** 7 psychic damage; I < 1 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 9 psychic damage; I < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1. If the target is [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way at the end of the encounter, they can't take a respite activity during their next respite.

> 🏹 **Recall**
>
> | **Magic, Ranged** |      **Maneuver** |
> |-------------------|------------------:|
> | **📏 Ranged 5**   | **🎯 Two allies** |
>
> **Effect:** Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the palinode. The palinode and each target then gain 5 temporary Stamina.

> ⭐️ **Otherworldly Grace**
>
> At the start of each of their turns, the palinode can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
