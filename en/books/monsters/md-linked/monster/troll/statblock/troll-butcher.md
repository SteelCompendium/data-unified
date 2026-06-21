---
agility: 1
ev: "28"
free_strike: 6
intuition: 0
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Butcher
organization: Elite
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.troll.statblock/troll-butcher
size: "2"
speed: 8
stability: 2
stamina: "120"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

|   Giant, Troll    |         -         |      Level 5       |      Elite Hexer      |              EV 28              |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:-------------------------------:|
|   **2**<br>Size   |  **8**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   |      **6**<br>Free Strike       |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **Acid 5, fire **<br>Weakness  |
|  **+3**<br>Might  | **+1**<br>Agility |  **+1**<br>Reason  |  **0**<br>Intuition   |        **0**<br>Presence        |

> 🗡 **Savoring Bite ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 14 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 17 damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
>
> **1 [Malice](../../../rule/monster/malice.md):** The butcher regains [Stamina](../../../rule/health/stamina.md) equal to the damage dealt.

> 🔳 **Rotten Scraps**
>
> | **Area, Ranged**        |                  **Main action** |
> |-------------------------|---------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each creature in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 poison damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 9 poison damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
> - **17+:** 11 poison damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
>
> **Effect:** Each troll in the area ignores the damage and instead regains 3 [Stamina](../../../rule/health/stamina.md).

> 👤 **Gourmet Flesh (2 [Malice](../../../rule/monster/malice.md))**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The butcher enhances their next use of Savoring Bite, changing the damage type and condition imposed to one of the following pairs: corruption damage and [dazed](../../../condition/dazed.md), acid damage and [restrained](../../../condition/restrained.md), or lightning damage and [frightened](../../../condition/frightened.md).

> ❗️ **Acquired Taste**
>
> | **Melee**      |           **Triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the butcher with an ability that gains an edge, has a double edge, or uses a [surge](../../../rule/resource/surge.md).
>
> **Effect:** The butcher makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target. Until the end of their next turn, the butcher gains an edge on power rolls and deals an extra 3 damage with strikes.

> ⭐️ **Bloody Feast**
>
> Each ally within 5 squares of the butcher gains an edge on power rolls against any enemy affected by a condition.

> ⭐️ **Relentless Hunger**
>
> The butcher dies only if they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md), or if they take acid or fire damage while at 0 [Stamina](../../../rule/health/stamina.md).
