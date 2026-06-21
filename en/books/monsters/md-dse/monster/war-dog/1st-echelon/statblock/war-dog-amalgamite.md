---
agility: 0
ev: "4"
file_basename: war-dog-amalgamite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 3
intuition: 0
item_id: war-dog-amalgamite
item_name: War Dog Amalgamite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
might: 2
name: War Dog Amalgamite
organization: Horde
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-amalgamite
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "25"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 2      |      Horde Brute      |         EV 4         |
|:---------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|        **2**<br>Size        |  **5**<br>Speed   | **25**<br>Stamina |  **2**<br>Stability   | **3**<br>Free Strike |
|      **-**<br>Immunity      | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+2**<br>Might       | **0**<br>Agility  |  **0**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Several Arms ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 5 damage; A < 1 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 6 damage; A < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** The amalgamite can have up to four targets [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) at once.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The amalgamite deals 3 damage to each creature [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way or who they already have [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), and regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to the damage dealt.

> 🏹 **Posthumous Promotion**
>
> | **Magic, Ranged** |       **Maneuver** |
> |-------------------|-------------------:|
> | **📏 Ranged 10**  | **🎯 One war dog** |
>
> **Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Loyalty Collar**
>
> When the amalgamite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
