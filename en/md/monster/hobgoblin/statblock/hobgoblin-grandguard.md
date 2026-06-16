---
agility: 2
ev: "16"
free_strike: 6
immunities:
    - Fire 6
intuition: 0
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 6
might: 3
name: Hobgoblin Grandguard
organization: Platoon
presence: 2
reason: 3
role: Defender
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-grandguard
size: "2"
speed: 4
stability: 4
stamina: "111"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |         -         |      Level 6       |   Platoon Defender    |        EV 16         |
|:-------------------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|             **2**<br>Size             |  **4**<br>Speed   | **111**<br>Stamina |  **4**<br>Stability   | **6**<br>Free Strike |
|        **Fire 6**<br>Immunity         | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+3**<br>Might            | **+2**<br>Agility |  **+3**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> 🗡 **Tower Shield Smash (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage
> - **17+:** 17 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
>
> **3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** Each ally [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to a [prone](scc:mcdm.heroes.v1/condition/prone) target can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that target.

> 🔳 **Thunder Rush (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Charge, Weapon**   |                         **Main action** |
> |----------------------------|----------------------------------------:|
> | **📏 1 x 2 line within 1** | **🎯 Each enemy or object in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage
> - **12-16:** 11 damage
> - **17+:** 14 damage
>
> **Effect:** Each target is [pushed](scc:mcdm.heroes.v1/movement/forced-movement) up to 10 squares in the same direction, and the grandguard [shifts](scc:mcdm.heroes.v1/movement/shifting) into the area left behind by the targets.

> ⭐️ **Wide Guard**
>
> Any strike made against an ally within 2 squares of the grandguard takes a bane.

> ⭐️ **Infernal Ichor**
>
> When the grandguard is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the grandguard takes 3 fire damage.
