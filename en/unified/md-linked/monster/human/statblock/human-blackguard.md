---
agility: 2
ev: "12"
free_strike: 4
immunities:
    - Corruption 2
    - psychic 2
intuition: 0
keywords:
    - Human
    - Humanoid
level: 1
might: 3
name: Human Blackguard
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.human.statblock/human-blackguard
size: 1M
speed: 5
stability: 2
stamina: "80"
type: statblock
---

|             Human, Humanoid             |         -         |      Level 1      |        Leader         |        EV 12         |
|:---------------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size              |  **5**<br>Speed   | **80**<br>Stamina |  **2**<br>Stability   | **4**<br>Free Strike |
| **Corruption 2, psychic 2**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|             **+3**<br>Might             | **+2**<br>Agility | **+2**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> ❇️ **Zweihander Swing (Signature Ability)**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
> - **12-16:** 6 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
> - **17+:** 8 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
>
> **Effect:** One ally within 10 squares can make a [free strike](../../../feature/common/main-actions/free-strike.md).
>
> **1 [Malice](../../../rule/monster/malice.md):** One ally within 10 squares can use their [signature ability](../../../rule/combat/signature-ability.md) instead.

> 🏹 **You!**
>
> | **Ranged**       |     **Maneuver** |
> |------------------|-----------------:|
> | **📏 Ranged 10** | **🎯 One enemy** |
>
> **Effect:** The target is marked until the start of the blackguard's next turn. The blackguard and each of their allies gain an edge on abilities used against targets marked by the blackguard.

> ⭐️ **[End Effect](../../../rule/monster/end-effect.md)**
>
> At the end of each of their turns, the blackguard can take 5 damage to end one effect on them that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.

> ⭐️ **Supernatural Insight**
>
> The blackguard ignores concealment if it's granted by a supernatural effect.

> ❗️ **Parry!**
>
> | **Melee**      |    **Triggered action** |
> |----------------|------------------------:|
> | **📏 Melee 1** | **🎯 Self or one ally** |
>
> **Trigger:** A creature makes a strike against the blackguard or an ally [adjacent](../../../rule/combat/adjacent.md) to them.
>
> **Effect:** The damage is halved.

> ☠️ **Advance! ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **-**       |       **-** | 
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The blackguard [shifts](../../../movement/shifting.md) up to their speed. During or after this movement, they can use their Zweihander Swing twice.

> ☠️ **Back! ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** The blackguard [slides](../../../movement/forced-movement.md) each target up to 5 squares.

> ☠️ **I Can Throw My Blade and So Should You! ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Magic, Ranged, Weapon** |                         **-** |
> |---------------------------------|------------------------------:|
> | **📏 3 cube within 5**          | **🎯 Each enemy in the area** |
>
> **Effect:** The blackguard uses their Zweihander Swing against each target. Each ally within 5 squares of the area can then make a [free strike](../../../feature/common/main-actions/free-strike.md) against a target (one target per ally).
