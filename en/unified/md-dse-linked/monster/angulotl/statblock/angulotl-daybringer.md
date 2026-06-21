---
agility: 2
ev: "12"
file_basename: angulotl-daybringer
file_dpath: monster/angulotl/statblock
free_strike: 4
immunities:
    - Poison 3
intuition: 2
item_id: angulotl-daybringer
item_name: Angulotl Daybringer
keywords:
    - Angulotl
    - Humanoid
level: 1
might: 3
movement: Climb, swim
name: Angulotl Daybringer
organization: Leader
presence: 0
reason: 0
scc: mcdm.monsters.v1/monster.angulotl.statblock/angulotl-daybringer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "80"
type: statblock
---

|    Angulotl, Humanoid    |              -              |      Level 1      |        Leader         |        EV 12         |
|:------------------------:|:---------------------------:|:-----------------:|:---------------------:|:--------------------:|
|      **1M**<br>Size      |       **5**<br>Speed        | **80**<br>Stamina |  **1**<br>Stability   | **4**<br>Free Strike |
| **Poison 3**<br>Immunity | **Climb, swim**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+3**<br>Might      |      **+2**<br>Agility      | **+0**<br>Reason  |  **+2**<br>Intuition  |  **+0**<br>Presence  |

> 🗡 **Acid Grasp (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |  
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 acid damage; A < 1 [dazed](../../../condition/dazed.md) (save ends)
> - **12-16:** 10 acid damage; A < 2 [dazed](../../../condition/dazed.md) (save ends)
> - **17+:** 13 acid damage; A < 3 [dazed](../../../condition/dazed.md) (save ends)
>
> **Effect:** The next time the target makes a strike against the daybringer, the target takes 4 acid damage after the strike is resolved.
>
> **1 [Malice](../../../rule/monster/malice.md):** The daybringer jumps up to 3 squares before or after using this ability.

> 👤 **Sun Lamp**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The daybringer expands their throat to make it resemble the sun until the start of their next turn. During that time, each angulotl who starts their turn within 10 squares of the daybringer regains 5 [Stamina](../../../rule/health/stamina.md) and gains a +3 bonus to speed until the end of their turn.

> ❗️ **Tongue Slap**
>
> | **Melee**      |             **Triggered action** |
> |----------------|---------------------------------:|
> | **📏 Melee 5** |              **🎯 One creature** |
>
> **Trigger:** The target makes a strike against the daybringer or an ally that isn't a critical hit.
>
> **Effect:** The outcome of the strike's power roll is reduced by one tier.
>
> **2 [Malice](../../../rule/monster/malice.md):** The target is [pulled](../../../movement/forced-movement.md) up to 4 squares after the strike resolves.

> ⭐️ **Moisturizing End Effect**
>
> At the end of each of the daybringer's turns, they can either take 5 damage or end the wet effect on an adjacent creature in order to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.

> ☠️ **New Dawn (Villain Action 1)**
>
> | **Ranged**       |          **-** |
> |------------------|---------------:|
> | **📏 Ranged 10** | **🎯 Special** |
>
> **Effect:** Four **angulotl pollywogs** erupt from the daybringer's back and waddle into unoccupied spaces within distance.

> ☠️ **Plague of Frogs (Villain Action 2)**
>
> | **Area**       |                                 **-** |
> |----------------|--------------------------------------:|
> | **📏 8 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target can jump up to 4 squares. Each non-[minion](../../../rule/organization/minion.md) target can make a [free strike](../../../feature/common/main-actions/free-strike.md) at the end of the jump.

> ☠️ **It Is Day (Villain Action 3)**
>
> | **-**          |          **-** |
> |----------------|---------------:|
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** The encounter map dries up and each enemy and object on it is illuminated until the end of the encounter. An illuminated creature or object can't hide or become invisible, and any strike made against an illuminated target gains an [edge](../../../rule/dice/edge.md). Additionally, each enemy in the encounter who is wet has that effect end and takes 6 acid damage. Each angulotl in the encounter has a double edge on their next strike.

> ⭐️ **Toxiferous**
>
> Whenever an adjacent enemy [grabs](../../../feature/common/maneuvers/grab.md) the daybringer or uses a melee ability against them, that enemy takes 3 poison damage.
