---
agility: 1
ev: "4"
file_basename: gnoll-bonesplitter
file_dpath: monster/gnoll/statblock
free_strike: 3
intuition: 0
item_id: gnoll-bonesplitter
item_name: Gnoll Bonesplitter
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 2
name: Gnoll Bonesplitter
organization: Horde
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-bonesplitter
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "25"
type: statblock
---

|  Abyssal, Gnoll   |         -         |      Level 2      |      Horde Brute      |         EV 4         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **5**<br>Speed   | **25**<br>Stamina |  **1**<br>Stability   | **3**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
| **+2**<br>Might | **+1**<br>Agility | **0**<br>Reason | **0**<br>Intuition | **+1**<br>Presence |

> 🗡 **Three-Tail Flail (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; [push](../../../movement/forced-movement.md) 2
> - **12-16:** 6 damage; [push](../../../movement/forced-movement.md) 2
> - **17+:** 8 damage; [grabbed](../../../condition/grabbed.md); M < 2 the target takes a bane on the Escape Grab maneuver
>
> **Effect:** While the bonesplitter has a target [grabbed](../../../condition/grabbed.md), they can't use Three-Tail Flail against another target.

> ❇️ **Bonesplitter's Cackletongue (4 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**       |                          **Maneuver** |
> |----------------|--------------------------------------:|
> | **📏 2 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Up to three targets can make a [free strike](../../../feature/common/main-actions/free-strike.md). If any target hasn't used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.

> ⭐️ **Death Frenzy**
>
> Whenever a non-[minion](../../../rule/organization/minion.md) ally within 5 squares of the bonesplitter is reduced to 0 [Stamina](../../../rule/health/stamina.md), the bonesplitter moves up to their speed and can make a melee [free strike](../../../feature/common/main-actions/free-strike.md).
