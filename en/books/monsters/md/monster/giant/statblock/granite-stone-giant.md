---
agility: 1
ev: "40"
free_strike: 8
intuition: 2
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Granite Stone Giant
organization: Elite
presence: 1
reason: 1
role: Defender
scc: mcdm.monsters.v1/monster.giant.statblock/granite-stone-giant
size: "4"
speed: 7
stability: 10
stamina: "247"
type: statblock
---

| Giant, Stone Giant |           -            |      Level 8       |    Elite Defender     |        EV 40         |
|:------------------:|:----------------------:|:------------------:|:---------------------:|:--------------------:|
|   **4**<br>Size    |     **7**<br>Speed     | **247**<br>Stamina |  **10**<br>Stability  | **8**<br>Free Strike |
| **-**<br>Immunity  | **Burrow**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+4**<br>Might   |   **+1**<br>Agility    |  **+1**<br>Reason  |  **+2**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Jagged Stone Club (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage
> - **12-16:** 17 damage; R < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 21 damage; R < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **Effect:** If the target is already [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), they are also [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).

> ❇️ **Crag Burst (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |                          **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|-----------------------------------------:|
> | **📏 2 burst** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
> - **17+:** 14 damage; vertical [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
>
> **Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain). Whenever a creature enters square in the area, they take 3 damage.

> 👤 **Castle Stone Shape**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The granite stone giant moves up to their speed and creates a 14 wall of stone in squares [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the path of their movement.

> ❗️ **Pillar**
>
> | **Melee**      |                     **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 3** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) away from the granite stone giant.
>
> **Effect:** A 1-square pillar of stone rises 5 squares out of the ground beneath the target, who moves with the ground to its new elevation, then is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 squares.

> ⭐️ **Stonebreaker Flesh**
>
> Whenever an enemy obtains a tier 1 outcome on a melee ability used against the granite stone giant, they take a bane on that ability until the end of the encounter.

> ⭐️ **Stone Steps**
>
> The granite stone giant ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> ⭐️ **Stone Swim**
>
> The granite stone giant can [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) through stone, but can't drag other creatures underground when they do so.
