---
agility: 4
ev: "84"
free_strike: 8
intuition: 0
keywords:
    - Accursed
    - Humanoid
    - Medusa
level: 5
might: 2
name: Medusa
organization: Solo
presence: 0
reason: 0
scc: mcdm.monsters.v1/monster.medusa.statblock/medusa
size: 1M
speed: 10
stability: 5
stamina: "420"
type: statblock
---

| Accursed, Humanoid, Medusa |         -         |       Level 5       |         Solo          |        EV 84         |
|:--------------------------:|:-----------------:|:-------------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size       |  **10**<br>Speed  |  **420**<br>Stamina |  **5**<br>Stability   | **8**<br>Free Strike |
|     **-**<br>Immunity      | **-**<br>Movement |          -          | **-**<br>With Captain |  **-**<br>Weakness   |
|      **+2**<br>Might       | **+4**<br>Agility |   **0**<br>Reason   |  **0**<br>Intuition   |  **0**<br>Presence   |

> ☠️ **Solo Monster**
>
> [**End Effect:**](scc.v1:mcdm.monsters.v1/rule.monster/end-effect) At the end of each of their turns, the medusa can take 10 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
>
> **Solo Turns:** The medusa can take two turns each round. They can't take turns consecutively.

> 🗡 **Snake Bites ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 16 damage; M < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 19 damage; M < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

> 🏹 **Damning Gaze ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Ranged, Strike** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **12-16:** 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
> - **17+:** 19 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The medusa targets two additional creatures or objects.

> ❇️ **Petrify (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** M < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** M < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** [Slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends); or if M < 4 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** A target with cover reduces the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1, while a [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) target increases the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1. A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way magically begins to turn to stone, and a target who ends two consecutive turns [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way is petrified.

> 👤 **Nimble Escape**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The medusa [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares and can attempt to hide even if observed.

> ❗️ **Venomous Spit (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee**      |           **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the medusa.
>
> **Power Roll + 4:**
>
> - **≤11:** 13 acid damage
> - **12-16:** 18 acid damage
> - **17+:** 22 acid damage

> ⭐️ **Cunning Edge**
>
> The medusa gains an edge on power rolls against any creature who is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) or [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by Petrify.

> ⭐️ **Many Peering Eyes**
>
> The medusa can't be flanked.

> ☠️ **Mass Petrify ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Magic, Ranged** |             **-** |
> |-------------------|------------------:|
> | **📏 Ranged 50**  | **🎯 Each enemy** |
>
> **Effect:** The medusa can use Petrify against each target without spending [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice). A target who doesn't have cover increases the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) by 1.

> ☠️ **Serpent Wings ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The medusa temporarily manifests wings and [flies](scc.v1:mcdm.heroes.v1/movement/fly) up to their speed without provoking opportunity attacks. During or after this movement, they can use Snake Bites and Damning Gaze once each.

> ☠️ **Stone Puppets ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area, Magic** |          **-** |
> |-----------------|---------------:|
> | **📏 10 burst** | **🎯 Special** |
>
> **Power Roll + 4:**
>
> - **≤11:** 8 acid damage; P < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **12-16:** 13 acid damage; P < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 17 acid damage; P < 5 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **Effect:** As a free triggered action, each stone statue and creature [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) or [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) by Petrify within distance moves up to their speed and uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an edge, targeting an enemy of the medusa's choice. A stone statue without its own statistics has speed 5 and uses the medusa's [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
