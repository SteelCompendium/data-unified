---
agility: 2
ev: "3"
file_basename: war-dog-eviscerite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 1
intuition: 0
item_id: war-dog-eviscerite
item_name: War Dog Eviscerite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 1
name: War Dog Eviscerite
organization: Horde
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-eviscerite
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "15"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 1      |     Horde Harrier     |         EV 3         |
|:---------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |  **7**<br>Speed   | **15**<br>Stamina |  **0**<br>Stability   | **1**<br>Free Strike |
|      **-**<br>Immunity      | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+1**<br>Might       | **+2**<br>Agility |  **0**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Chainsaw Whip ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                **Main action** |
> |---------------------------|-------------------------------:|
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage
> - **12-16:** 4 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **17+:** 5 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
>
> **Effect:** The eviscerite can automatically [grab](scc.v1:mcdm.heroes.v1/condition/grabbed) a target [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them this way.

> 🏹 **Posthumous Promotion**
>
> | **Magic, Ranged** |       **Maneuver** |
> |-------------------|-------------------:|
> | **📏 Ranged 10**  | **🎯 One war dog** |
>
> **Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Loyalty Collar**
>
> When the eviscerite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
