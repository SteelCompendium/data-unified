---
agility: 0
ev: "16"
file_basename: rival-talent
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 0
item_id: rival-talent
item_name: Rival Talent
keywords:
    - Humanoid
    - Rival
level: 2
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-talent
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "60"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 2      |      Elite Hexer      |        EV 16         |
|:-----------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **60**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|  **0**<br>Might   | **0**<br>Agility  | **+2**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Reverberating Blast ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Psionic, Ranged, Strike, Telekinesis** |                 **Main action** |
> |------------------------------------------|--------------------------------:|
> | **📏 Ranged 10**                         | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 psychic damage; M < 0 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 10 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 13 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> 🏹 **Muddle the Mind (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Psionic, Ranged, Telepathy** |                  **Maneuver** |
> |--------------------------------|------------------------------:|
> | **📏 Ranged 10**               | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** R < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** R < 1 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** R < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

> ❗️ **Precognitive Shift (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Psionic** | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature deals damage to the talent.
>
> **Effect:** The talent halves the damage and [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the talent chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the talent and the creature can add a d3 roll to power rolls they make against each other.
