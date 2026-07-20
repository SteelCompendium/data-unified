---
agility: 0
ev: "48"
free_strike: 10
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 10
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 5
role: Hexer
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-talent
size: 1M
speed: 5
stability: 2
stamina: "220"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 10      |      Elite Hexer      |         EV 48         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:---------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **220**<br>Stamina |  **2**<br>Stability   | **10**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |   **-**<br>Weakness   |
|  **0**<br>Might   | **0**<br>Agility  |  **+5**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence   |

> 🏹 **Override ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Psionic, Ranged, Strike, Telekinesis** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------------------------------|--------------------------------:|
> | **📏 Ranged 10**                         | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 psychic damage
> - **12-16:** 20 psychic damage
> - **17+:** 24 psychic damage
>
> **4 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each target moves up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against one enemy of the talent's choice. The target's movement can provoke opportunity attacks, but they can't otherwise be moved in a way that would harm them.

> 🏹 **Steal Time (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Chronopathy, Psionic, Ranged** |                  **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------------------------|------------------------------:|
> | **📏 Ranged 10**                 | **🎯 One creature or object** |
>
> **Power Roll + 5:**
>
> - **≤11:** R < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** R < 4 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** R < 5 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** One ally within distance can use an additional main action on their next turn.

> ❗️ **Psionic Retribution (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Psionic**            | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |------------------------|---------------------:|
> | **📏 Self; see below** |          **🎯 Self** |
>
> **Trigger:** A creature deals damage to the talent.
>
> **Effect:** The talent halves the damage and [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares. The triggering creature takes psychic damage equal to half the damage dealt and is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 5 squares.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the talent chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the talent and the creature can add a d3 roll to power rolls they make against each other.
