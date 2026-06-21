---
agility: 3
ev: "32"
file_basename: mindkiller
file_dpath: monster/voiceless-talker/statblock
free_strike: 7
immunities:
    - Psychic 6
intuition: 2
item_id: mindkiller
item_name: Mindkiller
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Fly, hover
name: Mindkiller
organization: Elite
presence: 0
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "140"
type: statblock
---

| Horror, Voiceless Talker  |             -              |      Level 6       |      Elite Hexer      |        EV 32         |
|:-------------------------:|:--------------------------:|:------------------:|:---------------------:|:--------------------:|
|      **1S**<br>Size       |       **6**<br>Speed       | **140**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
| **Psychic 6**<br>Immunity | **Fly, hover**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|      **-1**<br>Might      |     **+3**<br>Agility      |  **+3**<br>Reason  |  **+2**<br>Intuition  |  **0**<br>Presence   |

> ⭐️ **Brain Latch**
>
> The mindkiller can [grab](scc.v1:mcdm.heroes.v1/condition/grabbed) creatures who are size 4 or smaller, using their Reason score in place of Might. A creature [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the mindkiller takes a bane on ability rolls made to escape the grab.

> 🗡 **Killer Claws ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 11 damage
> - **12-16:** 17 damage; A < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 21 damage; A < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)

> 🏹 **Concealing Strike (2 Malice)**
>
> | **Psionic, Ranged, Strike** |      **Main action** |
> |-----------------------------|---------------------:|
> | **📏 Ranged 5**             | **🎯 Two creatures** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage; R < 1 the mindkiller is invisible to the target (save ends)
> - **12-16:** 15 damage; R < 2 the mindkiller is invisible to the target (save ends)
> - **17+:** 18 damage; R < 3 the mindkiller is invisible to the target (save ends)

> 🗡 **Mindwipe**
>
> | **Melee, Psionic, Strike** |        **Maneuver** |
> |----------------------------|--------------------:|
> | **📏 Melee 1**             | **🎯 One creature** |
>
> **Effect:** The target must be [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the mindkiller. If the target has R < 2, they take a −1 penalty to their Reason, Intuition, or Presence score and the mindkiller has a +1 bonus to the same score, all until the end of the encounter.

> ❗️ **Meat Shield**
>
> | **-**       | **[Triggered Action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The mindkiller takes damage.
>
> **Effect:** The mindkiller halves the damage. If the mindkiller has a creature [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), that creature takes the other half of the damage.
>
> **3 Malice:** A [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) creature takes the damage instead of the mindkiller.

> ⭐️ **Psionic Conductor**
>
> Whenever a non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) voiceless talker within 5 squares of the mindkiller uses a psionic ability, they can do so as if they were in the mindkiller's space.

> ⭐️ **Nimble**
>
> The mindkiller can move through enemies' spaces at their usual speed.
