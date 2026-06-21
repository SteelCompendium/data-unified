---
agility: 0
ev: "10"
file_basename: human-storm-mage
file_dpath: monster/human/statblock
free_strike: 5
immunities:
    - Corruption 3
    - psychic 3
intuition: 0
item_id: human-storm-mage
item_name: Human Storm Mage
keywords:
    - Human
    - Humanoid
level: 3
might: 0
name: Human Storm Mage
organization: Platoon
presence: 1
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.human.statblock/human-storm-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "40"
type: statblock
---

|             Human, Humanoid             |         -         |      Level 3      |  Platoon Controller   |        EV 10         |
|:---------------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size              |  **5**<br>Speed   | **40**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
| **Corruption 3, psychic 3**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|             **0**<br>Might              | **0**<br>Agility  | **+2**<br>Reason  |  **0**<br>Intuition   |  **+1**<br>Presence  |

> 🏹 **Lightning Bolt (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 15**          | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 lightning damage
> - **12-16:** 10 lightning damage
> - **17+:** 13 lightning damage
>
> **5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The ability loses the Ranged and Strike keywords, takes the Area keyword, and is a 10 x 1 line within 15 that targets each enemy and object in the area.

> 🔳 **Gust of Wind (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic**        |                             **Maneuver** |
> |------------------------|-----------------------------------------:|
> | **📏 5 cube within 1** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** [Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 0 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** [Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** [Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** The gust of wind disperses gas or vapor and extinguishes any flames, including supernatural effects.

> ⭐️ **Arcane Shield**
>
> Any melee ability targeting the storm mage takes a bane.
>
> Additionally, whenever the mage takes damage from an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy, the enemy takes 2 lightning damage, and if they have R < 1 they are [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 2 squares.

> ⭐️ **Supernatural Insight**
>
> The storm mage ignores concealment if it's granted by a supernatural effect.
