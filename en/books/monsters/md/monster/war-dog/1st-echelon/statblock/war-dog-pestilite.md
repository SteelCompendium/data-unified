---
agility: 1
ev: "5"
free_strike: 2
immunities:
    - Poison 3
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
might: 0
name: War Dog Pestilite
organization: Horde
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-pestilite
size: 1M
speed: 5
stability: 0
stamina: "20"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 3      |   Horde Controller    |         EV 5         |
|:---------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |  **5**<br>Speed   | **20**<br>Stamina |  **0**<br>Stability   | **2**<br>Free Strike |
|  **Poison 3**<br>Immunity   | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|       **0**<br>Might        | **+1**<br>Agility |  **0**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> 🔳 **Plaguecaster ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Area, Magic, Ranged** |                  **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------------|---------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each creature in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 2 poison damage; I < 0 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 4 poison damage; I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 5 poison damage; I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** The area is filled with a cloud of pestilence that lasts until the start of the pestilite's next turn. Any creature who enters the area for the first time in a round or starts their turn there takes 2 poison damage.

> 🏹 **Posthumous Promotion**
>
> | **Magic, Ranged** |       **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|-------------------:|
> | **📏 Ranged 10**  | **🎯 One war dog** |
>
> **Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Loyalty Collar**
>
> When the pestilite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
