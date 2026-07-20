---
agility: 2
ev: "3"
free_strike: 1
immunities:
    - Corruption 1
    - poison 1
intuition: 0
keywords:
    - Undead
level: 1
might: 0
name: Ghoul
organization: Horde
presence: -1
reason: -2
role: Harrier
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/ghoul
size: 1M
speed: 7
stability: 0
stamina: "15"
type: statblock
---

|                 Undead                 |         -         |      Level 1      |     Horde Harrier     |        EV 3          |
|:--------------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |  **7**<br>Speed   | **15**<br>Stamina |  **0**<br>Stability   | **1**<br>Free Strike |
| **Corruption 1, poison 1**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|             **0**<br>Might             | **+2**<br>Agility | **-2**<br>Reason  |  **0**<br>Intuition   |  **-1**<br>Presence  |

> 🗡 **Razor Claws ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Charge, Melee, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 1**                    | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage
> - **12-16:** 4 damage
> - **17+:** 5 damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)

> 👤 **Leap**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The ghoul jumps up to 3 squares. If they land on a size 1 enemy, that enemy is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) and the ghoul can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.

> ⭐️ **Arise**
>
> The first time the ghoul is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).

> ⭐️ **Hunger**
>
> When the ghoul uses the Charge main action, they gain a +2 bonus to speed until the end of their turn.
