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
scc: mcdm.monsters.v1/monster.voiceless-talkers.statblock/voiceless-talker-invader
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

> 🗡 **Tentacle ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage; M < 2 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 18 damage; M < 3 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)

> ❇️ **Psionic Boom (3 Malice)**
>
> | **Area, Psionic** |               **Main action** |
> |-------------------|------------------------------:|
> | **📏 3 burst**    | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 psychic damage; R < 1 [push](scc:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 10 psychic damage; R < 2 [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 12 psychic damage; R < 3 [push](scc:mcdm.heroes.v1/movement/forced-movement) 4 and [prone](scc:mcdm.heroes.v1/condition/prone)
>
> **2 Malice:** The size of the burst increases to 5.

> 🗡 **Tentacle Toss**
>
> | **Melee, Psionic** |        **Maneuver** |
> |--------------------|--------------------:|
> | **📏 Melee 1**     | **🎯 One creature** |
>
> **Effect:** The target must be [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the invader.
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; vertical [slide](scc:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 10 damage; vertical [slide](scc:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 12 damage; vertical [slide](scc:mcdm.heroes.v1/movement/forced-movement) 3

> ❗️ **Brain Drain**
>
> | **Melee, Psionic** |           **[Triggered Action](scc:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |--------------------|-------------------------------:|
> | **📏 Special**     | **🎯 The triggering creature** |
>
> **Trigger:** A creature [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the invader resists an ability's [potency](scc:mcdm.heroes.v1/rule.character/potency).
>
> **Effect:** The [potency](scc:mcdm.heroes.v1/rule.character/potency) increases by 2.

> ⭐️ **Psionic Amplifier**
>
> Whenever a non-[minion](scc:mcdm.monsters.v1/rule.organization/minion) voiceless talker within 5 squares of the invader uses a psionic ability, they can do so as if they were in the invader's space, and the ability has a double edge.
