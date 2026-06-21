---
agility: 4
ev: "10"
file_basename: war-dog-aerocite
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
intuition: 3
item_id: war-dog-aerocite
item_name: War Dog Aerocite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
might: 0
movement: Fly
name: War Dog Aerocite
organization: Horde
presence: 1
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-aerocite
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "50"
type: statblock
---

| Humanoid, Soulless, War Dog |          -          |      Level 8      |     Horde Harrier     |        EV 10         |
|:---------------------------:|:-------------------:|:-----------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |   **8**<br>Speed    | **50**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
|      **-**<br>Immunity      | **Fly**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|       **0**<br>Might        |  **+4**<br>Agility  | **+1**<br>Reason  |  **+3**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Dive Bomb ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage
> - **12-16:** 10 damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 12 damage; vertical [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
>
> **1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** An enemy [forced moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by this ability is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) instead.

> 🔳 **Caustic Paste Bomb (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic, Ranged** |                               **Maneuver** |
> |-------------------------|-------------------------------------------:|
> | **📏 3 cube within 5**  | **🎯 Each creature or object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 2 acid damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 4 acid damage; M < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 6 acid damage; M < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> ⭐️ **Jetwing Agility**
>
> If the aerocite moves 5 or more squares on their turn, strikes made against them take a bane until the start of their next turn.

> ⭐️ **Loyalty Collar**
>
> When the aerocite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
