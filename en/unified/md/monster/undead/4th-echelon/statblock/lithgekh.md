---
agility: 1
ev: "12"
free_strike: 5
immunities:
    - Corruption 10
    - poison 10
intuition: 3
keywords:
    - Undead
    - Soulless
level: 10
might: 0
movement: Fly, hover
name: Lithgekh
organization: Horde
presence: -1
reason: 5
role: Hexer
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/lithgekh
size: 1M
speed: 6
stability: 1
stamina: "55"
type: statblock
---

|             Undead, Soulless             |             -              |     Level 10      |      Horde Hexer      |        EV 12         |
|:----------------------------------------:|:--------------------------:|:-----------------:|:---------------------:|:--------------------:|
|              **1M**<br>Size              |       **6**<br>Speed       | **55**<br>Stamina |  **1**<br>Stability   | **5**<br>Free Strike |
| **Corruption 10, poison 10**<br>Immunity | **Fly, hover**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|              **0**<br>Might              |     **+1**<br>Agility      | **+5**<br>Reason  |  **+3**<br>Intuition  |  **-1**<br>Presence  |

> 🏹 **Heartstopper ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 15**          | **🎯 One creature or object** |
>
> **Power Roll + 5:**
>
> - **≤11:** 9 corruption damage; I < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 12 corruption damage; I < 4 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 14 corruption damage; I < 5 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** A creature [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on any ability that targets [undead](scc.v1:mcdm.monsters.v1/rule.keyword/undead).

> ❗️ **Mystic Battery (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |      **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 20**  | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance uses a magic ability.
>
> **Effect:** Any damage dealt by or [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) regained from the ability is halved. The lithgekh regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to the remaining damage dealt or [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) gained.

> ⭐️ **Devour Magic**
>
> Each ally within 10 squares of the lithgekh gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on magic abilities.
