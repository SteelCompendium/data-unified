---
agility: 3
ev: "32"
file_basename: devil-magistrate
file_dpath: monster/devil/statblock
free_strike: 7
immunities:
    - Fire 5
intuition: 1
item_id: devil-magistrate
item_name: Devil Magistrate
keywords:
    - Devil
    - Infernal
level: 6
might: 1
name: Devil Magistrate
organization: Elite
presence: 2
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.devil.statblock/devil-magistrate
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "160"
type: statblock
---

|    Devil, Infernal     |         -         |      Level 6       |     Elite Harrier     |        EV 32         |
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size     |  **7**<br>Speed   | **160**<br>Stamina |  **0**<br>Stability   | **7**<br>Free Strike |
| **Fire 5**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+1**<br>Might     | **+3**<br>Agility |  **+0**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Edge of the Law (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- |--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage
> - **17+:** 18 fire damage; R < 3 [dazed](../../../condition/dazed.md) (save ends)
>
> **Effect:** The magistrate [shifts](../../../movement/shifting.md) up to 3 squares before or after using this ability, or between each strike.

> 🗡 **Verdict**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 3:**
>
> - **≤11:** 11 damage
> - **12-16:** 17 damage
> - **17+:** 21 damage
>
> **Effect:** This ability has a double [edge](../../../rule/dice/edge.md) if the magistrate was hidden from the target, and deals an extra 5 damage if the target is [dazed](../../../condition/dazed.md).

> 👤 **Justice Turns Its Gaze**
>
> | **-**       | **Maneuver** | 
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The magistrate turns invisible until the start of their next turn, and can attempt to hide as a [free maneuver](../../../rule/combat/free-maneuver.md) before the end of the current turn.

> ❗️ **Devilish Charm (2 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** |           **Triggered action** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature targets the magistrate with a strike.
>
> **Effect:** The target makes a Presence test.
>
> - **≤11:** The magistrate chooses a new target for the strike.
> - **12-16:** The magistrate halves the triggering damage.
> - **17+:** The target takes a [bane](../../../rule/dice/bane.md) on the strike.

> ⭐️ **Leading**
>
> Whenever the magistrate moves away from an enemy who is [adjacent](../../../rule/combat/adjacent.md) to one of the magistrate's allies, they can [shift](../../../movement/shifting.md) instead.

> ⭐️ **True Name**
>
> If a creature within 10 squares speaks the magistrate's true name, the magistrate loses their damage immunities, any nondamaging effects of their [signature ability](../../../rule/combat/signature-ability.md), and their Devilish Charm ability until the end of the encounter.
