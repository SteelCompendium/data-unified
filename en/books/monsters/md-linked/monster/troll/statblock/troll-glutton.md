---
agility: 1
ev: "28"
free_strike: 7
intuition: 0
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Glutton
organization: Elite
presence: 1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.troll.statblock/troll-glutton
size: "2"
speed: 6
stability: 4
stamina: "160"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

|   Giant, Troll    |         -         |      Level 5       |      Elite Brute      |              EV 28              |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:-------------------------------:|
|   **2**<br>Size   |  **6**<br>Speed   | **160**<br>Stamina |  **4**<br>Stability   |      **7**<br>Free Strike       |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **Acid 5, fire **<br>Weakness  |
|  **+3**<br>Might  | **+1**<br>Agility |  **-1**<br>Reason  |  **0**<br>Intuition   |       **+1**<br>Presence        |

> 🗡 **Voracious Mastication ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 18 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
>
> **1 [Malice](../../../rule/monster/malice.md):** The glutton regains [Stamina](../../../rule/health/stamina.md) equal to the damage dealt.

> 👤 **Crash Through (3 [Malice](../../../rule/monster/malice.md))**
>
> | **-**       | **Main action** |
> |-------------|----------------:|
> | **📏 Self** |     **🎯 Self** |
>
> **Effect:** The glutton [shifts](../../../movement/shifting.md) up to their speed in a straight line, ignoring [difficult terrain](../../../movement/difficult-terrain.md). The first time during this movement that the glutton moves through the space of a creature or object their size or smaller, that creature or object takes 10 damage, or a creature can choose to fall [prone](../../../condition/prone.md) instead. If the glutton moves into a creature or object larger than them and doesn't knock the creature [prone](../../../condition/prone.md) or destroy the object, the glutton's movement ends and they are [dazed](../../../condition/dazed.md) until the end of their next turn.

> 👤 **Food Frenzy**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the start of their next turn, the glutton has a double edge on strikes, and strikes made against them gain an edge.

> ❗️ **Spiteful Retort (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee**      |      **Free triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** The glutton is reduced to 0 [Stamina](../../../rule/health/stamina.md) but doesn't die.
>
> **Effect:** The glutton uses Voracious Mastication against an [adjacent](../../../rule/combat/adjacent.md) creature.

> ⭐️ **Insatiable Appetite**
>
> Once per turn, the glutton can use the Charge main action as a free maneuver if they target a [winded](../../../rule/health/winded.md) creature.

> ⭐️ **Relentless Hunger**
>
> The glutton dies only if they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md), or if they take acid or fire damage while at 0 [Stamina](../../../rule/health/stamina.md).
