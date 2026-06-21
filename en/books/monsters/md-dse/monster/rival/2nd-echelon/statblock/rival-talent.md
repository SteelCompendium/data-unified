---
agility: 0
ev: "28"
file_basename: rival-talent
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 6
intuition: 0
item_id: rival-talent
item_name: Rival Talent
keywords:
    - Humanoid
    - Rival
level: 5
might: 0
name: Rival Talent
organization: Elite
presence: 1
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-talent
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "120"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 5       |      Elite Hexer      |        EV 28         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **0**<br>Might   | **0**<br>Agility  |  **+3**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Overwhelming Rend ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Psionic, Ranged, Strike, Telekinesis** |                 **Main action** |
> |------------------------------------------|--------------------------------:|
> | **📏 Ranged 10**                         | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 14 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 17 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)

> 🏹 **Disarrange Thoughts (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Psionic, Ranged, Telepathy** |                  **Maneuver** |
> |--------------------------------|------------------------------:|
> | **📏 Ranged 10**               | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 psychic damage; R < 1 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 6 psychic damage; R < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 6 psychic damage; R < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

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
