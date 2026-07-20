---
agility: 2
ev: "44"
free_strike: 10
immunities:
    - Fire 9
intuition: 2
keywords:
    - Fire Giant
    - Giant
level: 9
might: 4
name: Fire Giant Red Fist
organization: Elite
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-red-fist
size: "4"
speed: 8
stability: 5
stamina: "240"
type: statblock
---

|   Fire Giant, Giant    |         -         |      Level 9       |      Elite Brute      |         EV 44         |
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:---------------------:|
|     **4**<br>Size      |  **8**<br>Speed   | **240**<br>Stamina |  **5**<br>Stability   | **10**<br>Free Strike |
| **Fire 9**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |   **-**<br>Weakness   |
|    **+4**<br>Might     | **+2**<br>Agility |  **0**<br>Reason   |  **+2**<br>Intuition  |  **+1**<br>Presence   |

> 🗡 **Flaming Punch (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 14 fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 19 fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; A < 3 burning (save ends)
> - **17+:** 23 fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6; A < 4 burning (save ends)
>
> **Effect:** A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

> ❇️ **Caldera (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |                          **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|-----------------------------------------:|
> | **📏 Special** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** The distance is a 2 burst; 8 fire damage; M < 2 [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** The distance is a 3 burst; 12 fire damage; M < 3 [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
> - **17+:** The distance is a 4 burst; 15 fire damage; M < 4 [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
>
> **Effect:** The outermost squares of the area become a 1-square-tall wall of stone. The rest of the area is on fire until the end of the encounter. A creature who enters the area for the first time in a round or starts their turn there takes 3 fire damage.

> 👤 **Blazing Leap**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The red fist jumps up to 5 squares. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them when they land takes 5 fire damage.

> ❗️ **Heat and Pressure**
>
> | **Melee**      |      **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|-------------------------------:|
> | **📏 Melee 3** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance willingly moves or [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) away from the red fist.
>
> **Effect:** The target makes a **Might test**. A target with fire immunity automatically obtains a tier 3 outcome.
>
> - **≤11:** [Weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** [Weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (EoT)
> - **17+:** No effect

> ❗️ **Guardian Block**
>
> | **Melee**      | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|---------------------:|
> | **📏 Melee 3** |          **🎯 Self** |
>
> **Trigger:** An ally within distance is targeted by an enemy's ability.
>
> **Effect:** The red fist becomes the target of the triggering ability, then can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the enemy after the ability resolves.

> ⭐️ **Searing Skin**
>
> Whenever an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy [grabs](scc.v1:mcdm.heroes.v1/condition/grabbed) the red fist or uses a melee ability against them, that enemy takes 5 fire damage.
