---
agility: -1
ev: "84"
free_strike: 7
intuition: 1
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
> **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the shambling mound can take 10 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
>
> **Solo Turns:** The shambling mound can take two turns each round. They can't take turns consecutively.

> ⭐️ **Engulfing Sac**
>
> The shambling mound has a vegetative sack on their body where they carry engulfed creatures. The sack has 30 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), damage immunity 5, and fire weakness 10. Destroying the sack frees creatures trapped by the shambling mound's Engulf ability. The shambling mound regrows a destroyed sack at the start of their next turn.

> 🗡 **Vine Lash ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 6**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; A < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 16 damage; A < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 19 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The shambling mound can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) each target up to 6 squares.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each target takes 7 poison damage.

> ❇️ **Seismic Slam**
>
> | **Area, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------|------------------------------:|
> | **📏 6 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 damage; M < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 6 damage; M < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 7 damage; M < 4 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

> 🗡 **Engulf (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee**      |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|------------------------------:|
> | **📏 Melee 6** | **🎯 One creature or object** |
>
> **Effect:** The target must be size 1L or smaller. The shambling mound reaches out with writhing vines, and if the target has A < 3, they are engulfed into the shambling mound's sack. If the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the shambling mound, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1. An engulfed creature is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained), takes 3 poison damage at the start of each turn, and can't take damage from abilities used from outside the sack. When the shambling mound moves, the engulfed creature moves with them. If the shambling mound dies or their sack is destroyed, each engulfed creature is freed and appears in an unoccupied space within 2 squares of the shambling mound.
>
> **2+ [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The shambling mound can engulf one additional target for each 2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) spent.

> 👤 **Leech**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Each creature engulfed by the shambling mound takes 5 poison damage. The shambling mound gains 5 temporary [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) for each creature who takes damage this way.

> ❗️ **Tether Down**
>
> | **Melee**      |           **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|-------------------------------:|
> | **📏 Melee 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance willingly moves.
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **12-16:** 12 damage; M < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **17+:** 15 damage; M < 4 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)

> ⭐️ **False Appearance**
>
> While the shambling mound remains motionless, they are indistinguishable from ordinary vegetation.

> ⭐️ **Frothing Flora**
>
> The area within 6 squares of the shambling mound is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> ☠️ **Ravenous Overgrowth ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area, Weapon**            |                            **-** |
> |-----------------------------|---------------------------------:|
> | **📏 10 x 2 line within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage, [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **12-16:** 12 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; the target has poison weakness 3 until the end of the encounter
> - **17+:** 15 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6; the target has poison weakness 5 until the end of the encounter

> ☠️ **Composting ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Melee**      |             **-** |
> |----------------|------------------:|
> | **📏 Melee 6** | **🎯 Each enemy** |
>
> **Effect:** The shambling mound uses Engulf against each target without spending [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice).

> ☠️ **Exposed Crux ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Melee**   |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The shambling mound rips themself apart, exposing the crux of magic holding them together. The distance of the shambling mound's melee abilities increases to melee 10, the creature has a double edge on power rolls, and strikes made against them gain an edge.
