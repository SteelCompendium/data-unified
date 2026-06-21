---
agility: 1
ev: "16"
file_basename: bugbear-commander
file_dpath: monster/bugbear/statblock
free_strike: 5
intuition: 0
item_id: bugbear-commander
item_name: Bugbear Commander
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 2
name: Bugbear Commander
organization: Elite
presence: 0
reason: 2
role: Support
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-commander
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "80"
type: statblock
---

| Bugbear, Fey, Goblin, Humanoid |         -         |      Level 2      |     Elite Support     |        EV 16         |
|:------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|         **1L**<br>Size         |  **5**<br>Speed   | **80**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|       **-**<br>Immunity        | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|        **+2**<br>Might         | **+1**<br>Agility | **+2**<br>Reason  |  **+0**<br>Intuition  |  **+0**<br>Presence  |

> 🗡 **Inspiring Swordplay (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 10 damage
> - **17+:** 13 damage; one target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** One ally within 5 squares of the commander gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on their next strike until the start of the commander's next turn.

> 🏹 **You Next!**
>
> | **Ranged**      | **Main Action** |
> |-----------------|----------------:|
> | **📏 Ranged 8** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and uses a signature ability.

> ❇️ **Fall Back! (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |              **Main Action** |
> |----------------|-----------------------------:|
> | **📏 5 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, then can use the Throw maneuver.

> 🗡 **Throw**
>
> | **Melee, Strike** |                  **Maneuver** |
> |-------------------|------------------------------:|
> | **📏 Melee 1**    | **🎯 One creature or object** |
>
> **Special:** The target must be [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the commander.
>
> **Effect:** The target is vertical [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 4 squares. An ally doesn't take damage from being [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) this way.

> ❗️ **Catcher**
>
> | **Melee**      |                **Free triggered action** |
> |----------------|-----------------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A size 1 creature or object is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) within distance, or a size 1 ally willingly moves within distance.
>
> **Effect:** The target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the commander.

> ⭐️ **The Commander's Watching**
>
> Any ally who has line of effect to the commander can end one condition on themself at the start of each of their turns.
