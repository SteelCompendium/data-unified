---
agility: 2
ev: "20"
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
might: 3
name: War Dog Ground Commander
organization: Leader
presence: 2
reason: 3
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-ground-commander
size: 1M
speed: 5
stability: 2
stamina: "120"
type: statblock
---

| Humanoid, Soulless, War Dog |         -         |      Level 3       |        Leader         |        EV 20         |
|:---------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |  **5**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
|      **-**<br>Immunity      | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+3**<br>Might       | **+2**<br>Agility |  **+3**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> ⚔️ **Conditioning Spear ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Psionic, Ranged, Strike** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 5**         | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 12 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 15 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
>
> **Effect:** One ally within 10 squares of the ground commander can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
>
> **1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** A target who has I < 2 and who is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the ground commander after this ability is resolved is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) (save ends). This grab can't be escaped using the Escape Grab maneuver. The ground commander can grab up to two creatures at a time.

> ❇️ **Highest Posthumous Promotion**
>
> | **Area, Magic** |                    **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|--------------------------------:|
> | **📏 10 burst** | **🎯 Each war dog in the area** |
>
> **Effect:** Any target who has a loyalty collar is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ❗️ **Final Orders**
>
> | **Magic, Ranged** | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------------|---------------------:|
> | **📏 Ranged 10**  |      **🎯 One ally** |
>
> **Trigger:** The target takes damage, is [forced moved](scc.v1:mcdm.heroes.v1/movement/forced-movement), or is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
>
> **Effect:** Even if reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the target moves up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) after the triggering effect is resolved. The target then immediately dies.

> ⭐️ **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect)**
>
> At the end of each of their turns, the ground commander can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.

> ⭐️ **Loyalty Collar**
>
> When the ground commander is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.

> ☠️ **Combined Arms ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**        |                        **-** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target can make a ranged [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike), then immediately use the Charge main action.

> ☠️ **Make an Example of Them ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Magic, Ranged** |            **-** |
> |-------------------|-----------------:|
> | **📏 Ranged 10**  | **🎯 One enemy** |
>
> **Effect:** Each ally within 5 squares of the target moves up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target. If the target has I < 2, they are [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the ground commander (save ends).

> ☠️ **Claim Them for the Body Banks ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area, Magic** |                            **-** |
> |-----------------|---------------------------------:|
> | **📏 10 burst** | **🎯 Each creature in the area** |
>
> **Effect:** Each target ally [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and can use the Grab maneuver. Until the end of the encounter, each target enemy takes a bane on the Escape Grab maneuver.
