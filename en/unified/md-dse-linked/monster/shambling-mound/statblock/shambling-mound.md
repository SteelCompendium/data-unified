---
agility: -1
ev: "84"
file_basename: shambling-mound
file_dpath: monster/shambling-mound/statblock
free_strike: 7
intuition: 1
item_id: shambling-mound
item_name: Shambling Mound
keywords:
    - Plant
    - Shambling Mound
level: 5
might: 4
name: Shambling Mound
organization: Solo
presence: 0
reason: 0
scc: mcdm.monsters.v1/monster.shambling-mound.statblock/shambling-mound
size: "3"
source: mcdm.monsters.v1
speed: 3
stability: 5
stamina: "400"
type: statblock
---

| Plant, Shambling Mound |         -         |      Level 5       |         Solo          |        EV 84         |
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|     **3**<br>Size      |  **3**<br>Speed   | **400**<br>Stamina |  **5**<br>Stability   | **7**<br>Free Strike |
|   **-**<br>Immunity    | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+4**<br>Might     | **-1**<br>Agility |  **0**<br>Reason   |  **+1**<br>Intuition  |  **0**<br>Presence   |

> ☠️ **Solo Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the shambling mound can take 10 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
>
> **Solo Turns:** The shambling mound can take two turns each round. They can't take turns consecutively.

> ⭐️ **Engulfing Sac**
>
> The shambling mound has a vegetative sack on their body where they carry engulfed creatures. The sack has 30 [Stamina](../../../rule/health/stamina.md), damage immunity 5, and fire weakness 10. Destroying the sack frees creatures trapped by the shambling mound's Engulf ability. The shambling mound regrows a destroyed sack at the start of their next turn.

> 🗡 **Vine Lash ([Signature Ability](../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 6**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; A < 3 [grabbed](../../../condition/grabbed.md)
> - **12-16:** 16 damage; A < 4 [grabbed](../../../condition/grabbed.md)
> - **17+:** 19 damage; [grabbed](../../../condition/grabbed.md)
>
> **2 [Malice](../../../rule/monster/malice.md):** The shambling mound can [slide](../../../movement/forced-movement.md) each target up to 6 squares.
>
> **3 [Malice](../../../rule/monster/malice.md):** Each target takes 7 poison damage.

> ❇️ **Seismic Slam**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 6 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
> - **12-16:** 6 damage; M < 3 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 7 damage; M < 4 [dazed](../../../condition/dazed.md) (save ends)

> 🗡 **Engulf (2 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee**      |               **Main action** |
> |----------------|------------------------------:|
> | **📏 Melee 6** | **🎯 One creature or object** |
>
> **Effect:** The target must be size 1L or smaller. The shambling mound reaches out with writhing vines, and if the target has A < 3, they are engulfed into the shambling mound's sack. If the target is [grabbed](../../../condition/grabbed.md) by the shambling mound, the [potency](../../../rule/character/potency.md) increases by 1. An engulfed creature is [restrained](../../../condition/restrained.md), takes 3 poison damage at the start of each turn, and can't take damage from abilities used from outside the sack. When the shambling mound moves, the engulfed creature moves with them. If the shambling mound dies or their sack is destroyed, each engulfed creature is freed and appears in an unoccupied space within 2 squares of the shambling mound.
>
> **2+ [Malice](../../../rule/monster/malice.md):** The shambling mound can engulf one additional target for each 2 [Malice](../../../rule/monster/malice.md) spent.

> 👤 **Leech**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Each creature engulfed by the shambling mound takes 5 poison damage. The shambling mound gains 5 temporary [Stamina](../../../rule/health/stamina.md) for each creature who takes damage this way.

> ❗️ **Tether Down**
>
> | **Melee**      |           **Triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance willingly moves.
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [restrained](../../../condition/restrained.md) (EoT)
> - **12-16:** 12 damage; M < 3 [restrained](../../../condition/restrained.md) (EoT)
> - **17+:** 15 damage; M < 4 [restrained](../../../condition/restrained.md) (EoT)

> ⭐️ **False Appearance**
>
> While the shambling mound remains motionless, they are indistinguishable from ordinary vegetation.

> ⭐️ **Frothing Flora**
>
> The area within 6 squares of the shambling mound is [difficult terrain](../../../movement/difficult-terrain.md).

> ☠️ **Ravenous Overgrowth ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Weapon**            |                            **-** |
> |-----------------------------|---------------------------------:|
> | **📏 10 x 2 line within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage, [pull](../../../movement/forced-movement.md) 3
> - **12-16:** 12 damage; [pull](../../../movement/forced-movement.md) 4; the target has poison weakness 3 until the end of the encounter
> - **17+:** 15 damage; [pull](../../../movement/forced-movement.md) 6; the target has poison weakness 5 until the end of the encounter

> ☠️ **Composting ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Melee**      |             **-** |
> |----------------|------------------:|
> | **📏 Melee 6** | **🎯 Each enemy** |
>
> **Effect:** The shambling mound uses Engulf against each target without spending [Malice](../../../rule/monster/malice.md).

> ☠️ **Exposed Crux ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Melee**   |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The shambling mound rips themself apart, exposing the crux of magic holding them together. The distance of the shambling mound's melee abilities increases to melee 10, the creature has a double edge on power rolls, and strikes made against them gain an edge.
