---
agility: 2
ev: "12"
file_basename: basilisk-tonguesnapper
file_dpath: monster/basilisk/statblock
free_strike: 4
immunities:
    - Acid 2
    - Poison 2
intuition: -1
item_id: basilisk-tonguesnapper
item_name: Basilisk Tonguesnapper
keywords:
    - Basilisk
    - Beast
level: 1
might: 1
name: Basilisk Tonguesnapper
organization: Elite
presence: -1
reason: -3
role: Hexer
scc: mcdm.monsters.v1/monster.basilisk.statblock/basilisk-tonguesnapper
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "40"
type: statblock
---

|         Basilisk, Beast          |         -         |      Level 1      |      Elite Hexer      |        EV 12         |
|:--------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|          **2**<br>Size           |  **8**<br>Speed   | **40**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
| **Acid 2, Poison 2**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|         **+1**<br>Might          | **+2**<br>Agility | **-3**<br>Reason  |  **-1**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Prehensile Tongue (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 acid damage; pull 1
> - **12-16:** 10 acid damage; pull 2
> - **17+:** 14 acid damage; pull 3
>
> **Effect:** This ability can pull targets [restrained](../../../condition/restrained.md) by Petrifying Eye Beams, and ignores stability if it does so.
>
> **3 [Malice](../../../rule/monster/malice.md):** The tonguesnapper targets two additional creatures or objects.

> 🔳 **Petrifying Eye Beams**
>
> | **Area, Magic**            |   **Maneuver** |
> |----------------------------|---------------:|
> | **📏 5 x 2 line within 1** | **🎯 Special** |
>
> **Special:** The area extends from both the tonguesnapper’s eyes, and this ability targets the first creature without cover on either side of the area.
>
> **Power Roll + 2:**
>
> - **≤11:** A < 0 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** A < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** [Slowed](../../../condition/slowed.md) (save ends); or if A < 2 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** If a target is already [slowed](../../../condition/slowed.md), the potency increases by 1 for that target. A target [restrained](../../../condition/restrained.md) this way magically begins to turn to stone, and a target who ends two consecutive turns [restrained](../../../condition/restrained.md) this way is petrified. A target [restrained](../../../condition/restrained.md) this way or a creature adjacent to them can use a main action to cut encroaching stone from the target’s body, dealing 8 damage to the target that can’t be reduced in any way and ending this effect.

> ⚔️ **Wink (2 Malice)**
>
> | **Magic, Melee, Ranged, Strike** |     **Main action** |
> |----------------------------------|--------------------:|
> | **📏 Melee 1 or ranged 10**      | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 corruption damage; R < 0 [dazed](../../../condition/dazed.md) (save ends)
> - **12-16:** 10 corruption damage; R < 1 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 14 corruption damage; R < 2 [dazed](../../../condition/dazed.md) and [slowed](../../../condition/slowed.md) (save ends)
>
> **Effect:** A creature [dazed](../../../condition/dazed.md) this way can’t benefit from [edges](../../../rule/dice/edge.md) or double [edges](../../../rule/dice/edge.md) and can’t gain or use [surges](../../../rule/resource/surge.md).

> ❗️ **Neurotoxin Splash**
>
> | **Area**       |          **Triggered action** |
> |----------------|------------------------------:|
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** The tonguesnapper takes damage from a melee ability.
>
> **Effect:** Each target takes 4 acid damage. Any target who has M < 2 is also [slowed](../../../condition/slowed.md) (save ends).

> ⭐️ **Petrifying Fumes**
>
> Any creature who starts their turn adjacent to the tonguesnapper and has M < 1 is [slowed](../../../condition/slowed.md) (save ends).
