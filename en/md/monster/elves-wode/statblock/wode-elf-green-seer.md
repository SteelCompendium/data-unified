---
agility: 1
ev: "6"
free_strike: 3
intuition: 2
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
might: 0
name: Wode Elf Green Seer
organization: Platoon
presence: 1
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.elves-wode.statblock/wode-elf-green-seer
size: 1M
speed: 7
stability: 0
stamina: "20"
type: statblock
---

| Fey, Humanoid, Wode Elf |         -         |      Level 1      |     Platoon Hexer     |         EV 6         |
|:-----------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size      |  **7**<br>Speed   | **20**<br>Stamina |  **0**<br>Stability   | **3**<br>Free Strike |
|    **-**<br>Immunity    | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|     **0**<br>Might      | **+1**<br>Agility |  **0**<br>Reason  |  **+2**<br>Intuition  |  **+1**<br>Presence  |

> 🏹 **The Forest's Embrace (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 7 damage; I < 1 [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** 9 damage; I < 2 [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** While [restrained](scc:mcdm.heroes.v1/condition/restrained) this way, a target can't search for hidden creatures.

> 🏹 **The Natural Cycle (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged, Strike** |         **Maneuver** |
> |---------------------------|---------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures** |
>
> **Power Roll + 2:**
>
> - **≤11:** 2 damage
> - **12-16:** 4 damage; P < 1 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 6 damage; P < 1 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends); the target has a double bane on strikes (save ends)
>
> **Effect:** While [bleeding](scc:mcdm.heroes.v1/condition/bleeding) or [weakened](scc:mcdm.heroes.v1/condition/weakened) this way, a target is covered in lichen.

> ❗️ **Foreseen Punishment**
>
> | **Ranged**      |      **Free triggered action** |
> |-----------------|-------------------------------:|
> | **📏 Ranged 5** | **🎯 The triggering creature** |
>
> **Trigger:** A creature uses a triggered action targeting the green seer or an ally within distance.
>
> **Effect:** The green seer makes a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target after the target's triggered action is resolved.

> ⭐️ **Masking Glamor**
>
> Abilities targeting the green seer that would take a bane from cover or concealment have a double bane instead.
