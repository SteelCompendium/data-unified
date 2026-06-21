---
agility: 1
ev: "9"
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
keywords:
    - Undead
level: 7
might: 4
movement: Burrow, climb
name: Dirt Mournling
organization: Horde
presence: -3
reason: -2
role: Controller
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/dirt-mournling
size: "3"
speed: 6
stability: 3
stamina: "64"
type: statblock
---

|                 Undead                 |               -               |      Level 7      |   Horde Controller    |         EV 9         |
|:--------------------------------------:|:-----------------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **3**<br>Size              |        **6**<br>Speed         | **64**<br>Stamina |  **3**<br>Stability   | **3**<br>Free Strike |
| **Corruption 7, poison 7**<br>Immunity | **Burrow, climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+4**<br>Might             |       **+1**<br>Agility       | **-2**<br>Reason  |  **+1**<br>Intuition  |  **-3**<br>Presence  |

> 🗡 **Mudslide ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 10 damage; M < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 11 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** A 3-[cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) area of ground centered on the target is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies.

> ❇️ **Mourning Cry (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 3 corruption damage; I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 6 corruption damage; I < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 7 corruption damage; I < 4 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** A target [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of all [undead](scc.v1:mcdm.monsters.v1/rule.keyword/undead). This effect ends early if the mournling is destroyed.

> ⭐️ **Arise**
>
> The first time the mournling is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 15 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and fall [prone](scc.v1:mcdm.heroes.v1/condition/prone).

> ⭐️ **Immutable Form**
>
> The mournling's shape can't be changed by any external effect.

> ⭐️ **Rupture**
>
> Whenever the mournling uses the Dig maneuver to breach the surface, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy.
