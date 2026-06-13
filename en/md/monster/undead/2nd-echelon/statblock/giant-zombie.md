---
agility: -1
ev: "24"
free_strike: 6
immunities:
    - Corruption 4
    - poison 4
intuition: 1
keywords:
    - Undead
    - Soulless
level: 4
might: 3
name: Giant Zombie
organization: Elite
presence: 2
reason: -2
role: Brute
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/giant-zombie
size: "3"
speed: 6
stability: 2
stamina: "140"
type: statblock
---

|            Undead, Soulless            |         -         |      Level 4       |      Elite Brute      |        EV 24         |
|:--------------------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|             **3**<br>Size              |  **6**<br>Speed   | **140**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |
| **Corruption 4, poison 4**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+3**<br>Might             | **-1**<br>Agility |  **-2**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Rotten Smash ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage; A < 2 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 17 damage; A < 3 [grabbed](scc:mcdm.heroes.v1/condition/grabbed)

> ❗️ **Knocking Heads (1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       |   **Triggered action** |
> |-------------|-----------------------:|
> | **📏 Self** | **🎯 Self; see below** |
>
> **Trigger:** The giant zombie [grabs](scc:mcdm.heroes.v1/condition/grabbed) two creatures or objects, or starts their turn with two creatures or objects [grabbed](scc:mcdm.heroes.v1/condition/grabbed).
>
> **Effect:** The creatures or objects are smashed together using Rotten Smash, which has a double edge.

> ⭐️ **Endless Knight**
>
> The first time the giant zombie is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 50 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and fall [prone](scc:mcdm.heroes.v1/condition/prone).

> ⭐️ **Negative Nerves**
>
> When the giant zombie is targeted by an ability that deals rolled damage, they halve the damage from a tier 1 outcome.
