---
agility: -1
ev: "96"
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Horror
    - Olothec
level: 6
might: 4
movement: Fly, swim
name: Olothec
organization: Solo
presence: 3
reason: 4
scc: mcdm.monsters.v1/monster.olothec.statblock/olothec
size: "2"
speed: 7
stability: 0
stamina: "450"
type: statblock
---

|      Horror, Olothec      |             -             |      Level 6       |         Solo          |        EV 96         |
|:-------------------------:|:-------------------------:|:------------------:|:---------------------:|:--------------------:|
|       **2**<br>Size       |      **7**<br>Speed       | **450**<br>Stamina |  **0**<br>Stability   | **7**<br>Free Strike |
| **Psychic 6**<br>Immunity | **Fly, swim**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|      **+4**<br>Might      |     **-1**<br>Agility     |  **+4**<br>Reason  |  **+2**<br>Intuition  |  **+3**<br>Presence  |

> ☠️ **Solo Monster**
>
> [**End Effect:**](scc:mcdm.monsters.v1/rule.monster/end-effect) At the end of each of their turns, the olothec can take 10 damage to end one effect on them that can be ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
>
> **Solo Turns:** The olothec can take two turns each round. They can't take turns consecutively.

> ⭐️ **Gelatinosis**
>
> A creature permanently devolves into a slime servant if they spend 1 continuous minute [weakened](scc:mcdm.heroes.v1/condition/weakened) by Devolving Tentacles, they are reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) by the psychic damage from Devolving Tentacles, or they suffer all three transformations from Oozing Transformation.

> 🗡 **Devolving Tentacles ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; M < 2 [weakened](scc:mcdm.heroes.v1/condition/weakened) or the target is slimed (save ends)
> - **12-16:** 17 damage; M < 3 [weakened](scc:mcdm.heroes.v1/condition/weakened) or the target is slimed (save ends)
> - **17+:** 20 damage; M < 4 [weakened](scc:mcdm.heroes.v1/condition/weakened) and the target is slimed (save ends)
>
> **Effect:** A slimed target takes 4 psychic damage whenever they make a power roll.

> 🔳 **Slime Spew**
>
> | **Area, Weapon**           |                             **Main action** |
> |----------------------------|--------------------------------------------:|
> | **📏 7 x 2 line within 1** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 acid damage; A < 2 [push](scc:mcdm.heroes.v1/movement/forced-movement) special
> - **12-16:** 10 acid damage; A < 3 [push](scc:mcdm.heroes.v1/movement/forced-movement) special
> - **17+:** 13 acid damage; A < 4 [push](scc:mcdm.heroes.v1/movement/forced-movement) special and [prone](scc:mcdm.heroes.v1/condition/prone)
>
> **Effect:** Each creature [pushed](scc:mcdm.heroes.v1/movement/forced-movement) this way is pushed to an unoccupied space in the area as far as possible from the olothec.
>
> **1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). Any creature who enters the area or moves within it for the first time on a turn and has A < 3 is knocked [prone](scc:mcdm.heroes.v1/condition/prone).

> 🏹 **Oozing Transformation (2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Psionic, Ranged, Strike** |     **Main action** |
> |-----------------------------|--------------------:|
> | **📏 Ranged 10**            | **🎯 One creature** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 psychic damage; I < 2 the target is transformed (save ends)
> - **12-16:** 20 psychic damage; I < 3 the target is transformed (save ends)
> - **17+:** 23 psychic damage; I < 4 the target is transformed (save ends)
>
> **Effect:** Each time a target is transformed, the Director chooses one of the following transformations. When a target ends the transformed effect, all transformations on them end.
>
> **Head:** The target's head becomes a ball of slime. They can't communicate and have line of effect only within 3 squares.
>
> **Legs:** The target's legs become pillars of ooze. They are [slowed](scc:mcdm.heroes.v1/condition/slowed) while on land and can automatically swim at full speed while moving.
>
> **Torso:** The target's arms become gelatinous. They can't benefit from edges or double edges and can't gain or use [surges](scc:mcdm.heroes.v1/rule.resource/surge).

> 👤 **Jaunt**
>
> | **Psionic** | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The olothec [teleports](scc:mcdm.heroes.v1/movement/teleport) to an unoccupied space within 10 squares. Alternatively, they swap places with a creature or object within 5 squares of them.

> ❗️ **Liquify**
>
> | **Psionic, Ranged** | **Triggered action** |
> |---------------------|---------------------:|
> | **📏 Ranged 5**     |    **🎯 Each enemy** |
>
> **Trigger:** An enemy within distance deals damage to the olothec.
>
> **Effect:** The target takes 8 psychic damage and has psychic weakness 3 until the end of the olothec's next turn.

> ⭐️ **Primordial Mind**
>
> The olothec can't be made [frightened](scc:mcdm.heroes.v1/condition/frightened) or [taunted](scc:mcdm.heroes.v1/condition/taunted).

> ⭐️ **Slime Sense**
>
> A slimed or transformed creature can't have concealment from or be hidden from the olothec.

> ☠️ **Horrifying Form ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Psionic, Ranged, Strike** |             **-** |
> |-----------------------------|------------------:|
> | **📏 Ranged 20**            | **🎯 Each enemy** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 psychic damage; P < 2 [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 14 psychic damage; P < 3 [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 17 psychic damage; P < 4 [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** While [frightened](scc:mcdm.heroes.v1/condition/frightened) this way, a target can't make [saving throws](scc:mcdm.heroes.v1/rule.general/saving-throw) to end any other effects.

> ☠️ **Psychic Pulse ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area, Psionic** |                            **-** |
> |-------------------|---------------------------------:|
> | **📏 10 burst**   | **🎯 Each creature in the area** |
>
> **Effect:** The olothec [slides](scc:mcdm.heroes.v1/movement/forced-movement) each target up to 5 squares. Each target takes 12 psychic damage, and if they have M < 3 they are [weakened](scc:mcdm.heroes.v1/condition/weakened) and slimed (save ends). A slimed target takes 4 psychic damage whenever they make a power roll. Additionally, until the start of their next turn, the olothec has damage immunity 4.

> ☠️ **Return to Perfection ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area, Psionic** |                            **-** |
> |-------------------|---------------------------------:|
> | **📏 10 burst**   | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 psychic damage; R < 2 the target is devolved (save ends)
> - **12-16:** 13 psychic damage; R < 3 the target is devolved (save ends)
> - **17+:** 16 psychic damage; R < 3 the target is devolved (save ends)
>
> **Effect:** A devolved creature has a −1 score for all their characteristics other than Reason.
