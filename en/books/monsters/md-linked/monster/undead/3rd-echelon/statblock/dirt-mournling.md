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

> 🗡 **Mudslide ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **[Main action](../../../../rule/combat/turn.md)** |
> |---------------------------|------------------------------:|
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
> - **12-16:** 10 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
> - **17+:** 11 damage; [grabbed](../../../../condition/grabbed.md)
>
> **Effect:** A 3-[cube](../../../../rule/combat/cube.md) area of ground centered on the target is [difficult terrain](../../../../movement/difficult-terrain.md) for enemies.

> ❇️ **Mourning Cry (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area, Magic** |               **[Main action](../../../../rule/combat/turn.md)** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 3 corruption damage; I < 2 [frightened](../../../../condition/frightened.md) (save ends)
> - **12-16:** 6 corruption damage; I < 3 [frightened](../../../../condition/frightened.md) (save ends)
> - **17+:** 7 corruption damage; I < 4 [frightened](../../../../condition/frightened.md) (save ends)
>
> **Effect:** A target [frightened](../../../../condition/frightened.md) this way is [frightened](../../../../condition/frightened.md) of all [undead](../../../../rule/keyword/undead.md). This effect ends early if the mournling is destroyed.

> ⭐️ **Arise**
>
> The first time the mournling is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 15 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).

> ⭐️ **Immutable Form**
>
> The mournling's shape can't be changed by any external effect.

> ⭐️ **Rupture**
>
> Whenever the mournling uses the Dig maneuver to breach the surface, they make a [free strike](../../../../feature/common/main-actions/free-strike.md) against each [adjacent](../../../../rule/combat/adjacent.md) enemy.
