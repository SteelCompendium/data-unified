---
agility: 2
ev: "32"
free_strike: 7
immunities:
    - Poison 6
intuition: 3
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: -1
movement: Fly
name: Aeolyxria the Uncanny
organization: Elite
presence: 1
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.draconian.statblock/aeolyxria-the-uncanny
size: 1M
speed: 5
stability: 2
stamina: "140"
type: statblock
---

| Draconian, Dragon, Humanoid |          -          |      Level 6       |   Elite Controller    |        EV 32         |
|:---------------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|       **1M**<br>Size        |   **5**<br>Speed    | **140**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |
|  **Poison 6**<br>Immunity   | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|       **-1**<br>Might       |  **+2**<br>Agility  |  **+2**<br>Reason  |  **+3**<br>Intuition  |  **+1**<br>Presence  |

> 🏹 **Spittlesplash (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> |----------------------------|--------------------:|
> | **📏 Ranged 10**           |  **🎯 Two enemies** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 poison damage; M < 1 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 15 poison damage; M < 2 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 18 poison damage; M < 3 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)

> 🏹 **Experimental Treasure**
>
> | **Magic, Ranged, Strike** |                **Main action** |
> |---------------------------|-------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** The targets regains 10 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
> - **12-16:** 12 corruption damage; A < 2 [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 12 lightning damage; A < 2 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** The first time in an encounter that Aeolyxria makes a power roll for this ability, she can subsequently use the outcome of that roll instead of rolling whenever she uses this ability until the end of the encounter.
>
> **2+ [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** The ability targets one additional target for each 2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice) spent.

> 🔳 **Elevate (2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Ranged**       |   **Maneuver** |
> |------------------------|---------------:|
> | **📏 1 cube within 5** | **🎯 Special** |
>
> **Effect:** The ground in the area rises 5 squares, creating a pillar of dirt. Any creature in the area moves with the ground to its new elevation.
>
> **1+ [Malice](scc:mcdm.monsters.v1/rule.monster/malice):** Aeolyxria creates an additional pillar for each [Malice](scc:mcdm.monsters.v1/rule.monster/malice) spent.

> ❗️ **Blood For Blood**
>
> | **Ranged, Weapon** | **Triggered action** |
> |--------------------|---------------------:|
> | **📏 Ranged 5**    |  **🎯 One creature** |
>
> **Trigger:** An ally is made [bleeding](scc:mcdm.heroes.v1/condition/bleeding) by the target.
>
> **Power Roll + 3:**
>
> - **≤11:** 7 poison damage; A < 2 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 12 poison damage; A < 3 [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 15 poison damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)

> ⭐️ **That's Our Opening!**
>
> The Director gains 1 [Malice](scc:mcdm.monsters.v1/rule.monster/malice) whenever Aeolyxria imposes a condition on an enemy.
