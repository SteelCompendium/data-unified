---
agility: 1
ev: "3"
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
keywords:
    - Undead
level: 1
might: -5
movement: Fly, hover
name: Specter
organization: Horde
presence: 2
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/specter
size: 1M
speed: 5
stability: 1
stamina: "10"
type: statblock
---

|                 Undead                 |             -              |      Level 1      |      Horde Hexer      |         EV 3         |
|:--------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |       **5**<br>Speed       | **10**<br>Stamina |  **1**<br>Stability   | **1**<br>Free Strike |
| **Corruption 1, poison 1**<br>Immunity | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **-5**<br>Might             |     **+1**<br>Agility      | **+0**<br>Reason  |  **+0**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Decaying Touch ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Melee, Strike** |     **Main action** |
> |--------------------------|--------------------:|
> | **📏 Melee 1**           | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 corruption damage; P < 0 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **12-16:** 4 corruption damage; P < 1 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 5 corruption damage; P < 2 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** The [potency](scc:mcdm.heroes.v1/rule.character/potency) increases by 1. Any living creature who dies from this damage rises at the start of the next round in the target's space as a specter under the Director's control.

> 👤 **Hidden Movement**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The specter turns invisible, moves up to their speed, and is visible again.

> ⭐️ **Corruptive Phasing**
>
> The specter can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the specter moves through a creature, that creature takes 2 corruption damage. The specter doesn't take damage from being [force moved](scc:mcdm.heroes.v1/movement/forced-movement) into objects.
