---
agility: 2
ev: "10"
free_strike: 5
intuition: -1
keywords:
    - Humanoid
    - Orc
level: 3
might: 2
name: Orc Juggernaut
organization: Platoon
presence: 2
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.orcs.statblock/orc-juggernaut
size: 1L
speed: 6
stability: 0
stamina: "60"
type: statblock
---

|   Humanoid, Orc   |         -         |      Level 3      |     Platoon Brute     |        EV 10         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1L**<br>Size   |  **6**<br>Speed   | **60**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+2**<br>Agility | **-1**<br>Reason  |  **-1**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Haymaker Greataxe ([Signature Ability](scc:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
> - **17+:** 14 damage; [prone](scc:mcdm.heroes.v1/condition/prone); M < 2 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** A target who is already [prone](scc:mcdm.heroes.v1/condition/prone) takes an extra 6 damage.

> ❗️ **Hrraaaaaagh! (1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Free triggered action** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** The juggernaut takes damage.
>
> **Effect:** The juggernaut moves up to their speed and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike).

> ⭐️ **Blood in the Water**
>
> Whenever the juggernaut willingly moves, they can move 3 additional squares if they end their movement closer to a [prone](scc:mcdm.heroes.v1/condition/prone) creature.

> ⭐️ **Relentless**
>
> If the juggernaut is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), they can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying. If the target of the free strike is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), the juggernaut is reduced to 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) instead.
