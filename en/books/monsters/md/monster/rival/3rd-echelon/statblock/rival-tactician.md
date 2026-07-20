---
agility: 1
ev: "40"
free_strike: 9
intuition: 0
keywords:
    - Humanoid
    - Rival
level: 8
might: 4
name: Rival Tactician
organization: Elite
presence: 2
reason: 3
role: Artillery
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-tactician
size: 1M
speed: 5
stability: 2
stamina: "180"
type: statblock
---

|  Humanoid, Rival  |         -         |      Level 8       |    Elite Artillery    |        EV 40         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|  **1M**<br>Size   |  **5**<br>Speed   | **180**<br>Stamina |  **2**<br>Stability   | **9**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+4**<br>Might  | **+1**<br>Agility |  **+3**<br>Reason  |  **0**<br>Intuition   |  **+2**<br>Presence  |

> 🏹 **Command From the Back ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Ranged, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------------------|--------------------------------:|
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 damage
> - **12-16:** 18 damage; A < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 22 damage; A < 4 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **4 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Two allies within distance move up to their speed and can use a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability).

> 🏹 **Safeguard (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Ranged, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 10**           | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 15 damage; M < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **12-16:** 21 damage; M < 3 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
> - **17+:** 26 damage; M < 4 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
>
> **Effect:** Two allies [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target each regain 7 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).

> ❗️ **Quickshot**
>
> | **Ranged**       |        **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |------------------|----------------------------:|
> | **📏 Ranged 10** | **🎯 The triggering enemy** |
>
> **Trigger:** An enemy within distance willingly moves.
>
> **Effect:** At any point during the movement, the tactician uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target.

> ⭐️ **Rivalry**
>
> At the start of an encounter, the tactician chooses one creature within their [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect). Both the tactician and the creature can add a d3 roll to power rolls they make against each other.
