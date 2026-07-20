---
agility: 1
ev: "32"
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Hover, teleport
name: Voiceless Talker Invader
organization: Elite
presence: 2
reason: 3
role: Controller
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/voiceless-talker-invader
size: 1M
speed: 5
stability: 2
stamina: "140"
type: statblock
---

| Horror, Voiceless Talker  |                -                |      Level 6       |   Elite Controller    |        EV 32         |
|:-------------------------:|:-------------------------------:|:------------------:|:---------------------:|:--------------------:|
|      **1M**<br>Size       |         **5**<br>Speed          | **140**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
| **Psychic 6**<br>Immunity | **Hover, teleport**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|      **-1**<br>Might      |        **+1**<br>Agility        |  **+3**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Tentacle ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage; M < 2 [grabbed](../../../condition/grabbed.md)
> - **17+:** 18 damage; M < 3 [grabbed](../../../condition/grabbed.md)

> ❇️ **Psionic Boom (3 Malice)**
>
> | **Area, Psionic** |               **[Main action](../../../rule/combat/turn.md)** |
> |-------------------|------------------------------:|
> | **📏 3 burst**    | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 psychic damage; R < 1 [push](../../../movement/forced-movement.md) 2
> - **12-16:** 10 psychic damage; R < 2 [push](../../../movement/forced-movement.md) 3
> - **17+:** 12 psychic damage; R < 3 [push](../../../movement/forced-movement.md) 4 and [prone](../../../condition/prone.md)
>
> **2 Malice:** The size of the burst increases to 5.

> 🗡 **Tentacle Toss**
>
> | **Melee, Psionic** |        **[Maneuver](../../../rule/combat/turn.md)** |
> |--------------------|--------------------:|
> | **📏 Melee 1**     | **🎯 One creature** |
>
> **Effect:** The target must be [grabbed](../../../condition/grabbed.md) by the invader.
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; vertical [slide](../../../movement/forced-movement.md) 2
> - **12-16:** 10 damage; vertical [slide](../../../movement/forced-movement.md) 2
> - **17+:** 12 damage; vertical [slide](../../../movement/forced-movement.md) 3

> ❗️ **Brain Drain**
>
> | **Melee, Psionic** |           **[Triggered Action](../../../rule/combat/triggered-action.md)** |
> |--------------------|-------------------------------:|
> | **📏 Special**     | **🎯 The triggering creature** |
>
> **Trigger:** A creature [grabbed](../../../condition/grabbed.md) by the invader resists an ability's [potency](../../../rule/character/potency.md).
>
> **Effect:** The [potency](../../../rule/character/potency.md) increases by 2.

> ⭐️ **Psionic Amplifier**
>
> Whenever a non-[minion](../../../rule/organization/minion.md) voiceless talker within 5 squares of the invader uses a psionic ability, they can do so as if they were in the invader's space, and the ability has a double edge.
