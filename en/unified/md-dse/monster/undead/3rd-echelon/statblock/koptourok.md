---
agility: 2
ev: "9"
file_basename: koptourok
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: koptourok
item_name: Koptourok
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
source: mcdm.monsters.v1
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

> 🗡 **Choking Grasp ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 5**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 10 damage; M < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 11 damage; M < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** A creature [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way is [suffocating](scc.v1:mcdm.heroes.v1/rule.health/suffocating). The koptourok can have up to two creatures [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) at once.

> ❇️ **Inhale (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** [Pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 5 corruption damage
> - **12-16:** [Pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 3 5 corruption damage
> - **17+:** [Pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; M < 4 5 corruption damage
>
> **Effect:** This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against any target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the koptourok. If one or more targets are pulled [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the koptourok, the koptourok can [fly](scc.v1:mcdm.heroes.v1/movement/fly) until the end of the encounter.

> ⭐️ **Exhale**
>
> The first time the koptourok is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by damage that isn't fire damage or holy damage, each enemy within 3 squares of them takes 8 corruption damage. Any enemy who takes this damage and has M < 3 is also [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
