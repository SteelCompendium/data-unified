---
agility: 2
ev: "9"
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
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

> 🗡 **Exsanguinating Bite ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
> - **12-16:** 10 corruption damage; M < 3 5 corruption damage and [bleeding](../../../../condition/bleeding.md) (save ends)
> - **17+:** 11 corruption damage; M < 4 7 corruption damage and [bleeding](../../../../condition/bleeding.md) (save ends)
>
> **Effect:** The vampire regains [Stamina](../../../../rule/health/stamina.md) equal to any corruption damage dealt.

> 🗡 **Vicious Pursuit (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; A < 2 [slowed](../../../../condition/slowed.md) (save ends)
> - **12-16:** 10 damage; A < 3 [slowed](../../../../condition/slowed.md) (save ends)
> - **17+:** 11 damage; A < 4 [slowed](../../../../condition/slowed.md) (save ends)
>
> **Effect:** If the target is [bleeding](../../../../condition/bleeding.md), the vampire [shifts](../../../../movement/shifting.md) up to their speed before using this ability.

> ❗️ **Reactive Charm (2 [Malice](../../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** | **[Triggered action](../../../../rule/combat/triggered-action.md)** |
> |-------------------|---------------------:|
> | **📏 Ranged 5**   |     **🎯 One enemy** |
>
> **Trigger:** A creature makes a [strike](../../../../rule/combat/strike.md) against the vampire.
>
> **Effect:** The target becomes the new target of the [strike](../../../../rule/combat/strike.md).

> ⭐️ **Unslakable Bloodthirst**
>
> The vampire has speed 10 while any creature within 10 squares of them is [bleeding](../../../../condition/bleeding.md). The vampire must make a [strike](../../../../rule/combat/strike.md) against a [bleeding](../../../../condition/bleeding.md) creature on their turn if they are able to.
