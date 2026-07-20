---
agility: 2
ev: "12"
free_strike: 4
immunities:
    - Corruption 3
    - poison 3
intuition: 0
keywords:
    - Undead
level: 1
might: -2
movement: Fly, hover
name: Ghost
organization: Leader
presence: 3
reason: 0
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghost
size: 1M
speed: 6
stability: 1
stamina: "80"
type: statblock
---

|                 Undead                 |             -              |      Level 1      |        Leader         |        EV 12         |
|:--------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |       **6**<br>Speed       | **80**<br>Stamina |  **1**<br>Stability   | **4**<br>Free Strike |
| **Corruption 3, poison 3**<br>Immunity | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **-2**<br>Might             |     **+2**<br>Agility      |  **0**<br>Reason  |  **0**<br>Intuition   |  **+3**<br>Presence  |

> 🏹 **Heat Death ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Magic, Ranged, Strike** |      **[Main action](../../../../rule/combat/turn.md)** |
> |---------------------------|---------------------:|
> | **📏 Ranged 5**           | **🎯 Two creatures** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 cold damage; P < 1 [slowed](../../../../condition/slowed.md) (save ends)
> - **12-16:** 10 cold damage; P < 2 [slowed](../../../../condition/slowed.md) (save ends)
> - **17+:** 13 cold damage; P < 3 [slowed](../../../../condition/slowed.md) (save ends)
>
> **Effect:** The next strike made against the target gains an edge.

> 🏹 **Haunt**
>
> | **Ranged**      |                                 **[Maneuver](../../../../rule/combat/turn.md)** |
> |-----------------|---------------------------------------------:|
> | **📏 Ranged 8** | **🎯 Self or one ally with a Phasing trait** |
>
> **Effect:** The target [shifts](../../../../movement/shifting.md) up to their speed.
>
> **2 [Malice](../../../../rule/monster/malice.md):** The ghost chooses one additional target.

> ❗️ **Shriek (1 [Malice](../../../../rule/monster/malice.md))**
>
> | **Magic, Melee** |           **[Triggered action](../../../../rule/combat/triggered-action.md)** |
> |------------------|-------------------------------:|
> | **📏 Melee 1**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance targets the ghost with a strike.
>
> **Effect:** The ghost halves the damage from the strike and the target takes 2 sonic damage.

> ⭐️ **Phantom Flow**
>
> Each undead with a Phasing trait within 10 squares of the ghost can't be made [slowed](../../../../condition/slowed.md) or [weakened](../../../../condition/weakened.md).

> ☠️ **Paranormal Activity ([Villain Action](../../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Magic** |                                            **-** |
> |-----------------|-------------------------------------------------:|
> | **📏 5 burst**  | **🎯 Each size 3 or smaller object in the area** |
>
> **Effect:** Each target rises 1 square into the air and is vertically [pulled](../../../../movement/forced-movement.md) up to 5 squares toward the nearest enemy within 3 squares of the target.

> ☠️ **Spirited Away ([Villain Action](../../../../rule/monster/villain-action.md) 2)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** P < 1 the target is levitated (EoT)
> - **12-16:** P < 2 the target is levitated (EoT)
> - **17+:** P < 3 the target is levitated until the end of the encounter
>
> **Effect:** A levitated target floats 1 square off the ground when first affected, then rises 1 square at the end of each of their turns. If a levitated target can't already [fly](../../../../movement/fly.md), they can [fly](../../../../movement/fly.md) but are [slowed](../../../../condition/slowed.md) and [weakened](../../../../condition/weakened.md) while flying this way.

> ☠️ **Awful Wail ([Villain Action](../../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 sonic damage
> - **12-16:** 5 sonic damage
> - **17+:** 8 sonic damage
>
> **Effect:** A target who has P < 2 is reduced to 1 [Stamina](../../../../rule/health/stamina.md) if they are [winded](../../../../rule/health/winded.md) after taking this damage.

> ⭐️ **Corruptive Phasing**
>
> The ghost can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the ghost moves through a creature, that creature takes 2 corruption damage. The ghost doesn't take damage from being [force moved](../../../../movement/forced-movement.md) into objects.
