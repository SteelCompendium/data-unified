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
level: 7
might: 4
name: Koptourok
organization: Horde
presence: -1
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/koptourok
size: 1M
speed: 5
stability: 1
stamina: "40"
type: statblock
---

|                 Undead                 |         -         |      Level 7      |      Horde Hexer      |         EV 9         |
|:--------------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |  **5**<br>Speed   | **40**<br>Stamina |  **1**<br>Stability   | **3**<br>Free Strike |
| **Corruption 7, poison 7**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+4**<br>Might             | **+2**<br>Agility |  **0**<br>Reason  |  **+1**<br>Intuition  |  **-1**<br>Presence  |

> 🗡 **Choking Grasp ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **[Main action](../../../../rule/combat/turn.md)** |
> |---------------------------|------------------------------:|
> | **📏 Melee 5**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [grabbed](../../../../condition/grabbed.md)
> - **12-16:** 10 damage; M < 3 [grabbed](../../../../condition/grabbed.md)
> - **17+:** 11 damage; M < 4 [grabbed](../../../../condition/grabbed.md)
>
> **Effect:** A creature [grabbed](../../../../condition/grabbed.md) this way is [suffocating](../../../../rule/health/suffocating.md). The koptourok can have up to two creatures [grabbed](../../../../condition/grabbed.md) at once.

> ❇️ **Inhale (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area, Magic** |               **[Main action](../../../../rule/combat/turn.md)** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** [Pull](../../../../movement/forced-movement.md) 3; M < 2 5 corruption damage
> - **12-16:** [Pull](../../../../movement/forced-movement.md) 5; M < 3 5 corruption damage
> - **17+:** [Pull](../../../../movement/forced-movement.md) 7; M < 4 5 corruption damage
>
> **Effect:** This ability gains an [edge](../../../../rule/dice/edge.md) against any target [grabbed](../../../../condition/grabbed.md) by the koptourok. If one or more targets are pulled [adjacent](../../../../rule/combat/adjacent.md) to the koptourok, the koptourok can [fly](../../../../movement/fly.md) until the end of the encounter.

> ⭐️ **Exhale**
>
> The first time the koptourok is made [winded](../../../../rule/health/winded.md) by damage that isn't fire damage or holy damage, each enemy within 3 squares of them takes 8 corruption damage. Any enemy who takes this damage and has M < 3 is also [weakened](../../../../condition/weakened.md) (save ends)
