---
agility: -2
ev: "12"
file_basename: bonecage
file_dpath: monster/undead/4th-echelon/statblock
free_strike: 4
immunities:
    - Corruption 10
    - poison 10
intuition: 3
item_id: bonecage
item_name: Bonecage
keywords:
    - Undead
    - Soulless
level: 10
might: 5
movement: Climb
name: Bonecage
organization: Horde
presence: -1
reason: -2
role: Controller
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/bonecage
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 5
stamina: "55"
type: statblock
---

|             Undead, Soulless             |           -           |     Level 10      |   Horde Controller    |        EV 12         |
|:----------------------------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|              **3**<br>Size               |    **6**<br>Speed     | **55**<br>Stamina |  **5**<br>Stability   | **4**<br>Free Strike |
| **Corruption 10, poison 10**<br>Immunity | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|             **+5**<br>Might              |   **-2**<br>Agility   | **-2**<br>Reason  |  **+3**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Ribcage Chomp ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 9 damage; M < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 12 damage; M < 5 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 14 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** The bonecage can have up to four [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1 targets [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) at once. Any creature [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the bonecage takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the [Escape Grab](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/escape-grab) maneuver, and the bonecage has [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 5 against that creature's abilities. When the bonecage is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement), any creature or object they have [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) moves with them.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, a target can't [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) or be [teleported](scc.v1:mcdm.heroes.v1/movement/teleport).

> 🔳 **Labyrinth of Bone (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic, Ranged**           |               **Main action** |
> |-----------------------------------|------------------------------:|
> | **📏 Four 10 x 1 lines within 3** | **🎯 Each enemy in the area** |
>
> **Effect:** The bonecage can put up to two 90-degree bends in each of the lines. Each target makes an Agility test.
>
> - **≤11:** 9 damage
> - **12-16:** 7 damage
> - **17+:** 4 damage
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. The effect ends at the end of the encounter or when the bonecage uses this ability again.
