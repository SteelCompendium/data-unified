---
agility: 2
ev: "24"
file_basename: wyvern-predator
file_dpath: monster/wyvern/statblock
free_strike: 6
immunities:
    - Acid 5
intuition: 1
item_id: wyvern-predator
item_name: Wyvern Predator
keywords:
    - Beast
    - Wyvern
level: 4
might: 3
movement: Fly
name: Wyvern Predator
organization: Elite
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.wyvern.statblock/wyvern-predator
size: "3"
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "140"
type: statblock
---

|     Beast, Wyvern      |          -          |      Level 4       |      Elite Brute      |        EV 24         |
|:----------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|     **3**<br>Size      |   **7**<br>Speed    | **140**<br>Stamina |  **3**<br>Stability   | **6**<br>Free Strike |
| **Acid 5**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+3**<br>Might     |  **+2**<br>Agility  |  **-1**<br>Reason  |  **+1**<br>Intuition  |  **0**<br>Presence   |

> 🗡 **Sedating Stinger ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Magic, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 17 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
>
> **Effect:** If a target [slowed](../../../condition/slowed.md) this way is already [slowed](../../../condition/slowed.md), they are instead [restrained](../../../condition/restrained.md) (save ends).

> 🔳 **Tail Sweep**
>
> | **Area, Weapon**           |                          **Main action** |
> |----------------------------|-----------------------------------------:|
> | **📏 6 x 3 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; A < 1 3 acid damage
> - **12-16:** 11 damage; A < 2 3 acid damage
> - **17+:** 14 damage; A < 3 3 acid damage
>
> **5 Malice:** The predator uses this ability a second time, either recreating the same line or creating a new line.

> 🗡 **Grasping Jaws (2 Malice)**
>
> | **Magic, Strike, Weapon** |                  **Maneuver** |
> |---------------------------|------------------------------:|
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; A < 1 [grabbed](../../../condition/grabbed.md)
> - **12-16:** 14 damage; A < 2 [grabbed](../../../condition/grabbed.md)
> - **17+:** 17 damage; A < 3 [grabbed](../../../condition/grabbed.md) and the target takes a bane on the Escape Grab maneuver

> ❗️ **Deterring Sting (1 Malice)**
>
> | **Melee**      |           **Triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 3** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the predator with a melee ability.
>
> **Effect:** The predator uses Sedating Stinger against the target, then [shifts](../../../movement/shifting.md) up to 3 squares.

> ⭐️ **Stubborn Rage**
>
> While [winded](../../../rule/health/winded.md) or within 10 squares of another wyvern, the predator can't be made [dazed](../../../condition/dazed.md) or [frightened](../../../condition/frightened.md).

> ⭐️ **Tenacious Hunter**
>
> Any creature affected by a condition imposed by a wyvern can't be hidden from the predator.
