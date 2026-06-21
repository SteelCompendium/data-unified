---
agility: 2
ev: "4"
file_basename: war-dog-phosphorite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
immunities:
    - Acid 2
intuition: 0
item_id: war-dog-phosphorite
item_name: War Dog Phosphorite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
might: 0
name: War Dog Phosphorite
organization: Horde
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-phosphorite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 2      |      Horde Hexer      |         EV 4         |
|:---------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |  **5**<br>Speed   | **15**<br>Stamina |  **0**<br>Stability   | **2**<br>Free Strike |
|   **Acid 2**<br>Immunity    | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|       **0**<br>Might        | **+2**<br>Agility |  **0**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🏹 **Caustic Detonator ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Ranged** |               **Main action** |
> |-------------------|------------------------------:|
> | **📏 Ranged 10**  | **🎯 One creature or object** |
>
> **Effect:** A detonator attaches to the target. At the end of each round, roll a die. On an odd result, the detonator explodes, triggering the following power roll.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 acid damage; M < 0 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 6 acid damage; M < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 10 acid damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Special:** A creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target can attempt an **Agility test** as a maneuver to remove the detonator.
>
> - **≤11:** No effect.
> - **12-16:** The detonator is disarmed and destroyed.
> - **17+:** The creature can attach the detonator to another creature or object within 5 squares of them.

> 🏹 **Posthumous Promotion**
>
> | **Magic, Ranged** |       **Maneuver** |
> |-------------------|-------------------:|
> | **📏 Ranged 10**  | **🎯 One war dog** |
>
> **Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Loyalty Collar**
>
> When the phosphorite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
