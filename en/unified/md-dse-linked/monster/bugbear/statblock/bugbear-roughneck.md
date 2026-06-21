---
agility: 2
ev: "16"
file_basename: bugbear-roughneck
file_dpath: monster/bugbear/statblock
free_strike: 5
intuition: 0
item_id: bugbear-roughneck
item_name: Bugbear Roughneck
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 2
name: Bugbear Roughneck
organization: Elite
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-roughneck
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "109"
type: statblock
---

| Bugbear, Fey, Goblin, Humanoid |         -         |      Level 2       |      Elite Brute      |        EV 16         |
|:------------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|         **1L**<br>Size         |  **6**<br>Speed   | **109**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|       **-**<br>Immunity        | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|        **+2**<br>Might         | **+2**<br>Agility |  **+0**<br>Reason  |  **+0**<br>Intuition  |  **+0**<br>Presence  |

> 🗡 **Haymaker (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; one target is [grabbed](../../../condition/grabbed.md); one target is [pushed](../../../movement/forced-movement.md) up to 2 squares
> - **17+:** 14 damage; one target is [grabbed](../../../condition/grabbed.md); one target is vertical [pushed](../../../movement/forced-movement.md) up to 3 squares
>
> **5 [Malice](../../../rule/monster/malice.md):** The ability takes the Area keyword and loses the Strike keyword, its distance becomes a 1 burst, and it targets each enemy in the area.

> 🗡 **Leaping Fury**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; M < 1 [prone](../../../condition/prone.md)
> - **12-16:** 13 damage; M < 2 [prone](../../../condition/prone.md)
> - **17+:** 16 damage; M < 3 [prone](../../../condition/prone.md)
>
> **Effect:** The roughneck can jump up to 5 squares to an unoccupied space within distance of the target before making this strike.

> 🗡 **Drag Through Hell (3 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee**      |                  **Maneuver** |
> |----------------|------------------------------:|
> | **📏 Melee 1** | **🎯 One creature or object** |
>
> **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the roughneck.
>
> **Effect:** The roughneck moves up to their speed across the ground, dragging the target with them. The target takes 2 damage for each square they were dragged through. When this movement ends, the target is no longer [grabbed](../../../condition/grabbed.md) and falls [prone](../../../condition/prone.md). Each square the target was dragged through is difficult terrain for enemies.

> 🗡 **Throw**
>
> | **Melee, Strike** | **Maneuver** |
> | --- | ---:|
> | **📏 Melee 1** | **🎯 One creature or object** |
>
> **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the roughneck.
>
> **Effect:** The target is vertical [pushed](../../../movement/forced-movement.md) up to 5 squares. An ally doesn't take damage from being [force moved](../../../movement/forced-movement.md) this way.

> ❗️ **Catcher**
>
> | **Melee**      |                **Free triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A size 1 creature or object is [force moved](../../../movement/forced-movement.md) within distance, or a size 1 ally willingly moves within distance.
>
> **Effect:** The target is [grabbed](../../../condition/grabbed.md) by the roughneck.

> ❗️ **Flying Sawblade**
>
> | **Melee** | **Triggered action** |
> | --- | ---:|
> | **📏 Self** | **🎯 Self** |
>
> **Trigger:** The roughneck is vertical force moved by another creature.
>
> **Effect:** The roughneck uses Haymaker against a creature or object at any point during the forced movement, or after falling as a result of it.
