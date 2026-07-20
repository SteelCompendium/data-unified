---
agility: 1
ev: "16"
free_strike: 5
intuition: 0
keywords:
    - Giant
    - Ogre
level: 2
might: 2
name: Ogre Juggernaut
organization: Elite
presence: -1
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.ogre.statblock/ogre-juggernaut
size: "2"
speed: 6
stability: 2
stamina: "80"
type: statblock
---

|    Giant, Ogre    |         -         |      Level 2      |     Elite Harrier     |        EV 16         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **6**<br>Speed   | **80**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+1**<br>Agility | **-1**<br>Reason  |  **0**<br>Intuition   |  **-1**<br>Presence  |

> 🗡 **Pitchfork Catapult ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Charge, Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 2**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 10 damage; A < 1 vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 13 damage; A < 2 vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
>
> **1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each target who has M < 1 is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).

> ❇️ **Earth-Breaking Jump**
>
> | **Area, Weapon** |                  **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------|---------------------------------:|
> | **📏 3 burst**   | **🎯 Each creature in the area** |
>
> **Effect:** The juggernaut jumps up to 6 squares before using this ability.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> ❇️ **Horrible Bellow (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |                  **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|------------------------------:|
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** I < 0 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** While a target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, any ogre gains an edge on strikes against them.

> ❗️ **Hrraaaaaagh! (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** The juggernaut takes damage.
>
> **Effect:** The juggernaut moves up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).

> ⭐️ **Destructive Path**
>
> The juggernaut automatically destroys any mundane size 1 objects in their path when they move or are [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement). They can break through any mundane wall made of wood, stone, or a similarly sturdy material this way as long as the wall is 2 squares thick or less.

> ⭐️ **Defiant Anger**
>
> While [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), the juggernaut has damage immunity 2.
