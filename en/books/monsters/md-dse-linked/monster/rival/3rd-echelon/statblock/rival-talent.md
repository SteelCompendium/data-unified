---
agility: 0
ev: "40"
file_basename: rival-talent
file_dpath: monster/rival/3rd-echelon/statblock
free_strike: 8
intuition: 0
item_id: rival-talent
item_name: Rival Talent
keywords:
    - Humanoid
    - Rival
level: 8
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 4
role: Hexer
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-talent
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "180"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 8       |      Elite Hexer      |        EV 40         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **180**<br>Stamina |  **2**<br>Stability   | **8**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **0**<br>Might   | **0**<br>Agility  |  **+4**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Control Synapses ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Psionic, Ranged, Strike, Telekinesis** |                 **Main action** |
> |------------------------------------------|--------------------------------:|
> | **📏 Ranged 10**                         | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 psychic damage
> - **12-16:** 17 psychic damage
> - **17+:** 21 psychic damage
>
> **3 [Malice](../../../../rule/monster/malice.md):** Each target [shifts](../../../../movement/shifting.md) up to their speed and can make a [free strike](../../../../feature/common/main-actions/free-strike.md) against one enemy of the talent's choice. The target can't be moved in a way that would harm them.

> 🏹 **Disorientate (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Psionic, Ranged, Telepathy** |                  **Maneuver** |
> |--------------------------------|------------------------------:|
> | **📏 Ranged 10**               | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 8 psychic damage; R < 2 [dazed](../../../../condition/dazed.md) (save ends)
> - **12-16:** 8 psychic damage; R < 3 [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)
> - **17+:** 8 psychic damage; R < 4 [dazed](../../../../condition/dazed.md) and [slowed](../../../../condition/slowed.md) (save ends)

> ❗️ **Mind Requital (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Psionic** | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature deals damage to the talent.
>
> **Effect:** The talent halves the damage and [shifts](../../../../movement/shifting.md) up to 2 squares. The triggering creature takes psychic damage equal to half the damage dealt.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the talent chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the talent and the creature can add a d3 roll to power rolls they make against each other.
