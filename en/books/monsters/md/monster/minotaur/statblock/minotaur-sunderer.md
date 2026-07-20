---
agility: 1
ev: "20"
free_strike: 6
intuition: 2
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
might: 2
name: Minotaur Sunderer
organization: Elite
presence: -1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur-sunderer
size: "2"
speed: 6
stability: 2
stamina: "120"
type: statblock
---

| Accursed, Humanoid, Minotaur |         -         |      Level 3       |      Elite Brute      |        EV 20         |
|:----------------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|        **2**<br>Size         |  **6**<br>Speed   | **120**<br>Stamina |  **2**<br>Stability   | **6**<br>Free Strike |
|      **-**<br>Immunity       | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|       **+2**<br>Might        | **+1**<br>Agility |  **0**<br>Reason   |  **+2**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Spiked Maul ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Charge, Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|--------------------------------:|
> | **📏 Melee 2**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 12 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 15 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
>
> **Effect:** A target [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the sunderer is automatically [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).

> ❇️ **Fearsome Bay (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**       |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------|------------------------------:|
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
> 
> - **≤11:** I < 0 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** I < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** Until the end of their next turn, the minotaur has damage immunity 2 and deals an extra 5 damage with strikes.

> 🗡 **Disemboweling Horns (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Charge, Melee, Strike, Weapon** |        **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|--------------------:|
> | **📏 Melee 2**                    | **🎯 One creature** |
>
> **Special:** The target must be [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the sunderer.
>
> **Power Roll + 2:**
> 
> - **≤11:** 5 damage; M < 0 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 8 damage; M < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 9 damage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes 1d6 damage at the start of each of their turns.

> ❗️ **Retaliatory Strike**
>
> | **Ranged**      |           **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-----------------|-------------------------------:|
> | **📏 Ranged 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the sunderer.
>
> **Effect:** The sunderer uses the Charge main action and Spiked Maul against the target.

> ⭐️ **Minotaur Sense**
>
> The sunderer can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
