---
agility: 4
ev: "72"
file_basename: gloom-dragon
file_dpath: monster/dragon/statblock
free_strike: 6
immunities:
    - Psychic 5
intuition: 3
item_id: gloom-dragon
item_name: Gloom Dragon
keywords:
    - Dragon
    - Elemental
level: 4
might: 2
movement: Fly, hover
name: Gloom Dragon
organization: Solo
presence: 4
reason: 1
scc: mcdm.monsters.v1/monster.dragon.statblock/gloom-dragon
size: "4"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "350"
type: statblock
---

|     Dragon, Elemental     |             -              |      Level 4       |         Solo          |        EV 72         |   
|:-------------------------:|:--------------------------:|:------------------:|:---------------------:|:--------------------:|   
|       **4**<br>Size       |       **8**<br>Speed       | **350**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |   
| **Psychic 5**<br>Immunity | **Fly, hover**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |   
|      **+2**<br>Might      |     **+4**<br>Agility      |  **+1**<br>Reason  |  **+3**<br>Intuition  |  **+4**<br>Presence  |

> ☠️ **[Solo](scc.v1:mcdm.monsters.v1/rule.organization/solo) Monster**
>
> **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

> ❇️ **Gloaming Wyrmscale Aura**
>
> The dragon's scales create a 3 aura of dark supernatural fog around them that feeds on their victims' fears and provides concealment to the dragon only. Each enemy who starts their turn in the area takes 2 psychic damage. Additionally, whenever one or more enemies is in the area, the dragon's abilities deal an extra 3 psychic damage.

> 🔳 **Breath of Brume (Signature Ability)**
>
> | **Area, Magic, Ranged** |                          **Main action** |
> |-------------------------|-----------------------------------------:|
> | **📏 4 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an **Agility test**.
>
> - **≤11:** 14 cold damage; the target is dragonsealed (save ends)
> - **12-16:** 11 cold damage; the target is dragonsealed (save ends)
> - **17+:** 6 cold damage
>
> A dragonsealed creature has psychic weakness 3 and cold weakness 3. Additionally, the area is filled with magical darkness. The dragon ignores concealment created by this darkness.

> 🗡 **Phantom Tail Swing**
>
> | **Charge, Magic, Melee, Strike** |                 **Main action** |
> |----------------------------------|--------------------------------:|
> | **📏 Melee 3**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 psychic damage; pull 2
> - **12-16:** 15 psychic damage; pull 4
> - **17+:** 18 psychic damage; pull 6
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The pull becomes a vertical slide.

> ⭐️ **Shadow Skulk**
>
> Once per turn, the dragon can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed, leaving behind a 4 cube area of magical darkness in their starting space that lasts until the end of the encounter. The dragon ignores concealment created by this darkness. Any enemy who ends their turn in the area and has I < 3 is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the dragon until the end of their next turn.

> ❇️ **Visions in the Dark (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |                  **Maneuver** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target takes 3 psychic damage, and if they have I < 3 they immediately make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against one ally of the dragon's choice.

> ❗️ **Encroaching Darkness (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Free triggered action** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** A creature within 10 squares moves.
>
> **Effect:** The dragon moves two existing cubes of magical darkness they created up to 10 squares each.

> ☠️ **Enveloping Umbrage ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** Pull 2; I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT)
> - **12-16:** Pull 4; I < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** Pull 6; I < 4 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)

> ☠️ **Pall of Nightmares ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 psychic damage
> - **12-16:** 11 psychic damage
> - **17+:** 14 psychic damage
>
> **Effect:** Each target must be dragonsealed. Any target who has I < 3 is also [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends).

> ☠️ **Absence of All Light ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **-**          |          **-** |
> |----------------|---------------:
> | **📏 Special** | **🎯 Special** | 
>
> **Effect:** The dragon disappears from the encounter map. The dragon and three hallucinatory illusions of themself then immediately reappear in unoccupied spaces on the encounter map, and the dragon and each illusion uses Breath of Brume. Each illusion is indistinguishable from the dragon except by supernatural means, has 1 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), and has the dragon's speed. An illusion acts on the dragon's turns but can take only move actions. Once per round before or after using an ability, the dragon can trade places with any duplicate.
