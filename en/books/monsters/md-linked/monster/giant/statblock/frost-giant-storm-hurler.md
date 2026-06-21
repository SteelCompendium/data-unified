---
agility: -1
ev: "40"
free_strike: 9
immunities:
    - Cold 8
intuition: 0
keywords:
    - Frost Giant
    - Giant
level: 8
might: 4
name: Frost Giant Storm Hurler
organization: Elite
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-storm-hurler
size: "4"
speed: 7
stability: 5
stamina: "180"
type: statblock
---

|   Frost Giant, Giant   |         -         |      Level 8       |    Elite Artillery    |        EV 40         |
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|     **4**<br>Size      |  **7**<br>Speed   | **180**<br>Stamina |  **5**<br>Stability   | **9**<br>Free Strike |
| **Cold 8**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+4**<br>Might     | **-1**<br>Agility |  **0**<br>Reason   |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🏹 **Ice Javelins (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 15**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 cold damage
> - **12-16:** 18 cold damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
> - **17+:** 22 cold damage; M < 4 [bleeding](../../../condition/bleeding.md) (save ends)
>
> **Effect:** Whenever a creature [bleeding](../../../condition/bleeding.md) this way takes damage from that condition, their speed decreases by 1 (to a minimum of 0) until that condition ends.

> 🏹 **Flower of Frost (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** | **Main action** |
> |-------------------|----------------:|
> | **📏 Ranged 15**  |  **🎯 Special** |
>
> **Effect:** The storm hurler throws three size 1L ice javelins into unoccupied squares within distance. Each javelin has 30 [Stamina](../../../rule/health/stamina.md) and fire weakness 5. At the start of the storm hurler's next turn, all javelins not destroyed explode in a shower of icicles. Each enemy and object within 3 squares of an exploding javelin makes an **Agility test**.
>
> - **≤11:** 14 cold damage; [push](../../../movement/forced-movement.md) 4; [bleeding](../../../condition/bleeding.md) (save ends)
> - **12-16:** 11 cold damage; [push](../../../movement/forced-movement.md) 2; [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 7 cold damage

> 🗡 **Ice Dance**
>
> | **Melee**      |          **Maneuver** |
> |----------------|----------------------:|
> | **📏 Melee 1** | **🎯 One giant ally** |
>
> **Effect:** The storm hurler and the target each [shift](../../../movement/shifting.md) up to 6 squares while staying [adjacent](../../../rule/combat/adjacent.md) to each other. The target can then jump up to 5 squares and make a [free strike](../../../feature/common/main-actions/free-strike.md).

> ❗️ **Frozen Retribution**
>
> | **-**       | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The storm hurler is targeted by a ranged strike.
>
> **Effect:** The triggering strike has a double bane. If the strike obtains a tier 1 outcome, the storm hurler uses Ice Javelins against the creature who made it.

> ⭐️ **Kingdom of Isolation**
>
> The storm hurler is surrounded by a snowstorm. Any enemy who starts their turn within 2 squares of the storm hurler can't [shift](../../../movement/shifting.md).
