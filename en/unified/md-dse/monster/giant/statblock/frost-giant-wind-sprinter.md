---
agility: 4
ev: "40"
file_basename: frost-giant-wind-sprinter
file_dpath: monster/giant/statblock
free_strike: 8
immunities:
    - Cold 8
intuition: 0
item_id: frost-giant-wind-sprinter
item_name: Frost Giant Wind Sprinter
keywords:
    - Frost Giant
    - Giant
level: 8
might: 4
name: Frost Giant Wind Sprinter
organization: Elite
presence: 0
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-wind-sprinter
size: "4"
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: "200"
type: statblock
---

|   Frost Giant, Giant   |         -         |      Level 8       |     Elite Harrier     |        EV 40         |
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|     **4**<br>Size      |  **10**<br>Speed  | **200**<br>Stamina |  **5**<br>Stability   | **8**<br>Free Strike |
| **Cold 8**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+4**<br>Might     | **+4**<br>Agility |  **-1**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Cold Axe (Signature Ability)**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 3**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage
> - **12-16:** 17 damage; A < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 21 damage; A < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** A target who is already [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) takes an extra 1d6 cold damage.

> 👤 **Blizzard Surge (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Main action** |
> |-------------|----------------:|
> | **📏 Self** |     **🎯 Self** |
>
> **Effect:** The wind sprinter [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and uses Cold Axe against each enemy who comes within 2 squares of them during the move. The wind sprinter makes one power roll against all targets.

> 🗡 **Ice Dance**
>
> | **Melee**      |          **Maneuver** |
> |----------------|----------------------:|
> | **📏 Melee 1** | **🎯 One giant ally** |
>
> **Effect:** The wind sprinter and the target each [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 6 squares while staying [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to each other. The target can then jump up to 5 squares and make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).

> ❗️ **Begone, Smallfolk!**
>
> | **-**       | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The wind sprinter takes damage.
>
> **Effect:** The wind sprinter moves up to their speed and uses Cold Axe against one target.

> ⭐️ **Crush Underfoot**
>
> The wind sprinter can move through enemies' spaces at their usual speed. The first time on a turn that a wind sprinter enters a creature's space, that creature can choose to fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) or to take 8 damage.

> ⭐️ **Kingdom of Isolation**
>
> The wind sprinter is surrounded by a snowstorm. Any enemy who starts their turn within 2 squares of the wind sprinter can't [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
