---
agility: 2
ev: "6"
file_basename: wraith
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 2
immunities:
    - Corruption 4
    - poison 4
intuition: 1
item_id: wraith
item_name: Wraith
keywords:
    - Undead
level: 4
might: -2
movement: Fly, hover
name: Wraith
organization: Horde
presence: 3
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/wraith
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 1
stamina: "25"
type: statblock
---

|                 Undead                 |             -              |      Level 4      |      Horde Hexer      |         EV 6         |
|:--------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |       **8**<br>Speed       | **25**<br>Stamina |  **1**<br>Stability   | **2**<br>Free Strike |
| **Corruption 4, poison 4**<br>Immunity | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **-2**<br>Might             |     **+2**<br>Agility      | **+1**<br>Reason  |  **+1**<br>Intuition  |  **+3**<br>Presence  |

> 🗡 **Chilling Gravetouch ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Melee, Strike, Weapon** |               **Main action** |
> |----------------------------------|------------------------------:|
> | **📏 Melee 1**                   | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 cold damage; P < 1 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 7 cold damage; P < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 9 cold damage; P < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** Any living creature who dies from this damage rises at the start of the next round as a ghoul craver under the Director's control.

> 👤 **Hidden Movement**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The wraith turns invisible, moves up to their speed, and is visible again.

> ❗️ **Stolen Vitality (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |      **Free triggered action** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** An enemy within distance regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
>
> **Effect:** The target regains only half the [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), and the wraith regains the remaining [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ⭐️ **Agonizing Phasing**
>
> The wraith can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the wraith moves through a creature, that creature takes 5 corruption damage and takes a bane on their next strike. The wraith doesn't take damage from being [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into objects.
