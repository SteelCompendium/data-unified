---
agility: 1
ev: "8"
file_basename: orc-terranova
file_dpath: monster/orc/statblock
free_strike: 4
intuition: 1
item_id: orc-terranova
item_name: Orc Terranova
keywords:
    - Humanoid
    - Orc
level: 2
might: 1
movement: Burrow
name: Orc Terranova
organization: Platoon
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.orc.statblock/orc-terranova
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "30"
type: statblock
---

|   Humanoid, Orc   |           -            |      Level 2      |  Platoon Controller   |         EV 8         |
|:-----------------:|:----------------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |     **6**<br>Speed     | **30**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
| **-**<br>Immunity | **Burrow**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+1**<br>Might  |   **+1**<br>Agility    | **+0**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🏹 **Earth Pillar ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Magic, Ranged, Strike** |                   **Main action** |
> |---------------------------|----------------------------------:|
> | **📏 Ranged 10**          | **🎯 Three creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage; A < 0 [prone](../../../condition/prone.md) and can't stand (save ends)
> - **12-16:** 9 damage; A < 1 [prone](../../../condition/prone.md) and can't stand (save ends)
> - **17+:** 12 damage; A < 2 [prone](../../../condition/prone.md) and can't stand (save ends)
>
> **Effect:** Each target must be on the ground, and the ground in each target's space rises 1 square.

> ❇️ **Sinkhole (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Weapon** |                          **Main action** |
> |------------------|-----------------------------------------:|
> | **📏 3 burst**   | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage; M < 0 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** 7 damage; M < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 10 damage; M < 2 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** The area is [difficult terrain](../../../movement/difficult-terrain.md).

> ⭐️ **Seismic Step**
>
> The terranova ignores [difficult terrain](../../../movement/difficult-terrain.md). Additionally, they don't need [line of effect](../../../rule/combat/line-of-effect.md) to use abilities against creatures touching the ground.

> ⭐️ **Relentless**
>
> If the terranova is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the terranova is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
