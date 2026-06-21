---
agility: 2
ev: "6"
free_strike: 3
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
might: 2
name: Orc Chainlock
organization: Platoon
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.orc.statblock/orc-chainlock
size: 1L
speed: 5
stability: 2
stamina: "20"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 1      |     Platoon Hexer     |         EV 6         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **5**<br>Speed   | **20**<br>Stamina |  **2**<br>Stability   | **3**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+2**<br>Agility | **+1**<br>Reason  |  **+0**<br>Intuition  |  **+0**<br>Presence  |

> 🗡 **Hook and Chain ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; [pull](../../../movement/forced-movement.md) 1; M < 0 the target is hooked (save ends)
> - **12-16:** 7 damage; [pull](../../../movement/forced-movement.md) 2; M < 1 the target is hooked (save ends)
> - **17+:** 9 damage; [pull](../../../movement/forced-movement.md) 3; M < 2 the target is hooked (save ends)
>
> **Effect:** A hooked target can't move more than 3 squares away from the chainlock's position when this ability is used.

> 🏹 **Heavy Crossbolt (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 5**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; A < 0 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 7 damage; A < 1 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 9 damage; [prone](../../../condition/prone.md); A < 2 [slowed](../../../condition/slowed.md) (save ends)

> ⭐️ **Chain Link**
>
> Whenever the chainlock is [force moved](../../../movement/forced-movement.md) by a creature's melee ability, the creature is [pulled](../../../movement/forced-movement.md) the same distance toward the chainlock after the [forced movement](../../../movement/forced-movement.md) is resolved.

> ⭐️ **Relentless**
>
> If the chainlock is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the chainlock is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
