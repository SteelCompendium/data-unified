---
agility: 0
ev: "20"
free_strike: 5
immunities:
    - Cold 5
intuition: -1
keywords:
    - Elemental
level: 3
might: 2
movement: Swim
name: Essence of Tides
organization: Elite
presence: 2
reason: 1
role: Controller
scc: mcdm.monsters.v1/monster.elemental.statblock/essence-of-tides
size: 1M
speed: 7
stability: 1
stamina: "80"
type: statblock
---

|       Elemental        |          -           |      Level 3      |   Elite Controller    |        EV 20         |
|:----------------------:|:--------------------:|:-----------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size     |    **7**<br>Speed    | **80**<br>Stamina |  **1**<br>Stability   | **5**<br>Free Strike |
| **Cold 5**<br>Immunity | **Swim**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+2**<br>Might     |  **+0**<br>Agility   | **+1**<br>Reason  |  **-1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Water Wing (Signature Ability)**
>
> | **Magic, Melee, Strike** |                 **Main action** |
> |--------------------------|--------------------------------:|
> | **📏 Melee 1**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; [slide](../../../movement/forced-movement.md) 1
> - **12-16:** 11 damage; [slide](../../../movement/forced-movement.md) 2
> - **17+:** 14 damage; [slide](../../../movement/forced-movement.md) 3
>
> **Effect:** If a target has P < 2, their stability is reduced to 0 and they move 2 additional squares whenever they are force moved (save ends).

> 🏹 **Convocation of Waves**
>
> | **Magic, Ranged** |                 **Maneuver** |
> |-------------------|-----------------------------:|
> | **📏 Ranged 5**   | **🎯 Self or one elemental** |
>
> **Effect:** Until the start of the essence's next turn, the target has cold immunity 5.
>
> **3 [Malice](../../../rule/monster/malice.md):** Until the end of the encounter, the ground within 1 square of the target is a pool of water that is [difficult terrain](../../../movement/difficult-terrain.md). This water extends out behind the target as they move, creating a stream that lasts until the end of the encounter. Any enemy who ends their turn in the stream and has M < 2 is [slowed](../../../condition/slowed.md) (save ends).

> ❗️ **Sea-Salted Wounds (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee**      | **Triggered action** |
> |----------------|---------------------:|
> | **📏 Melee 1** |     **🎯 One enemy** |
>
> **Trigger:** An ally deals rolled damage to the target.
>
> **Effect:** The essence makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.

> ⭐️ **Fickle and Free**
>
> The essence can't be [restrained](../../../condition/restrained.md), [slowed](../../../condition/slowed.md), or knocked [prone](../../../condition/prone.md), and they ignore [difficult terrain](../../../movement/difficult-terrain.md).

> ⭐️ **Water Glide**
>
> Whenever the essence starts their turn in a space containing water, they can [fly](../../../movement/fly.md) until the end of their turn. While flying, the essence doesn't provoke opportunity attacks.
