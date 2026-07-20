---
agility: 2
ev: "20"
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Orc
level: 3
might: 3
name: Orc Warleader
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.orc.statblock/orc-warleader
size: 1M
speed: 6
stability: 2
stamina: "120"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 3       |        Leader         |        EV 20         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **6**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  | **+2**<br>Agility |  **+1**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Go. ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Ranged**       | **[Main action](../../../rule/combat/turn.md)** |
> |------------------|----------------:|
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a main action.
>
> **1 [Malice](../../../rule/monster/malice.md):** The warleader targets two allies.
>
> **3 [Malice](../../../rule/monster/malice.md):** The warleader targets one ally and a [minion](../../../rule/organization/minion.md) [squad](../../../rule/monster/squad.md).

> 🗡 **Mace Lariat**
>
> | **Melee, Strike, Weapon** |   **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|------------------:|
> | **📏 Melee 1**            | **🎯 Each enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; [push](../../../movement/forced-movement.md) 1; M < 1 [dazed](../../../condition/dazed.md) (save ends)
> - **12-16:** 10 damage; [push](../../../movement/forced-movement.md) 3; M < 2 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 13 damage; [push](../../../movement/forced-movement.md) 5; M < 3 [dazed](../../../condition/dazed.md) (save ends)

> 🏹 **Lockdown (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Ranged**                |                 **[Maneuver](../../../rule/combat/turn.md)** |
> |---------------------------|-----------------------------:|
> | **📏 Self and ranged 10** | **🎯 Self and three allies** |
>
> **Effect:** Each target moves up to their speed and can use the [Grab](../../../feature/common/maneuvers/grab.md) maneuver, which gains an edge.

> ❗️ **Courtesy Call**
>
> | **Ranged**       | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |------------------|---------------------:|
> | **📏 Ranged 10** |  **🎯 One creature** |
>
> **Trigger:** The target obtains a tier 1 outcome on one power roll.
>
> **Effect:** The target has a double edge on their next power roll before the end of the encounter.

> ☠️ **Close In ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area**       |                        **-** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Each enemy [adjacent](../../../rule/combat/adjacent.md) to a target after this move makes an Intuition test.
>
> - **≤11:** [Frightened](../../../condition/frightened.md) of the warleader (save ends)
> - **12-16:** [Frightened](../../../condition/frightened.md) of the warleader (EoT)
> - **17+:** No effect

> ☠️ **Familial Reinforcements ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Ranged**       |       **-** |
> |------------------|------------:|
> | **📏 Ranged 10** | **🎯 Self** |
>
> **Effect:** The warleader [shifts](../../../movement/shifting.md) up to their speed, and four orc blitzers appear in unoccupied spaces within distance.

> ☠️ **I'll Do This Myself ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Three times in succession, the warleader [shifts](../../../movement/shifting.md) up to their speed and can use Mace Lariat.

> ⭐️ **[End Effect](../../../rule/monster/end-effect.md)**
>
> At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.

> ⭐️ **Relentless**
>
> If the warleader is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the warleader is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
