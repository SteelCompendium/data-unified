---
agility: 3
ev: "20"
free_strike: 5
immunities:
    - Corruption 4
    - psychic 4
intuition: 3
keywords:
    - Human
    - Humanoid
level: 3
might: 2
name: Human Bandit Chief
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.human.statblock/human-bandit-chief
size: 1M
speed: 5
stability: 2
stamina: "120"
type: statblock
---

|             Human, Humanoid             |         -         |      Level 3       |        Leader         |        EV 20         |
|:---------------------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size              |  **5**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **Corruption 4, psychic 4**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|             **+2**<br>Might             | **+3**<br>Agility |  **+2**<br>Reason  |  **+3**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Whip and Magic Longsword (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------------------------|------------------------------:|
> | **📏 Melee 2**                   | **🎯 Two enemies or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 12 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 15 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
>
> **Effect:** Any target who is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the bandit chief after the power roll is resolved takes 3 corruption damage.
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** This ability targets one additional target.

> 🗡 **Kneel, Peasant!**
>
> | **Melee**      |     **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|-----------------:|
> | **📏 Melee 1** | **🎯 One enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** [Push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The ability takes the Area keyword, loses the Melee keyword, and is a 1 burst that targets each enemy in the area.

> ❗️ **Bloodstones**
>
> | **Magic**   | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The bandit chief makes a power roll.
>
> **Effect:** The bandit chief takes 5 corruption damage and increases the outcome of the power roll by one tier. This damage can't be reduced in any way.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the bandit chief can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ⭐️ **Supernatural Insight**
>
> The bandit chief ignores concealment if it's granted by a supernatural effect.

> ☠️ **Shoot! ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**        |                                  **-** |
> |-----------------|---------------------------------------:|
> | **📏 10 burst** | **🎯 Each artillery ally in the area** |
>
> **Effect:** Each target makes a ranged [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).

> ☠️ **Form Up! ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area**        |                        **-** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed. Additionally, until the end of the encounter, while the bandit chief or any ally is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a target, they have damage immunity 2.

> ☠️ **Lead From the Front ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The bandit chief [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 10 squares regardless of their speed. During or after this movement, they can use their Whip and Magic Longsword against up to four targets. Additionally, one ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to each target can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that target.
