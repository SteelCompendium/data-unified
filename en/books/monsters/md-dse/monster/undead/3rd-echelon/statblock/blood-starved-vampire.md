---
agility: 1
ev: 9 for four minions
file_basename: blood-starved-vampire
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: blood-starved-vampire
item_name: Blood-Starved Vampire
keywords:
    - Undead
    - Vampire
level: 7
might: 4
movement: Climb
name: Blood-Starved Vampire
organization: Minion
presence: -3
reason: -3
role: Harrier
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/blood-starved-vampire
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "12"
type: statblock
with_captain: +3 bonus to speed
---

|            Undead, Vampire             |           -           |      Level 7      |            Minion Harrier             | EV 9 for four minions |
|:--------------------------------------:|:---------------------:|:-----------------:|:-------------------------------------:|:---------------------:|
|             **1M**<br>Size             |    **6**<br>Speed     | **12**<br>Stamina |          **0**<br>Stability           | **3**<br>Free Strike  |
| **Corruption 7, poison 7**<br>Immunity | **Climb**<br>Movement |         -         | **+3 bonus to speed**<br>With Captain |   **-**<br>Weakness   |
|            **+4**<br>Might             |   **+1**<br>Agility   | **-3**<br>Reason  |          **+1**<br>Intuition          |  **-3**<br>Presence   |

> 🗡 **Feeding Frenzy ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Melee, Strike, Weapon** |                          **Main action** |
> |---------------------------|-----------------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object per minion** |
>
> **Power Roll + 4:**
>
> - **≤11:** 3 damage
> - **12-16:** 6 damage
> - **17+:** 7 damage; M < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (EoT)
>
> **Effect:** If a target made [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way is already [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding), they are instead knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand until the end of their next turn.

> ⭐️ **Unslakable Bloodthirst**
>
> The blood-starved vampire has speed 10 while any creature within 10 squares of them is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding). The vampire must use Feeding Frenzy against a [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) creature on their turn if they are able to.
