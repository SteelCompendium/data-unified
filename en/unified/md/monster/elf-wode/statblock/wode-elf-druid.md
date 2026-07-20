---
agility: 1
ev: "8"
free_strike: 3
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 2
might: 0
movement: Climb
name: Wode Elf Druid
organization: Platoon
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-druid
size: 1M
speed: 7
stability: 0
stamina: "30"
type: statblock
---

| Fey, Humanoid, Wode Elf |           -           |      Level 2      |  Platoon Controller   |         EV 8         |
|:-----------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size      |    **7**<br>Speed     | **30**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
|    **-**<br>Immunity    | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **0**<br>Might      |   **+1**<br>Agility   |  **0**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> 🔳 **Entangling Vines (Signature Ability)**
>
> | **Area, Magic, Ranged** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 10 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, a target can't search for hidden creatures.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The size of the cube and the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) both increase by 1.

> 🏹 **The Wode Protects Us (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |                 **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|-----------------------------:|
> | **📏 Ranged 5**   | **🎯 Self and three allies** |
>
> **Effect:** Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 10 squares to a space that has cover or concealment.

> ⭐️ **Masking Glamor**
>
> Abilities targeting the druid that would take a bane from cover or concealment have a double bane instead.
