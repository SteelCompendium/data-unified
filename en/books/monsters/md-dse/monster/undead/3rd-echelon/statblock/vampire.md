---
agility: 2
ev: "9"
file_basename: vampire
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: vampire
item_name: Vampire
keywords:
    - Undead
    - Vampire
level: 7
might: 4
movement: Climb
name: Vampire
organization: Horde
presence: 1
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/vampire
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: "40"
type: statblock
---

|            Undead, Vampire             |           -           |      Level 7      |      Horde Hexer      |         EV 9         |
|:--------------------------------------:|:---------------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |    **6**<br>Speed     | **40**<br>Stamina |  **3**<br>Stability   | **3**<br>Free Strike |
| **Corruption 7, poison 7**<br>Immunity | **Climb**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+4**<br>Might             |   **+2**<br>Agility   | **+1**<br>Reason  |  **+1**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Exsanguinating Bite ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 10 corruption damage; M < 3 5 corruption damage and [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 11 corruption damage; M < 4 7 corruption damage and [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** The vampire regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to any corruption damage dealt.

> 🗡 **Vicious Pursuit (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; A < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 10 damage; A < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 11 damage; A < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** If the target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), the vampire [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed before using this ability.

> ❗️ **Reactive Charm (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** | **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------------|---------------------:|
> | **📏 Ranged 5**   |     **🎯 One enemy** |
>
> **Trigger:** A creature makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the vampire.
>
> **Effect:** The target becomes the new target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).

> ⭐️ **Unslakable Bloodthirst**
>
> The vampire has speed 10 while any creature within 10 squares of them is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding). The vampire must make a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) creature on their turn if they are able to.
