---
agility: -1
ev: "32"
file_basename: lumbering-egress
file_dpath: monster/demon/2nd-echelon/statblock
free_strike: 7
intuition: 2
item_id: lumbering-egress
item_name: Lumbering Egress
keywords:
    - Abyssal
    - Demon
level: 6
might: 4
name: Lumbering Egress
organization: Leader
presence: 2
reason: 1
scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/lumbering-egress
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: "180"
type: statblock
weaknesses:
    - Holy 5
---

|  Abyssal, Demon   |         -         |      Level 6       |        Leader         |          EV 32           |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:------------------------:|
|   **3**<br>Size   |  **6**<br>Speed   | **180**<br>Stamina |  **3**<br>Stability   |   **7**<br>Free Strike   |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **Holy 5**<br>Weakness  |
|  **+4**<br>Might  | **-1**<br>Agility |  **+1**<br>Reason  |  **+2**<br>Intuition  |    **+2**<br>Presence    |

> 🏹 **Ensnarer Cannon (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** 16 corruption damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** 19 corruption damage; A < 4 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Two ensnarers appear in unoccupied spaces [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to each target. On a tier 3 outcome, four ensnarers appear.

> ❇️ **Demonic Egress (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |   **Maneuver** |
> |----------------|---------------:|
> | **📏 3 burst** | **🎯 Special** |
>
> **Effect:** Four level 1 demon [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) (most commonly ensnarers, frenzieds, and pitlings) burst forth from the egress and appear in unoccupied spaces in the area.
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Four level 4 demon [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) (most commonly orliq, grulqins, and wobalas) appear instead.

> ❗️ **Abyssal Protectors (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** | **Triggered action** |
> |-----------------|---------------------:|
> | **📏 5 burst**  |       **🎯 Special** |
>
> **Trigger:** The last ally [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) on the encounter map dies, or the egress is reduced below 25 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
>
> **Effect:** Eight ensnarers appear anywhere in the area.

> ⭐️ **End Effect**
>
> At the end of each of their turns, the egress can take 10 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ☠️ **Frenzied Deluge (Villain Action 1)**
>
> | **Ranged**       |                **-** |
> |------------------|---------------------:|
> | **📏 Ranged 10** | **🎯 Three enemies** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 corruption damage
> - **12-16:** 12 corruption damage
> - **17+:** 15 corruption damage; two frenzieds appear in unoccupied spaces [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to each target

> ☠️ **Fold Space (Villain Action 2)**
>
> | **Ranged**       |       **-** |
> |------------------|------------:|
> | **📏 Ranged 20** | **🎯 Self** |
>
> **Effect:** The egress folds into their own portal and [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space within distance. Four level 4 demon [minions](scc.v1:mcdm.monsters.v1/rule.organization/minion) (most commonly orliq, grulqins, and wobalas) appear in squares in the egress's former space.

> ☠️ **Blood of the Abyss (Villain Action 3)**
>
> | **Area, Magic**             |                                    **-** |
> |-----------------------------|-----------------------------------------:|
> | **📏 10 x 3 line within 1** | **🎯 Each enemy and object in the area** |  
>
> **Power Roll + 4:**
>
> - **≤11:** 6 corruption damage; R < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **12-16:** 11 corruption damage; R < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 14 corruption damage; R < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **Effect:** The egress recalls and instantly destroys any [minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) allies on the encounter map. A torrent of churned-up minion bodies, blood, and ichor erupts from the egress, dealing an extra 1 damage for each minion destroyed this way.
