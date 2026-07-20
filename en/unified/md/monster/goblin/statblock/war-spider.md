---
agility: 1
ev: "12"
free_strike: 4
intuition: 0
keywords:
    - Animal
    - Goblin
level: 1
might: 2
movement: Climb
name: War Spider
organization: Elite
presence: -3
reason: -4
role: Mount
scc: mcdm.monsters.v1/monster.goblin.statblock/war-spider
size: "3"
speed: 7
stability: 2
stamina: "60"
type: statblock
---

|  Animal, Goblin   |           -           |      Level 1      |      Elite Mount      |        EV 12         |
|:-----------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|   **3**<br>Size   |    **7**<br>Speed     | **60**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
| **-**<br>Immunity | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  |   **+1**<br>Agility   | **-4**<br>Reason  |  **0**<br>Intuition   |  **-3**<br>Presence  |

> 🗡 **Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 poison damage
> - **12-16:** 11 poison damage
> - **17+:** 14 poison damage; M < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** For any tier outcome, if the target has M < 3, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).

> 🗡 **Leg Blade**
>
> | **Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage

> 👤 **Trample (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-** | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> | --- | ---:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The spider [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and uses Leg Blade against each creature who comes [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them during the shift. The spider makes one power roll against all targets.

> 🔳 **Web**
>
> | **Area, Weapon**       |                     **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------------|---------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** A < 0 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.

> ❗️ **Skitter**
>
> | **-**       | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The spider or any ally riding the spider takes damage.
>
> **Effect:** The damage is halved, and the spider [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares after the triggering effect resolves.

> ⭐️ **Ride Launcher**
>
> Any ally who leaps off the back of the spider can jump up to 6 squares without making a test, and takes no damage if they fall during the jump. After any ally jumps, the first melee strike the make on the same turn gains an edge.

> ⭐️ **Wide Back**
>
> While riding the spider, two size 1 allies can occupy the same space.
