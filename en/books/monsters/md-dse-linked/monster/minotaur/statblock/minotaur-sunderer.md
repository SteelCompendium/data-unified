---
agility: 1
ev: "20"
file_basename: minotaur-sunderer
file_dpath: monster/minotaur/statblock
free_strike: 6
intuition: 2
item_id: minotaur-sunderer
item_name: Minotaur Sunderer
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
might: 2
name: Minotaur Sunderer
organization: Elite
presence: -1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-sunderer
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "120"
type: statblock
---

| Accursed, Humanoid, Minotaur |         -         |      Level 3       |      Elite Brute      |        EV 20         |
|:----------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|        **2**<br>Size         |  **6**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |
|      **-**<br>Immunity       | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+2**<br>Might        | **+1**<br>Agility |  **0**<br>Reason   |  **+2**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Spiked Maul ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 2**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; [pull](../../../movement/forced-movement.md) 1
> - **12-16:** 12 damage; [pull](../../../movement/forced-movement.md) 2
> - **17+:** 15 damage; [pull](../../../movement/forced-movement.md) 3
>
> **Effect:** A target [pulled](../../../movement/forced-movement.md) [adjacent](../../../rule/combat/adjacent.md) to the sunderer is automatically [grabbed](../../../condition/grabbed.md).

> ❇️ **Fearsome Bay (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**       |               **Main action** |
> |----------------|------------------------------:|
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
> 
> - **≤11:** I < 0 [frightened](../../../condition/frightened.md) (save ends)
> - **12-16:** I < 1 [frightened](../../../condition/frightened.md) (save ends)
> - **17+:** I < 2 [frightened](../../../condition/frightened.md) (save ends)
>
> **Effect:** Until the end of their next turn, the minotaur has damage immunity 2 and deals an extra 5 damage with strikes.

> 🗡 **Disemboweling Horns (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Charge, Melee, Strike, Weapon** |        **Maneuver** |
> |-----------------------------------|--------------------:|
> | **📏 Melee 2**                    | **🎯 One creature** |
>
> **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the sunderer.
>
> **Power Roll + 2:**
> 
> - **≤11:** 5 damage; M < 0 [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 8 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 9 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
>
> **Effect:** While [bleeding](../../../condition/bleeding.md) this way, the target takes 1d6 damage at the start of each of their turns.

> ❗️ **Retaliatory Strike**
>
> | **Ranged**      |           **Triggered action** |
> |-----------------|-------------------------------:|
> | **📏 Ranged 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the sunderer.
>
> **Effect:** The sunderer uses the Charge main action and Spiked Maul against the target.

> ⭐️ **Minotaur Sense**
>
> The sunderer can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
