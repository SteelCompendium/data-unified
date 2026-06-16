---
agility: 3
ev: "12"
free_strike: 2
intuition: 0
keywords:
    - Kobold
    - Humanoid
level: 1
might: 2
name: Kobold Centurion
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-centurion
size: 1S
speed: 5
stability: 2
stamina: "80"
type: statblock
---

| Kobold, Humanoid  |         -         |      Level 1      |        Leader         |        EV 12         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1S**<br>Size   |  **5**<br>Speed   | **80**<br>Stamina |  **2**<br>Stability   | **2**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+3**<br>Agility | **+2**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> ⚔️ **Pilum (Signature Ability)**
>
> | **Melee, Ranged, Strike, Weapon** |                 **Main action** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 10**       | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; M < 1 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **12-16:** 10 damage; M < 1 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 13 damage; M < 1 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **Effect:** Each ally [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to a target can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against that target.
>
> **3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** While [weakened](scc:mcdm.heroes.v1/condition/weakened) this way, a target is also [restrained](scc:mcdm.heroes.v1/condition/restrained).

> 🏹 **Concentrate All Fire on That Hero!**
>
> | **Ranged**       |     **Maneuver** |
> |------------------|-----------------:|
> | **📏 Ranged 10** | **🎯 One enemy** |
>
> **Effect:** Until the start of the centurion's next turn, the centurion and their allies gain an edge on power rolls against the target.

> ❗️ **Testudo!**
>
> | **Area**       |         **Triggered action** |
> |----------------|-----------------------------:|
> | **📏 5 burst** | **🎯 Each ally in the area** |
>
> **Trigger:** A creature uses an ability that targets the centurion or an ally of the centurion within distance.
>
> **Effect:** Each target [shifts](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before the damage is resolved. Each kobold with the Shield? Shield! trait gains damage immunity 2 against the triggering ability.

> ⭐️ **[End Effect](scc:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the centurion can take 5 damage to end one effect on them that can be ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ☠️ **Firetail Pilum ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **-**          |          **-** |
> |----------------|---------------:|
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** The centurion moves up to their speed, ignoring [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain), and uses Pilum against each creature whose space they move through. They make one power roll against all targets, and the ability deals an extra 5 damage. While [weakened](scc:mcdm.heroes.v1/condition/weakened) by that ability, each target takes 2 fire damage at the start of each of their turns.

> ☠️ **Boom Pilum! ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area, Weapon, Ranged** |                         **-** |
> |--------------------------|------------------------------:|
> | **📏 5 cube within 10**  | **🎯 Each enemy in the area** |
>
> **Effect:** The centurion uses Pilum against each target and has a double edge. Each target is then [pushed](scc:mcdm.heroes.v1/movement/forced-movement) up to 3 squares.

> ☠️ **Are You Not Entertained?! ([Villain Action](scc:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area**        |                         **-** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** A target who has P < 2 is [taunted](scc:mcdm.heroes.v1/condition/taunted) (save ends). Each ally within distance can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike). Additionally, until the end of the encounter, the centurion has damage immunity 2.

> ⭐️ **Shield? Shield!**
>
> While [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to an ally who also has this trait, the centurion has stability 3, has cover, and grants cover to allies.
