---
agility: 3
ev: 8 for four minions
file_basename: mindkiller-whelp
file_dpath: monster/voiceless-talker/statblock
free_strike: 3
immunities:
    - Psychic 6
intuition: 1
item_id: mindkiller-whelp
item_name: Mindkiller Whelp
keywords:
    - Horror
    - Voiceless Talker
level: 6
might: -1
movement: Fly, hover
name: Mindkiller Whelp
organization: Minion
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.voiceless-talker.statblock/mindkiller-whelp
size: 1S
source: mcdm.monsters.v1
speed: 4
stability: 0
stamina: "9"
type: statblock
with_captain: +2 damage bonus to strikes
---

| Horror, Voiceless Talker  |             -              |     Level 6      |                  Minion Hexer                  | EV 8 for four minions |
|:-------------------------:|:--------------------------:|:----------------:|:----------------------------------------------:|:---------------------:|
|      **1S**<br>Size       |       **4**<br>Speed       | **9**<br>Stamina |               **0**<br>Stability               | **3**<br>Free Strike  |
| **Psychic 6**<br>Immunity | **Fly, hover**<br>Movement |        -         | **+2 damage bonus to strikes**<br>With Captain |   **-**<br>Weakness   |
|      **-1**<br>Might      |     **+3**<br>Agility      | **+1**<br>Reason |              **+1**<br>Intuition               |   **0**<br>Presence   |

> 🗡 **Eager Claws ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                          **Main action** |
> |---------------------------|-----------------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object per minion** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 damage
> - **12-16:** 5 damage; the target takes a bane on their next strike
> - **17+:** 7 damage; the target takes a bane on their next strike

> ❗️ **Feast**
>
> | **Psionic** | **[Triggered Action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The whelp reduces a non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) creature to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
>
> **Effect:** The whelp transforms into a mindkiller whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equals their squad's [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) pool before transforming. The [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) pool then loses the whelp's [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Psionic Conductor**
>
> Whenever a non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) voiceless talker within 5 squares of the whelp uses a psionic ability, they can do so as if they were in the whelp's space.
