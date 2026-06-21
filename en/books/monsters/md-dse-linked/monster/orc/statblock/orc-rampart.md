---
agility: 2
ev: "8"
file_basename: orc-rampart
file_dpath: monster/orc/statblock
free_strike: 4
intuition: 2
item_id: orc-rampart
item_name: Orc Rampart
keywords:
    - Humanoid
    - Orc
level: 2
might: 2
name: Orc Rampart
organization: Platoon
presence: 2
reason: 2
role: Defender
scc: mcdm.monsters.v1/monster.orc.statblock/orc-rampart
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "59"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 2      |   Platoon Defender    |         EV 8         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **6**<br>Speed   | **59**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+2**<br>Agility | **+2**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **My Spear, My Foe ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage; [taunted](../../../condition/taunted.md) (EoT)
> - **17+:** 12 damage; [taunted](../../../condition/taunted.md) (EoT)
>
> **Effect:** This ability has a double edge against any target who dealt damage to the rampart this round.

> 👤 **Castling**
>
> | **-**                  |    **Maneuver** |
> |------------------------|----------------:|
> | **📏 Self; see below** | **🎯 One ally** |
>
> **Effect:** The rampart moves or [shifts](../../../movement/shifting.md) up to their speed [adjacent](../../../rule/combat/adjacent.md) to the target, then can swap places with the target.

> ❗️ **No.**
>
> | **-**       | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature targets an ally [adjacent](../../../rule/combat/adjacent.md) to the rampart with an ability that doesn't also target the rampart.
>
> **Effect:** The rampart becomes the target of the triggering ability instead.

> ⭐️ **Relentless**
>
> If the rampart is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the rampart is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
